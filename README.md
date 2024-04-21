# live
M3u Live share. Douyu、bilibili、huya、youtube

## 欢迎加入[tg交流群](https://t.me/+-e-b04EE5Cw2NmU1)
## 欢迎加入[tg频道](https://t.me/Ruk1ng001)

# 使用说明
直播源地址：[http://ruk1ng.kmdns.net:19527](http://ruk1ng.kmdns.net:19527)

## 直播源格式
直播源地址的末尾代表你需要的直播源格式，根据需要选择你需要`所有直播源`的格式：
- `txt`格式:
```text
http://ruk1ng.kmdns.net:19527/lives/all.txt
```
- `m3u`格式:
```text
http://ruk1ng.kmdns.net:19527/lives/all.m3u
```

## 直播分类
- 虎牙：huya
- 斗鱼：douyu
- bilibili：bili
- youtube(使用需要设备使用代理上网)：youtube

## 自定义直播源
所有直播源地址包含四种直播平台所有直播频道`（/lives/all.m3u实际上等同于lives/douyu_huya_bili_youtube.m3u）`。 如果你只需要集成其中`几种直播平台`的直播频道，请使用如下格式的直播源地址：
- 如：`m3u`格式源:
```text
http://ruk1ng.kmdns.net:19527/lives/直播源1_直播源2_直播源3.m3u
```
例: 如果你想获取虎牙和斗鱼的两个直播平台的直播频道，你需要使用的直播源地址为
```text
http://ruk1ng.kmdns.net:19527/lives/huya_douyu.m3u
```

# 计划更新

### 单直播平台根据直播类型进行自定义直播源
