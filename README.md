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

**[Pulse](https://github.com/salahuddinuqaili/pulse)** — GPU performance monitor for systems running gaming and local AI workloads.
*Tauri 2, Rust, React · Still in design/spec phase*
Learned: Framework evaluation (chose Tauri over Electron after building Neon — documented the tradeoffs), Rust backend for direct hardware access via NVML, real-time data patterns (ring buffers, tiered polling).

**[Neon Protocol IDE](https://github.com/salahuddinuqaili/neon-protocol-ide)** — Desktop IDE for navigating codebases through visual architecture maps and conversational AI.
*Electron, Next.js, React · 20 releases shipped*
Learned: IPC security boundaries (API keys never touch the renderer), multi-provider LLM routing with priority fallback, state management with Zustand (6 domain slices). Most complete exploration — 9,800+ LOC, 38 IPC handlers, 8 documented architecture decisions.

**[Skillich](https://github.com/salahuddinuqaili/skillich)** — 1,028 skills across 88 roles, each rated for AI impact. Python SDK with MCP server, OpenAI/Anthropic adapters, and CLI.
*Python, FastMCP · Published on PyPI*
Learned: MCP server design, agent-first architecture (AI tools are the primary consumers, not humans), multi-format function calling (OpenAI/Anthropic/MCP adapters), YAML taxonomy for contributor-friendly data.

**[RAG Starter](https://github.com/salahuddinuqaili/rag-starter)** — Your first RAG pipeline. Local with Ollama, no frameworks, no API keys, 15 minutes.
*Python, Ollama, Streamlit · 42 tests*
Learned: RAG fundamentals without frameworks (no LangChain — every line readable), text chunking strategy (hand-written recursive splitter), local-first AI architecture, educational software design (Groq free tier so beginners skip the credit card).

---

### What ties them together

- **AI-directed development** — every project built by orchestrating Claude Code, not manual coding
- **Documented trade-offs** — each repo has a DECISIONS.md explaining what was chosen, rejected, and why
- **Local-first architecture** — all projects work without cloud dependencies
- **Multi-interface design** — CLI, web, and agents share a single core (no logic duplication)

---

### Connect

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salahuddinuqaili)
