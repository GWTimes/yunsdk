# 简介
IotVideoSDK是基于Cloudlink™ P2P的智能家居平台工具集。SDK将监控、录像、回放、设备控制、设备通讯、设备报警等功能进行简单封装，方便合作伙伴集成。 

# 功能概述

## 【账户体系】
基于平台提供的账号体系，开发者可以实现自有APP开发中的注册、登录、忘记密码、登出、修改用户信息、分享、系统通知等功能。 
- [详见文档](账户体系开发指南.md)

## 【设备配网】
提供设备配网能力，支持多种配网方式，包含蓝牙配网、AP配网、有线配网、智能联机配网、扫码配网等。
- [详见文档](设备配网开发指南.md)

## 【设备模型】
 提供了丰富的接口供开发者实现设备参数设置、设备状态获取和设置能力。设备相关的返回数据都采用异步消息的方式通知接受者。  
- [详见文档](设备模型开发指南.md)

## 【多媒体】
提供音视频能力，包含实时监控、实时音视频通话、远程回放、录像、截图等功能
- [详见文档](多媒体指南.md)

## 【增值业务】
提供了设备相关增值业务，如云存储功能
- [详见文档](增值业务开发指南.md)

# 架构
架构图如下：
----
![架构图-w750](https://picabstract-preview-ftn.weiyun.com/ftn_pic_abs_v3/460ae626988aca93820bcd50fab9f4d7bbcb87cb45a5316155f0f9695f32cad464a241033fb9052e5a314f8dc281c526?pictype=scale&from=30113&version=3.3.3.3&uin=824538183&fname=%E6%8A%80%E5%A8%81P2PSDK%E6%A1%86%E6%9E%B6.png&size=750)

# 平台支持
具体平台支持情况如下表所示：

| 平台       | SDK 及兼容性                                                 | Demo 体验 | Demo 源码下载 |
| :--------- | :----------------------------------------------------------- | :-------- | :------------ |
| iOS        | 支持；兼容 iOS 9.0 及以上版本的 iPhone 或者 iPad 真机。      | 支持      | 支持          |
| Android    | 支持；最低兼容 Android 4.1（SDK API Level 16），建议使用 Android 5.0 （SDK API Level 21）及以上版本。 | 支持      | 支持          |
| Windows    | 支持；兼容 Windows 7 及以上版本。                            | 支持      | 支持          |
