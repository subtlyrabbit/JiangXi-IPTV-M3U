# JiangXi-IPTV-M3U

### 🆘1、须知

**本项目纯属个人兴趣，请不要利用本项目进行商业活动！**

直播资源由个人搜集于互联网，请不要DDOS订阅服务器

**直播源最后测试时间：2023/03/04**

---

### ✳️2、简介

本项目初衷为给父母与长辈家庭自用，只需在智能电视/电视盒子上安装DIPY直播APP，导入订阅链接后既可食用，源失效后可自动更新

还可免除送的垃圾ITPV盒子的卡顿、广告与~~有线电视费~~

只使用江西电信进行测试，主要频道为**央视、各省卫视、港澳台和江西本地台**

分辨率均为1920X1080及以上，为了保护眼睛，**不会收录1080P以下的源**

#### 1️⃣订阅链接介绍

1. 【推荐】M3U链接：http://home.subtlyrabbit.top:1999/api/share/3f95a89b-c33a-4907-9e40-362163b44681.m3u
   1. 每个频道只含有一个精选过的直播源（延迟测试基于江西电信）
   2. 可以实现一次订阅，每次开机自动更新
   3. 含有台标，方便显示
2. TXT链接：http://home.subtlyrabbit.top:1999/api/share/f8c78782-21e7-401c-82e4-e5eb1e2085f9.txt
   1. 量大管饱，每个频道包含多个直播源，可以手动切源
   2. 更新需手动配置（具体方案见下一节）
   3. 不含台标

---


### ✴️3、使用教程

#### 1️⃣基于安卓系统的智能电视/电视盒子

1. 在智能电视/电视盒子上安装DIPY直播APP

   - 不同设备安装第三方APP方法请百度
   - 指路：[小米电视不能优盘装软件怎么办，方法亲测有效](http://t.cn/A6KBDjHA https://weibo.com/3185567812/MlZ7uD0dG)

2. 添加直播链接
   1. 手动添加TXT链接
      1. 遥控器按设置键—选择显示设置—自定义源

      2. ![](https://imghost.subtlyrabbit.top//images%E6%89%8B%E5%8A%A8%E6%B7%BB%E5%8A%A0%E7%9B%B4%E6%92%AD%E6%BA%901.jpg)
   
      3. 访问控制台
   
      4. ![](https://imghost.subtlyrabbit.top//images%E6%89%8B%E5%8A%A8%E6%B7%BB%E5%8A%A0%E7%9B%B4%E6%92%AD%E6%BA%902.jpg)
   
      5. 添加分类，如央视、卫视、港澳台，并复制相应的源
   
      6. ![](https://imghost.subtlyrabbit.top//images%E6%89%8B%E5%8A%A8%E6%B7%BB%E5%8A%A0%E7%9B%B4%E6%92%AD%E6%BA%903.png)
      7. 添加后DIPY APP会立刻刷新，即可观看
   
   2. 使用M3U链接实现自动更新
      - TXT链接：http://home.subtlyrabbit.top:1999/api/share/f8c78782-21e7-401c-82e4-e5eb1e2085f9.txt
   
      - M3U链接：http://home.subtlyrabbit.top:1999/api/share/3f95a89b-c33a-4907-9e40-362163b44681.m3u


#### 2️⃣IOS/IPasOS/TVOS

1. 在Appstore下载 **TV+** 软件
2. 添加**订阅链接**
   - M3U链接：http://home.subtlyrabbit.top:1999/api/share/3f95a89b-c33a-4907-9e40-362163b44681.m3u

#### 3️⃣Jellyfin、Emby、Plex等流媒体管理软件
1. 添加电视源：http://home.subtlyrabbit.top:1999/api/share/3f95a89b-c33a-4907-9e40-362163b44681.m3u

2. 添加指南数据源：选择XmlTV，添加此网址：http://epg.51zmt.top:8000/e.xml



---

### 数据来源

- 直播源：https://github.com/SPX372928/MyIPTV 、[电视节目-娱乐你我他，为分享而生时光爱分享](https://blog.wemtime.com/dszb)
- 图标、指南：http://epg.51zmt.top:8000/
- IPTV存活检测：[一个橙子pro工具箱](https://github.com/biancangming/wtv/wiki/一个橙子pro工具箱使用指南)


---
### 🌈私货时间：0216

![efa9bba45ef795e5d8c5ab1ea21d7b5c.png](https://s1.imagehub.cc/images/2022/12/06/efa9bba45ef795e5d8c5ab1ea21d7b5c.png)
