<div align="center">

# Agent

**把通用 Agent runtime、skills、工具和协作基础设施放在一张图上。**

[![Snapshot](https://img.shields.io/badge/snapshot-github--universe--2026--08--26-0969DA)](https://github.com/zinan92/park-operating-system)
[![Entries](https://img.shields.io/badge/entries-105-2DA44E)](https://github.com/zinan92/agent)

</div>

---

```text
in  GitHub owned repos + starred repos at a fixed canonical snapshot
out stage catalog + Owned/Starred separation + locked external refs

fail canonical snapshot drift → regenerate from Park OS
fail private source inaccessible → keep link + mark PRIVATE
fail uncategorized repo → review_status=needs_review; do not silently place
```

> Canonical source: [Park OS](https://github.com/zinan92/park-operating-system) · this repo is a generated scoped view.

## At a glance

| Stage | Owned | Starred | Total |
|---|---:|---:|---:|
| 01 Runtimes & Harnesses | 3 | 17 | 20 |
| 02 Multi-Agent Orchestration | 0 | 10 | 10 |
| 03 Skills, Plugins & Marketplaces | 2 | 34 | 36 |
| 04 Memory, Context & Knowledge | 0 | 2 | 2 |
| 05 Tool Use & Integrations | 3 | 8 | 11 |
| 06 Models, Providers & Gateways | 0 | 4 | 4 |
| 07 Development Workflow & Quality | 1 | 9 | 10 |
| 08 Observability & Interfaces | 0 | 3 | 3 |
| 09 Knowledge & References | 0 | 9 | 9 |

## 01 Runtimes & Harnesses

> Codex、Claude Code、OpenClaw 和通用 Agent runtime · **20 repos** (3 owned / 17 starred)

### Owned

| Repo | Capability | State | Source |
|---|---|---|---|
| [zinan92/claw-code](https://github.com/zinan92/claw-code) | The fastest repo in history to surpass 50K stars ⭐, reaching the milestone in just 2 hours after publication. Better Harness Tools, not merely storing the archive of leaked Claude Code but also make real things done. Now rewriting in Rust. | `BUILDING · —` | Owned |
| [zinan92/loop](https://github.com/zinan92/loop) | 把一次性 coding-agent prompt 变成「按价值排序、可审计、可暂停」的执行闭环 · Value-ranked, auditable, pausable coding-agent loop. in: local Git repo + contract → out: GitHub issues/PRs + digest. Codex or Claude, macOS. | `BUILDING · —` | Owned |
| [zinan92/wechat-miniprogram-shipping](https://github.com/zinan92/wechat-miniprogram-shipping) | 证据门控的原生微信小程序交付路由器。in 意图/项目证据 → out 合同、QA verdict、可回退 receipt | `BUILDING · —` | Owned |

### Starred

| Repo | Capability | State / Lock | Source |
|---|---|---|---|
| [AAAAAAAJ/WaytoAGI-CLI](https://github.com/AAAAAAAJ/WaytoAGI-CLI) | WaytoAGI-CLI | `EXPLORING · NEEDS_REVIEW` | Starred · lock e145d1af49ec |
| [BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban) | Get 10X more out of Claude Code, Codex or any coding agent | `EXPLORING · —` | Starred · lock 4deb7eca8f38 |
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | The agent that grows with you | `EXPLORING · —` | Starred · lock a7b8281a16ef |
| [code-yeongyu/oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent) | omo/lazycodex: The coding agent for tokenmaxxers;the one and only agent harness for complex codebases. For your Codex, for your OpenCode | `EXPLORING · —` | Starred · lock 8c57e463e62d |
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | CLI tool for configuring and monitoring Claude Code | `EXPLORING · —` | Starred · lock 3a2f8c031527 |
| [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) | DeepSeek-native AI coding agent for your terminal. Engineered around prefix-cache stability — leave it running. | `EXPLORING · —` | Starred · lock c3f5b497d59c |
| [frankbria/ralph-claude-code](https://github.com/frankbria/ralph-claude-code) | Autonomous AI development loop for Claude Code with intelligent exit detection | `EXPLORING · —` | Starred · lock e8533cc3f009 |
| [garrytan/gstack](https://github.com/garrytan/gstack) | Use Garry Tan's exact Claude Code setup: 23 opinionated tools that serve as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA | `EXPLORING · —` | Starred · lock ad8400543cd9 |
| [karpathy/autoresearch](https://github.com/karpathy/autoresearch) | AI agents running research on single-GPU nanochat training automatically | `EXPLORING · —` | Starred · lock 228791fb499a |
| [mixedbread-ai/mgrep](https://github.com/mixedbread-ai/mgrep) | A calm, CLI-native way to semantically grep everything, like code, images, pdfs and more. | `EXPLORING · —` | Starred · lock 5c1ba628c62d |
| [openai/codex](https://github.com/openai/codex) | Lightweight coding agent that runs in your terminal | `EXPLORING · —` | Starred · lock 3e4707b34b16 |
| [openchamber/openchamber](https://github.com/openchamber/openchamber) | Desktop and web interface for OpenCode AI agent | `EXPLORING · —` | Starred · lock 74290852efef |
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞  | `EXPLORING · —` | Starred · lock 3b64e84f6ea2 |
| [rullerzhou-afk/clawd-on-desk](https://github.com/rullerzhou-afk/clawd-on-desk) | A pixel desktop pet that watches Claude Code, Codex, Cursor & other AI coding agents — so you don't have to. | `EXPLORING · —` | Starred · lock 7ab6a240fb10 |
| [thirdlayerinc/autoagent](https://github.com/thirdlayerinc/autoagent) | autonomous harness engineering | `EXPLORING · —` | Starred · lock eb3f185dc9fa |
| [ultraworkers/claw-code](https://github.com/ultraworkers/claw-code) | An agent-managed museum exhibit, built in Rust with Gajae-Code / LazyCodex — developed and maintained with no human intervention. | `EXPLORING · —` | Starred · lock 08106b0c3771 |
| [vercel-labs/json-render](https://github.com/vercel-labs/json-render) | The Generative UI framework | `EXPLORING · —` | Starred · lock a4d033cf041e |

## 02 Multi-Agent Orchestration

> 多 Agent 编排、控制面和 fleet 管理 · **10 repos** (0 owned / 10 starred)

### Owned

| Repo | Capability | State | Source |
|---|---|---|---|
| — | No owned repo in this stage | — | — |

### Starred

| Repo | Capability | State / Lock | Source |
|---|---|---|---|
| [21st-dev/1code](https://github.com/21st-dev/1code) | Orchestration layer for coding agents (Claude Code, Codex) | `EXPLORING · ARCHIVED` | Starred · lock 9f1bc76fa437 |
| [Enderfga/claw-orchestrator](https://github.com/Enderfga/claw-orchestrator) | Run Claude Code, Codex, Antigravity, Cursor Agent and OpenCode as one runtime — persistent sessions, multi-agent councils, an OpenAI-compatible endpoint, an MCP server, and an ACP agent any editor can drive. | `EXPLORING · —` | Starred · lock ed2ed594303d |
| [Untrivial-ai/agent-orchestrator](https://github.com/Untrivial-ai/agent-orchestrator) | Agent IDE that enables you to manage fleets of coding agents. It comes with an agentic orchestrator that plans tasks, spawns agents, and autonomously handles CI fixes, merge conflicts, and code reviews. | `EXPLORING · —` | Starred · lock c4abb8afc4a3 |
| [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) | Teams-first Multi-agent orchestration for Claude Code | `EXPLORING · —` | Starred · lock 08db8be068c2 |
| [catlog22/Claude-Code-Workflow](https://github.com/catlog22/Claude-Code-Workflow) |  JSON-driven multi-agent  cadence-team development framework with   intelligent CLI orchestration (Gemini/Qwen/Codex),   context-first architecture, and automated workflow   execution | `EXPLORING · ARCHIVED` | Starred · lock 07491b04ac30 |
| [cft0808/edict](https://github.com/cft0808/edict) | 🏛️ 三省六部制 · OpenClaw Multi-Agent Orchestration System — 9 specialized AI agents with real-time dashboard, model config, and full audit trails | `EXPLORING · —` | Starred · lock 14a207557719 |
| [huangruiteng/loopx](https://github.com/huangruiteng/loopx) | Long-horizon agent control plane for durable, governed work across Codex, Claude Code, and other harnesses. | `EXPLORING · —` | Starred · lock e8175d4e9ffe |
| [openai/symphony](https://github.com/openai/symphony) | Symphony turns project work into isolated, autonomous implementation runs, allowing teams to manage work instead of supervising coding agents. | `EXPLORING · —` | Starred · lock 8001b52e3062 |
| [paperclipai/paperclip](https://github.com/paperclipai/paperclip) | The open-source app everyone uses to manage agents at work | `EXPLORING · —` | Starred · lock 821573ede850 |
| [ruvnet/ruflo](https://github.com/ruvnet/ruflo) | 🌊 The original agent meta-harness. Deploy intelligent multi-player swarms, coordinate autonomous workflows, and build conversational AI systems. Features adaptive memory, self-learning intelligence, RAG integration, and native Claude Code / Codex / Hermes and many more Integrated | `EXPLORING · —` | Starred · lock e21aa352fdc8 |

## 03 Skills, Plugins & Marketplaces

> Skill 集合、插件、Marketplace 和 Skill 管理器 · **36 repos** (2 owned / 34 starred)

### Owned

| Repo | Capability | State | Source |
|---|---|---|---|
| [zinan92/agent-core](https://github.com/zinan92/agent-core) | AI agent 操作系统内核 — architecture-first starter package，提供 onboarding、skills、SOPs、runtime specs、curated knowledge 五大原语 | `BUILDING · —` | Owned |
| [zinan92/skills-repo](https://github.com/zinan92/skills-repo) | 按 data/content/dev/trading 分类组织的 62 个 AI agent skills 仓库，用 frontmatter + symlink 把 skills 路由到 Claude Code 与 OpenClaw。 | `BUILDING · —` | Owned |

### Starred

| Repo | Capability | State / Lock | Source |
|---|---|---|---|
| [Cocoon-AI/architecture-diagram-generator](https://github.com/Cocoon-AI/architecture-diagram-generator) | Generate beautiful dark-themed system architecture diagrams as standalone HTML/SVG files. Works as a Claude AI skill.     | `EXPLORING · —` | Starred · lock 4b9087d55268 |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | A curated list of awesome Claude Skills, resources, and tools for customizing Claude AI workflows | `EXPLORING · —` | Starred · lock be2a406907db |
| [FANzR-arch/Numerologist_skills](https://github.com/FANzR-arch/Numerologist_skills) | 🔮 An engineering framework to stop LLM hallucinations in Chinese astrology. / 给“赛博半仙”戴上紧箍咒：减少幻觉、固定排盘步骤的奇门遁甲与紫微斗数 AI skills。 | `EXPLORING · —` | Starred · lock ea28c3fb7e80 |
| [HughYau/qiushi-skill](https://github.com/HughYau/qiushi-skill) | Qiushi-Skill: Build agents that investigate first, focus on the main contradiction, validate in practice, and keep pushing until the work is actually done. 求是Skill——从经典唯物辩证法与实践哲学中提炼出一条总原则和九大方法论工具武装AI大脑。 | `EXPLORING · —` | Starred · lock 671079144dd2 |
| [KKKKhazix/khazix-skills](https://github.com/KKKKhazix/khazix-skills) | 数字生命卡兹克开源的 AI Skills 合集 / Agent Skills: leader（帮你定义目标）, neat-freak 洁癖, hv-analysis, khazix-writer & more — Claude Code, Codex & 40+ agents | `EXPLORING · —` | Starred · lock 7a5c4934be41 |
| [LearnPrompt/luban-skill](https://github.com/LearnPrompt/luban-skill) | 鲁班 / Luban — 把'能用的Skill'打磨成'能被装、能传播、能验证、能进化'的公共资产。Agent skill-polishing workshop: 验料·访行·过尺·慢刨·回炉 | `EXPLORING · —` | Starred · lock cea2da331027 |
| [Martian-Engineering/lossless-claw](https://github.com/Martian-Engineering/lossless-claw) | Lossless Claw — LCM (Lossless Context Management) plugin for OpenClaw | `EXPLORING · —` | Starred · lock 511e5f13cd9b |
| [Niall-Young/Canvasight](https://github.com/Niall-Young/Canvasight) | 用于梳理任务然后交付给 AI 工具的 plugin 插件 | `EXPLORING · —` | Starred · lock a12d848812ab |
| [NoizAI/skills](https://github.com/NoizAI/skills) | Allow your 🦞 bot to Shout, Speak, with "human" vibe | `EXPLORING · —` | Starred · lock 2a0e09d8cb90 |
| [Yeadon8888/cangjie-skill](https://github.com/Yeadon8888/cangjie-skill) | 仓颉 · 认知植入式思维蒸馏引擎 — 不是让AI说得像他，是让AI想得像他。基于女娲架构升级。 | `EXPLORING · —` | Starred · lock c489ba54a420 |
| [YishenTu/claudian](https://github.com/YishenTu/claudian) | An Obsidian plugin that embeds Claude Code/Codex as an AI collaborator in your vault | `EXPLORING · —` | Starred · lock 54b4290b6a1d |
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond. | `EXPLORING · —` | Starred · lock d8409a4b0813 |
| [agenmod/immortal-skill](https://github.com/agenmod/immortal-skill) | ♾️ 开源数字永生框架 — 从聊天记录蒸馏任何人的七维数字分身。支持微信/飞书/iMessage/Telegram等12+平台，7种角色模板，对齐 OpenClaw Soul Spec 标准。一行指令让你的AI学会蒸馏。 | `EXPLORING · —` | Starred · lock cdab91b37982 |
| [agenticnotetaking/arscontexta](https://github.com/agenticnotetaking/arscontexta) | Claude Code plugin that generates individualized knowledge systems from conversation. You describe how you think and work, have a conversation and get a complete second brain as markdown files you own. | `EXPLORING · —` | Starred · lock 2acfd5cc4473 |
| [alchaincyf/darwin-skill](https://github.com/alchaincyf/darwin-skill) | 达尔文.skill —— 一个让你的Skill无限进化的系统：评估→改进→测试→保留或回滚 / Autoresearch-inspired autonomous skill optimization for Claude Code. Evaluate, improve, test, keep or revert. | `EXPLORING · —` | Starred · lock 5539516444cf |
| [alchaincyf/nuwa-skill](https://github.com/alchaincyf/nuwa-skill) | 你想蒸馏的下一个员工，何必是同事。蒸馏任何人的思维方式——心智模型、决策启发式、表达DNA。Distill how anyone thinks. | `EXPLORING · —` | Starred · lock fe0374687037 |
| [anthropics/skills](https://github.com/anthropics/skills) | Public repository for Agent Skills | `EXPLORING · —` | Starred · lock 3b3fad96af16 |
| [czlonkowski/n8n-skills](https://github.com/czlonkowski/n8n-skills) | n8n skillset for Claude Code to build flawless n8n workflows | `EXPLORING · —` | Starred · lock 02965226846a |
| [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) | DeepSeek Harness: Everything is a Plugin. | `EXPLORING · —` | Starred · lock b150a551b8d4 |
| [dontbesilent2025/dbskill](https://github.com/dontbesilent2025/dbskill) | dontbesilent 的商业诊断 Skills | `EXPLORING · —` | Starred · lock 0393f4b178bd |
| [eze-is/web-access](https://github.com/eze-is/web-access) | 给 Claude Code 装上完整联网能力的 skill：三层通道调度 + 浏览器 CDP + 并行分治 | `EXPLORING · —` | Starred · lock 33eef84a55b1 |
| [iamzhihuix/skills-manage](https://github.com/iamzhihuix/skills-manage) | Desktop app to manage AI coding agent skills across Claude Code, Cursor, Gemini CLI, Codex, and 20+ platforms from one place. | `EXPLORING · —` | Starred · lock 467d0423beaf |
| [jinchenma94/bazi-skill](https://github.com/jinchenma94/bazi-skill) | 四柱八字命理分析 | `EXPLORING · —` | Starred · lock 112a5d84cd1a |
| [kangarooking/cangjie-skill](https://github.com/kangarooking/cangjie-skill) | 把书、长视频、播客等高价值内容蒸馏成可执行的 Agent Skills（Distill high-value content from books, long-form videos, podcasts, and more into executable Agent Skills） | `EXPLORING · —` | Starred · lock f751bf9ff9f8 |
| [larksuite/cli](https://github.com/larksuite/cli) | The official Lark/飞书 CLI tool, maintained by the larksuite team — built for humans and AI Agents. Covers core business domains including Messenger, Docs, Base, Sheets, Calendar, Mail, Tasks, Meetings, and more, with 200+ commands and 20+ AI Agent Skills. | `EXPLORING · —` | Starred · lock 0f9553385c48 |
| [libukai/awesome-agent-skills](https://github.com/libukai/awesome-agent-skills) | Agent Skills 终极指南：快速入门、资源推荐、精选技能与实用工具 ｜The Ultimate Guide to Agent Skills: QuickStart, Resources, Features&Toolkit | `EXPLORING · —` | Starred · lock 89f82b3a96fb |
| [limin112/min-skill](https://github.com/limin112/min-skill) |  | `EXPLORING · NEEDS_REVIEW` | Starred · lock c6295535b8c6 |
| [mattpocock/skills](https://github.com/mattpocock/skills) | Skills for Real Engineers. Straight from my .agents directory. | `EXPLORING · —` | Starred · lock 6654f6b60cd9 |
| [nicobailon/visual-explainer](https://github.com/nicobailon/visual-explainer) | Agent skill that generates rich HTML pages or slide decks for diagrams, diff reviews, plan audits, data tables, and project recaps | `EXPLORING · —` | Starred · lock df35d97a0019 |
| [notdog1998/yourself-skill](https://github.com/notdog1998/yourself-skill) | 与其蒸馏别人，不如蒸馏自己。欢迎加入数字永生！Inspired by colleague-skill（同事skill）。 | `EXPLORING · —` | Starred · lock 9deb1a87b123 |
| [obra/superpowers](https://github.com/obra/superpowers) | An agentic skills framework & software development methodology that works. | `EXPLORING · —` | Starred · lock b36e0829c6d0 |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | Vercel's official collection of agent skills | `EXPLORING · —` | Starred · lock dd089a8c752c |
| [volcengine/OpenViking](https://github.com/volcengine/OpenViking) | Self-evolving Context Database for AI Agents. Unify Agent Memory, Knowledge RAG and Skills. | `EXPLORING · —` | Starred · lock 24185a08488c |
| [wshobson/agents](https://github.com/wshobson/agents) | Multi-harness agentic plugin marketplace for Claude Code, Codex, Cursor, OpenCode, GitHub Copilot, and Google Antigravity | `EXPLORING · —` | Starred · lock d82998e7df39 |

## 04 Memory, Context & Knowledge

> memory、context、RAG 和个人知识层 · **2 repos** (0 owned / 2 starred)

### Owned

| Repo | Capability | State | Source |
|---|---|---|---|
| — | No owned repo in this stage | — | — |

### Starred

| Repo | Capability | State / Lock | Source |
|---|---|---|---|
| [EverMind-AI/EverOS](https://github.com/EverMind-AI/EverOS) | One portable memory layer for every AI agent: local-first, Markdown-native, user-owned, and self-evolving across apps, tools, and workflows. | `EXPLORING · —` | Starred · lock 786406129582 |
| [code-yeongyu/lazycodex](https://github.com/code-yeongyu/lazycodex) | The one and only agent harness for complex codebases. Project memory, planning, execution, and verified completion inside Codex. | `EXPLORING · —` | Starred · lock 10f95587d3ae |

## 05 Tool Use & Integrations

> 浏览器、MCP、CLI 和外部工具连接 · **11 repos** (3 owned / 8 starred)

### Owned

| Repo | Capability | State | Source |
|---|---|---|---|
| [zinan92/agent-browser](https://github.com/zinan92/agent-browser) | Browser automation CLI for AI agents | `BUILDING · —` | Owned |
| [zinan92/bb-browser](https://github.com/zinan92/bb-browser) | Your browser is the API. CLI + MCP server for AI agents to control Chrome with your login state. | `BUILDING · —` | Owned |
| [zinan92/opencli](https://github.com/zinan92/opencli) | Make any website your CLI. A powerful, AI-native runtime for seamless browser automation and dynamic web data extraction. | `BUILDING · —` | Owned |

### Starred

| Repo | Capability | State / Lock | Source |
|---|---|---|---|
| [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) | Chrome DevTools for coding agents | `EXPLORING · —` | Starred · lock 45f187b1e320 |
| [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) | 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl! | `EXPLORING · —` | Starred · lock 458e2a2ac909 |
| [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything) | "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/ | `EXPLORING · —` | Starred · lock 810c18b0d1ab |
| [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees. | `EXPLORING · —` | Starred · lock 06c202b03400 |
| [amantus-ai/vibetunnel](https://github.com/amantus-ai/vibetunnel) | Turn any browser into your terminal & command your agents on the go. | `EXPLORING · —` | Starred · lock f78324f5a6f5 |
| [furkankly/zoetrope](https://github.com/furkankly/zoetrope) | Watch a Claude Code session as a live flow graph, in your terminal or your browser. | `EXPLORING · —` | Starred · lock 077707da6799 |
| [jackwener/OpenCLI](https://github.com/jackwener/OpenCLI) | Make Any Website into CLI & Use your logged-in browser by AI agent.  | `EXPLORING · —` | Starred · lock 6b3dffd398b9 |
| [lightpanda-io/browser](https://github.com/lightpanda-io/browser) | Lightpanda: the headless browser designed for AI and automation | `EXPLORING · —` | Starred · lock 0590bd0f8067 |

## 06 Models, Providers & Gateways

> provider proxy、模型网关和运行时适配 · **4 repos** (0 owned / 4 starred)

### Owned

| Repo | Capability | State | Source |
|---|---|---|---|
| — | No owned repo in this stage | — | — |

### Starred

| Repo | Capability | State / Lock | Source |
|---|---|---|---|
| [farion1231/cc-switch](https://github.com/farion1231/cc-switch) | A cross-platform desktop All-in-One assistant for Claude Code, Codex, OpenCode, OpenClaw, Grok Build & Hermes Agent. Only official website: ccswitch.io | `EXPLORING · —` | Starred · lock c911c7e3c6aa |
| [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) | A clean web dashboard for OpenClaw. Connect your Gateway, manage agents, and ship faster. ⭐️ Star if you like it! | `EXPLORING · —` | Starred · lock 732b994120bb |
| [lidge-jun/opencodex](https://github.com/lidge-jun/opencodex) | Universal provider proxy for OpenAI Codex & Claude Code — use any LLM (Claude, Gemini, Grok, DeepSeek, Ollama…) with Codex CLI, App, SDK, and Claude Code | `EXPLORING · —` | Starred · lock ec51e42d745d |
| [router-for-me/CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) | Wrap Antigravity, ChatGPT Codex, Claude Code, Grok Build as an OpenAI/Gemini/Claude/Codex compatible API service, allowing you to enjoy the free Gemini 3.1 Pro, GPT 5.6 Series, Grok 4.5, Claude model through API | `EXPLORING · —` | Starred · lock 1f53b2eb03b9 |

## 07 Development Workflow & Quality

> coding workflow、TDD、spec、eval 和质量门 · **10 repos** (1 owned / 9 starred)

### Owned

| Repo | Capability | State | Source |
|---|---|---|---|
| [zinan92/doc-driven-dev-workflow](https://github.com/zinan92/doc-driven-dev-workflow) | 5-phase / 22-stage 的 AI-native 文档驱动开发 workflow，内置 task scaffolding、workflow guards、state/event writer scripts 与 local-first observer dashboard。 | `BUILDING · —` | Owned |

### Starred

| Repo | Capability | State / Lock | Source |
|---|---|---|---|
| [Pimzino/claude-code-spec-workflow](https://github.com/Pimzino/claude-code-spec-workflow) | Automated workflows for Claude Code. Features spec-driven development for new features (Requirements → Design → Tasks → Implementation) and streamlined bug fix workflow for quick issue resolution (Report → Analyze → Fix → Verify). | `EXPLORING · —` | Starred · lock f3de74d80551 |
| [SuperClaude-Org/SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) | A configuration framework that enhances Claude Code with specialized commands, cognitive personas, and development methodologies. | `EXPLORING · —` | Starred · lock 1b81e51db955 |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands. | `EXPLORING · —` | Starred · lock 005c5dade90c |
| [freestylefly/CodexGuide](https://github.com/freestylefly/CodexGuide) | CodexGuide：面向全球初学者、创作者、开发者与团队的 Codex 实践指南 | `EXPLORING · —` | Starred · lock 0c5d803f086a |
| [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) | A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables. | `EXPLORING · —` | Starred · lock ebe9c99acb5c |
| [nizos/tdd-guard](https://github.com/nizos/tdd-guard) | Automated TDD enforcement for Claude Code | `EXPLORING · —` | Starred · lock ccd71b49b11b |
| [open-gsd/gsd-core](https://github.com/open-gsd/gsd-core) | Git. Ship. Done - Core | `EXPLORING · —` | Starred · lock 3b18eff38879 |
| [openai/evals](https://github.com/openai/evals) | Evals is a framework for evaluating LLMs and LLM systems, and an open-source registry of benchmarks. | `EXPLORING · —` | Starred · lock 8eac7a7de521 |
| [yizhiyanhua-ai/fireworks-tech-graph](https://github.com/yizhiyanhua-ai/fireworks-tech-graph) | Generate production-quality SVG+PNG technical diagrams from natural language. 7 styles, UML support, and AI/Agent workflow patterns. | `EXPLORING · —` | Starred · lock e9c7a9351dee |

## 08 Observability & Interfaces

> Agent session、日志、面板和控制台 · **3 repos** (0 owned / 3 starred)

### Owned

| Repo | Capability | State | Source |
|---|---|---|---|
| — | No owned repo in this stage | — | — |

### Starred

| Repo | Capability | State / Lock | Source |
|---|---|---|---|
| [coze-dev/coze-studio](https://github.com/coze-dev/coze-studio) | An AI agent development platform with all-in-one visual tools, simplifying agent creation, debugging, and deployment like never before. Coze your way to AI Agent creation. | `EXPLORING · —` | Starred · lock fefb05ff27be |
| [kenn-io/agentsview](https://github.com/kenn-io/agentsview) | Local-first session search, analytics, insights, and token use statistics for coding agents, supporting Claude Code, Codex, and more than 20 other agents.  | `EXPLORING · —` | Starred · lock 31738009de94 |
| [zhaoxinyi02/ClawPanel](https://github.com/zhaoxinyi02/ClawPanel) | 🐾 ClawPanel — OpenClaw AI 助手可视化管理面板。Go 单二进制部署，支持 20+ 通道统一管理，跨平台，实时日志监控。 | `EXPLORING · —` | Starred · lock 28cfcb958da8 |

## 09 Knowledge & References

> Agent 教程、源码研究、cookbook 和资源索引 · **9 repos** (0 owned / 9 starred)

### Owned

| Repo | Capability | State | Source |
|---|---|---|---|
| — | No owned repo in this stage | — | — |

### Starred

| Repo | Capability | State / Lock | Source |
|---|---|---|---|
| [ChinaSiro/claude-code-sourcemap](https://github.com/ChinaSiro/claude-code-sourcemap) |  | `EXPLORING · —` | Starred · lock a8a678cb6244 |
| [alchaincyf/hermes-agent-orange-book](https://github.com/alchaincyf/hermes-agent-orange-book) | Hermes Agent 从入门到精通 · 橙皮书系列 · Nous Research 开源 AI Agent 框架实战指南 | `EXPLORING · —` | Starred · lock 9ac06e1d0537 |
| [anomalyco/opencode](https://github.com/anomalyco/opencode) | The open source coding agent. | `EXPLORING · —` | Starred · lock fd9bd448a2e6 |
| [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) | A collection of notebooks/recipes showcasing some fun and effective ways of using Claude. | `EXPLORING · —` | Starred · lock 35f2eec7e448 |
| [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | An open-source AI agent that brings the power of Gemini directly into your terminal. | `EXPLORING · —` | Starred · lock 64b5b79a6dd8 |
| [hangsman/claude-code-source](https://github.com/hangsman/claude-code-source) | claude code source map v2.1.88 | `EXPLORING · —` | Starred · lock d239e3f2c574 |
| [makecindy/cindy](https://github.com/makecindy/cindy) | Consider it done. The open-source AI agent that works out of the box · 想到，就能做到。开源、开箱即用的 AI Agent。 | `EXPLORING · —` | Starred · lock 173df24fb666 |
| [multica-ai/multica](https://github.com/multica-ai/multica) | Make humans and AI agents work as one team — open-source and self-hostable. | `EXPLORING · —` | Starred · lock 8fda4f22d542 |
| [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) | Bash is all you need -  A nano claude code–like 「agent harness」, built from 0 to 1 | `EXPLORING · —` | Starred · lock 04486201fc65 |

## Update contract

- Snapshot ID: `github-universe-2026-08-26` · entries: `105`.
- Owned and Starred are preserved per entry; each repo has one primary stage.
- External refs show a locked commit SHA and never advance from this public registry.
- Full catalog source and monthly update authority: [Park OS](https://github.com/zinan92/park-operating-system).

## For AI agents

```yaml
name: agent-universe
universe: agent
source_of_truth: https://github.com/zinan92/park-operating-system
snapshot_id: github-universe-2026-08-26
entry_count: 105
external_versioning: locked_commit_sha
```

This registry is a catalog of links and metadata. Validation does not certify product readiness.

