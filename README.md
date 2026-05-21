<p align="center">
  <img src="https://raw.githubusercontent.com/salahuddinuqaili/salahuddinuqaili/main/banner.svg" alt="Salahuddin Uqaili" width="100%"/>
</p>

Associate Product Manager at **Delivery Hero** in Berlin, working on logistics CX products at scale. Outside of work, I explore what a PM can build when AI writes the code — I design the architecture, make the trade-off calls, and direct AI agents to handle the implementation. Each project is an exploration that's taught me how AI orchestration, MCP servers, and agentic workflows actually work under the hood.

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,react,typescript,electron,tauri,rust,docker,github&theme=dark" />
  </a>
</p>

---

### What I've explored

**[MCP Studio](https://github.com/salahuddinuqaili/mcp-studio)** — Developer toolkit for MCP servers: connect, explore, execute, and validate. Postman + ESLint for MCP. *All phases shipped, 15 tests.*
- Compliance scanner: 16 rules across protocol/quality/security, A-F grading, CI-ready CLI
- WebSocket proxy architecture — browsers can't hold MCP connections, so the backend bridges them

**[Neon Protocol IDE](https://github.com/salahuddinuqaili/neon-protocol-ide)** — Desktop IDE for navigating codebases through visual architecture maps and conversational AI. *20 releases, most complete exploration.*
- IPC as the security boundary — API keys never touch the renderer; 38 handlers route all privileged ops
- Multi-provider LLM routing with priority fallback; Zustand over Redux with 6 domain slices

**[Pulse](https://github.com/salahuddinuqaili/pulse)** — GPU performance monitor for systems running gaming and local AI workloads. Tauri 2 + Rust. *Active exploration, v0.3.1.*
- Tauri 2 over Electron — 3-6x memory reduction matters for a tool monitoring resource-hungry workloads
- Rust backend for direct GPU access via NVML; tiered polling (1s/2s/5s) by data volatility

**[Skillich](https://github.com/salahuddinuqaili/skillich)** — 1,028 skills across 88 roles, each rated for AI impact. Python SDK with MCP server, OpenAI/Anthropic adapters, and CLI. *Published on PyPI.*
- Agent-first architecture — AI tools are the primary consumers; auto-exports to OpenAI/Anthropic/MCP formats
- YAML taxonomy over a database so contributors submit PRs, not SQL

**[Sprint Narrator](https://github.com/salahuddinuqaili/sprint-narrator)** — AI sprint summary generator that pulls from Linear, Jira, and GitHub to create narrative reports via local LLMs. *74 tests.*
- Async pipeline with model-tier adaptation — adjusts prompts based on which Ollama model is available
- Smart categorization (shipped, bug fixes, in progress, blocked) with dedup across sources

**[DecisionLog](https://github.com/salahuddinuqaili/decisionlog)** — CLI for managing Architecture Decision Records with git integration, search, and HTML reports. *30+ tests.*
- 9 commands with git integration — decisions link to the commits that implement them
- HTML reports with TOC and status badges; keyword search across decision history

**[RAG Starter](https://github.com/salahuddinuqaili/rag-starter)** — Your first RAG pipeline. Local with Ollama, no frameworks, no API keys, 15 minutes. *42 tests.*
- Framework-free by design — no LangChain or LlamaIndex, so every layer is readable and modifiable
- Hand-written recursive text splitter; Groq free tier for Colab so beginners don't need a credit card

---

### What ties them together

- **AI-directed development** — every project built by orchestrating Claude Code, not manual coding
- **Documented trade-offs** — each repo has a DECISIONS.md explaining what was chosen, rejected, and why
- **Local-first architecture** — every project works without cloud dependencies or API keys
- **Multi-interface design** — CLI, web, desktop, and agents share a single core (no logic duplication)

---

### Connect

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salahuddinuqaili)
