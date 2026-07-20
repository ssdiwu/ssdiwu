# Hi, I'm 507 👋

I build workflows and tools for AI agents. Some of my work extends [Pi](https://github.com/earendil-works/pi) with better planning, collaboration, observability, and local capabilities; the rest turns what I learn into reusable, host-agnostic Agent Skills.

I care less about making agents do more things than helping them understand how to start, how to keep going, how to verify their work, and when a task is actually done.

## Pi extensions

### Workflows and collaboration

- [`pi-dgoal`](https://github.com/ssdiwu/pi-dgoal) — Keeps agents moving toward independently verified completion with layered plans and build-check loops.
- [`pi-dteam`](https://github.com/ssdiwu/pi-dteam) — A lightweight multi-agent orchestration system for Pi.
- [`pi-dask`](https://github.com/ssdiwu/pi-dask) — Collects structured user decisions, including single-choice and multiple-choice answers, inside the terminal.
- [`pi-autoname`](https://github.com/ssdiwu/pi-autoname) — Automatically generates and updates semantic names for Pi sessions.

### Interface and observability

- [`pi-dhashline`](https://github.com/ssdiwu/pi-dhashline) — Hash-anchored read, edit, and search tools for more reliable file operations.
- [`pi-di18n`](https://github.com/ssdiwu/pi-di18n) — Full localization for Pi's TUI, summaries, and LLM-facing tool descriptions.
- [`pi-dstatus`](https://github.com/ssdiwu/pi-dstatus) — A configurable, multi-line Powerline status bar.
- [`pi-dusage`](https://github.com/ssdiwu/pi-dusage) — Checks provider quotas across Codex, z.ai Coding CN, and MiniMax CN.
- [`pi-daily`](https://github.com/ssdiwu/pi-daily) — Generates project-based daily work reports from local session activity.
- [`pi-token-stats`](https://github.com/ssdiwu/pi-token-stats) — Provides read-only insights into session usage, tool activity, project progress, and daily reports.

### Capabilities and integrations

- [`pi-sense`](https://github.com/ssdiwu/pi-sense) — Gives text-only models an understanding of images and local videos.
- [`pi-tinyfish`](https://github.com/ssdiwu/pi-tinyfish) — Adds web search, content extraction, and goal-driven browser automation.
- [`pi-reminders`](https://github.com/ssdiwu/pi-reminders) — Connects Pi with Apple Reminders.
- [`pi-key-pool`](https://github.com/ssdiwu/pi-key-pool) — Manages API keys with session-based rotation, cooldown recovery, and smart retries.
- [`pi-marketplace`](https://github.com/ssdiwu/pi-marketplace) — Searches, audits, and installs Pi packages from npm.
- [`pi-pdf-watermark`](https://github.com/ssdiwu/pi-pdf-watermark) — A Pi skill for adding custom text watermarks to PDF files.

<details>
<summary>Earlier Pi experiments</summary>

- [`pi-compaction-i18n`](https://github.com/ssdiwu/pi-compaction-i18n) — Localized compaction and branch summaries; this capability is now part of `pi-di18n`.
- [`pi-dvision`](https://github.com/ssdiwu/pi-dvision) — An early image-understanding extension that later evolved into the image-and-video workflow in `pi-sense`.

</details>

## Agent Skills

[`507-skills`](https://github.com/ssdiwu/507-skills) is a collection of workflow-oriented Agent Skills. It breaks working methods into skills that can be triggered independently, combined as needed, and connected through explicit deliverables. Each skill defines when to use it, what problem it solves, what it produces, and when it is complete.

- [`common/`](https://github.com/ssdiwu/507-skills/tree/main/common) — Project exploration, concept explanation, external research, decision alignment, and handoffs.
- [`code/`](https://github.com/ssdiwu/507-skills/tree/main/code) — Product specifications, prototypes, issue workflows, fixes, tests, reviews, commits, and releases.
- [`write/`](https://github.com/ssdiwu/507-skills/tree/main/write) — Turning source material, ideas, and video into articles, scripts, proposals, and publishing adaptations.

These skills are not tied to any single agent product. The goal is to preserve clear boundaries, deliverables, and completion criteria across different agent environments.
