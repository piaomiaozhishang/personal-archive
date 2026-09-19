# 个人体验档案库 PersonalArchive

> 写的时候像便签一样快，整理的时候像归档一样准，找的时候一句话就能搜到，回顾的时候能看到自己走过的路。

一个面向个人的 Android 应用，用来记录自己**做过、玩过、看过、吃过、去过**的一切。它不是普通日记本——而是一套按「分类 → 条目 → 日志时间线 → 附件」组织的个人体验档案。

## 特性

- **极速记录**：打开 App 直接写，一句话就是一条记录；支持拍照、相册、文字识别、语音输入。
- **分类记录**：小说、动漫、游戏、影视、运动、地点……分类可自定义，可增删改、排序、换图标和颜色。
- **条目时间线**：同一个条目下不断追加日志（开始看 / 看到第 30 章 / 看完 / 弃坑），旧日志只追加不覆盖。
- **待整理箱**：随手写的内容先进待整理箱，支持本地规则与 AI 一键整理。
- **强大搜索**：标题 / 别名 / 标签 / 分类 / 日志全文，支持拼音与拼音首字母，可扩展语义搜索。
- **那年今天**：自动回顾往年同一天的记录，并每日推送。
- **统计回顾**：年度/月度/周度/当日总结、分类占比、热力图、AI 总结（普通/详细）。
- **数据自主**：数据保存在本机，支持 Markdown / TXT / JSON 导出与 ZIP 备份恢复。
- **隐私优先**：应用锁 / 指纹、AI 默认关闭、核心功能完全离线可用。
- **性能**：Room 索引 + WAL、Paging 3、图片缩略图、FTS/2-gram 搜索、WorkManager 后台任务，长期使用不卡。

## 技术栈

- Kotlin · Jetpack Compose · Material 3
- Room · Hilt · Navigation Compose · Coil · DataStore · WorkManager
- minSdk 26 / targetSdk 35
- AI（可选）：OpenAI 兼容接口 / Gemini / Anthropic / 本地 Ollama，密钥加密存储

## 构建

1. Android Studio Hedgehog 或更新版本（JDK 17）
2. `./gradlew :app:assembleRelease`
3. 产物：`app/build/outputs/apk/release/app-release.apk`

## 下载

前往 [Releases](../../releases) 页面下载最新 APK。

## 开源许可

[Apache License 2.0](LICENSE) © 缥缈之上

如果这个应用对你有帮助，欢迎请作者喝杯柠檬水。
