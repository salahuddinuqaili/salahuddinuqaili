<p align="center">
  <img src="https://raw.githubusercontent.com/salahuddinuqaili/salahuddinuqaili/main/banner.svg" alt="Salahuddin Uqaili" width="100%"/>
</p>

I build and evaluate AI systems by directing coding agents: MCP tooling, local model infrastructure, human-reviewed workflows, and the developer experience around them. Product manager at Delivery Hero in Berlin by day, working on logistics CX at scale.

I don't write the code by hand. I specify the architecture, set the guardrails, direct the agents that implement it, and own every trade-off call. The featured projects below each carry a decision log recording what was chosen, what was rejected, and why, so you can audit the reasoning rather than take my word for it.

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

**[legal-ai-eval-lab](https://github.com/salahuddinuqaili/legal-ai-eval-lab)** is an interactive case study in evaluated, source-grounded legal AI. It compares naive and guardrailed retrieval across 15 synthetic cases, exposing the evidence, failed gate, mitigation, and required human action instead of treating fluent output as trustworthy. [Live demo](https://salahuddinuqaili.github.io/legal-ai-eval-lab/).

**[bar-loop](https://github.com/salahuddinuqaili/bar-loop)** is an AI implementation framework for law firms, built on the assumption that someone will eventually ask you to justify it. Set a bar a partner would sign off, run builder and adversarial critic pairs, compare them blind, and refuse to ship on six hard gates — with jurisdiction packs for UK, US and EU.

**[mcp-rubric](https://github.com/salahuddinuqaili/mcp-rubric)** is Postman and ESLint for MCP servers. An interactive playground for exploring and testing Model Context Protocol servers, plus a compliance scanner that catches spec violations before a client ever sees them.

**[llm-autobench](https://github.com/salahuddinuqaili/llm-autobench)** is an autonomous benchmarking harness for local models: a seven-step discover, pull, bench, judge, report, delete, commit cycle running on a cron. It uses a free NVIDIA NIM judge so my RTX 5070 stays free for the model under test. The commit history is the pipeline running itself.

**[neon-protocol-ide](https://github.com/salahuddinuqaili/neon-protocol-ide)** opens a codebase as an interactive architecture map with conversational AI on top. 21 releases. IPC is the security boundary, so API keys never reach the renderer.

**[skillich](https://github.com/salahuddinuqaili/skillich)** rates 1,028 skills across 88 roles for AI impact. Python SDK, MCP server, OpenAI and Anthropic adapters, CLI. Agent-first by design, with a [browsable action plan](https://salahuddinuqaili.github.io/skillich/) on the web.

**[tether](https://github.com/salahuddinuqaili/tether)** is an installable iPhone PWA that talks to my local and cloud models over Tailscale. No backend, no App Store, no Mac. Editor, GitHub commits, and multi-chat, all browser-direct.

**[pulse](https://github.com/salahuddinuqaili/pulse)** monitors a GPU that both games and runs local models, in Rust and Tauri 2. It shows what the card is doing and what it can still take on.

*Also public: [rag-starter](https://github.com/salahuddinuqaili/rag-starter), a local RAG pipeline over your own documents. FastAPI and React, ChromaDB, Ollama, plain Python you can read.*

### How I work

- **Agent-directed.** Every project here was built by directing agents, not by typing the implementation.
- **Local-first by default.** Your hardware, your documents. Where a cloud model earns its place, like the free judge in llm-autobench, that is a deliberate call and it is written down.
- **Structural over advisory.** Constraints enforced by the tool, not by docs you hope people read.
- **Documented trade-offs.** A decision log in every featured repo: what was chosen, what was rejected, why.

---

### Connect

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salahuddinuqaili)
