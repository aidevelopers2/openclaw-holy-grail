Welcome to the OpenClaw Holy Grail. This repository is a curated library for people learning, deploying, and operating OpenClaw in the real world. It collects setup guides, personas, memory systems, security hardening resources, MCP integrations, communities, comparisons, and workflow examples in one place.

It currently includes nearly 200 curated links across the OpenClaw ecosystem.

🛒 **[Browse the OpenClaw Marketplace](https://remoteopenclaw.com/marketplace)** — Production-tested personas, skills, and bundles from Remote OpenClaw.




---


## Table of Contents

1. [Introduction](#1-introduction)
   - [Overview](#overview-of-openclaw)
   - [Purpose](#purpose-of-this-repository)
2. [Official Resources](#2-official-resources)
3. [Getting Started & Setup Guides](#3-getting-started--setup-guides)
   - [Official Docs](#official-docs)
   - [Community Guides](#community-guides)
4. [Learning Resources](#4-learning-resources)
   - [YouTube Videos & Channels](#youtube-videos--channels)
   - [Blog Posts & Articles](#blog-posts--articles)
   - [Courses & Tutorials](#courses--tutorials)
5. [Personas & Agent Configurations](#5-personas--agent-configurations)
6. [Memory Systems](#6-memory-systems)
7. [Skills, Tools & Integrations](#7-skills-tools--integrations)
   - [Free Skills](#free-skills)
   - [Skill Registries & Collections](#skill-registries--collections)
   - [MCP Integrations](#mcp-integrations)
   - [Third-Party Tools](#third-party-tools)
8. [Security & Hardening](#8-security--hardening)
9. [Model Compatibility](#9-model-compatibility)
10. [Advanced Use Cases](#10-advanced-use-cases)
    - [Multi-Agent Systems](#multi-agent-systems)
    - [Real-World Workflows](#real-world-workflows)
11. [Communities](#11-communities)
    - [Discord](#discord)
    - [Reddit](#reddit)
    - [Skool Groups](#skool-groups)
    - [Other](#other)
12. [Alternatives & Comparisons](#12-alternatives--comparisons)
13. [Awesome Lists & Meta-Resources](#13-awesome-lists--meta-resources)
14. [Contributing & Code of Conduct](#14-contributing--code-of-conduct)
15. [Support My Work](#15-support-my-work)
16. [License](#16-license)
17. [Disclosure](#17-disclosure)
18. [Contact Me](#18-contact-me)

---

## 1. Introduction

### Overview of OpenClaw

OpenClaw is a fast-moving open-source, self-hosted AI agent platform focused on autonomous workflows, channel integrations, tools, memory, and agent orchestration. The ecosystem changes quickly, which is exactly why a curated operator-facing resource list is useful.

OpenClaw runs locally on your machine and connects to any AI model — Claude, GPT, Gemini, DeepSeek, Ollama local models, and more. It supports 15+ messaging channels including WhatsApp, Telegram, Slack, Discord, and iMessage. What makes it powerful is the persona system: SOUL.md for personality, AGENTS.md for operating rules, MEMORY.md for persistent context, and IDENTITY.md for personalization.

### Purpose of This Repository

This repository is an independent curated collection of OpenClaw resources. It includes official docs, setup guides, tutorials, security hardening resources, persona templates, memory systems, MCP integrations, community links, and advanced workflow references. Explore it, use it, and contribute improvements where the list is thin or stale.


---

## 2. Official Resources

| **Resource** | **Description** | **Link** |
|-------------|-----------------|----------|
| **OpenClaw Website** | Main official site for the OpenClaw project. | [openclaw.ai](https://openclaw.ai/) |
| **GitHub Repository** | Primary source code for the OpenClaw project. | [openclaw/openclaw](https://github.com/openclaw/openclaw) |
| **Official Documentation** | Setup, configuration, and reference docs. | [docs.openclaw.ai](https://docs.openclaw.ai/) |
| **Release Notes** | Official release notes and changelogs. | [Releases](https://github.com/openclaw/openclaw/releases) |
| **AGENTS.md Reference** | Official AGENTS.md template for agent operating rules. | [AGENTS.md](https://github.com/openclaw/openclaw/blob/main/AGENTS.md) |
| **ClawHub Skill Registry** | Official directory for publishing and searching agent skills. | [clawhub](https://github.com/openclaw/clawhub) |
| **Community GitHub** | Policies and documentation for the Discord server. | [community](https://github.com/openclaw/community) |
| **OpenClaw Wikipedia** | History, features, architecture, and security events. | [Wikipedia](https://en.wikipedia.org/wiki/OpenClaw) |
| **OpenClaws.io** | Community site covering OpenClaw news, resources, and commentary. | [openclaws.io](https://openclaws.io/) |

---

| **OpenClaw v2026.4.1 Release** | Latest stable release — April 2026 with control UI improvements and skill management updates. | [Release Notes](https://github.com/openclaw/openclaw/releases/tag/v2026.4.1) |

---

## 3. Getting Started & Setup Guides

### Official Docs

| **Guide** | **Description** | **Link** |
|-----------|-----------------|----------|
| **Getting Started Guide** | Official docs for first message, basic config. | [Getting Started](https://docs.openclaw.ai/start/getting-started) |
| **Personal Assistant Setup** | Official guide for configuring OpenClaw as your assistant. | [Personal Setup](https://docs.openclaw.ai/start/openclaw) |
| **Docker Install Guide** | Official Docker installation documentation. | [Docker](https://github.com/openclaw/openclaw/blob/main/docs/install/docker.md) |
| **Plugin Bundles** | Official docs on installing and managing plugins. | [Plugin Bundles](https://docs.openclaw.ai/plugins/bundles) |

### Community Guides

| **Guide** | **Description** | **Link** |
|-----------|-----------------|----------|
| **Ollama — Simplest Setup** | Set up OpenClaw with Ollama in under two minutes. | [Ollama Blog](https://ollama.com/blog/openclaw-tutorial) |
| **DigitalOcean — How to Run OpenClaw** | Step-by-step DigitalOcean deployment tutorial. | [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-run-openclaw) |
| **AWS Lightsail Quick Start** | Official AWS guide for running on Amazon Lightsail. | [AWS Lightsail](https://docs.aws.amazon.com/lightsail/latest/userguide/amazon-lightsail-quick-start-guide-openclaw.html) |
| **Verdent — Install & Configure in 15 Min** | Zero-to-assistant setup covering install, config, first connection. | [Verdent](https://www.verdent.ai/guides/openclaw-setup-guide-from-zero-to-ai-assistant) |
| **ShareUHack — Complete Installation Tutorial** | Detailed 2026 guide with legal/compliance considerations. | [ShareUHack](https://www.shareuhack.com/en/posts/openclaw-setup-tutorial-2026) |
| **WayIn AI — Step-by-Step for Beginners** | Beginner-friendly walkthrough covering prerequisites. | [WayIn AI](https://wayin.ai/blog/openclaw-setup-guide/) |
| **Creator Economy — Master in 30 Minutes** | Safe setup, 5 real use cases, and memory config. | [Creator Economy](https://creatoreconomy.so/p/master-openclaw-in-30-minutes-full-tutorial) |
| **Lenny's Newsletter — Complete Guide** | Building, training, and living with your personal AI agent. | [Lenny's](https://www.lennysnewsletter.com/p/openclaw-the-complete-guide-to-building) |
| **freeCodeCamp — Full Tutorial for Beginners** | Comprehensive written companion to the YouTube course. | [freeCodeCamp](https://www.freecodecamp.org/news/openclaw-full-tutorial-for-beginners/) |
| **LumaDock — Multi-Channel Setup** | Guide for WhatsApp, Telegram, Discord, Slack. | [LumaDock](https://lumadock.com/tutorials/openclaw-multi-channel-setup) |

---

## 4. Learning Resources

### YouTube Videos & Channels

| **Video / Channel** | **Description** | **Link** |
|---------------------|-----------------|----------|
| **freeCodeCamp — Full Tutorial** | 1-hour course: install, models, memory, skills, Docker. | [freeCodeCamp](https://www.freecodecamp.org/news/openclaw-full-tutorial-for-beginners/) |
| **Creator Economy — 24/7 AI Employee** | Video tutorial with top 5 use cases and safe setup. | [Creator Economy](https://creatoreconomy.so/p/full-tutorial-set-up-your-247-ai-employee-clawd-molt) |
| **TubeScout — Best Videos Summarized** | Aggregated and summarized top OpenClaw YouTube content. | [TubeScout](https://tubescout.app/topic/openclaw) |
| **Lilys AI — Tutorial Hub** | YouTube summary notes for OpenClaw tutorials. | [Lilys AI](https://lilys.ai/en/notes/openclaw-tutorial-20260204/) |
| **OpenClaw After 50 Days — All Prompts** | GitHub gist with all prompts for 20 real workflows. | [Gist](https://gist.github.com/velvet-shark/b4c6724c391f612c4de4e9a07b0a74b6) |
| **OpenClawAI.io — Tutorials & Videos** | Curated tutorials and video content aggregator. | [OpenClawAI](https://openclawai.io/tutorials/) |
| **Zac Frulloni — YouTube Channel** | OpenClaw tutorials, reviews, and deep dives. 1.8k+ subs. | [YouTube](https://www.youtube.com/@Zac-Frulloni) |

### Blog Posts & Articles

| **Article** | **Description** | **Link** |
|-------------|-----------------|----------|
| **KDnuggets — OpenClaw Explained** | Accessible overview of what OpenClaw is and why it went viral. | [KDnuggets](https://www.kdnuggets.com/openclaw-explained-the-free-ai-agent-tool-going-viral-already-in-2026) |
| **DigitalOcean — What is OpenClaw?** | Clear explanation for developers new to the platform. | [DigitalOcean](https://www.digitalocean.com/resources/articles/what-is-openclaw) |
| **Milvus — Complete Guide to the AI Agent** | Technical deep dive into architecture and capabilities. | [Milvus](https://milvus.io/blog/openclaw-formerly-clawdbot-moltbot-explained-a-complete-guide-to-the-autonomous-ai-agent.md) |
| **Turing College — The AI That Actually Does Things** | Review and practical assessment of real-world utility. | [Turing College](https://www.turingcollege.com/blog/openclaw) |
| **CyberNews — OpenClaw Review 2026** | Independent review covering features and security. | [CyberNews](https://cybernews.com/ai-tools/openclaw-review/) |
| **Serenities AI — 234K Stars Deep Dive** | Comprehensive deep dive on growth, architecture, memory. | [Serenities AI](https://serenitiesai.com/articles/openclaw-deep-dive-2026) |
| **Medium — Why is OpenClaw So Viral?** | Analysis of the agent revolution and explosive adoption. | [Medium](https://medium.com/@302.AI/why-is-openclaw-so-viral-a-deep-dive-into-the-agent-revolution-e92891c51eae) |
| **Medium — How a Proactive AI Agent Works** | Architecture, workflows, local setup, safety. | [Medium](https://medium.com/@chetankerhalkar/openclaw-deep-dive-2026-how-a-proactive-ai-agent-actually-works-architecture-workflows-10a8f8f0e758) |
| **OAX Foundation — The Epic Rise** | Long-form piece on the history and growth trajectory. | [OAX](https://www.oax.org/2026/03/23/A-Deep-Dive-Into-The-Epic-Rise-of-OpenClaw.html) |
| **OpenClaws.io — ContextEngine Deep Dive** | How OpenClaw 2026.3.7 turned context into a plugin. | [OpenClaws.io](https://openclaws.io/blog/openclaw-contextengine-deep-dive) |
| **VirtualUncle — Complete 2026 Guide** | Install, cost, hardware requirements, practical guidance. | [VirtualUncle](https://virtualuncle.com/openclaw-complete-guide-2026/) |
| **QubitTool — Build Your Own AI Agent** | Complete guide to building and customizing from scratch. | [QubitTool](https://qubittool.com/blog/openclaw-ai-agent-complete-guide) |
| **Every.to — Claw School for Beginners** | Polished beginner guide from the Every publication. | [Every.to](https://every.to/guides/claw-school) |
| **AWS Blog — OpenClaw on Lightsail** | AWS official announcement for running on Lightsail. | [AWS Blog](https://aws.amazon.com/blogs/aws/introducing-openclaw-on-amazon-lightsail-to-run-your-autonomous-private-ai-agents/) |

| **DigitalOcean — What Are OpenClaw Skills?** | Developer's guide to understanding and building OpenClaw skills. | [DigitalOcean](https://www.digitalocean.com/resources/articles/what-are-openclaw-skills) |
| **Top 10 OpenClaw Skills (Composio)** | Tested and ranked productivity skills for OpenClaw. | [Composio](https://composio.dev/content/top-openclaw-skills) |
| **Best OpenClaw Skills 2026 (TheGuidex)** | 20 best skills tested and ranked by category. | [TheGuidex](https://theguidex.com/best-openclaw-skills/) |

### Courses & Tutorials

| 📘 **Course** | 🏫 **Platform** | 💰 **Cost** | **Link** |
|---------------|-----------------|-------------|----------|
| **OpenClaw Full Tutorial for Beginners** | freeCodeCamp | Free | [Watch](https://www.freecodecamp.org/news/openclaw-full-tutorial-for-beginners/) |
| **Master OpenClaw in 30 Minutes** | Creator Economy | Free | [Read](https://creatoreconomy.so/p/master-openclaw-in-30-minutes-full-tutorial) |
| **IDENTITY.md Agent Identity Course** | Stanza | Free | [Take Course](https://www.stanza.dev/courses/openclaw-personalization/agent-persona/openclaw-personalization-identity-md) |
| **OpenClaw with Ollama Tutorial** | DataCamp | Free | [Tutorial](https://www.datacamp.com/tutorial/openclaw-ollama-tutorial) |
| **Complete Guide — Lenny's Newsletter** | Lenny's | Free | [Read](https://www.lennysnewsletter.com/p/openclaw-the-complete-guide-to-building) |
| **Claw School — Every.to** | Every.to | Free | [Read](https://every.to/guides/claw-school) |

---

## 5. Personas & Agent Configurations

| **Resource** | **Description** | **Link** |
|-------------|-----------------|----------|
| **OpenClaw Marketplace** | Pre-built personas, skills, and bundles — free and paid. | [Marketplace](https://remoteopenclaw.com/marketplace) |
| **Awesome OpenClaw Agents (162 Templates)** | 162 production-ready agent templates across 19 categories. | [mergisi/awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents) |
| **Will-Assistant — Agent Personalities** | Curated SOUL.md, AGENTS.md, IDENTITY.md personality configs. | [will-assistant](https://github.com/will-assistant/openclaw-agents/tree/main) |
| **AGENTS.md Template (Official)** | Official AGENTS.md template for creating agent rules. | [AGENTS.md](https://docs.openclaw.ai/reference/templates/AGENTS) |
| **AGENTS.dev.md Template** | Developer-focused AGENTS.md template from official repo. | [AGENTS.dev.md](https://github.com/openclaw/openclaw/blob/main/docs/reference/templates/AGENTS.dev.md) |
| **Default AGENTS.md Reference** | Reference for the default AGENTS.md configuration. | [Default Reference](https://openclawcn.com/en/docs/reference/agents.default/) |
| **Stanza — IDENTITY.md Course** | Course on personalizing agent identity via IDENTITY.md. | [Stanza](https://www.stanza.dev/courses/openclaw-personalization/agent-persona/openclaw-personalization-identity-md) |
| **Meta Intelligence — Agents Guide** | Agent add, list, config set, and model routing commands. | [Meta Intelligence](https://www.meta-intelligence.tech/en/insight-openclaw-agents-guide) |
| **Make Your Agent Useful & Secure** | Practical guide to useful and secure agent configuration. | [Substack](https://amankhan1.substack.com/p/how-to-make-your-openclaw-agent-useful) |
| **ucsandman — Personal Setup** | Real-world setup with hierarchical memory and tools. | [ucsandman](https://github.com/ucsandman/OpenClaw-Setup) |

---

## 6. Memory Systems

| **Resource** | **Description** | **Link** |
|-------------|-----------------|----------|
| **SOUL.md Guide (Official)** | Official guide to SOUL.md — the core personality file. | [SOUL.md Guide](https://clawdocs.org/guides/soul-md/) |
| **SOUL.md Personality Config** | Detailed SOUL.md configuration walkthrough. | [tenten.co](https://tenten.co/openclaw/en/docs/getting-started/soul-md-config) |
| **soul.md Generator Tool** | Let Claude Code ingest your data and build your AI soul. | [soul.md Generator](https://github.com/aaronjmars/soul.md) |
| **MMNTM — Identity Architecture** | Deep dive on Soul, Persona, Multi-Agent identity. | [MMNTM](https://www.mmntm.net/articles/openclaw-identity-architecture) |
| **Trilogy AI — Manage Memory** | Practical how-to for effective memory management. | [Trilogy AI](https://trilogyai.substack.com/p/how-to-manage-your-openclaw-memory) |
| **SoulClaw (Enhanced Memory Fork)** | Soul-aware fork with enhanced memory and security. | [SoulClaw](https://github.com/clawsouls/soulclaw) |
| **ClawSouls — Soul Spec Guide** | Guide to using Soul Spec for personality configuration. | [ClawSouls](https://blog.clawsouls.ai/en/guides/openclaw-soul/) |
| **AWS — Fine-Tuning Memory & Soul** | AWS guide for tuning SOUL.md, MEMORY.md, personality. | [DEV Community](https://dev.to/aws-builders/mastering-openclaw-on-aws-fine-tuning-personality-memory-and-soul-37ig) |
| **Workspace Files Explained** | SOUL.md, AGENTS.md, HEARTBEAT.md and all files explained. | [Medium](https://capodieci.medium.com/ai-agents-003-openclaw-workspace-files-explained-soul-md-agents-md-heartbeat-md-and-more-5bdfbee4827a) |

---

## 7. Skills, Tools & Integrations

### Free Skills

These are free, ready-to-use skills you can download and plug into any OpenClaw agent right now.

| **Skill** | **Description** | **Link** |
|-----------|-----------------|----------|
| **Cost Optimizer** | Routes tasks to the cheapest suitable model. Save 50-70% on API costs automatically. | [Get Free](https://remoteopenclaw.com/marketplace) |
| **Security Hardener** | Runs the 12-step security checklist and auto-fixes 7 of 12 checks. | [Get Free](https://remoteopenclaw.com/marketplace) |
| **Daily Briefing** | Morning Telegram summary with weather, tasks, and schedule. | [Get Free](https://remoteopenclaw.com/marketplace) |
| **Content Repurposer** | Turns a blog post URL into an X thread + LinkedIn post + Instagram caption. | [Get Free](https://remoteopenclaw.com/marketplace) |

### Skill Registries & Collections

| **Resource** | **Description** | **Link** |
|-------------|-----------------|----------|
| **ClawHub (Official Registry)** | Official directory for publishing, versioning, and searching skills. | [ClawHub](https://github.com/openclaw/clawhub) |
| **Awesome OpenClaw Skills (5,400+)** | 5,400+ skills filtered and categorized from the official registry. | [VoltAgent](https://github.com/VoltAgent/awesome-openclaw-skills) |
| **Awesome OpenClaw Agents (162 Templates)** | 162 production-ready agent templates with skills across 19 categories. | [mergisi](https://github.com/mergisi/awesome-openclaw-agents) |
| **Plugin Bundles (Official)** | Install and manage plugin bundles — local, archive, marketplace. | [Plugin Bundles](https://docs.openclaw.ai/plugins/bundles) |

### MCP Integrations

| **Tool** | **Description** | **Link** |
|---------|-----------------|----------|
| **OpenClaw MCP Bridge (Claude)** | Bridge Claude.ai to your self-hosted OpenClaw with OAuth2. | [openclaw-mcp](https://github.com/freema/openclaw-mcp) |
| **Composio — 500+ App Integrations** | Connect Slack, GitHub, Notion, Google Workspace, and more. | [Composio](https://composio.dev/toolkits/composio/framework/openclaw) |
| **Composio — Make (Integromat)** | Connect Make automation workflows to OpenClaw. | [Composio Make](https://composio.dev/toolkits/make/framework/openclaw) |
| **Composio — Browser Tool** | Web browsing automation for OpenClaw agents. | [Browser MCP](https://composio.dev/toolkits/browser_tool/framework/openclaw) |
| **Composio — Microsoft Teams** | Microsoft Teams integration for OpenClaw. | [Teams MCP](https://composio.dev/toolkits/microsoft_teams/framework/openclaw) |
| **TranscriptAPI — YouTube MCP** | Connect OpenClaw to YouTube via MCP for transcripts. | [TranscriptAPI](https://transcriptapi.com/blog/connect-openclaw-youtube-mcp) |
| **Chrome DevTools MCP** | Give OpenClaw full browser control — read pages, click, fill forms, trace performance. | [Chrome MCP Guide](https://medium.com/@tentenco/openclaw-chrome-devtools-mcp-how-to-give-your-local-agent-full-browser-control-a4e7c723a649) |
| **Cursor MCP + OpenClaw** | Connect Cursor IDE to OpenClaw via MCP. | [Composio Cursor](https://composio.dev/toolkits/cursor/framework/openclaw) |
| **Fast.io MCP Tools (251)** | 251 pre-built MCP tools for file management, web search, and more. | [Fast.io](https://fast.io/resources/openclaw-custom-mcp-server/) |
| **MCP Integration Guide 2026** | Complete walkthrough of MCP setup and custom server building. | [ComputerTech](https://computertech.co/openclaw-mcp-integration-guide-2026/) |

### Third-Party Tools

| **Tool** | **Description** | **Link** |
|---------|-----------------|----------|
| **Mission Control Dashboard** | AI agent orchestration — manage agents, assign tasks. | [Mission Control](https://github.com/abhi1693/openclaw-mission-control) |
| **Nova YouTube Agent** | YouTube growth agent — competitor scanning, script writing. | [Nova](https://github.com/sharbelxyz/nova-youtube-agent) |
| **OpenClaw YouTube Skill** | Skill for YouTube transcript retrieval and summarization. | [YouTube Skill](https://github.com/happynocode/openclaw-skill-youtube) |
| **GetYouTubeTranscript Skill** | ClawHub skill for YouTube transcripts in any caption language, YouTube search, and channel and playlist data (API key, 100 free credits). | [ClawHub](https://clawhub.ai/tubeagentkit/youtube-transcript) |
| **Reddit Read-Only Skill** | Browse and read Reddit without API keys. | [Reddit Skill](https://github.com/ajitesh-kuppa-sivakumar/reddit-openclaw) |
| **OpenClaw Master Skills (560+)** | 560+ curated skills, weekly updated by MyClaw.ai. | [Master Skills](https://github.com/LeoYeAI/openclaw-master-skills) |
| **OpenClaw Workspace (Hermes)** | Native web workspace — chat, terminal, memory, skills, inspector. | [hermes-workspace](https://github.com/outsourc-e/hermes-workspace) |
| **OpenClaw Quickstart Templates** | Pre-configured starter templates for common use cases. | [kasjens/nemoclaw-setup](https://github.com/kasjens/nemoclaw-setup) |
| **OpenClaw Claude Code Plugin** | Turn Claude Code CLI into a headless coding engine with agent teams and multi-model proxy. | [openclaw-claude-code](https://github.com/Enderfga/openclaw-claude-code) |
| **Lobster — Workflow Shell** | OpenClaw-native typed workflow shell — composable pipelines and safe automations from skills. | [Lobster](https://github.com/openclaw/lobster) |
| **OpenClaw Docker Templates** | Community Docker Compose templates for quick self-hosted deployment. | [GitHub Topics](https://github.com/topics/openclaw-plugins) |

---

## 8. Security & Hardening

> **Important:** OpenClaw is powerful, but the ecosystem moves quickly and third-party skills deserve scrutiny. Use sandboxing, least privilege, approval gates, and basic hardening before you trust a production deployment.

| **Resource** | **Description** | **Link** |
|-------------|-----------------|----------|
| **Official Security Docs** | Official security documentation for the Gateway. | [Security Docs](https://docs.openclaw.ai/gateway/security) |
| **Docker — Run Securely in Sandboxes** | Docker's official sandboxing guide. | [Docker Blog](https://www.docker.com/blog/run-openclaw-securely-in-docker-sandboxes/) |
| **Hostinger — Secure on VPS** | VPS-specific hardening guide. | [Hostinger](https://www.hostinger.com/support/how-to-secure-and-harden-openclaw-security/) |
| **Nebius — Security Architecture** | Comprehensive architecture analysis with hardening recs. | [Nebius](https://nebius.com/blog/posts/openclaw-security) |
| **Complete Hardening for VPS & Docker** | Detailed practitioner guide for production deployments. | [Medium](https://alirezarezvani.medium.com/openclaw-security-my-complete-hardening-guide-for-vps-and-docker-deployments-14d754edfc1e) |
| **Security Best Practices 2026** | 2026 best practices checklist for hardening. | [OpenClaw Desktop](https://openclawdesktop.com/blog/hardening-openclaw-security-best-practices.html) |
| **Complete Security Hardening Guide** | Step-by-step with checklists. | [OpenClaw Roadmap](https://openclawroadmap.com/security-best-practices.php) |
| **Docker Hardening for Production** | Production-grade Docker hardening walkthrough. | [AdvenBoost](https://advenboost.com/openclaw-docker-hardening-your-ai-sandbox-for-production-2026/) |
| **ClawHavoc — Lessons Learned** | Post-mortem on the supply chain attack. | [OpenClaw Blog](https://openclawblog.space/articles/openclaw-security-crisis-2026-what-happened-and-lessons-learned) |
| **Enterprise Security Assessment** | Enterprise risk analysis and what to know before deploying. | [Immersive Labs](https://www.immersivelabs.com/resources/c7-blog/openclaw-what-you-need-to-know-before-it-claws-its-way-into-your-organization) |
| **Daytona — Secure Sandbox** | Daytona sandbox environment for secure execution. | [Daytona](https://www.daytona.io/docs/en/guides/openclaw/openclaw-run-secure-sandbox/) |

| **ClawHavoc Security Advisory** | Malicious skills campaign — typosquatted names in ClawHub. Always verify before installing. | [Viblo Advisory](https://viblo.asia/p/best-way-to-uninstall-openclaw-completly-and-check-for-malware-2026-3RL1B8E8Vao) |

---

## 9. Model Compatibility

| **Resource** | **Description** | **Link** |
|-------------|-----------------|----------|
| **Ollama Official Integration** | Official Ollama docs for OpenClaw (official provider March 2026). | [Ollama Docs](https://docs.ollama.com/integrations/openclaw) |
| **Ollama Blog — Setup** | Getting started with OpenClaw locally via Ollama. | [Ollama Blog](https://ollama.com/blog/openclaw) |
| **Switching Models (Claude, GPT, Gemini)** | Guide to changing AI models and provider configuration. | [GetOpenClaw](https://www.getopenclaw.ai/en/help/switching-models-provider-config) |
| **Best Ollama Models (Tested)** | Local LLMs tested and ranked for performance. | [Haimaker](https://haimaker.ai/blog/best-local-models-for-openclaw/) |
| **Best Models — All Providers** | Cloud and local models tested and ranked (March 2026). | [Haimaker](https://haimaker.ai/blog/best-models-for-clawdbot/) |
| **Model Compatibility Chart** | DeepSeek, OpenAI, Anthropic and more. | [OpenClawed AI](https://openclawed-ai.com/models/) |
| **Private Local LLM with Ollama** | Real-world troubleshooting for Ollama + OpenClaw. | [Medium](https://medium.com/@rogerio.a.r/setting-up-a-private-local-llm-with-ollama-for-use-with-openclaw-a-tale-of-silent-failures-01cadfee717f) |
| **DataCamp — Local Data Analyst** | Build a local data analyst agent with Ollama. | [DataCamp](https://www.datacamp.com/tutorial/openclaw-ollama-tutorial) |
| **Zero API Cost — Local Models** | Run OpenClaw completely free with Ollama. | [LumaDock](https://lumadock.com/tutorials/openclaw-ollama-local-models-setup) |
| **No API Costs Guide** | Step-by-step for zero-cost OpenClaw. | [AI Tool Discovery](https://www.aitooldiscovery.com/how-to/openclaw-ollama-local-models) |
| **Zero Cost Gist** | Concise config for free OpenClaw via Ollama. | [GitHub Gist](https://gist.github.com/iam-veeramalla/9d10f968038ee76d5bc374b44f0cf8bb) |

---

## 10. Advanced Use Cases

### Multi-Agent Systems

| **Resource** | **Description** | **Link** |
|-------------|-----------------|----------|
| **Official Multi-Agent Docs** | Official documentation on multi-agent routing. | [Multi-Agent](https://docs.openclaw.ai/concepts/multi-agent) |
| **ClawDocs — Multi-Agent Guide** | Comprehensive guide to building multi-agent systems. | [ClawDocs](https://clawdocs.org/guides/multi-agent/) |
| **Deterministic Multi-Agent Pipeline** | Real build log of programmer + reviewer agent pipeline. | [DEV Community](https://dev.to/ggondim/how-i-built-a-deterministic-multi-agent-dev-pipeline-inside-openclaw-and-contributed-a-missing-4ool) |
| **Build a Multi-Agent System** | Step-by-step for specialized multi-agent setups. | [Open-ClawAI](https://www.open-clawai.com/en/blog/build-multi-agent-system) |
| **Multi-Agent Team Example** | Configuration example and documentation. | [GitHub](https://github.com/hesamsheikh/awesome-openclaw-usecases/blob/main/usecases/multi-agent-team.md) |

### Real-World Workflows

| **Resource** | **Description** | **Link** |
|-------------|-----------------|----------|
| **Advanced Workflows 2026** | Real power-user use cases and workflow patterns. | [LightNode](https://go.lightnode.com/tech/advanced-openclaw-workflows) |
| **Business Use Cases & Enterprise Risks** | Where autonomous AI creates value and where it needs guardrails. | [Codebridge](https://www.codebridge.tech/articles/openclaw-case-studies-for-business-workflows-that-show-where-autonomous-ai-creates-value-and-where-enterprises-need-guardrails) |
| **15 Use Cases That Actually Work** | Tested and validated real-world use cases. | [Kanerika](https://kanerika.com/blogs/openclaw-usecases/) |
| **50 Real-World Use Cases** | Extensive catalog of production use cases. | [ClawBot Blog](https://www.clawbot.blog/blog/openclaw-50-real-world-use-cases-for-the-open-source-ai-agent-framework/) |
| **500 OpenClaw Use Cases** | Massive collection of workflow automation use cases. | [Julian Goldie](https://juliangoldie.com/openclaw-use-cases/) |
| **9 Projects to Build in 2026** | From Reddit bots to self-healing servers. | [DataCamp](https://www.datacamp.com/blog/openclaw-projects) |
| **OpenClaw on exe.dev with Discord** | Running OpenClaw on exe.dev with Discord integration. | [DEV Community](https://dev.to/bdougieyo/setting-up-openclaw-on-exedev-with-discord-27n) |
| **10 GitHub Repos to Master OpenClaw** | Curated list of the best repos for learning. | [KDnuggets](https://www.kdnuggets.com/10-github-repositories-to-master-openclaw) |

---

## 11. Communities

### Discord

| **Community** | **Description** | **Link** |
|--------------|-----------------|----------|
| **Official Discord Server** | 8,000+ active members — primary hub for questions. | [Discord](https://docs.openclaw.ai/channels/discord) |

### Reddit

| **Community** | **Description** | **Link** |
|--------------|-----------------|----------|
| **r/clawdbot** | Original subreddit — broad discussions and use cases. | [r/clawdbot](https://www.reddit.com/r/clawdbot/) |

### Skool Groups

| **Community** | **Description** | **Link** |
|--------------|-----------------|----------|
| **Vibe Coding School** | Zac's community — operators sharing guides, configs, automations. | [Vibe Coding School](https://www.skool.com/vibe-coding-school/about) |
| **OpenClaw Labs** | Builders community — multi-agent architecture, security. | [OpenClaw Labs](https://www.skool.com/openclawlabs/about) |
| **OpenClaw Lab** | Founders building systems and deploying agents safely. | [OpenClaw Lab](https://www.skool.com/openclaw-lab/about) |
| **OpenClaw Academy (Free)** | Free community for learning to create AI assistants. | [Academy](https://www.skool.com/openclaw-academy) |
| **OpenClaw Mastery** | Self-described #1 community for learning OpenClaw. | [Mastery](https://www.skool.com/openclaw-mastery/about) |
| **OpenClaw Users** | Unofficial — sharing setups, swapping skills, getting help. | [Users](https://www.skool.com/openclawusers) |
| **OpenClaw Founders** | Founder-focused Skool community. | [Founders](https://www.skool.com/clawdbot/about) |

### Other

| **Community** | **Description** | **Link** |
|--------------|-----------------|----------|
| **X/Twitter Community** | 31.6K members on X/Twitter. | [X Community](https://x.com/i/communities/2013441068562325602) |
| **OpenClaw Forum** | 1.6M AI agents — world's first AI-only social network. | [Forum](https://openclawforum.org/) |
| **7 Best Communities Reviewed** | Curated review of the best communities for getting help. | [Medium](https://florian-darroman.medium.com/7-best-openclaw-community-and-courses-to-actually-get-help-0b9ca7f0d80b) |

---

## 12. Alternatives & Comparisons

| **Resource** | **Description** | **Link** |
|-------------|-----------------|----------|
| **Emergent — 6 Competitors** | Emergent x Moltbot, Adept, Humane, Rabbit, Devin, Inflection. | [Emergent](https://emergent.sh/learn/best-openclaw-alternatives-and-competitors) |
| **Top 10 Alternatives 2026** | Comprehensive comparison with feature matrices. | [o-mega](https://o-mega.ai/articles/top-10-openclaw-alternatives-2026) |
| **Taskade — Best Alternatives** | Alternatives for team productivity and collaboration. | [Taskade](https://www.taskade.com/blog/best-openclaw-alternatives) |
| **DataCamp — Local to Enterprise** | Alternatives spanning local, cloud, and enterprise. | [DataCamp](https://www.datacamp.com/blog/openclaw-alternatives) |
| **Till Freitag — Best Alternatives** | Lightweight to enterprise solutions. | [Till Freitag](https://till-freitag.com/en/blog/openclaw-alternatives-en) |
| **Lark Suite — 12 Alternatives** | Focused on unifying AI with team productivity. | [Lark Suite](https://www.larksuite.com/en_us/blog/openclaw-alternatives) |
| **CodeConductor — Secure & Scalable** | Security and scalability-focused comparison. | [CodeConductor](https://codeconductor.ai/blog/openclaw-alternatives/) |
| **Fountain City — Enterprise Security** | Honest enterprise security comparison. | [Fountain City](https://fountaincity.tech/resources/blog/openclaw-alternatives-enterprise-security-comparison/) |
| **AI Magicx — NanoClaw & More** | Every competitor compared including NanoClaw. | [AI Magicx](https://www.aimagicx.com/blog/openclaw-alternatives-comparison-2026) |
| **Adopt.ai — Open Source & Enterprise** | Open-source and enterprise-ready alternatives. | [Adopt.ai](https://www.adopt.ai/blog/open-source-enterprise-openclaw-alternatives) |

### Alternative Agent Platforms (GitHub Repos)

| **Agent** | **Description** | **Link** |
|-----------|-----------------|----------|
| **NemoClaw (NVIDIA)** | NVIDIA's security stack — runs OpenClaw inside OpenShell with sandboxed execution and policy controls. Apache 2.0. | [GitHub](https://github.com/NVIDIA/NemoClaw) |
| **Hermes Agent (Nous Research)** | Self-improving AI agent with built-in learning loop, persistent memory, and multi-platform support. | [GitHub](https://github.com/NousResearch/hermes-agent) |
| **Paperclip** | Open-source orchestration for multi-agent companies. 38k+ stars, MIT license. | [GitHub](https://github.com/paperclipai/paperclip) |
| **NanoClaw** | Ultra-lightweight OpenClaw alternative — ~500 lines of TypeScript, full Docker isolation per agent. | [GitHub](https://github.com/nanoclaw/nanoclaw) |
| **Nanobot (HKU)** | OpenClaw core features in 4,000 lines of Python. 26.8k+ stars. | [GitHub](https://github.com/nanobot-ai/nanobot) |
| **ZeroClaw** | Rust implementation of OpenClaw — 99% memory reduction for edge deployments. | [GitHub](https://github.com/zeroclaw/zeroclaw) |
| **PicoClaw** | Ultra-lightweight Go agent, under 10MB RAM, one-second boot, runs on $5-10 hardware. | [GitHub](https://github.com/picoclaw/picoclaw) |
| **Awesome NemoClaw** | Curated presets, recipes, and playbooks for NemoClaw/OpenShell. | [GitHub](https://github.com/VoltAgent/awesome-nemoclaw) |
| **Awesome Hermes Agent** | Curated skills, tools, integrations, and resources for Hermes Agent. | [GitHub](https://github.com/0xNyk/awesome-hermes-agent) |

---

## 13. Awesome Lists & Meta-Resources

| **Resource** | **Description** | **Link** |
|-------------|-----------------|----------|
| **Awesome OpenClaw (vincentkoc)** | Skills, plugins, memory systems, MCP tools, deployment stacks. | [awesome-openclaw](https://github.com/vincentkoc/awesome-openclaw) |
| **Awesome Skills (VoltAgent)** | 5,400+ skills filtered and categorized. | [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) |
| **Awesome Agents (mergisi)** | 162 production-ready templates across 19 categories. | [awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents) |
| **Awesome Use Cases (hesamsheikh)** | Real-world use case documentation and examples. | [awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) |
| **Awesome OpenClaw (alvinreal)** | Premium curated list — high-quality resources for the OpenClaw ecosystem. | [awesome-openclaw](https://github.com/alvinreal/awesome-openclaw) |
| **Awesome OpenClaw (rohitg00)** | Community-driven curated list of tools, skills, and guides. | [awesome-openclaw](https://github.com/rohitg00/awesome-openclaw) |
| **Awesome OpenClaw (SamurAIGPT)** | Tools, skills, tutorials, and articles for OpenClaw. | [awesome-openclaw](https://github.com/SamurAIGPT/awesome-openclaw) |
| **OpenClaw Master Skills (560+)** | 560+ best skills, weekly updated and curated by MyClaw.ai. | [openclaw-master-skills](https://github.com/LeoYeAI/openclaw-master-skills) |

---

## 14. Contributing & Code of Conduct

Contributions are welcome! If you know of a great OpenClaw resource that is missing from this list, please help us grow it.

### How to Contribute

1. **Fork** this repository.
2. **Create a branch** for your changes.
3. **Add your resource** in the appropriate section with a title, link, and one-line description.
4. **Submit a pull request** with a clear explanation of what you added.

Please be respectful and follow our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## 15. Support My Work

If this repository is useful to you, here are some ways to support the work:

- Give this repo a star on GitHub
- Subscribe to my [YouTube channel](https://www.youtube.com/@Zac-Frulloni)
- Join the [Vibe Coding School community](https://www.skool.com/vibe-coding-school/about)
- Share this repo with someone who would find it useful

---

## 16. License

This project is licensed under the [MIT License](LICENSE).

---

## 17. Disclosure

Some links in this repository may be affiliate links. If you purchase through these links, I may earn a small commission at no additional cost to you. This helps support the creation and maintenance of free resources like this one.

---

## 18. Contact Me

- YouTube: [@Zac-Frulloni](https://www.youtube.com/@Zac-Frulloni)
- LinkedIn: [zacfrulloni](https://www.linkedin.com/in/zacfrulloni/)
- X/Twitter: [zacfrulloni](https://x.com/zacfrulloni)
- Community: [Vibe Coding School on Skool](https://www.skool.com/vibe-coding-school/about)
