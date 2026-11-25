# TENGlish Android 0.1.3（4）

[下载 TENGlish-0.1.3-4-cn.apk](https://github.com/cleantengflight/tenglish-android-downloads/releases/download/v0.1.3-4/TENGlish-0.1.3-4-cn.apk)，约 15.6 MB，支持 Android 8.0 及以上。请下载 APK，不要下载 Source code 压缩包。

## 本版更新

- 接入与 iOS 共用的已生成配图，首页、场景、课程和题目优先显示匹配图片。
- 按场景、学习点和题目上下文匹配，区分美式、英式情境；填空例句不借用其他题目的 AI 图。
- 图片显示“AI 生成”标注，来源中保留 OpenAI、gpt-image-2 模型与生成说明。
- 已下载图片保存在本机，预加载当前学习内容和后续题目；断网时使用缓存或授权照片。
- 只读取公开图片文件，不调用模型，不发起生成任务，不上传学习资料。

现有课程、地区、收藏、复习和最新版图标保留。资源更新取决于服务端已发布内容，不代表每天必有新图或无限内容。

这些配图是 TENGlish 已发布的 AI 学习插图，并非实拍照片，也不属于下面 16 张授权场景照片。图片与题目不匹配时不显示；没有匹配资源时使用授权场景照片，不保证每道题都有独立 AI 配图。

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

已通过 9 项 JVM 专项测试、3 项 Android 流程测试，以及真实下载、本地缓存与离线读取验证。Release 构建与 Lint 通过（0 个错误、15 个警告）；签名、最新版图标、16 KB 对齐及共享资源一致性校验通过。已验证从 0.1.2（3）覆盖安装本版。

APK：15,635,891 字节。SHA-256：

```text
2156443030eb9b33a2f9337dcd666dea7efc5d8e4614356413cb953268c6ba82
```

配套 iOS 1.5.1（48）已可供现有内部测试员通过 TestFlight 安装，暂不提供公开 iOS 下载。本次只更新 Android。

本版沿用原包名和签名，可直接覆盖安装；不要先卸载。模拟器验证不代表所有手机均已验证。

[安装说明](INSTALL.md) · [隐私说明](PRIVACY.md)
