# 更新记录

按 GitHub Release 标签记录；应用内部版本当前为 1.0.0，下载时以 Release 标签区分构建。

## build-20261107-memory — 2026-11-07

- 新增长期记忆列表，支持主题与内容编辑、添加、删除、筛选及批量启用停用。
- 自动记忆总开关仅控制 AI 主动保存；每条参与回答独立控制，已有启用记忆跨对话使用。
- 相同内容去重，同主题更新 AI 记录，保护用户手动维护及停用的记忆；支持加密备份。
- AI 任务支持安全节点暂停、继续、消息排队、编辑取消、停止当前任务；队列在重启后暂停恢复。
- 命令卡片默认显示命令和输出两行摘要，点击内容展开收起；复制、选中文字和键盘操作正常。

## [build-20261107-avatar](https://github.com/HANLINGVABCN/shellpilot/releases/tag/build-20261107-avatar) — 2026-11-07

- 新的琥珀色终端脸头像，统一 Windows、Android、托盘、浏览器与应用界面图标。
- 历史对话直接显示删除入口，支持单条、批量删除和清空。
- 在菜单内确认删除，错误时保留记录，删除当前对话同步清理消息，运行任务受到保护。
- 修复历史菜单越出聊天面板与无效时间显示。

## [build-20261107-fix](https://github.com/HANLINGVABCN/shellpilot/releases/tag/build-20261107-fix) — 2026-11-07

- 首次 SSH 自动记录身份，后续变化才暂停；提示位于当前机器内容区，顶部导航固定。
- 总览和列表提供身份变化处理入口，切换机器不会显示其他服务器的指纹。
- Windows PowerShell/CIM 原生性能采集，避免把采集失败混同于 SSH 断连。
- 对齐机器选择菜单，固定 192px 标签及关闭按钮位置。
- MCP 增加完全托管，AI 四项预算默认 0，不设应用上限。

## [build-20261107](https://github.com/HANLINGVABCN/shellpilot/releases/tag/build-20261107) — 2026-11-07

- 内置 AI 与 MCP 共用 9 个工具、连接池、权限和审计。
- 批量命令、批量指标、诊断、日志、分页读文件、文件预览与备份校验。
- 任务停止、完整工具结果、重复失败处理、长消息折叠及机器范围清理。
- Android 单页导航，Windows 窗口大小和位置记忆。

## [v1.0](https://github.com/HANLINGVABCN/shellpilot/releases/tag/v1.0) — 2026-11-04

- 初期 Windows 与 Android 发布，提供 SSH 工作台、监控和 AI 对话。
