## JiangXi-IPTV-M3U

### ⚠️警告

- **本项目纯属个人兴趣，请不要利用本项目进行商业活动！**

- 直播资源由个人搜集于互联网，请不要DDOS订阅服务器

- **请批判性对待部分电视节目内容，节目仅代表主持人与嘉宾观点，不代表项目作者观点！**
- 作者**深刻领悟“两个确立”的决定性意义，增强“四个意识”、坚定“四个自信”、做到“两个维护”**，始终在思想上政治上行动上同以习近平同志为核心的党中央保持高度一致，为实现党的二十大提出的目标任务而团结奋斗

---

### ✳️简介

- 本项目旨在为父母与长辈提供一个【开启自启】【高清】【无广告】电视直播体验

- 仅需在智能电视/电视盒子上安装相应直播APP，导入订阅链接后既可食用

- 免除广电与运营商垃圾ITPV盒子的卡顿、广告与~~有线电视费~~

- 主要频道为央视、江西本地台、卫视、港澳台和国外优质新闻台，**不会收录乱七八糟的网络直播和轮播**

- 主要电视台直播源分辨率均为1080P及以上，响应速度在2000ms内，为了保护眼睛，**不会收录1080P以下的源**（除非这个台到23年还没有做没有高清化）~~（说的就是一大堆地方台，我只能说好死）~~


#### 1️⃣订阅链接（默认不含IPV6）

1. M3U链接：http://home.subtlyrabbit.top:1999/api/share/3f95a89b-c33a-4907-9e40-362163b44681.m3u
   - 每个频道只有一个精选过的**1080P低延迟直播源**（延迟测试基于江西电信）
   - 含有tvg-name，可与EPG匹配显示台标
2. TXT链接：http://home.subtlyrabbit.top:1999/api/share/f8c78782-21e7-401c-82e4-e5eb1e2085f9.txt
   - 每个频道一般包含多个直播源，可以手动切源
3. **包含IPV6直播源的版本**（维护中，待更新）
   - 某些地区使用IPV6可以拥有更低的延迟和更高的稳定性
4. **直播源最后更新时间：2023/03/06**


---


### ✴️使用教程

#### 1️⃣基于安卓系统的智能电视/电视盒子

1. 在智能电视/电视盒子上安装DIPY直播APP，[点我下载](https://github.com/subtlyrabbit/JiangXi-IPTV-M3U/releases)

   - 本项目提供的APP为32位，安卓4.4—安卓13全兼容（测试设备：XiaoMi 10U）
   - 安装第三方APP方法请自行搜索
   - 指路：
     - [小米电视不能优盘装软件怎么办，方法亲测有效]( https://weibo.com/3185567812/MlZ7uD0dG)
   
2. 添加TXT订阅链接
   1. **使用订阅链接实现自动更新**
      
      - 遥控器按：【设置】键—选择【接口设置】—【节目地址】
      ![](https://imghost.subtlyrabbit.top//images%E8%87%AA%E5%8A%A8%E6%B7%BB%E5%8A%A0%E7%9B%B4%E6%92%AD%E6%BA%901.jpg)
      - **填入上面提供的TXT订阅链接**
      ![](https://imghost.subtlyrabbit.top//imagesScreenshot_2023-03-05-10-23-16-078_com.player.diyp2020.jpg)
      - 重启生效
      
   2. 手动添加直播源
      - 遥控器按：【设置】键—选择【显示设置】—【自定义源】
   
       ![](https://imghost.subtlyrabbit.top//images%E6%89%8B%E5%8A%A8%E6%B7%BB%E5%8A%A0%E7%9B%B4%E6%92%AD%E6%BA%901.jpg)
   
      - 使用电脑（推荐）访问控制台
   
       ![](https://imghost.subtlyrabbit.top//images%E6%89%8B%E5%8A%A8%E6%B7%BB%E5%8A%A0%E7%9B%B4%E6%92%AD%E6%BA%902.jpg)
   
      - 添加分类（如央视、卫视、港澳台）并在对应分类填入相应的直播源
   
      ![](https://imghost.subtlyrabbit.top//images%E6%89%8B%E5%8A%A8%E6%B7%BB%E5%8A%A0%E7%9B%B4%E6%92%AD%E6%BA%903.png)
      - 添加后DIPY APP会立刻刷新，即可观看
   
3.  设置开机自启动

#### 2️⃣Apple TV

1. 在Appstore下载 **TV+** 软件
2. 添加M3U订阅链接

#### 3️⃣Jellyfin、Emby、Plex等流媒体管理软件
1. 添加M3U订阅链接

2. 添加指南数据源：选择XmlTV，添加此网址：http://epg.51zmt.top:8000/e.xml

#### 4️⃣Windows

1. 下载Potplayer播放器
2. 双击播放m3u文件即可

---

### 数据来源

- 直播源：https://github.com/SPX372928/MyIPTV 、[电视节目-娱乐你我他，为分享而生时光爱分享](https://blog.wemtime.com/dszb)
- 台标、EPG：http://epg.51zmt.top:8000/
- IPTV检测工具：[一个橙子pro工具箱](https://github.com/biancangming/wtv/wiki/一个橙子pro工具箱使用指南)

---

[![Star History Chart](https://api.star-history.com/svg?repos=subtlyrabbit/JiangXi-IPTV-M3U&type=Date)](https://star-history.com/#subtlyrabbit/JiangXi-IPTV-M3U)
