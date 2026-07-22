<p align="center">
  <img src="https://raw.githubusercontent.com/salahuddinuqaili/salahuddinuqaili/main/banner.svg" alt="Salahuddin Uqaili" width="100%"/>
</p>

**Associate Product Manager at Delivery Hero**, Berlin — logistics CX products at scale.

Off the clock, I don't just *use* AI agents — I'm **building** the factory that runs them. I've been designing the pieces of a local-first agent stack: a coding agent, its memory layer, an orchestrator that runs on my own GPU, and a type-checker that turns an agent's authority, cost, and lineage into compile-time facts. I direct the agents to build it while I own the architecture, the guardrails, and the trade-off calls. I can't write the code by hand — but I can specify it, direct it, and tell you exactly why every trade-off went the way it did.

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,rust,typescript,react,tauri,electron,docker,github&theme=dark" />
  </a>
</p>

---

### The system I'm architecting

A private, local-first agent stack I've been designing and directing — happy to walk through it in a conversation:

- **The agent** — an LLM-agnostic, approval-gated coding agent in Rust: multi-provider routing with logged decisions, a fallback tool-protocol for models without native tool use, git-shadow-ref checkpoints and one-command undo.
- **The memory** — a git-backed, local-first knowledge base and shared-memory contract that agents read and write over MCP.
- **The guardrail** — an experimental agentic language whose type-checker won't let an agent compile if it exceeds the authority or budget it was granted. Authority, cost, and lineage become *compile-time facts*, not runtime hopes.
- **The orchestrator** — a worktree-per-agent design that assigns work to a bench of specialists, with cost accounting and provenance built in.

### The explorations behind it

Public repos where I've built out pieces of the idea:

**[llm-autobench](https://github.com/salahuddinuqaili/llm-autobench)** — Autonomous benchmarking harness: a 7-step discover → pull → bench → judge → report → delete → commit cycle on a cron, using a free NVIDIA NIM judge to keep my RTX 5070 free for the model under test. The commit history *is* the pipeline running itself.

**[tether](https://github.com/salahuddinuqaili/tether)** — An installable iPhone PWA that talks to my local + cloud models over Tailscale. No backend, no App Store, no Mac — editor, GitHub commit, and multi-chat, all browser-direct.

**[changelog-genie](https://github.com/salahuddinuqaili/changelog-genie)** — Commits and PRs → clean, categorized changelogs via local LLMs. Packaged as a GitHub Action, 51 tests; nothing leaves your machine.

**[benchviz](https://github.com/salahuddinuqaili/benchviz)** — Turns messy LLM benchmark JSON into a static dashboard: leaderboard, capability radar, model×task heatmap, and regression detection that flags any drop >5%. One dependency, pytest-green on Python 3.9 / 3.11 / 3.12, zero API keys.

**[neon-protocol-ide](https://github.com/salahuddinuqaili/neon-protocol-ide)** — Desktop IDE that opens a codebase as an interactive architecture map with conversational AI. 21 releases; IPC as the security boundary so API keys never touch the renderer.

**[skillich](https://github.com/salahuddinuqaili/skillich)** — 1,028 skills across 88 roles, each rated for AI impact. Python SDK + MCP server + OpenAI/Anthropic adapters + CLI. Agent-first by design.

*Also public: [pulse](https://github.com/salahuddinuqaili/pulse) (Rust/Tauri GPU monitor), [rag-starter](https://github.com/salahuddinuqaili/rag-starter), [mcp-studio](https://github.com/salahuddinuqaili/mcp-studio), [sprint-narrator](https://github.com/salahuddinuqaili/sprint-narrator), [decisionlog](https://github.com/salahuddinuqaili/decisionlog).*

---

### What ties them together

- **AI-directed development** — every project built by directing agents, not by writing the code by hand
- **Local-first** — everything runs without cloud dependencies or API keys
- **Structural over advisory** — guardrails enforced by the type system, not by docs you hope people read
- **Documented trade-offs** — a DECISIONS.md in every repo: what was chosen, what was rejected, and why

---

### Connect

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salahuddinuqaili)
