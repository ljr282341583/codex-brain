# CONTEXT — codex-brain

## 项目身份

- 来源工具：Codex
- 项目 ID：codex-brain
- 本机项目根：`G:\ai\codex projects\projects\01_软件开发\codex-brain`
- 本机笔记根：本项目的 `outputs/项目/`
- 独立 GitHub 目标：`ljr282341583/codex-brain`，私有
- 建档日期：2026-11-05（Asia/Shanghai）

## 项目目标

给 Codex 从零建立独立项目记忆与 GitHub 交接机制，不接管、不迁移 DSH 已有项目，也不改变原大脑与运行配置。

## 已实现范围

- 四件套模板、专用 `codex-brain-handoff` 技能、本机路径配置、Codex 全局管理区块及备份。
- 明确开发任务开工自动建档；决定确认和阶段结束保存本地摘要；“收尾”再次检查并补建档案。
- 实际下达“收尾”时自动保存、提交、必要时建私有仓并推送项目与独立大脑；“保存进度”默认只本地。
- 项目与大脑分别管理；当前维护的项目本身就是大脑仓库，只同步这一份仓库。

## 权威入口

- `outputs/skills/codex-brain-handoff/SKILL.md`：具体执行规则。
- 当前机器 Codex home 的 `brain-config.json`：本机路径、项目绑定与 GitHub 目标。
- `outputs/templates/CODEX-AGENTS.md`：Codex 全局管理区块分发源；其他全局规则不在本库备份范围。
- `outputs/README.md`：用户用法与换机器恢复步骤。

## 约束与验证边界

- DSH 原 `agent-brain`、`.dsh` 配置、共享 `session-handoff` 和 `.agent-brain` 标记保持原样。
- 不上传密钥、账号快照、个人资料、缓存和 `work/` 下本机备份／样本。
- 本机配置检查与本地双仓 Git 演练已通过；没有验证其他真实业务项目和新聊天完整恢复行为。
- 笔记与既有 UI／开发流程互补，不替代审批或推断项目已经可发布。
