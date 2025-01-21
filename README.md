# freeLive
[![Stars](https://img.shields.io/github/stars/Ruk1ng001/freeLive)](https://github.com/Ruk1ng001/freeLive/stargazers)
[![TG](https://img.shields.io/badge/Telegram-gray?logo=Telegram)](https://t.me/Ruk1ng001)
### Lives share. Douyu、bilibili、huya、youtube

**直播源地址每半个小时更新一次**

[<img src="https://api.gitsponsors.com/api/badge/img?id=779725311" height="90">](https://api.gitsponsors.com/api/badge/link?p=UzxWE0/Sr257rDsDOuSqJybSqPcdqpjHYJR0q6o44Hd1s2+cDhmwJ1g71rFRC1LH52MmKxi6BK9cFmnqazFVAuG4tVdTOfyJv9R4qlN+XVOnQGwG7eU1aDgQHALuEmhnodpPykVztqQr9YVEgkauCg==)

## 打赏

|支付宝|微信|
|:-:|:-:|
|![支付宝打赏](FUNDING/支付宝.png)|![微信打赏](FUNDING/微信.png)|
|如果你觉得有用|请多多支持|

---

## 欢迎加入[tg频道](https://t.me/Ruk1ng001)、[tg交流群](https://t.me/+-e-b04EE5Cw2NmU1)

---

# 使用说明
直播源地址 1：[http://live.997269.xyz:19527](http://live.997269.xyz:19527)
直播源地址 2：[http://ruk1ng.serv00.net:19527](http://ruk1ng.serv00.net:19527)

---

## 直播源格式
直播源地址的末尾代表你需要的直播源格式，根据需要选择你需要`所有直播源`的格式：
### 家宽
```
- `txt`格式:
```text
http://live.997269.xyz:19527/lives/all.txt
```
- `m3u`格式:
```text
http://live.997269.xyz:19527/lives/all.m3u
```

### serv00
- `txt`格式:
```text
http://ruk1ng.serv00.net:19527/lives/all.txt
```
- `m3u`格式:
```text
http://ruk1ng.serv00.net:19527/lives/all.m3u

---

## 直播分类
- huya：huya
- douyu：douyu
- bilibili：bili
- youtube(使用需要设备使用代理上网)：youtube

## 自定义直播源
所有直播源地址包含四种直播平台所有直播频道`（/lives/all.m3u实际上等同于lives/douyu_huya_bili_youtube.m3u）`。 如果你只需要集成其中`几种直播平台`的直播频道，请使用如下格式的直播源地址：
- 如：`m3u`格式源:
```text
http://live.997269.xyz:19527/lives/直播源1_直播源2_直播源3.m3u
```
例: 如果你想获取虎牙和斗鱼的两个直播平台的直播频道，你需要使用的直播源地址为：
```text
http://live.997269.xyz:19527/lives/huya_douyu.m3u
```

---

## 直播类别

目前聚合了四种平台的直播源，每个平台暂时获取了如下这些类别的直播：

| 直播类型 | | | | | | | | | | | |
| :--- | :----: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| huya | 体育 | 原创 | 户外 | 一起看 | | | | | | | |
| douyu | 一起看 | 人文社科 | 户外 | 数码科技 | 美食 | 赛事| | | | | | |
| bili | 赛事 | 互动玩法 | 单机游戏 | 娱乐 | 手游 | 生活 | 电台 | 知识 | 网游 | 聊天室 | 虚拟主播 |
| youtube | 体育 | 新闻 | 游戏 | | | | | | | | |

## 自定义直播类别
如果你想要只获取某个平台下某一类型的直播节目，你需要自定义直播类别：

· 当你获取直播源时，默认获取的是该分类下的所有直播类别  
· 如果你需要只获取其中一种或者多种，请加上请求参数：`直播分类=类别1_类别2_类别3`。例如：`douyu=一起看_赛事`

例：如果你想要获取`douyu、huya下面一起看类别`和`bilibili下面赛事和生活`的直播源，你需要使用的直播源地址为：
```text
http://live.997269.xyz:19527/lives/huya_douyu_bili.m3u?huya=一起看&douyu=一起看&bili=赛事_生活
```
**注意：**`?`前后的直播分类需要对应上。

---

# 计划更新

- [x] 单直播平台根据直播类型进行自定义直播源

# 备用地址

## 统计

[![Stargazers over time](https://starchart.cc/Ruk1ng001/freeLive.svg)](https://starchart.cc/Ruk1ng001/freeLive)

