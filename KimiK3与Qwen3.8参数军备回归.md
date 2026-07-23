# Kimi K3与Qwen3.8参数军备回归

**2026年7月17日 12时34分56秒**

---

WAIC期间阿里发Qwen3.8预览版（2.4T参数），月之暗面发Kimi K3（2.8T参数）开源，两者均对标顶级闭源，强化长上下文与原生Agent。Qwen覆盖0.5B到3.8T全系，K3主打200万token上下文与工具调用。开源巨模意义不在刷榜而在生态：中小厂可基于K3做法律/医疗垂直蒸馏，高校可剖模型看MoE路由，云厂可拿Qwen3.8填智算中心空闲机时。风险在推理成本——2.8T全量激活虽走稀疏但长文档多轮仍烧卡，月之暗面靠云订阅摊薄，阿里靠通义灵码+钉钉闭环变现。国产开源阵营（Qwen、Kimi、DeepSeek）已形成对Llama部分替代，东南亚、中东开发者默认下Qwen/Kimi成新习惯。参数军备回归表面热闹，私底下比的是每美元Token与Agent完成率。

---

来源依据：
![](https://www.baidu.com/img/PCtm_d9c8750bed0b3c7d089fa7d55720d6cf.png)<br>

2026年7月01日 16时59分27秒 [一罐](https://soft2.kittyyw.com/index/47917.html)<br>
2026年6月11日 04时18分27秒 [泰剧兔正版](https://soft2.kittyyw.com/index/47918.html)<br>
2026年7月17日 07时43分50秒 [小狐狸](https://soft2.kittyyw.com/index/47919.html)<br>
2026年7月04日 00时04分42秒 [只有一道门手机版](https://soft2.kittyyw.com/index/47920.html)<br>
2026年6月18日 06时50分48秒 [音乐剪辑助手免费版](https://soft2.kittyyw.com/index/47921.html)<br>
2026年6月13日 17时11分52秒 [爱看影视](https://soft2.kittyyw.com/index/47922.html)<br>
2026年7月27日 01时08分17秒 [特狗免费](https://soft2.kittyyw.com/index/47923.html)<br>
2026年6月09日 02时17分04秒 [佳能相机](https://soft2.kittyyw.com/index/47924.html)<br>
2026年6月22日 13时30分52秒 [华律律师端](https://soft2.kittyyw.com/index/47925.html)<br>
2026年6月11日 17时33分28秒 [畅玩空间手机版](https://soft2.kittyyw.com/index/47926.html)<br>
2026年6月19日 16时56分04秒 [北斗导航系统](https://soft2.kittyyw.com/index/47927.html)<br>
2026年7月27日 19时00分22秒 [北斗导航手机版](https://soft2.kittyyw.com/index/47928.html)<br>
2026年6月19日 10时16分00秒 [北斗导航地图免费](https://soft2.kittyyw.com/index/47929.html)<br>
2026年6月14日 22时58分27秒 [北斗导航2026最新版](https://soft2.kittyyw.com/index/47930.html)<br>
2026年6月28日 07时43分35秒 [仙剑98完美移植手机版](https://soft2.kittyyw.com/index/47931.html)<br>
2026年7月18日 03时13分48秒 [抓抓地牢安卓版](https://soft2.kittyyw.com/index/47932.html)<br>
2026年6月05日 16时55分30秒 [笼庭的知更鸟游戏汉化版](https://soft2.kittyyw.com/index/47933.html)<br>
2026年7月03日 16时26分20秒 [地下城与商人](https://soft2.kittyyw.com/index/47934.html)<br>
2026年6月12日 06时42分25秒 [随记备忘录](https://soft2.kittyyw.com/index/47935.html)<br>
2026年6月03日 12时14分06秒 [FNF错误化恶搞之家模组](https://soft2.kittyyw.com/index/47936.html)<br>
2026年6月08日 09时27分03秒 [andpods正版](https://soft2.kittyyw.com/index/47937.html)<br>
2026年7月13日 09时23分33秒 [老爹芝士店中文版](https://soft2.kittyyw.com/index/47938.html)<br>
2026年6月10日 14时09分45秒 [仙剑98柔情篇完美版](https://soft2.kittyyw.com/index/47939.html)<br>
2026年6月28日 13时34分02秒 [越野热力](https://soft2.kittyyw.com/index/47940.html)<br>
2026年6月17日 14时44分23秒 [点击英雄最新版](https://soft2.kittyyw.com/index/47941.html)<br>
2026年6月22日 14时24分58秒 [交能宝最新版](https://soft2.kittyyw.com/index/47942.html)<br>
2026年6月21日 07时42分09秒 [奇瑞瑞享生活免费版](https://soft2.kittyyw.com/index/47943.html)<br>
2026年6月11日 12时24分54秒 [红灯狙击手](https://soft2.kittyyw.com/index/47944.html)<br>
2026年6月19日 09时00分48秒 [三国志幻想大陆2枭之歌游戏](https://soft2.kittyyw.com/index/47945.html)<br>
2026年6月13日 01时26分39秒 [回声乐桥](https://soft2.kittyyw.com/index/47946.html)<br>
2026年6月08日 04时40分33秒 [口袋妖怪XY](https://soft2.kittyyw.com/index/47947.html)<br>
2026年6月18日 07时11分25秒 [节奏盒子Candyland模组免费安装  手机版](https://soft2.kittyyw.com/index/47948.html)<br>
2026年7月09日 01时48分11秒 [潘多拉tv](https://soft2.kittyyw.com/index/47949.html)<br>
2026年6月22日 21时03分05秒 [幽雅](https://soft2.kittyyw.com/index/47950.html)<br>
2026年7月13日 00时05分08秒 [合并防御](https://soft2.kittyyw.com/index/47951.html)<br>
2026年7月16日 19时21分21秒 [汉典zdict最新版](https://soft2.kittyyw.com/index/47952.html)<br>
2026年7月15日 03时45分22秒 [亚托莉我的挚爱时光安卓汉化版](https://soft2.kittyyw.com/index/47953.html)<br>
2026年7月12日 00时13分44秒 [充广广手机版](https://soft2.kittyyw.com/index/47954.html)<br>
2026年6月21日 16时18分13秒 [Fitdays+](https://soft2.kittyyw.com/index/47955.html)<br>
2026年6月24日 15时51分47秒 [小智AI办公助手](https://soft2.kittyyw.com/index/47956.html)<br>
2026年6月05日 11时07分05秒 [合成像素立方](https://soft2.kittyyw.com/index/47957.html)<br>
2026年6月26日 23时26分13秒 [街机恐龙最新版](https://soft2.kittyyw.com/index/47958.html)<br>
2026年7月05日 01时09分12秒 [健康甘肃](https://soft2.kittyyw.com/index/47959.html)<br>
2026年7月11日 15时13分31秒 [开罗发现动物公园最新版](https://soft2.kittyyw.com/index/47960.html)<br>
2026年7月06日 17时18分12秒 [好甜免费版](https://soft2.kittyyw.com/index/47961.html)<br>
2026年6月28日 11时02分39秒 [哈哈喵开黑](https://soft2.kittyyw.com/index/47962.html)<br>
2026年7月13日 19时51分49秒 [懂球宝](https://soft2.kittyyw.com/index/47963.html)<br>
2026年6月11日 07时57分38秒 [天空中的烈火中文版](https://soft2.kittyyw.com/index/47964.html)<br>
2026年7月07日 12时12分33秒 [心灵达人最新版](https://soft2.kittyyw.com/index/47965.html)<br>
2026年7月11日 22时25分09秒 [西尔云学苑](https://soft2.kittyyw.com/index/47966.html)<br>
2026年6月11日 09时48分30秒 [免费漫画神器](https://soft2.kittyyw.com/index/47967.html)<br>
2026年6月11日 00时27分17秒 [鸟巢](https://soft2.kittyyw.com/index/47968.html)<br>
2026年7月02日 17时42分33秒 [七日世界国际服](https://soft2.kittyyw.com/index/47969.html)<br>
2026年6月06日 15时22分18秒 [JJ象棋](https://soft2.kittyyw.com/index/47970.html)<br>
2026年7月28日 21时31分48秒 [全能截图王](https://soft2.kittyyw.com/index/47971.html)<br>
2026年6月21日 20时04分48秒 [冒险守护九游版](https://soft2.kittyyw.com/index/47972.html)<br>
2026年6月15日 09时25分45秒 [金库网](https://soft2.kittyyw.com/index/47973.html)<br>
2026年6月26日 10时23分21秒 [僵尸猎人像素生存游戏](https://soft2.kittyyw.com/index/47974.html)<br>
2026年6月05日 16时51分43秒 [同程旅行商家](https://soft2.kittyyw.com/index/47975.html)<br>
2026年7月07日 09时55分14秒 [恒风行最新版](https://soft2.kittyyw.com/index/47976.html)<br>
2026年7月20日 16时06分45秒 [影分身最新版](https://soft2.kittyyw.com/index/47977.html)<br>
2026年7月26日 18时44分34秒 [足球中国](https://soft2.kittyyw.com/index/47978.html)<br>
2026年6月02日 17时09分52秒 [万能自动点击器](https://soft2.kittyyw.com/index/47979.html)<br>
2026年7月17日 02时44分10秒 [洪恩小画家](https://soft2.kittyyw.com/index/47980.html)<br>
2026年7月18日 03时10分00秒 [宝宝爱刷牙](https://soft2.kittyyw.com/index/47981.html)<br>
2026年6月05日 06时23分19秒 [轻便快速文件扫描](https://soft2.kittyyw.com/index/47982.html)<br>
2026年6月09日 08时36分49秒 [考研四六级](https://soft2.kittyyw.com/index/47983.html)<br>
2026年6月08日 18时31分12秒 [钢材金属重量计算器](https://soft2.kittyyw.com/index/47984.html)<br>
2026年6月11日 20时36分13秒 [远通天下贸易端](https://soft2.kittyyw.com/index/47985.html)<br>
2026年7月22日 01时43分03秒 [新感觉影视](https://soft2.kittyyw.com/index/47986.html)<br>
2026年6月02日 00时28分33秒 [流马风行](https://soft2.kittyyw.com/index/47987.html)<br>
2026年7月19日 12时17分13秒 [环卫小智最新版](https://soft2.kittyyw.com/index/47988.html)<br>
2026年7月01日 18时46分49秒 [potplayer播放器](https://soft2.kittyyw.com/index/47989.html)<br>
2026年6月08日 18时55分55秒 [国家电网网上营业厅](https://soft2.kittyyw.com/index/47990.html)<br>
2026年7月02日 19时25分58秒 [绿茵中国](https://soft2.kittyyw.com/index/47991.html)<br>
2026年7月24日 16时33分54秒 [淘爱交友](https://soft2.kittyyw.com/index/47992.html)<br>
2026年7月10日 17时52分12秒 [小说阅读吧免费](https://soft2.kittyyw.com/index/47993.html)<br>
2026年6月02日 13时04分15秒 [甜蜜夏日直装版](https://soft2.kittyyw.com/index/47994.html)<br>
2026年6月16日 15时50分31秒 [镜像相机](https://soft2.kittyyw.com/index/47995.html)<br>
2026年6月08日 16时09分40秒 [大武汉](https://soft2.kittyyw.com/index/47996.html)<br>
2026年7月24日 19时10分17秒 [附近寻爱](https://soft2.kittyyw.com/index/47997.html)<br>
2026年7月20日 08时01分27秒 [鹏云智慧管家](https://soft2.kittyyw.com/index/47998.html)<br>
2026年6月13日 05时59分00秒 [极客软件库全新版](https://soft2.kittyyw.com/index/47999.html)<br>
2026年7月08日 14时23分06秒 [欲漫软件](https://soft2.kittyyw.com/index/48000.html)<br>
2026年6月01日 06时06分08秒 [宝宝巴士奇妙恐龙世界游戏](https://soft2.kittyyw.com/index/48001.html)<br>
2026年7月19日 17时46分43秒 [兽耳桌面](https://soft2.kittyyw.com/index/48002.html)<br>
2026年6月07日 06时06分48秒 [每日荐片](https://soft2.kittyyw.com/index/48003.html)<br>
2026年7月24日 18时55分41秒 [海棠文学城安卓版](https://soft2.kittyyw.com/index/48004.html)<br>
2026年6月18日 20时53分43秒 [水印相机最新版](https://soft2.kittyyw.com/index/48005.html)<br>
2026年6月17日 20时36分39秒 [米兔音乐app](https://soft2.kittyyw.com/index/48006.html)<br>
2026年7月07日 23时58分20秒 [影视仓安卓版](https://soft2.kittyyw.com/index/48007.html)<br>
2026年6月03日 05时10分13秒 [灵听](https://soft2.kittyyw.com/index/48008.html)<br>
2026年6月03日 20时51分21秒 [Lanerc安卓版](https://soft2.kittyyw.com/index/48009.html)<br>
2026年7月09日 23时27分52秒 [对聊交友官网版](https://soft2.kittyyw.com/index/48010.html)<br>
2026年7月12日 13时39分04秒 [猫咪社区回家路最新版本](https://soft2.kittyyw.com/index/48011.html)<br>
2026年6月26日 16时31分23秒 [俄罗斯乡村赛车手](https://soft2.kittyyw.com/index/48012.html)<br>
2026年7月21日 14时39分25秒 [兽音译者官网版](https://soft2.kittyyw.com/index/48013.html)<br>
2026年6月14日 20时52分33秒 [51吃瓜网](https://soft2.kittyyw.com/index/48014.html)<br>
2026年7月12日 07时25分40秒 [零界绘漫画官方最新版](https://soft2.kittyyw.com/index/48015.html)<br>
2026年6月20日 18时59分01秒 [柠檬社区](https://soft2.kittyyw.com/index/48016.html)<br>

---

**来源参考：**
- [小红书BigMac多模态训练范式开源.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E5%B0%8F%E7%BA%A2%E4%B9%A6BigMac%E5%A4%9A%E6%A8%A1%E6%80%81%E8%AE%AD%E7%BB%83%E8%8C%83%E5%BC%8F%E5%BC%80%E6%BA%90.md)
- [北京布局Token工厂新增5万P.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E5%8C%97%E4%BA%AC%E5%B8%83%E5%B1%80Token%E5%B7%A5%E5%8E%82%E6%96%B0%E5%A2%9E5%E4%B8%87P.md)
- [全国首个海上浮式风电平台并网发电.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E5%85%A8%E5%9B%BD%E9%A6%96%E4%B8%AA%E6%B5%B7%E4%B8%8A%E6%B5%AE%E5%BC%8F%E9%A3%8E%E7%94%B5%E5%B9%B3%E5%8F%B0%E5%B9%B6%E7%BD%91%E5%8F%91%E7%94%B5.md)
- [全国首个数字人民币跨境支付走廊贯通.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E5%85%A8%E5%9B%BD%E9%A6%96%E4%B8%AA%E6%95%B0%E5%AD%97%E4%BA%BA%E6%B0%91%E5%B8%81%E8%B7%A8%E5%A2%83%E6%94%AF%E4%BB%98%E8%B5%B0%E5%BB%8A%E8%B4%AF%E9%80%9A.md)
- [乡村打造田间遮阳休息驿站，贴心服务高温务农农户.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E4%B9%A1%E6%9D%91%E6%89%93%E9%80%A0%E7%94%B0%E9%97%B4%E9%81%AE%E9%98%B3%E4%BC%91%E6%81%AF%E9%A9%BF%E7%AB%99%EF%BC%8C%E8%B4%B4%E5%BF%83%E6%9C%8D%E5%8A%A1%E9%AB%98%E6%B8%A9%E5%8A%A1%E5%86%9C%E5%86%9C%E6%88%B7.md)
- [Daily News_AI Builders_20260612_40.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/Daily%20News_AI%20Builders_20260612_40.md)
- [乡村公共浴室开放暑期惠民专场，方便村民清凉洗浴.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E4%B9%A1%E6%9D%91%E5%85%AC%E5%85%B1%E6%B5%B4%E5%AE%A4%E5%BC%80%E6%94%BE%E6%9A%91%E6%9C%9F%E6%83%A0%E6%B0%91%E4%B8%93%E5%9C%BA%EF%BC%8C%E6%96%B9%E4%BE%BF%E6%9D%91%E6%B0%91%E6%B8%85%E5%87%89%E6%B4%97%E6%B5%B4.md)
- [养老机器人IEC国际标准落地.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E5%85%BB%E8%80%81%E6%9C%BA%E5%99%A8%E4%BA%BAIEC%E5%9B%BD%E9%99%85%E6%A0%87%E5%87%86%E8%90%BD%E5%9C%B0.md)
- [具身智能上半年融资935亿同比5倍.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E5%85%B7%E8%BA%AB%E6%99%BA%E8%83%BD%E4%B8%8A%E5%8D%8A%E5%B9%B4%E8%9E%8D%E8%B5%84935%E4%BA%BF%E5%90%8C%E6%AF%945%E5%80%8D.md)
- [小鹏澳洲品牌日打包AI交通生态.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E5%B0%8F%E9%B9%8F%E6%BE%B3%E6%B4%B2%E5%93%81%E7%89%8C%E6%97%A5%E6%89%93%E5%8C%85AI%E4%BA%A4%E9%80%9A%E7%94%9F%E6%80%81.md)