# 音屿 SongLib Amp

**你的音乐 自成一屿**

Apple TV 与 iPhone 私人音乐播放器，连接自己的 NAS 曲库，原格式播放，显示同步歌词。

本仓库用于发布安装包、更新说明和收集反馈，不包含应用源码。

[官网](https://songlib.playsong.cn/) · [安装说明](https://songlib.playsong.cn/install.html) · [最新安装包](https://github.com/songdone/SongLibAmp-Release/releases/latest) · [问题反馈](https://github.com/songdone/SongLibAmp-Release/issues)

## 下载与系统要求

| 平台 | 当前版本 | 系统要求 | 下载 |
| --- | --- | --- | --- |
| Apple TV | 1.9.5（73） | tvOS 18 及以上 | [SongLibAmp-tvOS-1.9.5.ipa](https://github.com/songdone/SongLibAmp-Release/releases/download/tvOS-1.9.5-iOS-1.2.8/SongLibAmp-tvOS-1.9.5.ipa) |
| iPhone | 1.2.8（67） | iOS 16.4 及以上 | [SongLibAmp-iOS-1.2.8.ipa](https://github.com/songdone/SongLibAmp-Release/releases/download/tvOS-1.9.5-iOS-1.2.8/SongLibAmp-iOS-1.2.8.ipa) |

两端均为**未签名 IPA**，需要自行签名后安装。按官网教程操作，需要 Mac、Xcode 和自己的 Apple ID；免费 Apple ID 的签名到期后需要重新签名并覆盖安装。

项目仍在持续开发，功能尚不完善，可能遇到 bug。TV 端目前仅在最新一代 Apple TV 上测试，其他型号尚未验证。建议先阅读安装说明，再下载和试用。

安装包统一通过本仓库的 GitHub Releases 下载。手机 1.0.3、1.0.4 存在启动问题；1.0.6–1.0.10 在留声主题开启启动动画后存在顶部与状态栏重叠问题。这些问题版本只保留历史记录，不提供安装包；请使用最新版。

本版在模拟器与本机隔离的听己测试服务上完成入库、整理、洗版、刮削写回、标签修正与撤销的自动化验证。系统最低版本来自安装包声明，本轮未覆盖所有最低系统、设备与 NAS 组合。

本轮完整功能与修复见 [更新说明](CHANGELOG.md)，中间版本见 [逐版历史记录](HISTORY.md)。历史条目不附旧IPA；旧版原始包及调试符号仅在私有仓库归档。公开安装包须经过商业加固核验，调试符号不公开。

## 界面展示

<img src="images/demo-cinematic-tv-playing.jpg" alt="音屿 Apple TV 播放页，示例封面、同步歌词与涟漪背景" width="720">

<img src="images/demo-cinematic-ios-home-r11.webp" alt="音屿 iPhone 首页，示例曲库与原创封面" width="280">
<img src="images/demo-cinematic-ios-playing.webp" alt="音屿 iPhone 播放页，同步歌词与涟漪背景" width="280">

截图来自应用的示例曲库，使用原创专辑封面、虚构音乐人写真、合成音频和原创演示歌词。TV 和 iPhone 的播放、歌词截图采用涟漪背景；频谱背景为 Pro 功能。更多页面可在官网轮播中查看。

## 功能

- **主题外观**：经典、星尘、弹性、留声；留声包含唱盘、唱臂、仪表、歌词和主题开场。
- **媒体库连接**：Plex、Emby、飞牛音乐、极音乐、Navidrome / Subsonic、WebDAV。
- **歌词与播放**：原格式播放、同步歌词、全屏歌词、歌词时间校准、待播队列；手机端支持横屏播放和睡眠定时。
- **写入 NAS**：手机连接 NAS 的 WebDAV 后，可将在线歌曲入库、写回歌词与封面、清理重复和规范命名；支持多台 NAS 与断点续传。
- **音效与统一响度**：十款预设与低频、高频、声场宽度、混响微调；统一响度依据回放增益或 Plex 响度分析。
- **本机音乐**：缓存曲目、本地歌单、头像封面、排序与下载管理；手机支持文件夹曲库、长按多选、批量导出和清理删除。
- **推荐与报告**：每日推荐、好久没听、时段常听和听歌报告；手机可配对部署在 NAS 上的「听己 · AI音乐助理」，获取基于声音与歌词特征的推荐、歌单和听歌画像。
- **听己联动**：配对自己部署在 NAS 上的听己后，在线入库、歌单补全、整理、洗版、刮削写回和标签修正由听己在 NAS 内完成，可撤销；数据只在设备与你自己的 NAS 之间传输，同步内容默认全部关闭。电视也可配对，播放在线歌曲时入库到 NAS。
- **Pro 功能**：多库合并、频谱背景、在线发现、曲库管家；手机可预览更高音质候选并执行备份替换与撤销。

## 授权与音乐内容

新安装有 3 天基础功能试用，官网可领取 60 天 Pro 内测码。一个付费授权码可分别激活一台 Apple TV 和一台 iOS 设备。

音屿不提供音乐内容，也不内置第三方音源。在线发现与在线播放需自行导入兼容且可用的模块或音源。

## 文件校验

每次发布附带 `SHA256SUMS.txt`。在 Mac 的终端中，进入安装包和校验文件所在目录后执行：

```sh
shasum -a 256 -c SHA256SUMS.txt
```

## 反馈

请在 Issues 中说明设备型号、系统版本、应用版本、媒体库类型、操作步骤和实际表现。截图请遮挡服务器地址、账号和授权码，不要公开密码或令牌。
