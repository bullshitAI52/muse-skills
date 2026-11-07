# 无限画布：Muse＋BeefTV 视频实操教程

[返回首页](../README.md)

## 用途

把 Muse 的图片与视频生成能力接进本地无限画布（BeefTV），从角色图、分镜首帧做到一段带剧情字幕的短视频成片。面向没有视频制作经验、想用 Agent 组合工具完成一次创作的人。

## 内容类型

- `Muse无限画布实操教程.md`：Markdown 教程，GitHub 直接渲染，含成片拆解、五方分工、画布结构、四步部署（MacBook）、五步实操、可复制的 Agent 接入指令、局限与避坑。
- 本页：用途、步骤与来源说明。

## 使用步骤

1. 按教程第 04 节部署：装 BeefTV 桌面版，Docker 起 muse2api，Chrome 扩展导入 Muse 登录态，BeefTV 模型配置指向 `http://localhost:18610`，先验一张图、再验一个视频。
2. 按教程五步实操：新建画布 → 提目标 → 看结果 → 反馈纠正 → 先跑通一个镜头再扩成多镜头。
3. 去 Muse 网页核对生成记录，确认任务确实在 Muse 上生成；最后进时间线加字幕成片。

## 验证状态

- 部署与操作步骤来自公开文档与原文作者的实测记录，未在本机逐项验证；软件版本与账号状态会变，以官方文档为准。
- muse2api 是第三方桥接项目，不是 Muse 官方 API；生成消耗自己 Muse 账号的额度，存在账号风险。MacBook 睡眠会中断服务，18610 端口不要对外暴露。

## 来源

- 原文：森叔 @harrisonitsme 的 X 文章《Muse＋无限画布实操，从角色图到视频成片（保姆级教程）》，2026 年 11 月 7 日，https://x.com/harrisonitsme/status/2119044513155158242
- 画布：[BeefTV](https://github.com/glanderness/BeefTV)
- 桥接：[muse2api](https://github.com/czg86389-hub/muse2api)

教程页为原文的整理版（非逐字转载），方法与链接均来自原文。

## 下载

- BeefTV 桌面版 v2.1.6（安装包单个超过 100MB，GitHub 仓库放不下，只放直链）：
  - macOS（苹果芯片）：https://github.com/glanderness/BeefTV/releases/download/v2.1.6/BeefTV-v2.1.6-darwin-arm64.dmg
  - macOS（Intel）：https://github.com/glanderness/BeefTV/releases/download/v2.1.6/BeefTV-v2.1.6-darwin-amd64.dmg
  - Windows：https://github.com/glanderness/BeefTV/releases/download/v2.1.6/BeefTV-v2.1.6-windows-amd64-setup.exe
  - Linux：https://github.com/glanderness/BeefTV/releases/download/v2.1.6/BeefTV-v2.1.6-linux-amd64.deb
- muse2api 源码压缩包：直接下载 https://github.com/czg86389-hub/muse2api/archive/refs/heads/main.zip（主分支最新版，237KB；浏览器传不了二进制附件，所以用直链，下载到的是同样的代码）
