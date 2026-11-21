# BugHunter 防御代码审查 · BugHunter Defensive Code Review

审查本地源代码、补丁和配置，按源码证据整理发现、影响范围和修复建议。

在 AGH「插件 → 市场 → 社区」安装 `@wblxr408/bughunter-code-review`，然后从「智能体」打开「BugHunter 防御代码审查」。补充要审查的文件、提交或工作区差异后发送。也可在会话中输入 `$` 选择 Skill。

智能体入口采用只读审查预设。报告包含源码位置、被违反的安全约束、影响范围和建议修复。适合维护者评审权限检查、数据隔离和敏感信息处理。

本包包含 [Skill](skills/bughunter-code-review/SKILL.md) 和启动配置。方法来源见 [NOTICE](NOTICE)。
