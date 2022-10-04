# 卷毛鼠公益项目之广播电视源

- [目录](#目录)
- [**卷毛鼠广播电视简介**](#卷毛鼠广播电视仓库简介)
- [**广播电视源**](#广播电视源)
  - [**广播电视目录导航**](#广播电视目录导航)
  - [**卷毛鼠推流直播源**](#卷毛鼠推流直播源)
    - [卷毛鼠推流](#卷毛鼠推流-1)
    - [更新日志](#更新日志-1)
  - [**卷毛鼠代理直播平台源**](#卷毛鼠代理直播平台源)
    - [使用教程](#使用教程-2)
    - [更新日志](#更新日志-2)
  - [**卷毛鼠代理youtube源**](#卷毛鼠代理youtube源)
    - [使用教程](#使用教程-3)
    - [更新日志](#更新日志-3)
  - [**卷毛鼠自制轮播源**](#卷毛鼠自制轮播源)
    - [M3U文件](#m3u文件-5)
    - [更新日志](#更新日志-5)
  - [**互联网收集直播源**](#互联网收集直播源)
    - [M3U文件](#m3u文件-6)
    - [更新日志](#更新日志-6)
  - [**卷毛鼠代理广播源**](#卷毛鼠代理广播源)
    - [使用教程](#使用教程-7)
    - [更新日志](#更新日志-7)
- [**鸣谢**](#鸣谢)  
---
---

# **卷毛鼠广播电视简介**


卷毛鼠广播电视是卷毛鼠公益项目之一，主要以分享全球IPTV直播源、广播源为主，所有电视直播源广播源均收集于互联网并经过精挑细选而成。同时为方便各位观看，卷毛鼠代理了一些其他平台可开放观看的直播节目/频道。JMSIPTV/JMSRadio内含有世界各国电视直播广播频道，因各国文件差异及认知水平不同在收看节目时请理性思考，恪守爱国、敬业、诚信、友善社会主义核心价值观公民个人层面的价值准则。

卷毛鼠公益项目成立于2020年8月30日，已稳定运行将近两年，卷毛鼠公益项目包括：公益流媒体服务（Emby）、公益电视直播与广播服务（IPTV&Radio）您关注卷毛鼠，卷毛鼠关注世界，世界在您身边！

卷毛鼠节目源均来自于互联网开源项目和代码，仅用于学习研究使用，请下载后于24小时内删除，严禁用于非法牟利！




---
---




# **广播电视源**
## **广播电视源目录导航**
* [卷毛鼠推流直播源](#卷毛鼠推流直播源)
* [卷毛鼠代理直播平台源](#卷毛鼠代理直播平台源)
* [卷毛鼠代理youtube源](#卷毛鼠代理youtube源)
* [卷毛鼠自制轮播源](#卷毛鼠自制轮播源)
* [互联网收集直播源](#互联网收集直播源)
* [卷毛鼠代理广播源](#卷毛鼠代理广播源)



---



## **卷毛鼠推流直播源**
卷毛鼠通过服务器FFMPEG推流出的电视直播源，可直接在各种终端平台的播放器中直接播放。为防止滥用，推流源限制频道通道为200，就是说同时可允许200人观看不重复的200个频道，多人同时观看同一频道不额外占用通道名额。

![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.10.04-brightgreen?style=for-the-badge)

频道列表

![image](https://user-images.githubusercontent.com/105055212/193534177-0ee6ef1a-b0d7-47f8-b13d-22c2504aa23d.png)





频道源订阅

> https://m3u.52sf.ga/JMSTV-ALL.m3u
> 
> https://m3u.52sf.ga/JMSTV-4G.m3u
> 

### 更新日志
> **2022.10.04**：上线自推流电视频道，包含之前的PHP代理和两制区频道，频道数：281；4GTV是取自github开源源，如失效请等原作者修复，频道数：121。
>
> **2022.09.26**：上线两制区节目源涵盖翡翠、凤凰、艾尔达体育等热门频道。
>
> **2022.09.06**：剔除失效代理和慢速代理，已涵盖TVB无线新闻、Now新闻系列频道，央视、卫视以及运营商付费数字频道。
> 
> **2022.07.31**：新增一组咪咕代理源。
> 
> **2022.05.30**：因特殊原因，下架电视匣，请使用PHP代理源。
> 
> **2022.05.28**：电视匣代理源代码已更新，代理源已恢复正常；新增一套PHP代理直播源。
> 
> **2022.05.27**：电视匣官方更换了key数组，代理中key数组失效，项目作者正在咕咕代码，敬请期待~~
> 
> **2022.05.26**：添加两套不同类型的代理源，节目源已套用CloudFlareCDN，如播放卡顿请挂代理观看。
> 


---



## **卷毛鼠代理直播平台源**

卷毛鼠基于Golang语言做的一套国内知名直播平台代理系统，实现重定向访问虎牙、斗鱼、Bilibili直播间M3U8/FLV直播流，将直播平台动态源转换为静态链接，方便在各种终端平台的播放器中直接播放。在原作者(原作者已跑路两年)代码基础上修复了部分错误，提高了代理的性能！更多直播平台将陆续添加。

![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.09.21-brightgreen?style=for-the-badge)

### 使用教程

直播源表现格式：

> https://live.52sf.ga/平台/ID
>   * 虎牙=huya；斗鱼=douyu；B站=bilibili
>

完整直播源举例：

> https://live.52sf.ga/bilibili/10375360
>   * 如果主播下播将无法观看哦~
> 

### 更新日志
> **2022.09.21**：迁移节目源服务器，下架备份直播代理服务器，后续看负载量重新上架。
> 
> **2022.09.06**：修复备份直播代理服务器。
> 
> **2022.05.30**：虎牙一起看、斗鱼已修复，感谢我飞哥和原作者linsongze提供技术支持！增加备份直播代理服务器缓解主服压力。
> 
> **2022.05.28**：虎牙直播间已修复，虎牙一起看修复中。
> 
> **2022.05.27**：B站解析已上线，斗鱼虎牙还在做代码。
> 
---



## **卷毛鼠代理youtube源**

卷毛鼠基于PHP语言做的一套Youtube代理(解析)系统，实现重定向访问Youtube直播流无需挂代理，可直接在各种终端平台的播放器中直接播放，较之前的Youtube代理更具灵活性和稳定性。

![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.09.26-brightgreen?style=for-the-badge)

### 使用教程

> https://php.52sf.ga/@Curly_MouseIPTV-YTB.php?id=youtubeID&P=分辨率
>  

使用示例：
> Youtube链接：https://www.youtube.com/watch?v=LbS-xQ67fos
> 
> 分辨率：720P=720  1080P=1080
> 
> https://php.52sf.ga/@Curly_MouseIPTV-YTB.php?id=watch?v=LbS-xQ67fos&P=1080
> 
### 更新日志
> **2022.09.26**：因此代理方式对播放器兼容性不是很友好，请播放时选用解码功能强点的播放器。
>
> **2022.09.06**：因用户反馈部分频道无法播放，经检测发现此代理方式对播放器兼容性不是很友好，暂时下架。
> 
> **2022.09.06**：更换代理方式，更自由灵活，用户可自定义制作自己的Youtube代理频道。
> 
> **2022.08.09**：迁移节目源服务器，修复失效节目源，下架停播源，新增earthTV、K-POP等娱乐性频道当前收录频道数：43
> 
> **2022.07.31**：修复失效节目源，下架停播源，新增earthTV、K-POP等娱乐性频道当前收录频道数：44
> 
> **2022.06.09**：修复失效节目源。当前收录频道数：42
> 
> **2022.06.03**：选择性新增群友投稿节目源，修复失效节目源。当前收录频道数：42
> 
> **2022.05.30**：选择性新增群友投稿节目源，增加多套影视剧综艺节目源。当前收录频道数：39
> 
> **2022.05.29**：上线Youtube直播频道代理源，当前收录频道数：24
> 


---



## **卷毛鼠自制轮播源**
卷毛鼠基于Golang语言做的一套自推流轮播系统，可对接全球知名直播平台，也可单独推出轮播节目源。

### 一直没时间去做，预计在10月下旬开始提供。
---



## **互联网收集直播源**
卷毛鼠从互联网以及群友分享的节目源中检测整理的节目源，精简好用。但大街源失效迅速，维护不易，且用且珍惜。


![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.09.26-brightgreen?style=for-the-badge)

### M3U文件

> https://m3u.52sf.ga/各地组播源.txt
> 
> https://m3u.52sf.ga/JMSTV-JSYD.m3u
> 
> https://m3u.52sf.ga/JMSTV-HNYD.m3u
> 

### 更新日志
> **2022.09.26**：上线一套组播源部分地区播放受限，大街源失效不补，随缘更新。
> 
> **2022.09.06**：上线江苏移动大街源、湖南移动大街源、大街源失效不补，随缘更新。
> 

---

## **卷毛鼠代理广播源**
卷毛鼠通过PHP代码代理出的广播源，目前支持蜻蜓FM、喜马拉雅FM、云听FM中所有广播频道，适用任何播放器。三家各有优势，同时频道可能会重复，请按需选用，方便喜欢收听广播又不想安装手机软件的听友们。

![](https://img.shields.io/badge/%E6%9B%B4%E6%96%B0%E6%97%A5%E6%9C%9F-2022.09.06-brightgreen?style=for-the-badge)




### 使用教程

> 随机收听蜻蜓FM电台：https://php.52sf.ga/@Curly_MouseIPTV-FMQT.php?id=rand
> 
> 获取地区分类蜻蜓FM电台：https://php.52sf.ga/@Curly_MouseIPTV-FMQT.php?id=rand&type=蜻蜓FM分类ID
> 
> 蜻蜓FM分类ID
> 
> 407=网络台   217=广东   3=北京
> 433=咨询台   139=江西   5=天津
> 442=音乐台   151=山东   7=河北
> 429=交通台   19=山西    83=上海
> 439=经济台   202=湖南   257=重庆
> 432=文艺台   187=湖北   169=河南
> 441=都市台   254=海南   85=江苏
> 430=体育台   59=吉林    281=贵州
> 431=双语台   69=黑龙江  44=辽宁
> 440=综合台   316=陕西   259=四川
> 438=生活台   31=内蒙古  99=浙江
> 435=旅游台   239=广西   351=宁夏
> 436=曲艺台   291=云南   129=福建
> 434=方言台   11=安徽    327=甘肃
> 357=新疆     342=青海   308=西藏


> 随机收听云听FM电台：https://php.52sf.ga/@Curly_MouseIPTV-FMYT.php?id=&type=
> 
> 获取地区分类云听FM电台：https://php.52sf.ga/@Curly_MouseIPTV-FMYT.php?id=list&type=云听FM分类ID
> 
> 云听FM分类ID
> 
> china=中国        shandong=7山东
> beijing=北京      shanxi_1=山西
> hebei=河北        hunan=湖南
> shanghai=上海     hubei=湖北
> chongqing=重庆    hainan=海南
> henan=河南        jilin=吉林
> jiangsu=江苏      heilongjiang=黑龙江
> guizhou=贵州      shanxi_2=陕西
> liaoning=辽宁     neimenggu=内蒙古
> sichuan=四川      guangxi=广西
> zhejiang=浙江     yunnan=云南
> ningxia=宁夏      anhui=安徽
> fujian=福建       qinghai=青海
> gansu=甘肃        xinjiang=新疆
> guangdong=广东    xizang=西藏
> jiangxi=江西      xinjiangbingtuan=新疆兵团


> 随机收听喜马拉雅FM电台：https://php.52sf.ga/@Curly_MouseIPTV-FMXMLY.php?id=rand
> 
> 获取喜马拉雅全部FM电台：https://php.52sf.ga/@Curly_MouseIPTV-FMXMLY.php?id=list
> 
### 更新日志
> **2022.09.06**：新增加广播节目，云听、蜻蜓FM、喜马拉雅FM。
> 



---

## 鸣谢

感谢渣渣飞、 linsongze、已经跑路了、土豆、nani、Fola LCR、Chris恩山论坛等提供技术支持和指导！


