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

**[Neon Protocol IDE](https://github.com/salahuddinuqaili/neon-protocol-ide)** — Desktop IDE for navigating codebases through visual architecture maps and conversational AI. *20 releases shipped.*
- IPC as the security boundary — API keys never touch the renderer process
- Multi-provider LLM routing with priority fallback for zero vendor lock-in
- Zustand over Redux — 6 domain slices, independently testable
- Most complete exploration: 9,800+ LOC, 38 IPC handlers, 8 documented ADRs

**[Skillich](https://github.com/salahuddinuqaili/skillich)** — 1,028 skills across 88 roles, each rated for AI impact. Python SDK with MCP server, OpenAI/Anthropic adapters, and CLI. *Published on PyPI.*
- Agent-first architecture — AI tools are the primary consumers, not humans
- MCP server design with multi-format function calling (OpenAI/Anthropic/MCP adapters)
- YAML taxonomy over a database so contributors can submit PRs, not SQL

**[MCP Studio](https://github.com/salahuddinuqaili/mcp-studio)** — Developer toolkit for MCP servers: interactive playground, compliance scanner, and CI-ready CLI. *Early development.*
- Identified a tooling gap in the MCP ecosystem (85K+ stars on servers, zero quality dev tools)
- WebSocket proxy architecture — browsers can't hold MCP connections, so the backend bridges them
- Compliance engine: 18+ protocol/quality/security rules with A-F scoring
- TypeScript monorepo: React SPA + Hono backend + CLI (pnpm workspaces)

**[RAG Starter](https://github.com/salahuddinuqaili/rag-starter)** — Your first RAG pipeline. Local with Ollama, no frameworks, no API keys, 15 minutes. *42 tests.*
- Framework-free by design — no LangChain or LlamaIndex, so every line is readable
- Hand-written recursive text splitter (most RAG failures stem from chunking)
- Groq free tier for Colab — beginners shouldn't need a credit card

**[Pulse](https://github.com/salahuddinuqaili/pulse)** — GPU performance monitor for systems running gaming and local AI workloads. *Still in design/spec phase.*
- Chose Tauri 2 over Electron after building Neon — documented the tradeoffs
- Rust backend for direct hardware access via NVML
- Real-time data patterns: ring buffers, tiered polling by data volatility

---

### What ties them together

- **AI-directed development** — every project built by orchestrating Claude Code, not manual coding
- **Documented trade-offs** — each repo has a DECISIONS.md explaining what was chosen, rejected, and why
- **Local-first architecture** — all projects work without cloud dependencies
- **Multi-interface design** — CLI, web, and agents share a single core (no logic duplication)

---

### Connect

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salahuddinuqaili)
