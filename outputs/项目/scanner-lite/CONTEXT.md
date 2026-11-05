# CONTEXT — scanner-lite

## 项目身份

- 来源工具：Codex
- 项目 ID：scanner-lite
- 代码根目录：G:\ai\codex projects\projects\01_软件开发\scanner-lite
- Git 远程身份：暂无（项目尚未初始化 Git）
- 建档日期：2026-11-05

## 项目目标

构建一个面向个人用户的 Android 文档扫描 APK，支持单页/多页扫描、PDF 导出，以及通过微信/QQ 等应用分享。

## 当前阶段与约束

- 当前阶段：P5 交付后修复（0.2.3）。
- 已确认：用户为个人；核心能力为单页/多页扫描、PDF 导出、微信/QQ 分享；按 UI 优先流程推进。
- 已确认：Kotlin + Jetpack Compose + CameraX，最低 Android 8.0（API 26）；本地优先、不做账号/云同步/OCR；首页以“开始扫描”为唯一主操作，文档列表为次入口。
- 硬约束：P1 原型和设计 token 通过前，不写界面代码；不修改 DSH 资产。
- 当前实现：多页模式在相机页连续拍摄，点击“完成（N 页）”后进入整理；拍摄图片执行 EXIF 方向校正、保守纸张亮区裁边、灰度和对比度增强。

## 关键入口

- 需求卡：[docs/PRD.md](G:\ai\codex projects\projects\01_软件开发\scanner-lite\docs\PRD.md)
- 决策记录：[docs/DECISIONS.md](G:\ai\codex projects\projects\01_软件开发\scanner-lite\docs\DECISIONS.md)

## 与其他记录的关系

本文件只保存项目摘要与恢复索引；需求、UI 设计、接口契约和验收文档仍以项目 docs 为准。
