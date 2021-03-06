# Agora macOS Signaling Tutorial for Swift

*Read this in other languages: [English](README.md)*

这个开源示例项目演示了如何快速集成 Agora 信令 SDK 实现发消息功能。

在这个示例项目中包含了以下功能：

- 登录信令服务器
- 发送点对点消息，离线接收点对点消息
- 显示点对点的聊天记录
- 加入频道
- 发送频道消息，接收频道消息
- 离开频道
- 注销信令登录

Agora 信令 SDK 支持 Android / Web / MacOS / iOS 等多个平台，你可以查看对应各平台的示例项目：

- Android: https://github.com/AgoraIO/Agora-Signaling-Tutorial-Android
- Web    : https://github.com/AgoraIO/Agora-Signaling-Tutorial-Web
- iOS  : https://github.com/AgoraIO/Agora-Signaling-Tutorial-iOS-Swift
- Linux  : https://github.com/AgoraIO/Agora-Signaling-Tutorial-Linux
- Java   : https://github.com/AgoraIO/Agora-Signaling-Tutorial-Java
- Windows: https://github.com/AgoraIO/Agora-Signaling-Tutorial-Windows


## 运行示例程序
首先在 [Agora.io 注册](https://dashboard.agora.io/cn/signup/) 注册账号，并创建自己的测试项目，获取到 AppID。
然后选择测试项目里的编辑，App Certificate 点击启用，根据操作拿到App Certificate。
将 AppID 和App Certificate 填写进 "Agora-Signaling-Tutorial-macOS-Swift/Agora-Signaling-Tutorial/MainPage/KeyCenter.swift"

```
let AppId: String = "YOUR APPID"
```



然后在 Agora.io SDK 下载 信令 SDK，解压后将其中的 libs 文件夹复制到本项目目录下，和 “Agora-Signaling-Tutorial” 文件夹平级。

最后使用 XCode 打开 Agora-Signaling-Tutorial.xcodeproj，设置有效的开发者签名后即可运行。

## 运行环境
* XCode 8.0 +
* macOS

## 联系我们
- 完整的 API 文档见 [文档中心](https://docs.agora.io/cn/)
- 如果在集成中遇到问题, 你可以到 [开发者社区](https://dev.agora.io/cn/) 提问
- 如果有售前咨询问题, 可以拨打 400 632 6626，或加入官方Q群 12742516 提问
- 如果需要售后技术支持, 你可以在 [Agora Dashboard](https://dashboard.agora.io) 提交工单
- 如果发现了示例代码的 bug, 欢迎提交 [issue](https://github.com/AgoraIO/Agora-Signaling-Tutorial-iOS-Swift/issues)

## 代码许可
The MIT License (MIT).

