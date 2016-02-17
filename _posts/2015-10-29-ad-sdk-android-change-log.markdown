---
layout: post
title:  "广告 SDK 更新日志 (Android)"
date:   2015-10-29 12:00:00 +0800
categories: SDK ChangeLog
---

## V2.0.0

2015年2月18日

- 修改
  - 去掉通知栏广告
  - 将WebView广告全部改为Native广告
  - 修改SDK使用Api

## V1.2.2 ~~（建议使⽤）~~

- 修改
    - 优化内存
    - 修改混淆设置
    - 修复部分 BUG，提⾼稳定性

## V1.2.1

- 修改
    - 丰富 Log 信息
    - 提供 Debug 开关
    - SDK中将添加检测广告的`slotid`、类型等因素

## V1.2.0

- 修复
    - 添加各种广告回调
    - 提供⾃定义⼤⼩广告接⼝
    - 添加注册回调
    - 提供预加载`Popup`功能

## V1.1.0

- 修复
    - Compatible with version 7(Android 2.1)
    - edit ad Permissions
    - add `onDetachedFromWindow` in AdView(FOR:stop show ad when closed
view)
    - Asynchronous processing of all advertising data when all the data is
acquired
