<p align="center">
  <img src="https://raw.githubusercontent.com/salahuddinuqaili/salahuddinuqaili/main/banner.svg" alt="Salahuddin Uqaili" width="100%"/>
</p>

I build AI developer tooling by directing coding agents: MCP tooling, local model infrastructure, and the developer experience around both. Product manager at Delivery Hero in Berlin by day, working on logistics CX at scale.

I don't write the code by hand. I specify the architecture, set the guardrails, direct the agents that implement it, and own every trade-off call. The six projects below each carry a DECISIONS.md recording what was chosen, what was rejected, and why, so you can audit the reasoning rather than take my word for it.

<p align="center">
  <img src="https://img.shields.io/badge/Anthropic-191919?style=for-the-badge&logo=anthropic&logoColor=white" alt="Anthropic"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI"/>
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama"/>
  <img src="https://img.shields.io/badge/MCP-1F1F1F?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="Model Context Protocol"/>
  <img src="https://img.shields.io/badge/NVIDIA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="NVIDIA"/>
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,rust,typescript,tauri,docker&theme=dark" alt="Python, Rust, TypeScript, Tauri, Docker"/>
  </a>
</p>

---

### What I build

**[mcp-studio](https://github.com/salahuddinuqaili/mcp-studio)** is Postman and ESLint for MCP servers. An interactive playground for exploring and testing Model Context Protocol servers, plus a compliance scanner that catches spec violations before a client ever sees them.

**[llm-autobench](https://github.com/salahuddinuqaili/llm-autobench)** is an autonomous benchmarking harness for local models: a seven-step discover, pull, bench, judge, report, delete, commit cycle running on a cron. It uses a free NVIDIA NIM judge so my RTX 5070 stays free for the model under test. The commit history is the pipeline running itself.

**[neon-protocol-ide](https://github.com/salahuddinuqaili/neon-protocol-ide)** opens a codebase as an interactive architecture map with conversational AI on top. 21 releases. IPC is the security boundary, so API keys never reach the renderer.

**[skillich](https://github.com/salahuddinuqaili/skillich)** rates 1,028 skills across 88 roles for AI impact. Python SDK, MCP server, OpenAI and Anthropic adapters, CLI. Agent-first by design, with a [browsable action plan](https://salahuddinuqaili.github.io/skillich/) on the web.

**[tether](https://github.com/salahuddinuqaili/tether)** is an installable iPhone PWA that talks to my local and cloud models over Tailscale. No backend, no App Store, no Mac. Editor, GitHub commits, and multi-chat, all browser-direct.

**[pulse](https://github.com/salahuddinuqaili/pulse)** monitors a GPU that both games and runs local models, in Rust and Tauri 2. It shows what the card is doing and what it can still take on.

*Also public: [rag-starter](https://github.com/salahuddinuqaili/rag-starter), a local RAG pipeline you can stand up in fifteen minutes with no frameworks.*

### How I work

- **Agent-directed.** Every project here was built by directing agents, not by typing the implementation.
- **Local-first.** It runs on your own machine, without cloud dependencies or API keys.
- **Structural over advisory.** Guardrails enforced by the type system, not by docs you hope people read.
- **Documented trade-offs.** A DECISIONS.md in every featured repo: what was chosen, what was rejected, why.

---

### Connect

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salahuddinuqaili)
