# TENGlish Android 0.1.2（3）

[下载 TENGlish-0.1.2-3-cn.apk](https://github.com/cleantengflight/tenglish-android-downloads/releases/download/v0.1.2-3/TENGlish-0.1.2-3-cn.apk)，约 15.6 MB，支持 Android 8.0 及以上。请下载 APK，不要下载 Source code 压缩包。

## 本版更新

- 课程、场景照片和地区导语改为共用一套资源版本，支持与新版 iOS 使用相同内容。
- 通过统一 ION 服务获取资源；相同文件复用本地副本，只下载变化部分。
- 保留当前完整资源，整包校验后供下次完整启动使用；下载失败、内容损坏时可回退。
- 启动、返回前台及跨本地零点时检查更新；成功后当天不重复，失败后至少间隔一小时再试。
- 保留最新版 V12 图标、iOS 风格布局、收藏、复习、英文学习及可展开的中文辅助。

本版不调用 AI，不增加账号、云同步、广告或学习资料上传。更新机制不代表每日自动新增课程或无限内容。

## 随包内容与来源

共享资源版本：`shared-64f9c833c62676b521af`，共 27 个文件、4,993,540 字节。包含 109 个生活场景、327 个任务、687 条来源例句、16 张授权照片及 256 份英文地区导语。

| 内容 | 来源与许可 |
|---|---|
| 场景课程、教学说明和迁移练习 | CleanTENGflight 编排；与第三方例句来源分别标明，不把全部练习说成语料原句 |
| NGSL 1.2 | Charles Browne、Brent Culligan、Joseph Phillips；CC BY-SA 4.0；2,809 个排名词及 52 个补充词 |
| Tatoeba 例句 | 674 条 CC BY 2.0 FR、13 条 CC0 1.0；逐句保留作者、原文链接、许可与哈希；中文翻译与选择元数据单独标明 |
| 16 张场景照片 | 逐图保留 Wikimedia Commons 来源、摄影者、CC BY / CC BY-SA / CC0 许可和改动说明；原照片未改变，显示时可裁切 |
| 256 份地区导语 | Wikipedia contributors；CC BY-SA 4.0；保留原文修订版本、时间和哈希，最多五句导语，并非完整国家文章 |

完整可下载归属记录：[语料许可](https://cleantengflight.com/tenglish/resources/v1/versions/shared-64f9c833c62676b521af/learning/corpus/CORPUS-LICENSES.txt)、[逐句来源与作者](https://cleantengflight.com/tenglish/resources/v1/versions/shared-64f9c833c62676b521af/learning/corpus/tatoeba-v1.json)、[逐图摄影者与许可](https://cleantengflight.com/tenglish/resources/v1/versions/shared-64f9c833c62676b521af/learning/media/CREDITS.txt)、[图片元数据](https://cleantengflight.com/tenglish/resources/v1/versions/shared-64f9c833c62676b521af/learning/media/practice-artwork.json)、[地区导语与修订记录](https://cleantengflight.com/tenglish/resources/v1/versions/shared-64f9c833c62676b521af/learning/regions/introductions-v1.json)。这些来源不代表作者或机构对应用的背书。

## 验证与升级

共享资源更新专项测试、正式签名、V12 图标像素、全部 27 份资源与统一源文件一致性、16 KB 对齐检查通过。ION 共享资源及旧版兼容接口共 37 个公开地址验证通过；Android 与 iOS 原生客户端的实际服务加载、校验及缓存验证分别通过。

配套 iOS 共享资源客户端 1.5.1（48）已可供现有内部测试员通过 TestFlight 安装，暂不提供公开 iOS 下载。本次公开下载发布的是 Android 0.1.2（3）。

本版与 0.1.0、0.1.1 使用同一包名和签名，可覆盖安装，请勿先卸载。真机体验仍需反馈，模拟器或构建验证不代表所有手机已验证。公开下载不代表已通过安卓应用商店审核。

文件：`TENGlish-0.1.2-3-cn.apk`，15,603,123 字节。

SHA-256：

```text
9c06a58da3d449e934bcc55ad4914a7946484ce57440ba215a2aa37f3fd7930d
```

[安装说明](INSTALL.md) · [隐私说明](PRIVACY.md)
