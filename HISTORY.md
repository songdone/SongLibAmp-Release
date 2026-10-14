# 版本沿革

2026-10-11 补齐早期历史记录，2026-10-12 继续补齐留声集成与开屏修复记录。此前公开下载由手机 0.4.7／TV 1.8.34 更新至手机 1.0.5／TV 1.8.48；2026-10-14 补充手机 1.1.0–1.2.2 与 TV 1.9.1–1.9.3 记录，当前推荐安装包为[手机 1.2.8／TV 1.9.5](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.9.5-iOS-1.2.8)。手机 1.1.0–1.2.1、1.2.3–1.2.7 与 TV 1.9.1–1.9.2、1.9.4 未公开发布，不提供安装包。

独立历史条目不附安装包；已公开的稳定组合版本保留原发行资产，可核验的中间版本原始 IPA 及符号在私有源码仓库按版本归档。手机 0.4.10–0.4.13、1.0.1、1.0.3、1.0.4 的已知故障均保留记录。手机 1.0.6–1.0.10 经后续复测，确认仅留声主题开启启动动画后存在顶部与状态栏重叠，关闭启动动画后正常；这些问题版本不提供公开安装包，修复已在 1.0.11 获用户真机确认。

| 平台 / 版本 | build | 源码记录日期 | 主要变更 | 状态 |
| --- | --- | --- | --- | --- |
| [iOS 0.4.8](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-0.4.8) | 28 | 2026-10-04 | 电视 1.8.35 / 手机 0.4.8：视觉重构第一批，「我的」改成听歌数据页、设置进齿轮、墨金 / 雾白配色 | 历史记录 |
| [iOS 0.4.9](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-0.4.9) | 29 | 2026-10-06 | 电视 1.8.36 / 手机 0.4.9：视觉重构第 3～6 批、歌手照片与补封面、修频谱动效跟不上音乐 | 历史记录 |
| [iOS 0.4.10](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-0.4.10) | 30 | 2026-10-06 | 电视 1.8.37 / 手机 0.4.10：基础防逆向加固；频谱按先行版实施记录再修三处 | 问题记录，无安装包 |
| [iOS 0.4.11](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-0.4.11) | 31 | 2026-10-06 | 电视 1.8.38 / 手机 0.4.11：推荐列表每首歌带一句推荐理由，同一首歌的不同版本只留一个 | 问题记录，无安装包 |
| [iOS 0.4.12](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-0.4.12) | 32 | 2026-10-08 | 电视 1.8.39 / 手机 0.4.12：收藏取全并按排序排、审查遗留收尾、设置里加「支持与诊断」 | 问题记录，无安装包 |
| [iOS 0.4.13](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-0.4.13) | 33 | 2026-10-08 | 电视 1.8.40 / 手机 0.4.13：接入「星尘」「弹性」两套外观主题，实测修补与组件动效 | 问题记录，无安装包 |
| [iOS 0.4.14](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-0.4.14) | 34 | 2026-10-08 | 手机 0.4.14：修 iOS 16～17.3 一打开就闪退 | 历史记录 |
| [iOS 0.4.15](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-0.4.15) | 35 | 2026-10-09 | 电视 1.8.41 / 手机 0.4.15：主题组件动效补齐、iOS 16 一批、主题分享卡片、启动动画四选一、开屏跟随昼夜、播放模式记住 | 历史记录 |
| [iOS 0.4.16](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-0.4.16) | 36 | 2026-10-10 | 电视 1.8.42 / 手机 0.4.16：检查更新、连接测试、Navidrome / Jellyfin、报错改书面、开机首页黑带、播放页外观入口 | 历史记录 |
| [iOS 1.0.0](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-1.0.0) | 37 | 2026-10-11 | 手机 1.0.0 / 电视 1.8.43：补齐文件夹曲库与异常 MP3 定位，完成手机回归 | 历史记录 |
| [iOS 1.0.1](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-1.0.1) | 38 | 2026-10-11 | 补齐缓存来源与实际音质识别，验证本地多选导出删除及断库资料 | 问题记录，无安装包 |
| [iOS 1.0.2](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-1.0.2) | 39 | 2026-10-11 | 修复本地歌曲滚动与多选手势，屏蔽同次长按的松手点击并验证160首列表 | 历史记录 |
| [iOS 1.0.3](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-1.0.3) | 40 | 2026-10-11 | 修复主题开屏显示时钟与手机首帧交接，保留完整动画并回归重复启动 | 问题记录，无安装包 |
| [iOS 1.0.4](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-1.0.4) | 41 | 2026-10-11 | 修复手机完整口号后永久等待，独立挂载探测及双信号缺失回归并升级1.0.4 | 问题记录，无安装包 |
| [tvOS 1.8.35](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.35) | 53 | 2026-10-04 | 电视 1.8.35 / 手机 0.4.8：视觉重构第一批，「我的」改成听歌数据页、设置进齿轮、墨金 / 雾白配色 | 历史记录 |
| [tvOS 1.8.36](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.36) | 54 | 2026-10-06 | 电视 1.8.36 / 手机 0.4.9：视觉重构第 3～6 批、歌手照片与补封面、修频谱动效跟不上音乐 | 历史记录 |
| [tvOS 1.8.37](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.37) | 55 | 2026-10-06 | 电视 1.8.37 / 手机 0.4.10：基础防逆向加固；频谱按先行版实施记录再修三处 | 历史记录 |
| [tvOS 1.8.38](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.38) | 56 | 2026-10-06 | 电视 1.8.38 / 手机 0.4.11：推荐列表每首歌带一句推荐理由，同一首歌的不同版本只留一个 | 历史记录 |
| [tvOS 1.8.39](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.39) | 57 | 2026-10-08 | 电视 1.8.39 / 手机 0.4.12：收藏取全并按排序排、审查遗留收尾、设置里加「支持与诊断」 | 历史记录 |
| [tvOS 1.8.40](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.40) | 58 | 2026-10-08 | 电视 1.8.40 / 手机 0.4.13：接入「星尘」「弹性」两套外观主题，实测修补与组件动效 | 历史记录 |
| [tvOS 1.8.41](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.41) | 59 | 2026-10-09 | 电视 1.8.41 / 手机 0.4.15：主题组件动效补齐、iOS 16 一批、主题分享卡片、启动动画四选一、开屏跟随昼夜、播放模式记住 | 历史记录 |
| [tvOS 1.8.42](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.42) | 60 | 2026-10-10 | 电视 1.8.42 / 手机 0.4.16：检查更新、连接测试、Navidrome / Jellyfin、报错改书面、开机首页黑带、播放页外观入口 | 历史记录 |
| [tvOS 1.8.43](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.43) | 61 | 2026-10-11 | 手机 1.0.0 / 电视 1.8.43：补齐文件夹曲库与异常 MP3 定位，完成手机回归 | 历史记录 |
| [tvOS 1.8.44](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.44) | 62 | 2026-10-11 | 修复电视三主题开屏明暗闪切并优化启动绘制，版本1.8.44 | 历史记录；后续有修复 |
| [tvOS 1.8.45](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.45) | 63 | 2026-10-11 | 避免首页加载跳过主题开屏，按帧完整播放并保留Release取证 | 历史记录；后续有修复 |
| [tvOS 1.8.46](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.46) | 64 | 2026-10-11 | 等待首页首帧后退场消除开屏空白，减轻星尘渲染并异步解码经典照片 | 历史记录；后续有修复 |
| [tvOS 1.8.47](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.47) | 65 | 2026-10-11 | 降低电视首页大图加载的主线程开销，后台准备歌手排行与照片缓存 | 历史记录；后续有修复 |
| [iOS 1.0.5](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.48-iOS-1.0.5) | 42 | 2026-10-11 | 恢复稳定启动，修正星尘口号与弹性开屏；曾获用户真机确认 | 已公开的历史稳定组合 |
| [tvOS 1.8.48](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.48-iOS-1.0.5) | 66 | 2026-10-11 | 改善三主题开屏交接及首页资料准备，修正异常 MP3 时长与定位 | 已公开的历史稳定组合 |
| [iOS 1.0.6](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-1.0.6) | 43 | 2026-10-11 | 新增留声主题与唱盘仪表，完善收起重开、待播列表和歌词校准 | 问题记录，无安装包 |
| [iOS 1.0.7](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-1.0.7) | 44 | 2026-10-12 | 修正搜索输入与返回手势，完善封面补边、分享场景与可见性调度 | 问题记录，无安装包 |
| [iOS 1.0.8](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-1.0.8) | 45 | 2026-10-12 | 尝试调整导航安全区交接，并接入留声唱片封面处理；真机顶部问题未解决 | 问题记录，无安装包 |
| [iOS 1.0.9](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-1.0.9) | 46 | 2026-10-12 | 尝试恢复页面背景边界和内部停帧调度，补充布局诊断；顶部问题未闭环 | 问题记录，无安装包 |
| [iOS 1.0.10](https://github.com/songdone/SongLibAmp-Release/releases/tag/iOS-1.0.10) | 47 | 2026-10-12 | 移除留声底栏换肤并补根布局诊断；用户复测仍出现留声开屏顶部重叠 | 问题记录，无安装包 |
| [tvOS 1.8.49](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.8.49) | 67 | 2026-10-11 | 新增 TV 留声主题，修正抽屉首帧并补歌词校准、主题与待播入口 | 历史记录，已由 1.9.0 替代 |
| [iOS 1.0.11](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.9.0-iOS-1.0.11) | 48 | 2026-10-12 | 恢复稳定根导航挂载，开屏独立接收触控；修复留声开屏顶部重叠 | 已公开的历史稳定组合，用户真机确认 |
| [tvOS 1.9.0](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.9.0-iOS-1.0.11) | 68 | 2026-10-12 | 调整留声唱盘仪表与右栏，完善循环和字号；主题→全屏→竖向更多→列表→进度 | 已公开的历史稳定组合，12 项最终遥控复测及用户确认 |
| iOS 1.1.0 | 49 | 2026-10-12 | 接入听己配对与推荐同步，各项同步默认关闭 | 历史记录，无安装包 |
| iOS 1.1.1 | 50 | 2026-10-12 | 写入 NAS 重做：选择曲库文件夹、按媒体库自动核对；读取 Emby 文件位置；整理前逐首检查 | 历史记录，无安装包 |
| iOS 1.1.2 | 51 | 2026-10-13 | 写入 NAS 子页面改为底部弹出，修复 iOS 16 导航卡住；只填根地址时自动查找曲库文件夹 | 历史记录，无安装包 |
| iOS 1.1.3 | 52 | 2026-10-13 | 在线歌曲入库到 NAS，本地音乐多选入库；听己入口与连接稳定性修正 | 历史记录，无安装包 |
| iOS 1.1.4 | 53 | 2026-10-13 | 本地音乐与本地缓存分开管理；写入 NAS 地址与账号打码显示 | 历史记录，无安装包 |
| iOS 1.1.5 | 54 | 2026-10-13 | 新增音效与统一响度；iOS 16.6.1 真机播放无声 | 问题记录，无安装包 |
| iOS 1.1.6 | 55 | 2026-10-13 | 音效按需接入效果器并增加出声自检，修复 1.1.5 播放无声 | 历史记录，无安装包 |
| iOS 1.1.7 | 56 | 2026-10-13 | 音效原地切换、耳机适配；FLAC 拖动定位校正；入库只创建缺少的目录 | 历史记录，无安装包 |
| iOS 1.1.8 | 57 | 2026-10-13 | 入库改为临时文件上传、断点续传与后台传输；启动画面改用启动故事板，修复标志被拉伸（真机确认） | 历史记录，无安装包 |
| iOS 1.1.9 | 58 | 2026-10-13 | 写入 NAS 支持添加多台 NAS | 历史记录，无安装包 |
| iOS 1.2.0 | 59 | 2026-10-13 | 核对结论写入运行日志，查询被断开时重试一次 | 历史记录，无安装包；后续有修正 |
| iOS 1.2.1 | 60 | 2026-10-13 | 核对支持文件夹名称不同、歌曲未分文件夹的媒体库；查询被断开时改为列出文件夹确认 | 历史记录，无安装包 |
| tvOS 1.9.1 | 69 | 2026-10-13 | 新增音效与统一响度 | 历史记录，已由 1.9.2 替代 |
| tvOS 1.9.2 | 70 | 2026-10-13 | 音效按需接入效果器并增加出声自检 | 历史记录，无安装包 |
| [iOS 1.2.2](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.9.3-iOS-1.2.2) | 61 | 2026-10-13 | 写入中断后核实实际结果，封面与歌手图片只写入对应文件夹；自定义命名规则、单独刷新媒体库、音源补充刮削 | 已公开的历史稳定组合 |
| [tvOS 1.9.3](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.9.3-iOS-1.2.2) | 71 | 2026-10-13 | 音效原地切换，从当前位置继续播放；FLAC 拖动定位校正 | 已公开的历史稳定组合 |
| iOS 1.2.3 | 62 | 2026-10-14 | 与听己联动：在线歌曲由听己入库、歌单补全与存成飞牛 / Plex 歌单、整理交给听己、统一响度使用听己测量 | 历史记录，无安装包 |
| tvOS 1.9.4 | 72 | 2026-10-14 | 设置新增听己配对，在线歌曲可由听己入库到 NAS | 历史记录，无安装包 |
| iOS 1.2.4 | 63 | 2026-10-14 | 听己繁忙自动重试；曲库对应支持 Emby / Jellyfin、Subsonic / Navidrome；按声音查找重复；写入 NAS 核对遇过时记录先刷新 | 历史记录，无安装包 |
| iOS 1.2.5 | 64 | 2026-10-14 | 曲库对应按真实产品名显示听己来源 | 历史记录，无安装包 |
| iOS 1.2.6 | 65 | 2026-10-14 | 歌曲洗版、刮削写回交给听己 | 历史记录，无安装包 |
| iOS 1.2.7 | 66 | 2026-10-14 | 标签修正；听己页面重排、连接与使用说明、数据与隐私说明 | 历史记录，无安装包 |
| [iOS 1.2.8](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.9.5-iOS-1.2.8) | 67 | 2026-10-14 | 内网地址只读听己公布的地址，不扫描所在网络 | 当前推荐 |
| [tvOS 1.9.5](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.9.5-iOS-1.2.8) | 73 | 2026-10-14 | 听己暂时繁忙时自动重试 | 当前推荐 |
