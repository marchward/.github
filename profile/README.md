# Marchward

**Runtime authority for AI agents.**

Your agent holds one Marchward key, not your GitHub token, your Stripe key, or your database password. Marchward brokers every action the agent takes: it injects the real credential server-side so the agent never holds it, enforces a hard inference cost cap, gates irreversible actions for human approval, and writes a tamper-evident audit log of what actually executed.

Output guardrails check what an agent says. Marchward governs what it does, because the agent never holds the credential and every action runs through the governor.

Works with LangGraph, LangChain, the raw SDK, or any agent runtime.

### Start here

- **[marchward/marchward](https://github.com/marchward/marchward)** — the open-core engine, proxy, and SDK (Apache-2.0)
- `pip install marchward` — the Python SDK
- **[marchward.ai](https://marchward.ai)** — docs and the managed control plane

Open core: self-host the governor under Apache-2.0, or use the managed cloud.
