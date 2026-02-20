# Awesome Claude Code

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Last Updated](https://img.shields.io/badge/last%20updated-2026--02--20-brightgreen)](#)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

> A curated list of awesome tools, skills, MCP servers, tips, and resources for [Claude Code](https://github.com/anthropics/claude-code) -- Anthropic's agentic coding tool that lives in your terminal.

Claude Code understands your codebase, executes routine tasks, explains complex code, and handles git workflows through natural language. This list collects the best ecosystem resources to help you get the most out of it.

## Contents

- [Official Resources](#official-resources)
- [Skills and Plugins](#skills-and-plugins)
- [MCP Servers](#mcp-servers)
  - [Code and Development](#code-and-development)
  - [Browser and Web](#browser-and-web)
  - [Data and Database](#data-and-database)
  - [Productivity and Communication](#productivity-and-communication)
  - [Cloud and Infrastructure](#cloud-and-infrastructure)
  - [Security and Reverse Engineering](#security-and-reverse-engineering)
  - [MCP Frameworks and Tooling](#mcp-frameworks-and-tooling)
- [Slash Commands](#slash-commands)
- [CLI Extensions and Companion Tools](#cli-extensions-and-companion-tools)
- [GUI and Remote Clients](#gui-and-remote-clients)
- [Monitoring and Cost Tracking](#monitoring-and-cost-tracking)
- [Workflow and Multi-Agent Tools](#workflow-and-multi-agent-tools)
- [Configuration and Tips](#configuration-and-tips)
  - [CLAUDE.md Best Practices](#claudemd-best-practices)
  - [Settings and Permissions](#settings-and-permissions)
  - [Model Selection and Cost Optimization](#model-selection-and-cost-optimization)
  - [Keyboard Shortcuts](#keyboard-shortcuts)
- [Prompt Engineering for Claude Code](#prompt-engineering-for-claude-code)
- [Tutorials and Guides](#tutorials-and-guides)
- [Alternative Coding Agents](#alternative-coding-agents)
- [Community](#community)

---

## Official Resources

- [Claude Code](https://github.com/anthropics/claude-code) - The official Claude Code repository from Anthropic. ![GitHub Repo stars](https://img.shields.io/github/stars/anthropics/claude-code)
- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code) - Official documentation covering installation, usage, and configuration.
- [Model Context Protocol Specification](https://github.com/modelcontextprotocol/modelcontextprotocol) - The formal MCP spec that powers Claude Code's extensibility. ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/modelcontextprotocol)
- [MCP Server Registry](https://github.com/modelcontextprotocol/registry) - Community-driven registry of Model Context Protocol servers. ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/registry)
- [MCP Inspector](https://github.com/modelcontextprotocol/inspector) - Visual testing tool for MCP servers. ![GitHub Repo stars](https://img.shields.io/github/stars/modelcontextprotocol/inspector)
- [Anthropic Claude Code Plugins (Official)](https://github.com/anthropics/claude-plugins-official) - Official Anthropic-managed directory of high quality Claude Code plugins. ![GitHub Repo stars](https://img.shields.io/github/stars/anthropics/claude-plugins-official)
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) - Official recipes and patterns for building with Claude, including Claude Code examples.
- [Claude Code Blog Post](https://www.anthropic.com/blog/claude-code) - Anthropic's announcement and overview of Claude Code.

## Skills and Plugins

Skills are reusable markdown-based instructions that extend Claude Code's capabilities with domain-specific expertise.

- [everything-claude-code](https://github.com/affaan-m/everything-claude-code) - Complete Claude Code configuration collection: agents, skills, hooks, commands, rules, and MCPs. Battle-tested from an Anthropic hackathon winner. ![GitHub Repo stars](https://img.shields.io/github/stars/affaan-m/everything-claude-code)
- [Awesome Claude Skills (Composio)](https://github.com/ComposioHQ/awesome-claude-skills) - Curated list of Claude Skills, resources, and tools for customizing Claude AI workflows. ![GitHub Repo stars](https://img.shields.io/github/stars/ComposioHQ/awesome-claude-skills)
- [UI/UX Pro Max Skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) - AI skill providing design intelligence for building professional UI/UX across multiple platforms. ![GitHub Repo stars](https://img.shields.io/github/stars/nextlevelbuilder/ui-ux-pro-max-skill)
- [Antigravity Awesome Skills](https://github.com/sickn33/antigravity-awesome-skills) - The ultimate collection of 800+ agentic skills for Claude Code, Antigravity, and Cursor. ![GitHub Repo stars](https://img.shields.io/github/stars/sickn33/antigravity-awesome-skills)
- [Planning with Files](https://github.com/OthmanAdi/planning-with-files) - Claude Code skill implementing Manus-style persistent markdown planning. ![GitHub Repo stars](https://img.shields.io/github/stars/OthmanAdi/planning-with-files)
- [Awesome Claude Code Subagents](https://github.com/VoltAgent/awesome-claude-code-subagents) - Collection of 100+ specialized Claude Code subagents covering a wide range of development use cases. ![GitHub Repo stars](https://img.shields.io/github/stars/VoltAgent/awesome-claude-code-subagents)
- [Awesome Agent Skills (VoltAgent)](https://github.com/VoltAgent/awesome-agent-skills) - 300+ agent skills from official dev teams and the community, compatible with Claude Code, Codex, Gemini CLI, and more. ![GitHub Repo stars](https://img.shields.io/github/stars/VoltAgent/awesome-agent-skills)
- [Awesome Claude Skills (travisvn)](https://github.com/travisvn/awesome-claude-skills) - Curated list of Claude Skills and resources for customizing Claude AI workflows. ![GitHub Repo stars](https://img.shields.io/github/stars/travisvn/awesome-claude-skills)
- [Awesome Agent Skills (heilcheng)](https://github.com/heilcheng/awesome-agent-skills) - Curated skills, tools, tutorials, and capabilities for AI coding agents. ![GitHub Repo stars](https://img.shields.io/github/stars/heilcheng/awesome-agent-skills)
- [Claude Code Infrastructure Showcase](https://github.com/diet103/claude-code-infrastructure-showcase) - Examples of Claude Code infrastructure with skill auto-activation, hooks, and agents. ![GitHub Repo stars](https://img.shields.io/github/stars/diet103/claude-code-infrastructure-showcase)
- [Marketing Skills](https://github.com/coreyhaines31/marketingskills) - Marketing skills for Claude Code: CRO, copywriting, SEO, analytics, and growth engineering. ![GitHub Repo stars](https://img.shields.io/github/stars/coreyhaines31/marketingskills)
- [Awesome Claude Code Plugins](https://github.com/ComposioHQ/awesome-claude-plugins) - Curated list of plugins that extend Claude Code with custom commands, agents, hooks, and MCP servers. ![GitHub Repo stars](https://img.shields.io/github/stars/ComposioHQ/awesome-claude-plugins)
- [Awesome LLM Skills](https://github.com/Prat011/awesome-llm-skills) - Curated list of LLM and AI Agent Skills that work with Claude Code, Codex, Gemini CLI, and custom agents. ![GitHub Repo stars](https://img.shields.io/github/stars/Prat011/awesome-llm-skills)
- [Claude Code Skill Factory](https://github.com/alirezarezvani/claude-code-skill-factory) - Toolkit for building and deploying production-ready Claude Skills, agents, and slash commands at scale. ![GitHub Repo stars](https://img.shields.io/github/stars/alirezarezvani/claude-code-skill-factory)
- [Claude Code Tresor](https://github.com/alirezarezvani/claude-code-tresor) - Collection of autonomous skills, expert agents, slash commands, and prompts for Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/alirezarezvani/claude-code-tresor)
- [BMAD Method Skills](https://github.com/aj-geddes/claude-code-bmad-skills) - BMAD Method skills for Claude Code with auto-detection, memory integration, and slash commands. ![GitHub Repo stars](https://img.shields.io/github/stars/aj-geddes/claude-code-bmad-skills)
- [SuperClaude Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) - Configuration framework enhancing Claude Code with specialized commands, cognitive personas, and development methodologies. ![GitHub Repo stars](https://img.shields.io/github/stars/SuperClaude-Org/SuperClaude_Framework)

## MCP Servers

The Model Context Protocol (MCP) allows Claude Code to interact with external tools and data sources. Below are popular MCP servers organized by category.

### Code and Development

- [GitHub MCP Server](https://github.com/github/github-mcp-server) - GitHub's official MCP server for repository management, issues, PRs, and more. ![GitHub Repo stars](https://img.shields.io/github/stars/github/github-mcp-server)
- [Context7](https://github.com/upstash/context7) - Up-to-date code documentation for LLMs and AI code editors. ![GitHub Repo stars](https://img.shields.io/github/stars/upstash/context7)
- [Serena](https://github.com/oraios/serena) - Powerful coding agent toolkit providing semantic retrieval and editing capabilities. ![GitHub Repo stars](https://img.shields.io/github/stars/oraios/serena)
- [GitMCP](https://github.com/idosal/git-mcp) - Free, open-source remote MCP server for any GitHub project to eliminate code hallucinations. ![GitHub Repo stars](https://img.shields.io/github/stars/idosal/git-mcp)
- [DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) - MCP server providing terminal control, file system search, and diff file editing capabilities. ![GitHub Repo stars](https://img.shields.io/github/stars/wonderwhy-er/DesktopCommanderMCP)
- [Pal MCP Server](https://github.com/BeehiveInnovations/pal-mcp-server) - Bridges Claude Code with Gemini, OpenAI, OpenRouter, Azure, Grok, Ollama, and more as one unified tool. ![GitHub Repo stars](https://img.shields.io/github/stars/BeehiveInnovations/pal-mcp-server)

### Browser and Web

- [Playwright MCP](https://github.com/microsoft/playwright-mcp) - Microsoft's Playwright MCP server for browser automation. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/playwright-mcp)
- [Figma Context MCP](https://github.com/GLips/Figma-Context-MCP) - Provides Figma layout information to AI coding agents. ![GitHub Repo stars](https://img.shields.io/github/stars/GLips/Figma-Context-MCP)
- [MCP Chrome](https://github.com/hangwin/mcp-chrome) - Chrome extension-based MCP server for browser automation, content analysis, and semantic search. ![GitHub Repo stars](https://img.shields.io/github/stars/hangwin/mcp-chrome)
- [Browser MCP](https://github.com/BrowserMCP/mcp) - Model Context Provider server that allows AI applications to control your browser. ![GitHub Repo stars](https://img.shields.io/github/stars/BrowserMCP/mcp)
- [Firecrawl MCP Server](https://github.com/firecrawl/firecrawl-mcp-server) - Official Firecrawl MCP server adding powerful web scraping and search to Claude and other LLM clients. ![GitHub Repo stars](https://img.shields.io/github/stars/firecrawl/firecrawl-mcp-server)
- [MCP Playwright](https://github.com/executeautomation/mcp-playwright) - Playwright MCP server to automate browsers and APIs in Claude Desktop, Cline, and Cursor. ![GitHub Repo stars](https://img.shields.io/github/stars/executeautomation/mcp-playwright)
- [WhatsApp MCP](https://github.com/lharries/whatsapp-mcp) - WhatsApp MCP server for messaging integration. ![GitHub Repo stars](https://img.shields.io/github/stars/lharries/whatsapp-mcp)

### Data and Database

- [MindsDB](https://github.com/mindsdb/mindsdb) - Federated query engine for AI, acting as a comprehensive MCP server. ![GitHub Repo stars](https://img.shields.io/github/stars/mindsdb/mindsdb)
- [GenAI Toolbox for Databases](https://github.com/googleapis/genai-toolbox) - Google's MCP toolbox for databases. ![GitHub Repo stars](https://img.shields.io/github/stars/googleapis/genai-toolbox)
- [Kreuzberg](https://github.com/kreuzberg-dev/kreuzberg) - Polyglot document intelligence framework for text extraction from PDFs, Office docs, images, and 75+ formats. Available as CLI, REST API, or MCP server. ![GitHub Repo stars](https://img.shields.io/github/stars/kreuzberg-dev/kreuzberg)

### Productivity and Communication

- [Activepieces](https://github.com/activepieces/activepieces) - AI workflow automation platform with 400+ MCP servers for agents. ![GitHub Repo stars](https://img.shields.io/github/stars/activepieces/activepieces)
- [Apple MCP](https://github.com/supermemoryai/apple-mcp) - Collection of Apple-native tools for the Model Context Protocol. ![GitHub Repo stars](https://img.shields.io/github/stars/supermemoryai/apple-mcp)

### Cloud and Infrastructure

- [AWS MCP Servers](https://github.com/awslabs/mcp) - Official MCP servers for AWS services. ![GitHub Repo stars](https://img.shields.io/github/stars/awslabs/mcp)

### Security and Reverse Engineering

- [HexStrike AI](https://github.com/0x4m4/hexstrike-ai) - Advanced MCP server for 150+ cybersecurity tools covering automated pentesting, vulnerability discovery, and security research. ![GitHub Repo stars](https://img.shields.io/github/stars/0x4m4/hexstrike-ai)
- [GhidraMCP](https://github.com/LaurieWired/GhidraMCP) - AI-powered reverse engineering assistant bridging IDA Pro with language models through MCP. ![GitHub Repo stars](https://img.shields.io/github/stars/LaurieWired/GhidraMCP)
- [IDA Pro MCP](https://github.com/mrexodia/ida-pro-mcp) - MCP server for IDA Pro reverse engineering. ![GitHub Repo stars](https://img.shields.io/github/stars/mrexodia/ida-pro-mcp)

### MCP Frameworks and Tooling

- [FastMCP](https://github.com/PrefectHQ/fastmcp) - The fast, Pythonic way to build MCP servers and clients. ![GitHub Repo stars](https://img.shields.io/github/stars/PrefectHQ/fastmcp)
- [MCP Use](https://github.com/mcp-use/mcp-use) - Fullstack MCP framework to develop MCP apps for ChatGPT, Claude, and AI agents. ![GitHub Repo stars](https://img.shields.io/github/stars/mcp-use/mcp-use)
- [FastAPI MCP](https://github.com/tadata-org/fastapi_mcp) - Expose your FastAPI endpoints as MCP tools with authentication. ![GitHub Repo stars](https://img.shields.io/github/stars/tadata-org/fastapi_mcp)
- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - The definitive collection of MCP servers. ![GitHub Repo stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers)
- [Awesome MCP Servers (appcypher)](https://github.com/appcypher/awesome-mcp-servers) - Another curated list of Model Context Protocol servers. ![GitHub Repo stars](https://img.shields.io/github/stars/appcypher/awesome-mcp-servers)
- [MCP for Beginners](https://github.com/microsoft/mcp-for-beginners) - Microsoft's open-source curriculum introducing MCP fundamentals with real-world examples in multiple languages. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/mcp-for-beginners)
- [Metorial](https://github.com/metorial/metorial) - Connect any AI model to 600+ integrations powered by MCP. ![GitHub Repo stars](https://img.shields.io/github/stars/metorial/metorial)
- [ACI.dev](https://github.com/aipotheosis-labs/aci) - Open source tool-calling platform with 600+ tools through direct function calling or a unified MCP server. ![GitHub Repo stars](https://img.shields.io/github/stars/aipotheosis-labs/aci)

## Slash Commands

Custom slash commands extend Claude Code's built-in command palette with project-specific or general-purpose workflows.

- [Claude Code Commands](https://github.com/wshobson/commands) - Collection of production-ready slash commands for Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/wshobson/commands)
- [Claude Sessions](https://github.com/iannuttall/claude-sessions) - Custom slash commands providing comprehensive development session tracking and documentation. ![GitHub Repo stars](https://img.shields.io/github/stars/iannuttall/claude-sessions)
- [Claude Command Suite](https://github.com/qdhenry/Claude-Command-Suite) - Professional slash commands for structured workflows: code review, feature creation, security auditing, and architectural analysis. ![GitHub Repo stars](https://img.shields.io/github/stars/qdhenry/Claude-Command-Suite)
- [Awesome Claude Code Plugins (ccplugins)](https://github.com/ccplugins/awesome-claude-code-plugins) - Curated list of slash commands, subagents, MCP servers, and hooks for Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/ccplugins/awesome-claude-code-plugins)
- [Awesome Claude Code Setup](https://github.com/cassler/awesome-claude-code-setup) - Power user collection of bash scripts and slash commands for Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/cassler/awesome-claude-code-setup)
- [ccexp](https://github.com/nyatinte/ccexp) - Interactive terminal interface for discovering, previewing, and managing Claude Code configuration files and slash commands. ![GitHub Repo stars](https://img.shields.io/github/stars/nyatinte/ccexp)

## CLI Extensions and Companion Tools

Tools that extend or complement the Claude Code CLI experience.

- [CC Switch](https://github.com/farion1231/cc-switch) - Cross-platform desktop all-in-one assistant tool for Claude Code, Codex, OpenCode, and Gemini CLI. ![GitHub Repo stars](https://img.shields.io/github/stars/farion1231/cc-switch)
- [Claude Mem](https://github.com/thedotmack/claude-mem) - Plugin that automatically captures everything Claude does, compresses it with AI, and injects relevant context into future sessions. ![GitHub Repo stars](https://img.shields.io/github/stars/thedotmack/claude-mem)
- [Claude Code Router](https://github.com/musistudio/claude-code-router) - Use Claude Code as the foundation for coding infrastructure while controlling model interaction. ![GitHub Repo stars](https://img.shields.io/github/stars/musistudio/claude-code-router)
- [Claude Code Templates](https://github.com/davila7/claude-code-templates) - CLI tool for configuring and monitoring Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/davila7/claude-code-templates)
- [AionUI](https://github.com/iOfficeAI/AionUi) - Free, local, open-source 24/7 cowork app for Gemini CLI, Claude Code, Codex, OpenCode, and more. ![GitHub Repo stars](https://img.shields.io/github/stars/iOfficeAI/AionUi)
- [Claude Squad](https://github.com/smtg-ai/claude-squad) - Manage multiple AI terminal agents like Claude Code, Aider, Codex, OpenCode, and Amp simultaneously. ![GitHub Repo stars](https://img.shields.io/github/stars/smtg-ai/claude-squad)
- [Vibe Kanban](https://github.com/BloopAI/vibe-kanban) - Get 10x more out of Claude Code, Codex, or any coding agent with kanban-style task management. ![GitHub Repo stars](https://img.shields.io/github/stars/BloopAI/vibe-kanban)
- [Agents (wshobson)](https://github.com/wshobson/agents) - Intelligent automation and multi-agent orchestration for Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/wshobson/agents)

## GUI and Remote Clients

Graphical and remote interfaces for interacting with Claude Code beyond the terminal.

- [OpCode](https://github.com/winfunc/opcode) - Powerful GUI app and toolkit for Claude Code: custom agents, interactive sessions, and secure background agents. ![GitHub Repo stars](https://img.shields.io/github/stars/winfunc/opcode)
- [Happy](https://github.com/slopus/happy) - Mobile and web client for Codex and Claude Code with real-time voice, encryption, and full features. ![GitHub Repo stars](https://img.shields.io/github/stars/slopus/happy)
- [CloudCLI (Claude Code UI)](https://github.com/siteboon/claudecodeui) - Free open-source web UI and GUI for managing Claude Code sessions and projects remotely. ![GitHub Repo stars](https://img.shields.io/github/stars/siteboon/claudecodeui)
- [Claudable](https://github.com/opactorai/Claudable) - Open-source web builder leveraging local CLI agents like Claude Code, Codex, and Gemini CLI. ![GitHub Repo stars](https://img.shields.io/github/stars/opactorai/Claudable)
- [CodePilot](https://github.com/op7418/CodePilot) - Native desktop GUI for Claude Code built with Electron and Next.js. ![GitHub Repo stars](https://img.shields.io/github/stars/op7418/CodePilot)
- [Companion](https://github.com/The-Vibe-Company/companion) - Web and mobile UI for Claude Code and Codex with session launching, response streaming, and tool approval. ![GitHub Repo stars](https://img.shields.io/github/stars/The-Vibe-Company/companion)
- [IDEA Claude Code GUI](https://github.com/zhukunpenglinyutong/idea-claude-code-gui) - IntelliJ IDEA plugin providing a GUI for Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/zhukunpenglinyutong/idea-claude-code-gui)
- [Claude Code Remote (Telegram/Email/Discord)](https://github.com/JessyTsui/Claude-Code-Remote) - Control Claude Code remotely via email, Discord, or Telegram with task notifications and reply-to-command. ![GitHub Repo stars](https://img.shields.io/github/stars/JessyTsui/Claude-Code-Remote)
- [Claude Code Telegram](https://github.com/RichardAtCT/claude-code-telegram) - Telegram bot providing remote access to Claude Code with full AI assistance and session persistence. ![GitHub Repo stars](https://img.shields.io/github/stars/RichardAtCT/claude-code-telegram)
- [Claude Code Telegram (hanxiao)](https://github.com/hanxiao/claudecode-telegram) - Telegram bridge for Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/hanxiao/claudecode-telegram)

## Monitoring and Cost Tracking

Tools for tracking token usage, API costs, and session analytics.

- [Claude Code Statusline](https://github.com/rz1989s/claude-code-statusline) - Transform your terminal with atomic precision statusline featuring real-time cost tracking, MCP monitoring, and beautiful themes. ![GitHub Repo stars](https://img.shields.io/github/stars/rz1989s/claude-code-statusline)
- [Claude Dashboard](https://github.com/uppinote20/claude-dashboard) - Comprehensive status line plugin with context usage, API rate limits, and cost tracking. ![GitHub Repo stars](https://img.shields.io/github/stars/uppinote20/claude-dashboard)
- [Splitrail](https://github.com/Piebald-AI/splitrail) - Fast, cross-platform, real-time token usage tracker and cost monitor for Gemini CLI, Claude Code, Codex CLI, and more. ![GitHub Repo stars](https://img.shields.io/github/stars/Piebald-AI/splitrail)
- [Claude Usage Tracker](https://github.com/masorange/ClaudeUsageTracker) - Track Claude Code API usage from your macOS menu bar with accurate cost calculations. ![GitHub Repo stars](https://img.shields.io/github/stars/masorange/ClaudeUsageTracker)
- [toktrack](https://github.com/mag123c/toktrack) - Ultra-fast token and cost tracker for LLM token usage including Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/mag123c/toktrack)
- [cccost](https://github.com/badlogic/cccost) - Instrument Claude Code to track actual token usage and cost. ![GitHub Repo stars](https://img.shields.io/github/stars/badlogic/cccost)
- [claude-loop](https://github.com/li0nel/claude-loop) - Automation toolkit for running iterative Claude Code sessions with cost tracking and monitoring. ![GitHub Repo stars](https://img.shields.io/github/stars/li0nel/claude-loop)

## Workflow and Multi-Agent Tools

Orchestration frameworks, CI/CD integrations, and multi-agent patterns for Claude Code.

- [Agents (wshobson)](https://github.com/wshobson/agents) - Intelligent automation and multi-agent orchestration for Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/wshobson/agents)
- [Awesome Claude Agents](https://github.com/vijaythecoder/awesome-claude-agents) - An orchestrated sub-agent dev team powered by Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/vijaythecoder/awesome-claude-agents)
- [Claude Squad](https://github.com/smtg-ai/claude-squad) - Manage multiple AI terminal agents like Claude Code, Aider, Codex, and OpenCode. ![GitHub Repo stars](https://img.shields.io/github/stars/smtg-ai/claude-squad)
- [Vibe Kanban](https://github.com/BloopAI/vibe-kanban) - Kanban-style task management to coordinate work across Claude Code, Codex, or any coding agent. ![GitHub Repo stars](https://img.shields.io/github/stars/BloopAI/vibe-kanban)
- [Remote Agentic Coding System](https://github.com/coleam00/remote-agentic-coding-system) - Connect Claude Code or Codex to Slack, Telegram, GitHub, and more. ![GitHub Repo stars](https://img.shields.io/github/stars/coleam00/remote-agentic-coding-system)
- [Daytona](https://github.com/daytonaio/daytona) - Secure and elastic infrastructure for running AI-generated code. ![GitHub Repo stars](https://img.shields.io/github/stars/daytonaio/daytona)
- [Awesome Claude Code (hesreallyhim)](https://github.com/hesreallyhim/awesome-claude-code) - Curated list of skills, hooks, slash-commands, agent orchestrators, applications, and plugins. ![GitHub Repo stars](https://img.shields.io/github/stars/hesreallyhim/awesome-claude-code)

### Multi-Agent Patterns

Claude Code supports spawning subagents with `Task` and `Agent` tools. Common orchestration patterns include:

- **Coordinator-Worker** - A coordinator agent delegates tasks to specialized worker agents, each with their own `CLAUDE.md` instructions and tool permissions.
- **Judge-Review** - After workers complete tasks, a judge agent reviews output quality before the coordinator accepts or requests revisions.
- **Pipeline** - Agents are chained sequentially, where each agent's output becomes the next agent's input (e.g., plan -> implement -> test -> review).
- **God Mode** - Autonomous long-running orchestration where a coordinator manages workers and judges, reporting results via email or messaging while the user is away.

## Configuration and Tips

### CLAUDE.md Best Practices

`CLAUDE.md` is the primary way to give Claude Code persistent project context. It is automatically loaded when Claude Code starts in a directory.

- **Place `CLAUDE.md` at the project root.** It is loaded automatically and applies to all sessions in that directory.
- **Use `~/.claude/CLAUDE.md` for global instructions** that apply across all projects (e.g., preferred coding style, commit message format).
- **Keep it concise and actionable.** Claude Code reads the full file at session start -- avoid verbose prose and focus on rules and patterns.
- **Structure with headers.** Use markdown headers to separate concerns: coding standards, testing requirements, project architecture, deployment notes.
- **Include file path conventions.** Tell Claude Code where to find tests, configs, source code, and documentation.
- **Specify tool restrictions.** For example: "Never use `rm -rf` without confirmation" or "Always run tests before committing."
- **Reference other instruction files.** Use `@AGENTS.md` or `@docs/architecture.md` to modularize complex instructions.
- **Document naming conventions.** Include variable naming, file naming, branch naming, and commit message patterns.
- **List forbidden patterns.** Explicitly state what Claude Code should NOT do: "Do not modify files in `/config/production/`".
- **Update regularly.** As the project evolves, keep `CLAUDE.md` in sync with reality.

Example minimal `CLAUDE.md`:

```markdown
# Project: my-app

## Stack
- TypeScript, React 19, Next.js 15, Tailwind CSS 4
- Testing: Vitest + React Testing Library

## Rules
- All new code must have tests
- Use conventional commits (feat:, fix:, docs:, etc.)
- Never modify .env files directly
- Run `pnpm test` before committing

## Structure
- src/components/ -- React components
- src/lib/ -- Utility functions
- src/app/ -- Next.js app router pages
- tests/ -- Test files mirror src/ structure
```

### Settings and Permissions

Claude Code's behavior can be configured through `.claude/settings.json` at both project and user levels.

- **Project settings** (`.claude/settings.json` in repo root) - Shared with your team via version control.
- **User settings** (`~/.claude/settings.json`) - Personal preferences that apply globally.

Key settings to know:

```jsonc
{
  // Allow specific tools to run without asking for permission
  "permissions": {
    "allow": [
      "Bash(npm test)",
      "Bash(npm run lint)",
      "Bash(git status)",
      "Bash(git diff)"
    ],
    "deny": [
      "Bash(rm -rf *)",
      "Bash(git push --force)"
    ]
  }
}
```

Tips:

- **Pre-approve safe commands** like `git status`, `git diff`, `npm test`, and `npm run lint` so Claude Code does not pause for confirmation.
- **Deny destructive commands** explicitly to prevent accidents with `rm -rf`, `git push --force`, `DROP TABLE`, etc.
- **Use glob patterns** in permissions for flexibility: `Bash(npm run *)` allows all npm scripts.
- **Scope MCP server permissions** per project to avoid exposing sensitive tools across unrelated codebases.

### Model Selection and Cost Optimization

- **Use `/model` to switch models** during a session. Use the most capable model for complex architectural decisions and switch to faster models for routine tasks.
- **Use `/compact` to compress context** when a session gets long. This reduces token usage and costs while preserving important context.
- **Use `--resume` to continue sessions** instead of starting fresh, saving the overhead of re-reading the codebase.
- **Write focused prompts.** Specific, well-scoped requests consume fewer tokens than vague instructions that require multiple rounds of clarification.
- **Leverage `CLAUDE.md`** to front-load context so you spend fewer tokens explaining project structure in every conversation.
- **Use subagents for parallel work.** The `Task` tool allows Claude Code to spawn focused subagents, each with a narrow scope, reducing token waste from context switching.
- **Set `--max-turns`** when running in headless mode to cap autonomous execution and prevent runaway costs.

### Keyboard Shortcuts

Key shortcuts available in the Claude Code terminal interface:

| Shortcut | Action |
|----------|--------|
| `Enter` | Send message / confirm |
| `Escape` | Cancel current generation |
| `Ctrl+C` | Interrupt / exit |
| `Ctrl+L` | Clear screen |
| `Tab` | Accept autocomplete suggestion |
| `Up/Down` | Navigate command history |
| `/` | Open slash command menu |
| `Shift+Enter` | Newline in message (multi-line input) |

## Prompt Engineering for Claude Code

Effective patterns for getting the most out of Claude Code.

### Task Decomposition

Break complex tasks into smaller, verifiable steps:

```
Instead of: "Build me a full authentication system"

Better: "Let's implement auth step by step:
1. First, create the User model with email and hashed password fields
2. Then implement the registration endpoint with validation
3. Add login endpoint that returns JWT tokens
4. Add middleware for protected routes
5. Write tests for each endpoint
After each step, run the tests before proceeding."
```

### Context Priming

Give Claude Code the relevant context upfront:

```
Read src/lib/database.ts and src/types/user.ts first, then implement
a new function in src/lib/auth.ts that validates JWT tokens using
the existing database connection pattern.
```

### Verification Loops

Always ask Claude Code to verify its own work:

```
After making the changes, run the test suite and fix any failures.
Then run the linter and fix any warnings. Show me the final test output.
```

### Constraint-Based Prompting

State what you want AND what you do not want:

```
Refactor the payment module to use the Strategy pattern.
- Keep the public API identical (no breaking changes)
- Do not modify any test files
- Do not add new dependencies
- Each strategy should be in its own file under src/payments/strategies/
```

### Exploratory Prompting

When you need to understand a codebase:

```
Trace the complete request lifecycle for POST /api/orders:
1. Which middleware runs first?
2. How is the request validated?
3. What database queries are executed?
4. How are errors handled?
Show me the relevant code snippets for each step.
```

### Git-Aware Prompting

Leverage Claude Code's git integration:

```
Look at the git diff for the last 3 commits. Write a comprehensive
changelog entry summarizing the user-facing changes. Ignore internal
refactoring and test changes.
```

### Multi-File Coordinated Changes

When changes span multiple files:

```
I need to rename the "Organization" model to "Workspace" everywhere.
This affects: the database schema, all API routes, the frontend
components, and the tests. Make all changes atomically and ensure
nothing references the old name. Run grep afterwards to confirm.
```

### Defensive Prompting

Prevent common mistakes:

```
Before making any changes, create a git commit with the current state.
Then make the refactoring changes. If the tests fail after refactoring,
show me the diff so I can review instead of attempting fixes.
```

## Tutorials and Guides

### Getting Started

- [Claude Code Guide (zebbern)](https://github.com/zebbern/claude-code-guide) - Setup, commands, workflows, agents, skills, and tips. ![GitHub Repo stars](https://img.shields.io/github/stars/zebbern/claude-code-guide)
- [Claude Code Guide (Cranot)](https://github.com/Cranot/claude-code-guide) - Comprehensive Claude Code CLI guide, auto-updated every 2 days. ![GitHub Repo stars](https://img.shields.io/github/stars/Cranot/claude-code-guide)
- [MCP for Beginners (Microsoft)](https://github.com/microsoft/mcp-for-beginners) - Open-source curriculum introducing MCP fundamentals through real-world examples. ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/mcp-for-beginners)
- [MCP Chinese Getting Started Guide](https://github.com/liaokongVFX/MCP-Chinese-Getting-Started-Guide) - MCP getting started guide in Chinese. ![GitHub Repo stars](https://img.shields.io/github/stars/liaokongVFX/MCP-Chinese-Getting-Started-Guide)
- [Awesome MCP ZH](https://github.com/yzfly/Awesome-MCP-ZH) - MCP resources in Chinese. ![GitHub Repo stars](https://img.shields.io/github/stars/yzfly/Awesome-MCP-ZH)
- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code) - Official Anthropic documentation.

### Advanced Workflows

- [everything-claude-code](https://github.com/affaan-m/everything-claude-code) - Battle-tested configurations from an Anthropic hackathon winner covering agents, skills, hooks, commands, and MCPs. ![GitHub Repo stars](https://img.shields.io/github/stars/affaan-m/everything-claude-code)
- [Claude Code Infrastructure Showcase](https://github.com/diet103/claude-code-infrastructure-showcase) - Real-world examples of skill auto-activation, hooks, and agent orchestration. ![GitHub Repo stars](https://img.shields.io/github/stars/diet103/claude-code-infrastructure-showcase)
- [SuperClaude Framework](https://github.com/SuperClaude-Org/SuperClaude_Framework) - Advanced framework with specialized commands, cognitive personas, and development methodologies. ![GitHub Repo stars](https://img.shields.io/github/stars/SuperClaude-Org/SuperClaude_Framework)

### System Prompts and Internals

- [System Prompts of AI Tools](https://github.com/x1xhlol/system-prompts-and-models-of-ai-tools) - Collection of system prompts for Claude Code, Cursor, Windsurf, Devin, and dozens of other AI tools. ![GitHub Repo stars](https://img.shields.io/github/stars/x1xhlol/system-prompts-and-models-of-ai-tools)
- [AI System Prompts](https://github.com/dontriskit/awesome-ai-system-prompts) - Curated collection of system prompts for top AI tools including Claude Code. ![GitHub Repo stars](https://img.shields.io/github/stars/dontriskit/awesome-ai-system-prompts)

### Video Tutorials

- [Claude Code Official YouTube](https://www.youtube.com/results?search_query=claude+code+anthropic) - Search for official and community video tutorials.
- [Building with Claude Code](https://www.youtube.com/results?search_query=building+with+claude+code+tutorial) - Community tutorials on building real projects with Claude Code.

## Alternative Coding Agents

Other AI-powered coding tools in the same space. Understanding the landscape helps you choose the right tool for each job.

- [Claude Code](https://github.com/anthropics/claude-code) - Anthropic's agentic coding tool in the terminal. ![GitHub Repo stars](https://img.shields.io/github/stars/anthropics/claude-code)
- [OpenAI Codex](https://github.com/openai/codex) - OpenAI's lightweight coding agent for the terminal. ![GitHub Repo stars](https://img.shields.io/github/stars/openai/codex)
- [Aider](https://github.com/Aider-AI/aider) - AI pair programming in your terminal, supporting multiple LLM providers. ![GitHub Repo stars](https://img.shields.io/github/stars/Aider-AI/aider)
- [Cursor](https://github.com/cursor/cursor) - The AI code editor with deep codebase understanding. ![GitHub Repo stars](https://img.shields.io/github/stars/cursor/cursor)
- [Roo Code](https://github.com/RooCodeInc/Roo-Code) - A whole dev team of AI agents in your code editor. ![GitHub Repo stars](https://img.shields.io/github/stars/RooCodeInc/Roo-Code)
- [OpenCode](https://github.com/opencode-ai/opencode) - Powerful AI coding agent built for the terminal. ![GitHub Repo stars](https://img.shields.io/github/stars/opencode-ai/opencode)
- [GitHub Copilot CLI](https://github.com/github/copilot-cli) - GitHub Copilot coding agent directly in your terminal. ![GitHub Repo stars](https://img.shields.io/github/stars/github/copilot-cli)
- [Cherry Studio](https://github.com/CherryHQ/cherry-studio) - AI productivity studio with smart chat, autonomous agents, and 300+ assistants. ![GitHub Repo stars](https://img.shields.io/github/stars/CherryHQ/cherry-studio)
- [iFlow CLI](https://github.com/iflow-ai/iflow-cli) - Command-line intelligence that embeds in your terminal for repository analysis and workflow automation. ![GitHub Repo stars](https://img.shields.io/github/stars/iflow-ai/iflow-cli)
- [TabbyML](https://github.com/TabbyML/tabby) - Self-hosted AI coding assistant. ![GitHub Repo stars](https://img.shields.io/github/stars/TabbyML/tabby)

## Community

- [Anthropic Discord](https://discord.gg/anthropic) - Official Anthropic Discord server with Claude Code channels.
- [Claude Code GitHub Discussions](https://github.com/anthropics/claude-code/discussions) - Official discussion forum for Claude Code.
- [Claude Code GitHub Issues](https://github.com/anthropics/claude-code/issues) - Bug reports and feature requests.
- [r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/) - Reddit community for Claude users, with frequent Claude Code discussions.
- [r/ClaudeCode](https://www.reddit.com/r/ClaudeCode/) - Dedicated Reddit community for Claude Code.
- [Anthropic Blog](https://www.anthropic.com/blog) - Official announcements and technical deep dives.
- [MCP Discord](https://discord.gg/mcp) - Community Discord for Model Context Protocol development.

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work. See [LICENSE](LICENSE) for details.
