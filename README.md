# Hi, I'm 507 👋

我主要在做 `AI Agent`（AI 智能体）的工作流与工具：一部分是在 [Pi](https://github.com/earendil-works/pi) 中补齐规划、协作、可观测性和本地能力，另一部分是把实践沉淀为可复用、跨宿主的 `Agent Skills`（智能体技能）。

我关心的不只是让 Agent 多做几个动作，而是让它知道如何开始、怎样继续、如何验证，以及什么时候才算真正完成。

## Pi extensions（Pi 扩展）

### 工作流与协作

- [`pi-dgoal`](https://github.com/ssdiwu/pi-dgoal) — 用分层计划与持续建检循环，让 Agent 推进到经过独立验证的完成状态。
- [`pi-dteam`](https://github.com/ssdiwu/pi-dteam) — 面向多 Agent 工作流的轻量协作与编排系统。
- [`pi-dask`](https://github.com/ssdiwu/pi-dask) — 在终端中收集单选、复选等结构化用户决策。
- [`pi-autoname`](https://github.com/ssdiwu/pi-autoname) — 根据对话语义自动生成并更新 Pi 会话名称。

### 交互与可观测性

- [`pi-dhashline`](https://github.com/ssdiwu/pi-dhashline) — 用行号与内容哈希锚定更可靠的读取、编辑和搜索。
- [`pi-di18n`](https://github.com/ssdiwu/pi-di18n) — 为 Pi 提供 TUI（终端用户界面）、摘要与思考语言的完整本地化支持。
- [`pi-dstatus`](https://github.com/ssdiwu/pi-dstatus) — 可配置的多行 Powerline（分段式）状态栏。
- [`pi-dusage`](https://github.com/ssdiwu/pi-dusage) — 检查 Codex、z.ai Coding CN 与 MiniMax CN 等服务的额度状态。
- [`pi-daily`](https://github.com/ssdiwu/pi-daily) — 从本地会话活动生成按项目组织的工作日报。
- [`pi-token-stats`](https://github.com/ssdiwu/pi-token-stats) — 只读聚合会话消耗、工具活动、项目进展与日报洞察。

### 能力与集成

- [`pi-sense`](https://github.com/ssdiwu/pi-sense) — 让纯文本模型理解图片与本地视频。
- [`pi-tinyfish`](https://github.com/ssdiwu/pi-tinyfish) — 提供网页搜索、内容抓取与目标驱动的浏览器自动化。
- [`pi-reminders`](https://github.com/ssdiwu/pi-reminders) — 通过 Pi 使用 Apple Reminders（苹果提醒事项）。
- [`pi-key-pool`](https://github.com/ssdiwu/pi-key-pool) — 提供按会话轮换、冷却恢复与智能重试的 API Key（接口密钥）池。
- [`pi-marketplace`](https://github.com/ssdiwu/pi-marketplace) — 搜索、审查并安装 npm（Node 包注册表）中的 Pi 扩展。
- [`pi-pdf-watermark`](https://github.com/ssdiwu/pi-pdf-watermark) — 为 PDF（便携式文档格式）添加自定义文字水印的 Pi Skill（Pi 技能）。

<details>
<summary>早期 Pi 实验</summary>

- [`pi-compaction-i18n`](https://github.com/ssdiwu/pi-compaction-i18n) — 压缩与分支摘要本地化，能力现已整合进 `pi-di18n`。
- [`pi-dvision`](https://github.com/ssdiwu/pi-dvision) — 让纯文本模型理解图片的早期实现，后续演进为支持图片与视频的 `pi-sense`。

</details>

## Agent Skills（智能体技能）

[`507-skills`](https://github.com/ssdiwu/507-skills) 是我维护的一组工作流型 Agent Skills。它把工作方法拆成可以独立触发、自由组合、通过明确产物接力的技能；每个 Skill 都说明什么时候使用、解决什么问题、产出什么，以及何时结束。

- [`common/`](https://github.com/ssdiwu/507-skills/tree/main/common) — 项目探索、概念解释、外部研究、决策对齐与会话移交。
- [`code/`](https://github.com/ssdiwu/507-skills/tree/main/code) — 产品规格、原型、工单、修复、测试、审查、提交与发布。
- [`write/`](https://github.com/ssdiwu/507-skills/tree/main/write) — 从素材、观点与视频，到文章、讲稿、方案和发布适配。

这套 Skills 不绑定某一个 Agent 产品。我的目标，是让同一套工作方法可以在不同宿主中保持一致的边界、产物与完成标准。
