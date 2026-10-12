# 版本沿革

2026-10-11 补齐早期历史记录，2026-10-12 继续补齐留声集成与开屏修复记录。此前公开下载由手机 0.4.7／TV 1.8.34 更新至手机 1.0.5／TV 1.8.48；当前推荐安装包为[手机 1.0.11／TV 1.9.0](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.9.0-iOS-1.0.11)。

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
| [iOS 1.0.11](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.9.0-iOS-1.0.11) | 48 | 2026-10-12 | 恢复稳定根导航挂载，开屏独立接收触控；修复留声开屏顶部重叠 | 当前推荐，用户真机确认 |
| [tvOS 1.9.0](https://github.com/songdone/SongLibAmp-Release/releases/tag/tvOS-1.9.0-iOS-1.0.11) | 68 | 2026-10-12 | 调整留声唱盘仪表与右栏，完善循环和字号；主题→全屏→竖向更多→列表→进度 | 当前推荐，12 项最终遥控复测及用户确认 |
