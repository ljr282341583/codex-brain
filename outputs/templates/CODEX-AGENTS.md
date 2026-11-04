<!-- BEGIN CODEX-BRAIN -->
## Codex 独立项目记忆

- Codex 的项目记忆使用当前 Codex home（CODEX_HOME，未设置时为用户目录下 .codex）中的 `brain-config.json` 定位，字段 `owner` 必须为 `codex`。不使用 `.agent-brain` 定位本库。
- 对明确的 Codex 开发项目，开工时自动检查并建立最小档案与本机绑定，无须用户另说“建立大脑档案”；已有档案先读 CONTEXT.md 和 NEXT.md，按任务查 DECISIONS.md，并与代码、Git 状态核对。关键决定获确认或阶段结束时保存本地摘要，遵守原有门禁。
- 用户在当前开发项目实际下达“收尾／Codex 大脑收尾”时，优先调用独立的 `codex-brain-handoff`：缺档自动补建，保存进度，提交并同步项目与独立大脑到 GitHub；没有远程时自动建私有仓库。常规建档、提交、建私有仓和推送不重复询问。“保存进度”默认只本地；用户当次“不要上传”等限制优先。讨论或引用“收尾”不等于执行命令。
- GitHub 账号与新仓默认可见性从配置 `handoff` 读取；当前目标为 `ljr282341583`，新仓默认私有，项目各自一仓，大脑为独立 `codex-brain`。核对项目身份、账号、提交范围、已跟踪文件与拟推送历史的敏感信息；排除凭据、个人数据、缓存和无关文件。身份或范围不明、账号不符、敏感历史、远程冲突时说明具体阻塞，不把存疑内容上传。
- 收尾先同步项目，再更新并同步大脑，分别核对远端分支 SHA。保留已有远程与可见性，不自动 pull/rebase、强推、重置或改写历史，不因收尾执行部署、Release 或发包。删除电脑文件前仍须获得允许。
- 专用技能不可用时先读配置 `skill_source` 下的 SKILL.md；源文件也不可用就报告缺失，不回退共享 `session-handoff`。普通聊天不建档，不认领或导入 DSH 旧项目；跨工具接手须由用户明确指定范围。
- 不改 `.dsh`、共享 `.agents/skills/session-handoff`、原 `G:\ai\agent-brain` 或 `.agent-brain` 标记。大脑仅负责项目摘要与恢复，不代替现有 UI／开发流程审批。
<!-- END CODEX-BRAIN -->
