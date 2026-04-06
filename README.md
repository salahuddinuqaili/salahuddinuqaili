<p align="center">
  <img src="https://raw.githubusercontent.com/salahuddinuqaili/salahuddinuqaili/main/banner.svg" alt="Salahuddin Uqaili" width="100%"/>
</p>

Associate Product Manager at **Delivery Hero** in Berlin, working on logistics products at scale. Outside of work, I build software by orchestrating AI — designing the architecture, making the trade-off calls, and directing AI agents to write the implementation.

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=typescript,react,nextjs,electron,tauri,rust,python,docker,github&theme=dark" />
  </a>
</p>

---

### Projects

**[Pulse](https://github.com/salahuddinuqaili/pulse)** — GPU performance monitor for systems running both gaming and local AI workloads. Answers "what can my GPU do right now?" with VRAM process maps and headroom indicators. ~10MB installer, ~30MB RAM.
- Tauri 2 over Electron — native Rust backend for GPU polling at a fraction of the footprint
- NVML integration in Rust for direct hardware access without Node.js overhead
- Zustand with ring buffer for time-series state — fixed-size buffer instead of growing arrays

**[Neon Protocol IDE](https://github.com/salahuddinuqaili/neon-protocol-ide)** — Desktop IDE for navigating codebases through visual architecture maps and conversational AI. Electron + Next.js + React, 20 releases shipped.
- Chose IPC as the security boundary — API keys never touch the renderer process
- Multi-provider LLM routing with priority fallback for zero vendor lock-in
- Zustand over Redux — minimal boilerplate, independently testable slices

**[Skillich](https://github.com/salahuddinuqaili/skillich)** — 1,028 skills across 88 roles, each rated for AI impact. Python SDK with MCP server, OpenAI/Anthropic adapters, and CLI.
- Agent-first architecture — primary consumers are AI tools (MCP, function calling), the web app is a generated artifact
- YAML taxonomy over a database so contributors can submit PRs, not SQL

**[RAG Starter](https://github.com/salahuddinuqaili/rag-starter)** — Your first RAG pipeline. Local with Ollama, no frameworks, no API keys, 15 minutes.
- Framework-free by design — no LangChain or LlamaIndex, so every line is readable
- Custom exceptions over sys.exit() — library code shouldn't kill notebooks or Streamlit
- Groq free tier for Colab instead of OpenAI — beginners shouldn't need a credit card

---

### Connect

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salahuddinuqaili)
