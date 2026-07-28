# Angel Hermon

Software engineer. I build systems and the tools around them.

Right now that's agentic engineering — harnesses, MCP tracing, control planes,
and observability for agent runs.

### Work

| Repo | What it does |
| --- | --- |
| [anvil](https://github.com/anhermon/anvil) | Agent harness in Rust. One binary, pluggable LLM providers, sub-agents, a skill library, and episodic memory in SQLite. |
| [mcp-trace](https://github.com/anhermon/mcp-trace) | Transparent Go proxy for MCP servers. One OpenTelemetry span per JSON-RPC tool call; no code changes on either side, you point the client at the proxy's port instead of the server's. |
| [agent-tower](https://github.com/anhermon/agent-tower) | Read-only control plane for agent harnesses. Reads transcripts off disk and gives you a dashboard, a CLI, and an MCP server over the same analytics. |
| [obs-dashboard](https://github.com/anhermon/obs-dashboard) | Real-time observability for Claude Code and Codex runs — no instrumentation, it tails the transcripts. |
| [awesome-agent-observability](https://github.com/anhermon/awesome-agent-observability) | Curated list of tracing, eval, guardrail, gateway, and MCP tooling for LLM and agent observability. |

### Stack

Go · Rust · Python · TypeScript · Kubernetes · OpenTelemetry

---

More at [anhermon.dev](https://anhermon.dev).
Open to freelance and contract work. Reach me at angel.hermon.mail@gmail.com.
