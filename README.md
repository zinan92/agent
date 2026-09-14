<div align="center">

# Agent

**Agent 的 capability-first registry：按子分类浏览 owned 与 starred repo。**

[![Snapshot](https://img.shields.io/badge/snapshot-107%20repos-0969DA.svg)](snapshot.yaml)
[![Source](https://img.shields.io/badge/source-Park%20OS-8250DF.svg)](https://github.com/zinan92/park-operating-system)

</div>

---

```text
in  canonical Park OS snapshot + source provenance + fixed commit locks
out  107-repo Agent map, grouped by function and owned/starred source

fail snapshot checksum mismatch → stop before publishing
fail private source inaccessible → preserve name/link and mark PRIVATE
fail unclassified placement → keep needs_review; do not guess
```

Snapshot: `github-universe-2026-09-14` · canonical source: [Park OS](https://github.com/zinan92/park-operating-system)

## How to read this page

- **Owned** — repo owned by Park.
- **Starred** — external repo selected as a locked reference.
- **Lock** — external source is pinned to a commit SHA, not a live branch.
- **PRIVATE / ARCHIVED** — GitHub visibility or lifecycle flags are preserved.

## Browse by function

### Agent Eyes & Hands (18)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [amantus-ai/vibetunnel](https://github.com/amantus-ai/vibetunnel) | Turn any browser into your terminal & command your agents on the go. | Starred | `f78324f5a6f5` |
| [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) | Chrome DevTools for coding agents | Starred | `d9a8cb6ec22a` |
| [citrolabs/ego-lite](https://github.com/citrolabs/ego-lite) | The fastest browser for AI agents to run browser automation, built for sharing your logged-in browser state with your AI agents, like Codex or Claude Code, without disturbing you. Zero cost, zero config. | Starred | `d01be93325c7` |
| [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling) | 🕷️ An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl! | Starred | `48da61d1ee85` |
| [eze-is/web-access](https://github.com/eze-is/web-access) | 给 Claude Code 装上完整联网能力的 skill：三层通道调度 + 浏览器 CDP + 并行分治 | Starred | `33eef84a55b1` |
| [HD838A/remote-mic-app](https://github.com/HD838A/remote-mic-app) | 无线麦（SayAll.app）：支持小米蓝牙遥控器 2 和 2 Pro，变成 Mac 语音输入设备 | Starred | `c8c065456b80` |
| [HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything) | "CLI-Anything: Making ALL Software Agent-Native" -- CLI-Hub: https://clianything.cc/ | Starred | `810c18b0d1ab` |
| [jackwener/OpenCLI](https://github.com/jackwener/OpenCLI) | Make Any Website into CLI & Use your logged-in browser by AI agent. | Starred | `8271afc67e85` |
| [larksuite/cli](https://github.com/larksuite/cli) | The official Lark/飞书 CLI tool, maintained by the larksuite team — built for humans and AI Agents. Covers core business domains including Messenger, Docs, Base, Sheets, Calendar, Mail, Tasks, Meetings, and more, with 200+ commands and 20+ AI Agent Skills. | Starred | `39aaf9fca0e0` |
| [lightpanda-io/browser](https://github.com/lightpanda-io/browser) | Lightpanda: the headless browser designed for AI and automation | Starred | `5163c6d3856c` |
| [mixedbread-ai/mgrep](https://github.com/mixedbread-ai/mgrep) | A calm, CLI-native way to semantically grep everything, like code, images, pdfs and more. | Starred | `5c1ba628c62d` |
| [n8n-io/n8n](https://github.com/n8n-io/n8n) | Fair-code workflow automation platform with native AI capabilities. Combine visual building with custom code, self-host or cloud, 400+ integrations. | Starred | `aba174c9f3a4` |
| [NoizAI/skills](https://github.com/NoizAI/skills) | Allow your 🦞 bot to Shout, Speak, with "human" vibe | Starred | `2a0e09d8cb90` |
| [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach) | Give your AI agent eyes to see the entire internet. Read & search Twitter, Reddit, YouTube, GitHub, Bilibili, XiaoHongShu — one CLI, zero API fees. | Starred | `da5044d26fc6` |
| [riba2534/feishu-cli](https://github.com/riba2534/feishu-cli) | feishu-cli 是一个功能完整的飞书开放平台命令行工具。它将飞书文档、知识库、电子表格、消息、日历、任务等操作封装为简洁的命令行接口，核心能力是 Markdown ↔ 飞书文档双向无损转换。 | Starred | `930c3f56eef8` |
| [zinan92/agent-browser](https://github.com/zinan92/agent-browser) | Browser automation CLI for AI agents | Owned | `owned source` |
| [zinan92/bb-browser](https://github.com/zinan92/bb-browser) | Your browser is the API. CLI + MCP server for AI agents to control Chrome with your login state. | Owned | `owned source` |
| [zinan92/opencli](https://github.com/zinan92/opencli) | Make any website your CLI. A powerful, AI-native runtime for seamless browser automation and dynamic web data extraction. | Owned | `owned source` |

### Agent Runtime & Harness (19)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [AAAAAAAJ/WaytoAGI-CLI](https://github.com/AAAAAAAJ/WaytoAGI-CLI) | WaytoAGI-CLI | Starred | `e145d1af49ec` |
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | The agent harness performance optimization system. Skills, instincts, memory, security, and research-first development for Claude Code, Codex, Opencode, Cursor and beyond. | Starred | `8321021c54d6` |
| [agenticnotetaking/arscontexta](https://github.com/agenticnotetaking/arscontexta) | Claude Code plugin that generates individualized knowledge systems from conversation. You describe how you think and work, have a conversation and get a complete second brain as markdown files you own. | Starred | `2acfd5cc4473` |
| [anomalyco/opencode](https://github.com/anomalyco/opencode) | The open source coding agent. | Starred | `df23b7f9488a` |
| [BytePioneer-AI/codex-host](https://github.com/BytePioneer-AI/codex-host) | Run Pi and Claude Code directly in Codex Desktop. 在 Codex Desktop 中直接运行 Pi 和 Claude Code。 | Starred | `a67aed315f6b` |
| [code-yeongyu/lazycodex](https://github.com/code-yeongyu/lazycodex) | The one and only agent harness for complex codebases. Project memory, planning, execution, and verified completion inside Codex. | Starred | `e6be07d3bf9c` |
| [code-yeongyu/oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent) | OmO: Just type "mass ulw" keyword with your prompt. Now you are the master of graph engineering. | Starred | `dd2586709248` |
| [deepseek-ai/deepseek-harness](https://github.com/deepseek-ai/deepseek-harness) | DeepSeek Harness: Everything is a Plugin. | Starred | `c291e7961a51` |
| [esengine/DeepSeek-Reasonix](https://github.com/esengine/DeepSeek-Reasonix) | DeepSeek-native AI coding agent for your terminal. Engineered around prefix-cache stability — leave it running. | Starred | `7278072720a2` |
| [EverMind-AI/EverOS](https://github.com/EverMind-AI/EverOS) | One portable memory layer for every AI agent: local-first, Markdown-native, user-owned, and self-evolving across apps, tools, and workflows. | Starred | `5076683ab88d` |
| [farion1231/cc-switch](https://github.com/farion1231/cc-switch) | A cross-platform desktop All-in-One assistant for Claude Code, Codex, OpenCode, OpenClaw, Grok Build & Hermes Agent. Only official website: ccswitch.io | Starred | `bd247a4adb92` |
| [garrytan/gbrain](https://github.com/garrytan/gbrain) | Garry's Opinionated OpenClaw/Hermes Agent Brain | Starred | `a6be012a3bcf` |
| [lidge-jun/opencodex](https://github.com/lidge-jun/opencodex) | Universal provider proxy for OpenAI Codex & Claude Code — use any LLM (Claude, Gemini, Grok, DeepSeek, Ollama…) with Codex CLI, App, SDK, and Claude Code | Starred | `9f7397ed1582` |
| [makecindy/cindy](https://github.com/makecindy/cindy) | Consider it done. The open-source AI agent that works out of the box · 想到，就能做到。开源、开箱即用的 AI Agent。 | Starred | `f4422f816ccb` |
| [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | The agent that grows with you | Starred | `5eb99eb2844b` |
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | The AI that really does things. Any OS. Any Platform. The lobster way. 🦞 | Starred | `bcb8fa7b2bd5` |
| [router-for-me/CLIProxyAPI](https://github.com/router-for-me/CLIProxyAPI) | Wrap Antigravity, ChatGPT Codex, Claude Code, Grok Build as an OpenAI/Gemini/Claude/Codex compatible API service, allowing you to enjoy the free Gemini 3.1 Pro, GPT 5.6 Series, Grok 4.5, Claude model through API | Starred | `7fa443dc8bf8` |
| [volcengine/OpenViking](https://github.com/volcengine/OpenViking) | Self-evolving Context Database for AI Agents. Unify Agent Memory, Knowledge RAG and Skills. | Starred | `b54001e2e5c9` |
| [zinan92/agent-core](https://github.com/zinan92/agent-core) | AI agent 操作系统内核 — architecture-first starter package，提供 onboarding、skills、SOPs、runtime specs、curated knowledge 五大原语 | Owned + Starred | `owned source` |

### Agent Workflow (29)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [botiverse/hands](https://github.com/botiverse/hands) | The release platform for client apps, full loop: draft-first releases, staged rollouts, share pages, in-app updates, feedback & crash tickets — agent-native, built on Cloudflare. | Starred | `e16ce58c624b` |
| [catlog22/Claude-Code-Workflow](https://github.com/catlog22/Claude-Code-Workflow) | JSON-driven multi-agent cadence-team development framework with intelligent CLI orchestration (Gemini/Qwen/Codex), context-first architecture, and automated workflow execution | Starred | `07491b04ac30` · ARCHIVED |
| [cft0808/edict](https://github.com/cft0808/edict) | 🏛️ 三省六部制 · OpenClaw Multi-Agent Orchestration System — 9 specialized AI agents with real-time dashboard, model config, and full audit trails | Starred | `14a207557719` |
| [chenjin-cmd/wechat-miniprogram-builder](https://github.com/chenjin-cmd/wechat-miniprogram-builder) | wechat-miniprogram-builder | Starred | `e8bba7855d92` |
| [Enderfga/claw-orchestrator](https://github.com/Enderfga/claw-orchestrator) | Run Claude Code, Codex, Antigravity, Cursor Agent and OpenCode as one runtime — persistent sessions, multi-agent councils, an OpenAI-compatible endpoint, an MCP server, and an ACP agent any editor can drive. | Starred | `3e09b032a2f9` |
| [frankbria/ralph-claude-code](https://github.com/frankbria/ralph-claude-code) | Autonomous AI development loop for Claude Code with intelligent exit detection | Starred | `e8533cc3f009` |
| [garrytan/gstack](https://github.com/garrytan/gstack) | Use Garry Tan's exact Claude Code setup: 23 opinionated tools that serve as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA | Starred | `71f6048e8ada` |
| [huangruiteng/loopx](https://github.com/huangruiteng/loopx) | Long-horizon agent control plane for durable, governed work across Codex, Claude Code, and other harnesses. | Starred | `f87b5ea90e53` |
| [karpathy/autoresearch](https://github.com/karpathy/autoresearch) | AI agents running research on single-GPU nanochat training automatically | Starred | `228791fb499a` |
| [mattpocock/skills](https://github.com/mattpocock/skills) | Skills for Real Engineers. Straight from my .agents directory. | Starred | `3cca18b368ae` |
| [msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents) | A complete AI agency at your fingertips - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables. | Starred | `ad9264e309bd` |
| [multica-ai/multica](https://github.com/multica-ai/multica) | Make humans and AI agents work as one team — open-source and self-hostable. | Starred | `7dafc0cd6254` |
| [nizos/tdd-guard](https://github.com/nizos/tdd-guard) | Automated TDD enforcement for Claude Code | Starred | `fa4fa79551c2` |
| [obra/superpowers](https://github.com/obra/superpowers) | An agentic skills framework & software development methodology that works. | Starred | `b36e0829c6d0` |
| [open-gsd/gsd-core](https://github.com/open-gsd/gsd-core) | Git. Ship. Done - Core | Starred | `ed819aa4d642` |
| [openai/evals](https://github.com/openai/evals) | Evals is a framework for evaluating LLMs and LLM systems, and an open-source registry of benchmarks. | Starred | `8eac7a7de521` |
| [openai/symphony](https://github.com/openai/symphony) | Symphony turns project work into isolated, autonomous implementation runs, allowing teams to manage work instead of supervising coding agents. | Starred | `e0ccc83720a4` |
| [paperclipai/paperclip](https://github.com/paperclipai/paperclip) | The open-source app everyone uses to manage agents at work | Starred | `13368c518303` |
| [phuryn/pm-skills](https://github.com/phuryn/pm-skills) | PM Skills Marketplace: 100+ agentic skills, commands, and plugins — from discovery to strategy, execution, launch, and growth. | Starred | `18468a95b427` |
| [Pimzino/claude-code-spec-workflow](https://github.com/Pimzino/claude-code-spec-workflow) | Automated workflows for Claude Code. Features spec-driven development for new features (Requirements → Design → Tasks → Implementation) and streamlined bug fix workflow for quick issue resolution (Report → Analyze → Fix → Verify). | Starred | `f3de74d80551` |
| [ruvnet/ruflo](https://github.com/ruvnet/ruflo) | 🌊 The original agent harness. Deploy intelligent multi-player swarms, coordinate autonomous workflows, and build conversational AI systems. Features adaptive memory, self-learning intelligence, federation, vector RAG integration, and native Claude Code / Codex / Hermes and many more Integrated | Starred | `b02c0cacec22` |
| [SeemSeam/claude_codex_bridge](https://github.com/SeemSeam/claude_codex_bridge) | Visible multi-agent CLI workspace for mixing Codex, Claude, Gemini, Kimi, Qwen, Cursor, Copilot, Pi, OpenCode, and other AI coding agents | Starred | `20ac0ec58c17` |
| [SeemSeam/plan-tree](https://github.com/SeemSeam/plan-tree) | Codex skill for maintaining structured planning document trees | Starred | `b57be8261030` |
| [SuperClaude-Org/SuperClaude_Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) | A configuration framework that enhances Claude Code with specialized commands, cognitive personas, and development methodologies. | Starred | `1b81e51db955` |
| [Untrivial-ai/agent-orchestrator](https://github.com/Untrivial-ai/agent-orchestrator) | Run and supervise teams of coding agents from planning to merge. Any harness (Claude code, codex, +25 more). Desktop, web, mobile, and cloud agents. | Starred | `84fb98e3f14e` |
| [Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode) | Teams-first Multi-agent orchestration for Claude Code | Starred | `5281b19e0d64` |
| [zinan92/doc-driven-dev-workflow](https://github.com/zinan92/doc-driven-dev-workflow) | 5-phase / 22-stage 的 AI-native 文档驱动开发 workflow，内置 task scaffolding、workflow guards、state/event writer scripts 与 local-first observer dashboard。 | Owned + Starred | `owned source` |
| [zinan92/loop](https://github.com/zinan92/loop) | 把一次性 coding-agent prompt 变成「按价值排序、可审计、可暂停」的执行闭环 · Value-ranked, auditable, pausable coding-agent loop. in: local Git repo + contract → out: GitHub issues/PRs + digest. Codex or Claude, macOS. | Owned + Starred | `owned source` |
| [zinan92/wechat-miniprogram-shipping](https://github.com/zinan92/wechat-miniprogram-shipping) | 证据门控的原生微信小程序交付路由器。in 意图/项目证据 → out 合同、QA verdict、可回退 receipt | Owned + Starred | `owned source` |

### Agent Skills & Plugins (15)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [alchaincyf/darwin-skill](https://github.com/alchaincyf/darwin-skill) | 达尔文.skill —— 一个让你的Skill无限进化的系统：评估→改进→测试→保留或回滚 \| Autoresearch-inspired autonomous skill optimization for Claude Code. Evaluate, improve, test, keep or revert. | Starred | `5539516444cf` |
| [anthropics/skills](https://github.com/anthropics/skills) | Public repository for Agent Skills | Starred | `34040c9c5685` |
| [czlonkowski/n8n-skills](https://github.com/czlonkowski/n8n-skills) | n8n skillset for Claude Code to build flawless n8n workflows | Starred | `2df0f18cb520` |
| [LearnPrompt/luban-skill](https://github.com/LearnPrompt/luban-skill) | 鲁班 \| Luban — 把'能用的Skill'打磨成'能被装、能传播、能验证、能进化'的公共资产。Agent skill-polishing workshop: 验料·访行·过尺·慢刨·回炉 | Starred | `cea2da331027` |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | Taste-Skill - gives your AI good taste. stops the AI from generating boring, generic slop | Starred | `ccbc15639c97` |
| [Martian-Engineering/lossless-claw](https://github.com/Martian-Engineering/lossless-claw) | Lossless Claw — LCM (Lossless Context Management) plugin for OpenClaw | Starred | `a3eedf5c94ea` |
| [nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) | An AI skill that provides design intelligence for building professional UI/UX across multiple platforms. | Starred | `7f69fed6a271` |
| [nexu-io/html-anything](https://github.com/nexu-io/html-anything) | ✨ The agentic HTML editor — your local AI agent writes the HTML, you ship it. 🚀 75 Skills × 9 Surfaces (magazine · deck · poster · XHS / tweet · prototype · data report · Hyperframes) 🛡️ Sandboxed preview · 📤 1-click to WeChat / X / Zhihu / HTML / PNG 🔑 Zero API key — Claude Code / Cursor / Codex / Gemini / Copilot / OpenCode / Qwen / Aider. | Starred | `c31204544230` |
| [nexu-io/open-design](https://github.com/nexu-io/open-design) | 🎨 Best DeepSeek Harness Design Plugin. The open-source Claude Design alternative. 🖥️ Local-first desktop app. 🖼️ Your coding agent becomes the design engine: prototypes, landing pages, dashboards, slides, images & video — real files, HTML/PDF/PPTX/MP4 export. 🤖 Claude Code / Codex / Cursor / DeepSeek Harness / OpenCode & 20+ CLIs via BYOK. | Starred | `1424be972701` |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | The design language that makes your AI harness better at design. | Starred | `cb56ed6c19a0` |
| [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) | Vercel's official collection of agent skills | Starred | `063bee94c3f4` |
| [wshobson/agents](https://github.com/wshobson/agents) | Multi-harness agentic plugin marketplace for Claude Code, Codex, Cursor, OpenCode, GitHub Copilot, Google Antigravity, and Pi | Starred | `4236bb91f839` |
| [YishenTu/claudian](https://github.com/YishenTu/claudian) | An Obsidian plugin that embeds Claude Code/Codex as an AI collaborator in your vault | Starred | `2c07ee664439` |
| [zinan92/proactive-explorer](https://github.com/zinan92/proactive-explorer) | Strategic product direction finder for open-source repos — 5 MECE categories: Product Depth, Product Reach, Time-to-Value, Trust & Proof, Growth | Owned | `owned source` |
| [zinan92/repo-evals](https://github.com/zinan92/repo-evals) | Claim-first repo 评测框架。in target repo + claim map → out bilingual verdict dossier + all-evals dashboard | Owned + Starred | `owned source` |

### Agent Knowledge (9)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [alchaincyf/hermes-agent-orange-book](https://github.com/alchaincyf/hermes-agent-orange-book) | Hermes Agent 从入门到精通 · 橙皮书系列 · Nous Research 开源 AI Agent 框架实战指南 | Starred | `9ac06e1d0537` |
| [anthropics/claude-cookbooks](https://github.com/anthropics/claude-cookbooks) | A collection of notebooks/recipes showcasing some fun and effective ways of using Claude. | Starred | `a97b9a2dc300` |
| [birobirobiro/awesome-shadcn-ui](https://github.com/birobirobiro/awesome-shadcn-ui) | A curated list of awesome things related to shadcn/ui. | Starred | `395573307d79` |
| [ChinaSiro/claude-code-sourcemap](https://github.com/ChinaSiro/claude-code-sourcemap) | No description | Starred | `a8a678cb6244` |
| [freestylefly/CodexGuide](https://github.com/freestylefly/CodexGuide) | CodexGuide：面向全球初学者、创作者、开发者与团队的 Codex 实践指南 | Starred | `02d7b779d74f` |
| [hangsman/claude-code-source](https://github.com/hangsman/claude-code-source) | claude code source map v2.1.88 | Starred | `d239e3f2c574` |
| [libukai/awesome-agent-skills](https://github.com/libukai/awesome-agent-skills) | Agent Skills 终极指南：快速入门、资源推荐、精选技能与实用工具 ｜The Ultimate Guide to Agent Skills: QuickStart, Resources, Features&Toolkit | Starred | `5ccadec8831f` |
| [shareAI-lab/learn-claude-code](https://github.com/shareAI-lab/learn-claude-code) | Bash is all you need - A nano claude code–like 「agent harness」, built from 0 to 1 | Starred | `0dcafa2ae053` |
| [yanhua1010/dsh-harness-tutorial](https://github.com/yanhua1010/dsh-harness-tutorial) | DeepSeek Harness Agent 的原理与实现：从零到一实现一个 AI Agent —— 一切皆插件的中文教程（VitePress 站点 + 8 个 Demo + mini-harness 教学项目） | Starred | `2a29d03a8385` |

### Agent Observability (17)

| Repo | Capability / description | Source | Lock / flags |
|---|---|---|---|
| [BloopAI/vibe-kanban](https://github.com/BloopAI/vibe-kanban) | Get 10X more out of Claude Code, Codex or any coding agent | Starred | `4deb7eca8f38` |
| [cclank/lanshu-animated-architecture-diagram](https://github.com/cclank/lanshu-animated-architecture-diagram) | Premium hand-drawn animated architecture diagram Codex skill | Starred | `c17f5b4e5de9` |
| [chuspeeism/dashi-taskboard](https://github.com/chuspeeism/dashi-taskboard) | 现代化可灵活嵌入的任务面板，支持 Codex、DeepSeek Harness | Starred | `c346e8e16c9c` |
| [Cocoon-AI/architecture-diagram-generator](https://github.com/Cocoon-AI/architecture-diagram-generator) | Generate beautiful dark-themed system architecture diagrams as standalone HTML/SVG files. Works as a Claude AI skill. | Starred | `4b9087d55268` |
| [coze-dev/coze-studio](https://github.com/coze-dev/coze-studio) | An AI agent development platform with all-in-one visual tools, simplifying agent creation, debugging, and deployment like never before. Coze your way to AI Agent creation. | Starred | `fefb05ff27be` |
| [furkankly/zoetrope](https://github.com/furkankly/zoetrope) | Watch a Claude Code or Codex session as a live flow graph, in your terminal or your browser. | Starred | `b1f31dd26bd4` |
| [grp06/openclaw-studio](https://github.com/grp06/openclaw-studio) | A clean web dashboard for OpenClaw. Connect your Gateway, manage agents, and ship faster. ⭐️ Star if you like it! | Starred | `732b994120bb` |
| [kenn-io/agentsview](https://github.com/kenn-io/agentsview) | Local-first session search, analytics, insights, and token use statistics for coding agents, supporting Claude Code, Codex, and more than 20 other agents. | Starred | `9be7745ad190` |
| [Niall-Young/Canvasight](https://github.com/Niall-Young/Canvasight) | 用于梳理任务然后交付给 AI 工具的 plugin 插件 | Starred | `b4a002db9c4f` |
| [nicobailon/visual-explainer](https://github.com/nicobailon/visual-explainer) | Agent skill that generates rich HTML pages or slide decks for diagrams, diff reviews, plan audits, data tables, and project recaps | Starred | `7163c3e10660` |
| [openchamber/openchamber](https://github.com/openchamber/openchamber) | Agentic Development Environment based on OpenCode AI agent | Starred | `1636fd2bf8e4` |
| [rullerzhou-afk/clawd-on-desk](https://github.com/rullerzhou-afk/clawd-on-desk) | A pixel desktop pet that watches Claude Code, Codex, Cursor & other AI coding agents — so you don't have to. | Starred | `9367b8c3b1c2` |
| [tt-a1i/archify](https://github.com/tt-a1i/archify) | Agent skill for beautiful, verifiable architecture, workflow, sequence, data-flow, and lifecycle diagrams—self-contained HTML with motion and crisp export. | Starred | `a07fa1d5b2a1` |
| [vercel-labs/json-render](https://github.com/vercel-labs/json-render) | The Generative UI framework | Starred | `6c7164342a37` |
| [yizhiyanhua-ai/fireworks-tech-graph](https://github.com/yizhiyanhua-ai/fireworks-tech-graph) | Generate production-quality SVG+PNG technical diagrams from natural language. 7 styles, UML support, and AI/Agent workflow patterns. | Starred | `31fea364eda5` |
| [zhaoxinyi02/ClawPanel](https://github.com/zhaoxinyi02/ClawPanel) | 🐾 ClawPanel — OpenClaw AI 助手可视化管理面板。Go 单二进制部署，支持 20+ 通道统一管理，跨平台，实时日志监控。 | Starred | `28cfcb958da8` |
| [zinan92/agent-ticket-tracker](https://github.com/zinan92/agent-ticket-tracker) | Agent delivery map and safe wake briefs. in local spec and ticket artifacts → out map, evidence view, and safe next-action brief | Owned | `owned source` |

## Update contract

This README and the generated data are scoped views. Taxonomy, source state and lock authority remain in Park OS.

```bash
bash scripts/verify-scoped.sh
```

The registry is a catalog, not a production-readiness or execution-authorization claim.
