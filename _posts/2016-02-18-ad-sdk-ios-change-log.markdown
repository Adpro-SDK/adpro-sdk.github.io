---
layout: post
title:  "广告 SDK 更新日志 (iOS)"
date:   2016-2-18 12:00:00 +0800
categories: SDK ChangeLog
---

## V2.0.0

2016年2月18日

- 修改
  - 去掉通知栏广告
  - 将WebView广告全部改为Native广告
  - 修改SDK使用Api

## V1.2.1版本
2015年 10月29日

- 修改
    - 完善广告展示方式
    - `AdProBanner`、`AdProPopup`对象新增`rootViewController`属性，该属性为广告对象所属的`ViewController`，必填！

## V1.2.0版本
2015年 10月15日

- 修改
    - 完善广告刷新机制

## V1.1.0版本
2015年 9月28日

- 新增
    - 适配 iOS 6.0
    - 提示开发者在释放实现了`AdProPopupDelegate`、`AdProBannerDelegate`协议的对象之前，将`delegate`置为`nil`，以防止程序意外闪退

- 修复
    - 修复展示某些广告内容会自动跳转 Safari 的问题
    - 修复`delegate`导致程序闪退的问题

## V1.0.1版本
2015年 9月22日

- 修复
    - 修复`AdProPopup`自动刷新bug

## V1.0.0版本
2015年 9月14日

- 新增
    - `AdProPopup`类，可以初始化`AdProPopup`对象，加载广告`loadAd`方法，展示广告`show`方法。
    - `AdProPopup`对象可以实现`AdProDelegate`协议，并实现协议里的方法来监听相关事件。
    - 可以通过 xib 文件或者 storyboard 来创建`AdProBanner`对象，但是需要单独设置`slotID`，才能请求到广告。

- 修改
    - `AdProBanner`对象不再会修改自身的 size 来适配广告内容，改为广告内容来适配`AdProBanner`对象的size。
