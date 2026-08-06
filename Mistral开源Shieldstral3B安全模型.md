# Mistral开源Shieldstral 3B安全模型

**2026年7月17日 12时34分56秒**

---

Mistral发3B参数Shieldstral内容审核模型，12语言，单张16GB GPU可跑，做实时评论过滤、邮件分类、Agent输出护栏。安全对齐模型开源化是趋势：不再只靠云端Moderation API，端侧App也能本地拦违禁输出，利于医疗教育隐私场景。3B尺寸说明“安全”是轻量伴随模型而非主模型附属服务，未来每个Agent会带一个Shieldstral式小模型做出口审查，类似操作系统杀毒常驻。

---

来源依据：
![](https://www.baidu.com/img/PCtm_d9c8750bed0b3c7d089fa7d55720d6cf.png)<br>

2026年7月14日 23时46分38秒 [尘烟霓虹中文版](https://www.xiazainiao.com/xiazai/68794.html)<br>
2026年6月03日 18时53分52秒 [qq输入法2023最新版](https://www.xiazainiao.com/xiazai/68795.html)<br>
2026年7月11日 16时05分29秒 [萌推最新版本](https://www.xiazainiao.com/xiazai/68796.html)<br>
2026年7月10日 16时10分41秒 [我是大剑士最新版\(I Am Warrior\)](https://www.xiazainiao.com/xiazai/68797.html)<br>
2026年6月02日 17时57分54秒 [萌推客户端](https://www.xiazainiao.com/xiazai/68798.html)<br>
2026年6月06日 16时23分24秒 [全民巡警模拟器手机版](https://www.xiazainiao.com/xiazai/68799.html)<br>
2026年6月06日 01时30分00秒 [鲜花小镇手游](https://www.xiazainiao.com/xiazai/68800.html)<br>
2026年7月06日 13时24分13秒 [agoda酒店预订app](https://www.xiazainiao.com/xiazai/68801.html)<br>
2026年6月14日 12时40分51秒 [三国大时代3无限乐币破解版](https://www.xiazainiao.com/xiazai/68802.html)<br>
2026年7月20日 05时57分55秒 [欢乐大派对游戏](https://www.xiazainiao.com/xiazai/68803.html)<br>
2026年6月02日 10时37分04秒 [石油大亨手机版中文版最新版2023](https://www.xiazainiao.com/xiazai/68804.html)<br>
2026年7月09日 02时08分52秒 [刷圈兔app免费版](https://www.xiazainiao.com/xiazai/68805.html)<br>
2026年6月01日 17时27分52秒 [猫狗大战游戏单机版\(Cat](https://www.xiazainiao.com/xiazai/68806.html)<br>
2026年6月03日 19时25分13秒 [应用汇旧版本](https://www.xiazainiao.com/xiazai/68807.html)<br>
2026年7月16日 19时00分48秒 [警察模拟器2023最新版](https://www.xiazainiao.com/xiazai/68808.html)<br>
2026年6月15日 16时37分18秒 [熊猫换一换手机版](https://www.xiazainiao.com/xiazai/68809.html)<br>
2026年6月02日 11时30分20秒 [超级玛丽3游戏手机版](https://www.xiazainiao.com/xiazai/68810.html)<br>
2026年7月06日 09时59分21秒 [动画训练游戏](https://www.xiazainiao.com/xiazai/68811.html)<br>
2026年7月05日 05时42分22秒 [AI跳绳计数器\(跳绳计数天天练\)](https://www.xiazainiao.com/xiazai/68812.html)<br>
2026年7月23日 12时19分11秒 [我的餐厅最新版](https://www.xiazainiao.com/xiazai/68813.html)<br>
2026年6月15日 21时13分52秒 [像素冒险世界游戏](https://www.xiazainiao.com/xiazai/68814.html)<br>
2026年6月08日 22时21分53秒 [十色app](https://www.xiazainiao.com/xiazai/68815.html)<br>
2026年7月08日 18时59分27秒 [Kingdom Rush](https://www.xiazainiao.com/xiazai/68816.html)<br>
2026年6月07日 18时33分46秒 [Ink Sans fight手机版\(跟sans的战斗\)](https://www.xiazainiao.com/xiazai/68817.html)<br>
2026年7月03日 09时54分38秒 [e家帮家政服务app](https://www.xiazainiao.com/xiazai/68818.html)<br>
2026年6月03日 19时12分29秒 [史莱姆糖果工厂手机版](https://www.xiazainiao.com/xiazai/68819.html)<br>
2026年7月04日 11时48分10秒 [消除决斗游戏](https://www.xiazainiao.com/xiazai/68820.html)<br>
2026年6月02日 15时00分30秒 [诗歌中国app](https://www.xiazainiao.com/xiazai/68821.html)<br>
2026年6月17日 01时10分55秒 [纽兰枢纽官方版](https://www.xiazainiao.com/xiazai/68822.html)<br>
2026年6月16日 21时22分53秒 [兽王争霸正版](https://www.xiazainiao.com/xiazai/68823.html)<br>
2026年7月13日 04时54分10秒 [视听海南app最新版](https://www.xiazainiao.com/xiazai/68824.html)<br>
2026年6月17日 13时47分31秒 [为了东村最新版](https://www.xiazainiao.com/xiazai/68825.html)<br>
2026年6月16日 21时18分01秒 [莉景天气app安卓版](https://www.xiazainiao.com/xiazai/68826.html)<br>
2026年7月27日 06时54分23秒 [贵州和校园app最新版](https://www.xiazainiao.com/xiazai/68827.html)<br>
2026年7月18日 15时06分09秒 [欧洲骑士3手游](https://www.xiazainiao.com/xiazai/68828.html)<br>
2026年7月17日 18时46分09秒 [喵侦探咪雅游戏最新版\(Detective Mio\)](https://www.xiazainiao.com/xiazai/68829.html)<br>
2026年7月15日 18时06分06秒 [孚科思专注力机构版app](https://www.xiazainiao.com/xiazai/68830.html)<br>
2026年6月18日 07时03分38秒 [恐怖庄园的秘密中文版](https://www.xiazainiao.com/xiazai/68831.html)<br>
2026年7月19日 01时32分37秒 [特摄大乱斗游戏手机版](https://www.xiazainiao.com/xiazai/68832.html)<br>
2026年6月05日 10时34分44秒 [羿才教育app题库](https://www.xiazainiao.com/xiazai/68833.html)<br>
2026年6月01日 09时13分34秒 [王蓝莓的幸福生活正版最新版本](https://www.xiazainiao.com/xiazai/68834.html)<br>
2026年7月27日 21时32分37秒 [抖个大包袱2最新版](https://www.xiazainiao.com/xiazai/68835.html)<br>
2026年7月08日 15时24分50秒 [机车游侠app](https://www.xiazainiao.com/xiazai/68836.html)<br>
2026年6月01日 01时51分00秒 [我的合成世界游戏](https://www.xiazainiao.com/xiazai/68837.html)<br>
2026年6月06日 22时50分57秒 [炸弹客的冒险之旅游戏](https://www.xiazainiao.com/xiazai/68838.html)<br>
2026年7月09日 18时24分33秒 [职多多app](https://www.xiazainiao.com/xiazai/68839.html)<br>
2026年7月03日 18时47分26秒 [我在三国有个局官方版](https://www.xiazainiao.com/xiazai/68840.html)<br>
2026年6月04日 11时05分52秒 [渡劫模拟器游戏](https://www.xiazainiao.com/xiazai/68841.html)<br>
2026年7月18日 23时04分56秒 [火线警戒游戏](https://www.xiazainiao.com/xiazai/68842.html)<br>
2026年7月18日 14时30分37秒 [全能录音转文字软件手机版\(飞咕录音转文字\)](https://www.xiazainiao.com/xiazai/68843.html)<br>
2026年7月02日 22时32分43秒 [托卡小镇少女屋手机版\(托卡世界少女屋\)](https://www.xiazainiao.com/xiazai/68844.html)<br>
2026年7月09日 02时07分07秒 [表情消消乐游戏](https://www.xiazainiao.com/xiazai/68845.html)<br>
2026年6月20日 16时50分38秒 [合肥通卡app](https://www.xiazainiao.com/xiazai/68846.html)<br>
2026年7月25日 03时35分32秒 [丧尸横行手游](https://www.xiazainiao.com/xiazai/68847.html)<br>
2026年7月19日 20时25分11秒 [神算子老师版\(更名一起中学老师\)](https://www.xiazainiao.com/xiazai/68848.html)<br>
2026年6月17日 02时49分53秒 [炸鸡派对官方正版](https://www.xiazainiao.com/xiazai/68849.html)<br>
2026年7月02日 06时32分55秒 [太空山羊模拟器3D2官方正版](https://www.xiazainiao.com/xiazai/68850.html)<br>
2026年6月26日 05时41分39秒 [高省app](https://www.xiazainiao.com/xiazai/68851.html)<br>
2026年6月16日 15时42分34秒 [谁是凶手游戏](https://www.xiazainiao.com/xiazai/68852.html)<br>
2026年6月11日 01时22分29秒 [山村老屋4之深林魅影官方正版](https://www.xiazainiao.com/xiazai/68853.html)<br>
2026年6月07日 21时53分39秒 [第一财经杂志app](https://www.xiazainiao.com/xiazai/68854.html)<br>
2026年7月17日 12时59分17秒 [吸血鬼幸存者无限金币版](https://www.xiazainiao.com/xiazai/68855.html)<br>
2026年6月18日 19时48分41秒 [rhythmhive直装版](https://www.xiazainiao.com/xiazai/68856.html)<br>
2026年6月21日 22时47分34秒 [俄罗斯方块消消消正版](https://www.xiazainiao.com/xiazai/68857.html)<br>
2026年6月18日 07时38分12秒 [司法考试宝典手机版](https://www.xiazainiao.com/xiazai/68858.html)<br>
2026年7月06日 19时03分11秒 [欢乐水果消消乐手游](https://www.xiazainiao.com/xiazai/68859.html)<br>
2026年7月26日 08时59分09秒 [智讯开店宝app](https://www.xiazainiao.com/xiazai/68860.html)<br>
2026年6月20日 17时27分09秒 [斌哥游戏宝盒最新版](https://www.xiazainiao.com/xiazai/68861.html)<br>
2026年7月18日 17时16分05秒 [足球天才九游版](https://www.xiazainiao.com/xiazai/68862.html)<br>
2026年6月25日 10时54分56秒 [一起中学老师](https://www.xiazainiao.com/xiazai/68863.html)<br>
2026年6月20日 11时29分16秒 [爱你省优惠券app](https://www.xiazainiao.com/xiazai/68864.html)<br>
2026年7月12日 07时47分56秒 [桥梁建造师2破解版](https://www.xiazainiao.com/xiazai/68865.html)<br>
2026年7月13日 05时25分13秒 [wearos工具箱手机版](https://www.xiazainiao.com/xiazai/68866.html)<br>
2026年7月14日 12时28分44秒 [加菲猫跑酷最新版\(Garfield Rush\)](https://www.xiazainiao.com/xiazai/68867.html)<br>
2026年6月04日 19时27分07秒 [先锋云盘手机版app](https://www.xiazainiao.com/xiazai/68868.html)<br>
2026年6月15日 19时24分00秒 [建造乌托邦最新版\(Growtopia\)](https://www.xiazainiao.com/xiazai/68869.html)<br>
2026年6月24日 03时10分36秒 [星球建造大师小游戏2023年最新版本](https://www.xiazainiao.com/xiazai/68870.html)<br>
2026年6月26日 20时17分16秒 [养老模拟器最新版](https://www.xiazainiao.com/xiazai/68871.html)<br>
2026年7月01日 22时23分03秒 [沈阳市考试院官方app](https://www.xiazainiao.com/xiazai/68872.html)<br>
2026年7月24日 04时17分57秒 [皖教云app](https://www.xiazainiao.com/xiazai/68873.html)<br>
2026年6月26日 22时47分07秒 [功夫火柴人游戏](https://www.xiazainiao.com/xiazai/68874.html)<br>
2026年7月28日 18时25分26秒 [达美嘉教育app最新版](https://www.xiazainiao.com/xiazai/68875.html)<br>
2026年6月11日 12时02分21秒 [Terraria1.4汉化破解版](https://www.xiazainiao.com/xiazai/68876.html)<br>
2026年6月09日 20时53分16秒 [佩皮小镇医院生活游戏](https://www.xiazainiao.com/xiazai/68877.html)<br>
2026年6月17日 01时41分46秒 [红魔姬mora官方版](https://www.xiazainiao.com/xiazai/68878.html)<br>
2026年7月18日 16时25分41秒 [老爹鸡翅店手机版](https://www.xiazainiao.com/xiazai/68879.html)<br>
2026年7月08日 07时28分43秒 [tibetan翻译软件](https://www.xiazainiao.com/xiazai/68880.html)<br>
2026年7月15日 04时42分27秒 [托卡城堡小镇游戏](https://www.xiazainiao.com/xiazai/68881.html)<br>
2026年7月04日 12时08分49秒 [卫星街景地图最新版](https://www.xiazainiao.com/xiazai/68882.html)<br>
2026年7月10日 08时33分51秒 [植物大战僵尸欧美版](https://www.xiazainiao.com/xiazai/68883.html)<br>
2026年6月17日 21时45分40秒 [世界杯模拟器手游\(wordcup\)](https://www.xiazainiao.com/xiazai/68884.html)<br>
2026年6月08日 19时55分39秒 [布偶的梦游戏](https://www.xiazainiao.com/xiazai/68885.html)<br>
2026年7月20日 01时52分45秒 [幻影WIFI](https://www.xiazainiao.com/xiazai/68886.html)<br>
2026年7月16日 12时06分45秒 [轻轻松松做黄帝游戏](https://www.xiazainiao.com/xiazai/68887.html)<br>
2026年7月23日 09时21分44秒 [孙美琪疑案刘青春游戏](https://www.xiazainiao.com/xiazai/68888.html)<br>
2026年7月16日 03时47分23秒 [豪华竞速手游](https://www.xiazainiao.com/xiazai/68889.html)<br>
2026年6月08日 12时30分37秒 [简武游戏](https://www.xiazainiao.com/xiazai/68890.html)<br>
2026年7月21日 01时07分59秒 [驾驶俱乐部手机版](https://www.xiazainiao.com/xiazai/68891.html)<br>
2026年6月25日 01时11分31秒 [拳击鸭手机版](https://www.xiazainiao.com/xiazai/68892.html)<br>
2026年7月22日 01时26分19秒 [全时空间手机app](https://www.xiazainiao.com/xiazai/68893.html)<br>

---

**来源参考：**
- [上海光机所中红外光谱合束进展.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E4%B8%8A%E6%B5%B7%E5%85%89%E6%9C%BA%E6%89%80%E4%B8%AD%E7%BA%A2%E5%A4%96%E5%85%89%E8%B0%B1%E5%90%88%E6%9D%9F%E8%BF%9B%E5%B1%95.md)
- [中昊芯英须臾二代TPU三倍算力.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E4%B8%AD%E6%98%8A%E8%8A%AF%E8%8B%B1%E9%A1%BB%E8%87%BE%E4%BA%8C%E4%BB%A3TPU%E4%B8%89%E5%80%8D%E7%AE%97%E5%8A%9B.md)
- [家用智能摄像头隐私保护新规7月生效，规范数据采集使用.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E5%AE%B6%E7%94%A8%E6%99%BA%E8%83%BD%E6%91%84%E5%83%8F%E5%A4%B4%E9%9A%90%E7%A7%81%E4%BF%9D%E6%8A%A4%E6%96%B0%E8%A7%847%E6%9C%88%E7%94%9F%E6%95%88%EF%BC%8C%E8%A7%84%E8%8C%83%E6%95%B0%E6%8D%AE%E9%87%87%E9%9B%86%E4%BD%BF%E7%94%A8.md)
- [2026年7月中国跨境电商持续高增长，海外仓布局加速.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/2026%E5%B9%B47%E6%9C%88%E4%B8%AD%E5%9B%BD%E8%B7%A8%E5%A2%83%E7%94%B5%E5%95%86%E6%8C%81%E7%BB%AD%E9%AB%98%E5%A2%9E%E9%95%BF%EF%BC%8C%E6%B5%B7%E5%A4%96%E4%BB%93%E5%B8%83%E5%B1%80%E5%8A%A0%E9%80%9F.md)
- [乡村荷塘生态观光带成型，打造夏日清凉短途微旅游目的地.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E4%B9%A1%E6%9D%91%E8%8D%B7%E5%A1%98%E7%94%9F%E6%80%81%E8%A7%82%E5%85%89%E5%B8%A6%E6%88%90%E5%9E%8B%EF%BC%8C%E6%89%93%E9%80%A0%E5%A4%8F%E6%97%A5%E6%B8%85%E5%87%89%E7%9F%AD%E9%80%94%E5%BE%AE%E6%97%85%E6%B8%B8%E7%9B%AE%E7%9A%84%E5%9C%B0.md)
- [国家发改委推进海外优质再生原料进口利用，扩大再生材料应用规模.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E5%9B%BD%E5%AE%B6%E5%8F%91%E6%94%B9%E5%A7%94%E6%8E%A8%E8%BF%9B%E6%B5%B7%E5%A4%96%E4%BC%98%E8%B4%A8%E5%86%8D%E7%94%9F%E5%8E%9F%E6%96%99%E8%BF%9B%E5%8F%A3%E5%88%A9%E7%94%A8%EF%BC%8C%E6%89%A9%E5%A4%A7%E5%86%8D%E7%94%9F%E6%9D%90%E6%96%99%E5%BA%94%E7%94%A8%E8%A7%84%E6%A8%A1.md)
- [2026年7月中国城市15分钟便民生活圈建设提速，社区商业焕发新活力.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/2026%E5%B9%B47%E6%9C%88%E4%B8%AD%E5%9B%BD%E5%9F%8E%E5%B8%8215%E5%88%86%E9%92%9F%E4%BE%BF%E6%B0%91%E7%94%9F%E6%B4%BB%E5%9C%88%E5%BB%BA%E8%AE%BE%E6%8F%90%E9%80%9F%EF%BC%8C%E7%A4%BE%E5%8C%BA%E5%95%86%E4%B8%9A%E7%84%95%E5%8F%91%E6%96%B0%E6%B4%BB%E5%8A%9B.md)
- [Qwen3-Coder-480B开源编程大模型.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/Qwen3-Coder-480B%E5%BC%80%E6%BA%90%E7%BC%96%E7%A8%8B%E5%A4%A7%E6%A8%A1%E5%9E%8B.md)
- [文具店上架夏日防汗防滑学习好物，解决伏案学习闷热难题.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E6%96%87%E5%85%B7%E5%BA%97%E4%B8%8A%E6%9E%B6%E5%A4%8F%E6%97%A5%E9%98%B2%E6%B1%97%E9%98%B2%E6%BB%91%E5%AD%A6%E4%B9%A0%E5%A5%BD%E7%89%A9%EF%BC%8C%E8%A7%A3%E5%86%B3%E4%BC%8F%E6%A1%88%E5%AD%A6%E4%B9%A0%E9%97%B7%E7%83%AD%E9%9A%BE%E9%A2%98.md)
- [乡村果蔬驿站推行早晚低温收货，保障农产品新鲜度.md](https://github.com/haoccc123321-gif/daily-news-zt14/blob/main/%E4%B9%A1%E6%9D%91%E6%9E%9C%E8%94%AC%E9%A9%BF%E7%AB%99%E6%8E%A8%E8%A1%8C%E6%97%A9%E6%99%9A%E4%BD%8E%E6%B8%A9%E6%94%B6%E8%B4%A7%EF%BC%8C%E4%BF%9D%E9%9A%9C%E5%86%9C%E4%BA%A7%E5%93%81%E6%96%B0%E9%B2%9C%E5%BA%A6.md)