<div align="center">

# Agent

**Agent 的 capability-first registry：按子分类浏览 owned 与 starred repo。**

[![Snapshot](https://img.shields.io/badge/snapshot-122%20repos-0969DA.svg)](snapshot.yaml)
[![Source](https://img.shields.io/badge/source-Park%20OS-8250DF.svg)](https://github.com/zinan92/park-operating-system)

</div>

---

```text
in  canonical Park OS snapshot + source provenance + fixed commit locks
out 122-repo Agent map, grouped by function and owned/starred source

fail snapshot checksum mismatch → stop before publishing
fail private source inaccessible → preserve name/link and mark PRIVATE
fail unclassified placement → keep needs_review; do not guess
```

Snapshot: `github-universe-2026-08-27-content-review-01` · canonical source: [Park OS](https://github.com/zinan92/park-operating-system)

## How to read this page

- **Owned** — repo owned by Park.
- **Starred** — external repo selected as a locked reference.
- **Lock** — external source is pinned to a commit SHA, not a live branch.
- **PRIVATE / ARCHIVED** — GitHub visibility or lifecycle flags are preserved.

## Browse by function

### Agent Eyes & Hands (19)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [amantus-ai/vibetunnel](https://github.com/amantus-ai/vibetunnel) | Turn any browser into your terminal & command your agents on the go. | Starred | `f78324f5a6f5` |
| [chenglou/pretext](https://github.com/chenglou/pretext) | Fast, accurate & comprehensive text measurement & layout | Starred | `ac49b09b7d83` |
| [chenjin-cmd/wechat-miniprogram-builder](https://github.com/chenjin-cmd/wechat-miniprogram-builder) | wechat-miniprogram-builder | Starred | `e8bba7855d92` |
| [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) | Chrome DevTools for coding agents | Starred | `45f187b1e320` |
| [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) | 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl! | Starred | `458e2a2ac909` |
| [eze-is/web-access](https://github.com/eze-is/web-access) | 给 Claude Code 装上完整联网能力的 skill：三层通道调度 + 浏览器 CDP + 并行分治 | Starred | `33eef84a55b1` |
| [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything) | "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/ | Starred | `810c18b0d1ab` |
| [jackwener/OpenCLI](https://github.com/jackwener/OpenCLI) | Make Any Website into CLI & Use your logged-in browser by AI agent. | Starred | `6b3dffd398b9` |
| [larksuite/cli](https://github.com/larksuite/cli) | The official Lark/飞书 CLI tool, maintained by the larksuite team — built for humans and AI Agents. Covers core business domains including Messenger, Docs, Base, Sheets, Calendar, Mail, Tasks, Meetings, and more, with 200+ commands and 20+ AI Agent Skills. | Starred | `0f9553385c48` |
| [lightpanda-io/browser](https://github.com/lightpanda-io/browser) | Lightpanda: the headless browser designed for AI and automation | Starred | `0590bd0f8067` |
| [mixedbread-ai/mgrep](https://github.com/mixedbread-ai/mgrep) | A calm, CLI-native way to semantically grep everything, like code, images, pdfs and more. | Starred | `5c1ba628c62d` |
| [n8n-io/n8n](https://github.com/n8n-io/n8n) | Fair-code workflow automation platform with native AI capabilities. Combine visual building with custom code, self-host or cloud, 400+ integrations. | Starred | `48c42fa4b8ca` |
| [nexu-io/html-anything](https://github.com/nexu-io/html-anything) | ✨ The agentic HTML editor — your local AI agent writes the HTML, you ship it. 🚀 75 Skills × 9 Surfaces (magazine · deck · poster · XHS / tweet · prototype · data report · Hyperframes) 🛡️ Sandboxed preview · 📤 1-click to WeChat / X / Zhihu / HTML / PNG 🔑 Zero API key — Claude Code / Cursor / Codex / Gemini / Copilot / OpenCode / Qwen / Aider. | Starred | `c31204544230` |
| [nexu-io/open-design](https://github.com/nexu-io/open-design) | 🎨 Best DeepSeek Harness Design Plugin. The open-source Claude Design alternative. 🖥️ Local-first desktop app. 🖼️ Your coding agent becomes the design engine: prototypes, landing pages, dashboards, slides, images & video — real files, HTML/PDF/PPTX/MP4 export. 🤖 Claude Code / Codex / Cursor / DeepSeek Harness / OpenCode & 20+ CLIs via BYOK. | Starred | `f888d72d5f1a` |
| [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees. | Starred | `06c202b03400` |
| [riba2534/feishu-cli](https://github.com/riba2534/feishu-cli) | feishu-cli 是一个功能完整的飞书开放平台命令行工具。它将飞书文档、知识库、电子表格、消息、日历、任务等操作封装为简洁的命令行接口，核心能力是 Markdown ↔ 飞书文档双向无损转换。 | Starred | `0e92eec364b1` |
| [zinan92/agent-browser](https://github.com/zinan92/agent-browser) | Browser automation CLI for AI agents | Owned | owned source |
| [zinan92/bb-browser](https://github.com/zinan92/bb-browser) | Your browser is the API. CLI + MCP server for AI agents to control Chrome with your login state. | Owned | owned source |
| [zinan92/opencli](https://github.com/zinan92/opencli) | Make any website your CLI. A powerful, AI-native runtime for seamless browser automation and dynamic web data extraction. | Owned | owned source |

### Agent Runtime & Harness (22)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [AAAAAAAJ/WaytoAGI-CLI](https://github.com/AAAAAAAJ/WaytoAGI-CLI) | WaytoAGI-CLI | Starred | `e145d1af49ec` |
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond. | Starred | `d8409a4b0813` |
| [anomalyco/opencode](https://github.com/anomalyco/opencode) | The open source coding agent. | Starred | `fd9bd448a2e6` |
| [anthropics/claude-code](https://github.com/anthropics/claude-code) | Claude Code is an agentic coding tool that lives in your terminal, understands your codebase, and helps you code faster by executing routine tasks, explaining complex code, and handling git workflows - all through natural language commands. | Starred | `005c5dade90c` |
| [code-yeongyu/lazycodex](https://github.com/code-yeongyu/lazycodex) | The one and only agent harness for complex codebases. Project memory, planning, execution, and verified completion inside Codex. | Starred | `10f95587d3ae` |
| [code-yeongyu/oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent) | omo/lazycodex: The coding agent for tokenmaxxers;the one and only agent harness for complex codebases. For your Codex, for your OpenCode | Starred | `8c57e463e62d` |
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | CLI tool for configuring and monitoring Claude Code | Starred | `3a2f8c031527` |
| [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) | DeepSeek Harness: Everything is a Plugin. | Starred | `b150a551b8d4` |
| [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) | DeepSeek-native AI coding agent for your terminal. Engineered around prefix-cache stability — leave it running. | Starred | `c3f5b497d59c` |
| [farion1231/cc-switch](https://github.com/farion1231/cc-switch) | A cross-platform desktop All-in-One assistant for Claude Code, Codex, OpenCode, OpenClaw, Grok Build & Hermes Agent. Only official website: ccswitch.io | Starred | `c911c7e3c6aa` |
| [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | An open-source AI agent that brings the power of Gemini directly into your terminal. | Starred | `64b5b79a6dd8` |
| [lidge-jun/opencodex](https://github.com/lidge-jun/opencodex) | Universal provider proxy for OpenAI Codex & Claude Code — use any LLM (Claude, Gemini, Grok, DeepSeek, Ollama…) with Codex CLI, App, SDK, and Claude Code | Starred | `ec51e42d745d` |
| [makecindy/cindy](https://github.com/makecindy/cindy) | Consider it done. The open-source AI agent that works out of the box · 想到，就能做到。开源、开箱即用的 AI Agent。 | Starred | `173df24fb666` |
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | The agent that grows with you | Starred | `a7b8281a16ef` |
| [openai/codex](https://github.com/openai/codex) | Lightweight coding agent that runs in your terminal | Starred | `3e4707b34b16` |
| [openchamber/openchamber](https://github.com/openchamber/openchamber) | Desktop and web interface for OpenCode AI agent | Starred | `74290852efef` |
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | Your own personal AI assistant. Any OS. Any Platform. The lobster way. 🦞 | Starred | `3b64e84f6ea2` |
| [router-for-me/CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) | Wrap Antigravity, ChatGPT Codex, Claude Code, Grok Build as an OpenAI/Gemini/Claude/Codex compatible API service, allowing you to enjoy the free Gemini 3.1 Pro, GPT 5.6 Series, Grok 4.5, Claude model through API | Starred | `1f53b2eb03b9` |
| [thirdlayerinc/autoagent](https://github.com/thirdlayerinc/autoagent) | autonomous harness engineering | Starred | `eb3f185dc9fa` |
| [ultraworkers/claw-code](https://github.com/ultraworkers/claw-code) | An agent-managed museum exhibit, built in Rust with Gajae-Code / LazyCodex — developed and maintained with no human intervention. | Starred | `08106b0c3771` |
| [zinan92/agent-core](https://github.com/zinan92/agent-core) | AI agent 操作系统内核 — architecture-first starter package，提供 onboarding、skills、SOPs、runtime specs、curated knowledge 五大原语 | Owned + Starred | owned source |
| [zinan92/claw-code](https://github.com/zinan92/claw-code) | The fastest repo in history to surpass 50K stars ⭐, reaching the milestone in just 2 hours after publication. Better Harness Tools, not merely storing the archive of leaked Claude Code but also make real things done. Now rewriting in Rust. | Owned | owned source |

### Agent Workflow (29)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [21st-dev/1code](https://github.com/21st-dev/1code) | Orchestration layer for coding agents (Claude Code, Codex) | Starred | `9f1bc76fa437` · ARCHIVED |
| [BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban) | Get 10X more out of Claude Code, Codex or any coding agent | Starred | `4deb7eca8f38` |
| [catlog22/Claude-Code-Workflow](https://github.com/catlog22/Claude-Code-Workflow) | JSON-driven multi-agent  cadence-team development framework with   intelligent CLI orchestration (Gemini/Qwen/Codex),   context-first architecture, and automated workflow   execution | Starred | `07491b04ac30` · ARCHIVED |
| [cft0808/edict](https://github.com/cft0808/edict) | 🏛️ 三省六部制 · OpenClaw Multi-Agent Orchestration System — 9 specialized AI agents with real-time dashboard, model config, and full audit trails | Starred | `14a207557719` |
| [chuspeeism/dashi-taskboard](https://github.com/chuspeeism/dashi-taskboard) | No description | Starred | `f0f4cabced1b` |
| [Enderfga/claw-orchestrator](https://github.com/Enderfga/claw-orchestrator) | Run Claude Code, Codex, Antigravity, Cursor Agent and OpenCode as one runtime — persistent sessions, multi-agent councils, an OpenAI-compatible endpoint, an MCP server, and an ACP agent any editor can drive. | Starred | `ed2ed594303d` |
| [frankbria/ralph-claude-code](https://github.com/frankbria/ralph-claude-code) | Autonomous AI development loop for Claude Code with intelligent exit detection | Starred | `e8533cc3f009` |
| [freestylefly/CodexGuide](https://github.com/freestylefly/CodexGuide) | CodexGuide：面向全球初学者、创作者、开发者与团队的 Codex 实践指南 | Starred | `0c5d803f086a` |
| [garrytan/gstack](https://github.com/garrytan/gstack) | Use Garry Tan's exact Claude Code setup: 23 opinionated tools that serve as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA | Starred | `ad8400543cd9` |
| [huangruiteng/loopx](https://github.com/huangruiteng/loopx) | Long-horizon agent control plane for durable, governed work across Codex, Claude Code, and other harnesses. | Starred | `e8175d4e9ffe` |
| [HughYau/qiushi-skill](https://github.com/HughYau/qiushi-skill) | Qiushi-Skill: Build agents that investigate first, focus on the main contradiction, validate in practice, and keep pushing until the work is actually done. 求是Skill——从经典唯物辩证法与实践哲学中提炼出一条总原则和九大方法论工具武装AI大脑。 | Starred | `671079144dd2` |
| [karpathy/autoresearch](https://github.com/karpathy/autoresearch) | AI agents running research on single-GPU nanochat training automatically | Starred | `228791fb499a` |
| [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) | A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables. | Starred | `ebe9c99acb5c` |
| [multica-ai/multica](https://github.com/multica-ai/multica) | Make humans and AI agents work as one team — open-source and self-hostable. | Starred | `8fda4f22d542` |
| [Niall-Young/Canvasight](https://github.com/Niall-Young/Canvasight) | 用于梳理任务然后交付给 AI 工具的 plugin 插件 | Starred | `a12d848812ab` |
| [nizos/tdd-guard](https://github.com/nizos/tdd-guard) | Automated TDD enforcement for Claude Code | Starred | `ccd71b49b11b` |
| [obra/superpowers](https://github.com/obra/superpowers) | An agentic skills framework & software development methodology that works. | Starred | `b36e0829c6d0` |
| [open-gsd/gsd-core](https://github.com/open-gsd/gsd-core) | Git. Ship. Done - Core | Starred | `3b18eff38879` |
| [openai/evals](https://github.com/openai/evals) | Evals is a framework for evaluating LLMs and LLM systems, and an open-source registry of benchmarks. | Starred | `8eac7a7de521` |
| [openai/symphony](https://github.com/openai/symphony) | Symphony turns project work into isolated, autonomous implementation runs, allowing teams to manage work instead of supervising coding agents. | Starred | `8001b52e3062` |
| [paperclipai/paperclip](https://github.com/paperclipai/paperclip) | The open-source app everyone uses to manage agents at work | Starred | `821573ede850` |
| [Pimzino/claude-code-spec-workflow](https://github.com/Pimzino/claude-code-spec-workflow) | Automated workflows for Claude Code. Features spec-driven development for new features (Requirements → Design → Tasks → Implementation) and streamlined bug fix workflow for quick issue resolution (Report → Analyze → Fix → Verify). | Starred | `f3de74d80551` |
| [ruvnet/ruflo](https://github.com/ruvnet/ruflo) | 🌊 The original agent meta-harness. Deploy intelligent multi-player swarms, coordinate autonomous workflows, and build conversational AI systems. Features adaptive memory, self-learning intelligence, RAG integration, and native Claude Code / Codex / Hermes and many more Integrated | Starred | `e21aa352fdc8` |
| [SuperClaude-Org/SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) | A configuration framework that enhances Claude Code with specialized commands, cognitive personas, and development methodologies. | Starred | `1b81e51db955` |
| [Untrivial-ai/agent-orchestrator](https://github.com/Untrivial-ai/agent-orchestrator) | Agent IDE that enables you to manage fleets of coding agents. It comes with an agentic orchestrator that plans tasks, spawns agents, and autonomously handles CI fixes, merge conflicts, and code reviews. | Starred | `c4abb8afc4a3` |
| [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) | Teams-first Multi-agent orchestration for Claude Code | Starred | `08db8be068c2` |
| [zinan92/doc-driven-dev-workflow](https://github.com/zinan92/doc-driven-dev-workflow) | 5-phase / 22-stage 的 AI-native 文档驱动开发 workflow，内置 task scaffolding、workflow guards、state/event writer scripts 与 local-first observer dashboard。 | Owned + Starred | owned source |
| [zinan92/loop](https://github.com/zinan92/loop) | 把一次性 coding-agent prompt 变成「按价值排序、可审计、可暂停」的执行闭环 · Value-ranked, auditable, pausable coding-agent loop. in: local Git repo + contract → out: GitHub issues/PRs + digest. Codex or Claude, macOS. | Owned + Starred | owned source |
| [zinan92/wechat-miniprogram-shipping](https://github.com/zinan92/wechat-miniprogram-shipping) | 证据门控的原生微信小程序交付路由器。in 意图/项目证据 → out 合同、QA verdict、可回退 receipt | Owned | owned source |

### Agent Skills & Plugins (33)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [agenmod/immortal-skill](https://github.com/agenmod/immortal-skill) | ♾️ 开源数字永生框架 — 从聊天记录蒸馏任何人的七维数字分身。支持微信/飞书/iMessage/Telegram等12+平台，7种角色模板，对齐 OpenClaw Soul Spec 标准。一行指令让你的AI学会蒸馏。 | Starred | `cdab91b37982` |
| [agenticnotetaking/arscontexta](https://github.com/agenticnotetaking/arscontexta) | Claude Code plugin that generates individualized knowledge systems from conversation. You describe how you think and work, have a conversation and get a complete second brain as markdown files you own. | Starred | `2acfd5cc4473` |
| [alchaincyf/darwin-skill](https://github.com/alchaincyf/darwin-skill) | 达尔文.skill —— 一个让你的Skill无限进化的系统：评估→改进→测试→保留或回滚 \| Autoresearch-inspired autonomous skill optimization for Claude Code. Evaluate, improve, test, keep or revert. | Starred | `5539516444cf` |
| [alchaincyf/nuwa-skill](https://github.com/alchaincyf/nuwa-skill) | 你想蒸馏的下一个员工，何必是同事。蒸馏任何人的思维方式——心智模型、决策启发式、表达DNA。Distill how anyone thinks. | Starred | `fe0374687037` |
| [anthropics/skills](https://github.com/anthropics/skills) | Public repository for Agent Skills | Starred | `3b3fad96af16` |
| [Cocoon-AI/architecture-diagram-generator](https://github.com/Cocoon-AI/architecture-diagram-generator) | Generate beautiful dark-themed system architecture diagrams as standalone HTML/SVG files. Works as a Claude AI skill. | Starred | `4b9087d55268` |
| [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills) | A curated list of awesome Claude Skills, resources, and tools for customizing Claude AI workflows | Starred | `be2a406907db` |
| [czlonkowski/n8n-skills](https://github.com/czlonkowski/n8n-skills) | n8n skillset for Claude Code to build flawless n8n workflows | Starred | `02965226846a` |
| [dontbesilent2025/dbskill](https://github.com/dontbesilent2025/dbskill) | dontbesilent 的商业诊断 Skills | Starred | `0393f4b178bd` |
| [FANzR-arch/Numerologist_skills](https://github.com/FANzR-arch/Numerologist_skills) | 🔮 An engineering framework to stop LLM hallucinations in Chinese astrology. / 给“赛博半仙”戴上紧箍咒：减少幻觉、固定排盘步骤的奇门遁甲与紫微斗数 AI skills。 | Starred | `ea28c3fb7e80` |
| [gnipbao/dao-skill](https://github.com/gnipbao/dao-skill) | 道生万物：从混沌需求生成可运行、可验证、可进化的 Agent Skill | Starred | `1cae835995c0` |
| [iamzhihuix/skills-manage](https://github.com/iamzhihuix/skills-manage) | Desktop app to manage AI coding agent skills across Claude Code, Cursor, Gemini CLI, Codex, and 20+ platforms from one place. | Starred | `467d0423beaf` |
| [jinchenma94/bazi-skill](https://github.com/jinchenma94/bazi-skill) | 四柱八字命理分析 | Starred | `112a5d84cd1a` |
| [kangarooking/cangjie-skill](https://github.com/kangarooking/cangjie-skill) | 把书、长视频、播客等高价值内容蒸馏成可执行的 Agent Skills（Distill high-value content from books, long-form videos, podcasts, and more into executable Agent Skills） | Starred | `f751bf9ff9f8` |
| [KKKKhazix/khazix-skills](https://github.com/KKKKhazix/khazix-skills) | 数字生命卡兹克开源的 AI Skills 合集 \| Agent Skills: leader（帮你定义目标）, neat-freak 洁癖, hv-analysis, khazix-writer & more — Claude Code, Codex & 40+ agents | Starred | `7a5c4934be41` |
| [LearnPrompt/luban-skill](https://github.com/LearnPrompt/luban-skill) | 鲁班 \| Luban — 把'能用的Skill'打磨成'能被装、能传播、能验证、能进化'的公共资产。Agent skill-polishing workshop: 验料·访行·过尺·慢刨·回炉 | Starred | `cea2da331027` |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | Taste-Skill - gives your AI good taste. stops the AI from generating boring, generic slop | Starred | `ccbc15639c97` |
| [libukai/awesome-agent-skills](https://github.com/libukai/awesome-agent-skills) | Agent Skills 终极指南：快速入门、资源推荐、精选技能与实用工具 ｜The Ultimate Guide to Agent Skills: QuickStart, Resources, Features&Toolkit | Starred | `89f82b3a96fb` |
| [limin112/min-skill](https://github.com/limin112/min-skill) | No description | Starred | `c6295535b8c6` |
| [Martian-Engineering/lossless-claw](https://github.com/Martian-Engineering/lossless-claw) | Lossless Claw — LCM (Lossless Context Management) plugin for OpenClaw | Starred | `511e5f13cd9b` |
| [mattpocock/skills](https://github.com/mattpocock/skills) | Skills for Real Engineers. Straight from my .agents directory. | Starred | `6654f6b60cd9` |
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | An AI skill that provides design intelligence for building professional UI/UX across multiple platforms. | Starred | `e353a508767c` |
| [NoizAI/skills](https://github.com/NoizAI/skills) | Allow your 🦞 bot to Shout, Speak, with "human" vibe | Starred | `2a0e09d8cb90` |
| [notdog1998/yourself-skill](https://github.com/notdog1998/yourself-skill) | 与其蒸馏别人，不如蒸馏自己。欢迎加入数字永生！Inspired by colleague-skill（同事skill）。 | Starred | `9deb1a87b123` |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | The design language that makes your AI harness better at design. | Starred | `fcd7622cd2d8` |
| [phuryn/pm-skills](https://github.com/phuryn/pm-skills) | PM Skills Marketplace: 100+ agentic skills, commands, and plugins — from discovery to strategy, execution, launch, and growth. | Starred | `18468a95b427` |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | Vercel's official collection of agent skills | Starred | `dd089a8c752c` |
| [wshobson/agents](https://github.com/wshobson/agents) | Multi-harness agentic plugin marketplace for Claude Code, Codex, Cursor, OpenCode, GitHub Copilot, and Google Antigravity | Starred | `d82998e7df39` |
| [Yeadon8888/cangjie-skill](https://github.com/Yeadon8888/cangjie-skill) | 仓颉 · 认知植入式思维蒸馏引擎 — 不是让AI说得像他，是让AI想得像他。基于女娲架构升级。 | Starred | `c489ba54a420` |
| [YishenTu/claudian](https://github.com/YishenTu/claudian) | An Obsidian plugin that embeds Claude Code/Codex as an AI collaborator in your vault | Starred | `54b4290b6a1d` |
| [yizhiyanhua-ai/fireworks-tech-graph](https://github.com/yizhiyanhua-ai/fireworks-tech-graph) | Generate production-quality SVG+PNG technical diagrams from natural language. 7 styles, UML support, and AI/Agent workflow patterns. | Starred | `e9c7a9351dee` |
| [zinan92/proactive-explorer](https://github.com/zinan92/proactive-explorer) | Strategic product direction finder for open-source repos — 5 MECE categories: Product Depth, Product Reach, Time-to-Value, Trust & Proof, Growth | Owned | owned source |
| [zinan92/repo-evals](https://github.com/zinan92/repo-evals) | Claim-first repo 评测框架。in target repo + claim map → out bilingual verdict dossier + all-evals dashboard | Owned + Starred | owned source |

### Agent Knowledge (10)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [alchaincyf/hermes-agent-orange-book](https://github.com/alchaincyf/hermes-agent-orange-book) | Hermes Agent 从入门到精通 · 橙皮书系列 · Nous Research 开源 AI Agent 框架实战指南 | Starred | `9ac06e1d0537` |
| [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) | A collection of notebooks/recipes showcasing some fun and effective ways of using Claude. | Starred | `35f2eec7e448` |
| [birobirobiro/awesome-shadcn-ui](https://github.com/birobirobiro/awesome-shadcn-ui) | A curated list of awesome things related to shadcn/ui. | Starred | `7417bbeae2d2` |
| [ChinaSiro/claude-code-sourcemap](https://github.com/ChinaSiro/claude-code-sourcemap) | No description | Starred | `a8a678cb6244` |
| [EverMind-AI/EverOS](https://github.com/EverMind-AI/EverOS) | One portable memory layer for every AI agent: local-first, Markdown-native, user-owned, and self-evolving across apps, tools, and workflows. | Starred | `786406129582` |
| [GitHubDaily/GitHubDaily](https://github.com/GitHubDaily/GitHubDaily) | 坚持分享 GitHub 上高质量、有趣实用的开源技术教程、开发者工具、编程网站、技术资讯。A list cool, interesting projects of GitHub. | Starred | `5108d021a173` |
| [hangsman/claude-code-source](https://github.com/hangsman/claude-code-source) | claude code source map v2.1.88 | Starred | `d239e3f2c574` |
| [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) | Bash is all you need -  A nano claude code–like 「agent harness」, built from 0 to 1 | Starred | `04486201fc65` |
| [Shubham0812/SwiftUI-Animations](https://github.com/Shubham0812/SwiftUI-Animations) | A repository containing a variety of animations and Animated components created in SwiftUI that you can use in your own projects. | Starred | `030bd1c710f9` |
| [volcengine/OpenViking](https://github.com/volcengine/OpenViking) | Self-evolving Context Database for AI Agents. Unify Agent Memory, Knowledge RAG and Skills. | Starred | `24185a08488c` |

### Agent Observability (9)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [cclank/lanshu-animated-architecture-diagram](https://github.com/cclank/lanshu-animated-architecture-diagram) | Premium hand-drawn animated architecture diagram Codex skill | Starred | `1818562e9fa8` |
| [coze-dev/coze-studio](https://github.com/coze-dev/coze-studio) | An AI agent development platform with all-in-one visual tools, simplifying agent creation, debugging, and deployment like never before. Coze your way to AI Agent creation. | Starred | `fefb05ff27be` |
| [furkankly/zoetrope](https://github.com/furkankly/zoetrope) | Watch a Claude Code session as a live flow graph, in your terminal or your browser. | Starred | `077707da6799` |
| [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) | A clean web dashboard for OpenClaw. Connect your Gateway, manage agents, and ship faster. ⭐️ Star if you like it! | Starred | `732b994120bb` |
| [kenn-io/agentsview](https://github.com/kenn-io/agentsview) | Local-first session search, analytics, insights, and token use statistics for coding agents, supporting Claude Code, Codex, and more than 20 other agents. | Starred | `31738009de94` |
| [nicobailon/visual-explainer](https://github.com/nicobailon/visual-explainer) | Agent skill that generates rich HTML pages or slide decks for diagrams, diff reviews, plan audits, data tables, and project recaps | Starred | `df35d97a0019` |
| [rullerzhou-afk/clawd-on-desk](https://github.com/rullerzhou-afk/clawd-on-desk) | A pixel desktop pet that watches Claude Code, Codex, Cursor & other AI coding agents — so you don't have to. | Starred | `7ab6a240fb10` |
| [vercel-labs/json-render](https://github.com/vercel-labs/json-render) | The Generative UI framework | Starred | `a4d033cf041e` |
| [zhaoxinyi02/ClawPanel](https://github.com/zhaoxinyi02/ClawPanel) | 🐾 ClawPanel — OpenClaw AI 助手可视化管理面板。Go 单二进制部署，支持 20+ 通道统一管理，跨平台，实时日志监控。 | Starred | `28cfcb958da8` |

## Update contract

This README and the generated data are scoped views. Taxonomy, source state and lock authority remain in Park OS.

```bash
bash scripts/verify-scoped.sh
```

The registry is a catalog, not a production-readiness or execution-authorization claim.
