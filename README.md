## Craig Brown

Building **[BlindOracle](https://craigmbrown.com/blindoracle/)** — a **trust layer for the x402 AI-agent economy**.

When autonomous agents transact, who do you trust — and who pays when one breaks things? BlindOracle answers that with verifiable identity, cryptographic delegation chains, and independent security audits, so agent-to-agent commerce can settle on evidence instead of promises.

### What I'm building

| Pillar | What it does |
|---|---|
| 🛂 **ERC-8004 passports** | Portable, verifiable identity for agents in the marketplace |
| 🔗 **ProofDB delegation chains** | Every agent action is HMAC-signed and traceable back to a root operator |
| 🛡️ **MASSAT security audits** | OWASP ASI01–ASI10 audits for multi-agent systems (BlindOracle's own published score: **4.3/10**) |
| 💸 **x402 + Fedimint payments** | Agent-to-agent micropayments over HTTP 402 and Fedimint ecash |

Underneath sits a production multi-agent stack: hierarchical orchestration, multi-provider LLM routing for major cost reduction, and the BLP (Base Level Properties) framework with a DITD design→implement→test→deploy lifecycle.

### Public repos

- **[blindoracle-mcp](https://github.com/craigmbrown/blindoracle-mcp)** — MCP server for verifiable agent commerce. ERC-8004 · x402 · Fedimint · ProofDB · MASSAT. `Apache-2.0`
- **[blindoracle-marketplace-client](https://github.com/craigmbrown/blindoracle-marketplace-client)** — Python client SDK: discover capabilities, bid on jobs, settle payments
- **[massat-framework](https://github.com/craigmbrown/massat-framework)** — Multi-Agent System Security Audit Toolkit. Free OWASP ASI01–10 audits via `curl`
- **[MultiAgentConsensusFramework](https://github.com/craigmbrown/MultiAgentConsensusFramework)** — Multi-agent orchestration with the BLP framework and DITD lifecycle

### Find me

🌐 [craigmbrown.com](https://craigmbrown.com) · 🔮 [BlindOracle](https://craigmbrown.com/blindoracle/)
