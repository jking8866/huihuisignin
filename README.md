#卉卉打卡

##介绍
卉卉打卡是一款小巧简单的打卡软件，记录你的日常事项有没有做完。制作的初衷是给卉卉女神做一个记录跑步看书等小事的软件。
	
第一版采用跨平台的Qt编写，也方便移植到Windows、iOS、Linux等系统，但由于Qml界面渲染的不太美观，现在的版本采用<a href="http://www.dcloud.io/mui.html">mui</a>框架编写，日历展示用到了
	<a href="https://github.com/zzyss86/LunarCalendar">小推万年历</a>。<br />
	旧版源码地址 <a href="http://github.com/0312birdzhang/huisignin">huisignin</a>,
	当前版本源码地址 <a href="http://github.com/0312birdzhang/huihuisignin">huihuisignin</a>

如果你觉得本软件对你的生活或者工作有一些帮助，请在下载的商店里评价一下，或者推荐给你的亲朋好友。你的支持，是我最大的动力^_^


##RoadMap

- [x] 加入打卡统计

- [x] 加入分享功能

- [ ] 重新设计添加打卡内容页面，加入是否需要提醒，加入语音输入

- [ ] 加入9宫格锁定


##感谢

* <a href="https://github.com/zzyss86/LunarCalendar">小推万年历</a>

* <a href="http://www.dcloud.io/mui.html">Mui框架</a>

* <a href="http://fontawesome.io/icons/">FontAwesome</a>


##下载地址

* 安卓
	http://www.wandoujia.com/apps/com.birdzhang.huihuisignin
* IOS
	https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=1116482144&mt=8
	
##已知bug

* 时区不为东八区的情况下不能使用，暂时等待小推万年历更新