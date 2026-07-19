# Srinivas Merugu

**Senior AI Engineer** — multi-agent LLM systems and tool-use safety, built on **12+ years of data & systems engineering**. I build systems that let AI act safely in the real world.

Most recently, solo: a production-shaped **multi-agent AI runtime** — an LLM assistant with 29 tools over WhatsApp, 16 always-on backend services, and guarded execution against live financial accounts. The design rule that makes it safe: **the model proposes, deny-by-default gated code disposes.** The LLM never places an order or runs git.

### 🔗 Start here

| | |
|---|---|
| 🛡️ **[llm-tool-host](https://github.com/srinu16it/llm-tool-host)** | The open-sourced core: a dependency-free LLM tool-host whose injection harness holds **even against a fully-compromised model**. Green CI, runs in 30s. |
| 📄 **[Case study](https://github.com/srinu16it/llm-tool-host/blob/main/CASE_STUDY.md)** | The full system — architecture, 3 hard problems, what broke, tradeoffs. |
| 🌊 **[arinflow.com](https://arinflow.com)** | Where the runtime is headed as a consumer product (vision / prototype). |
| 💼 **[LinkedIn](https://www.linkedin.com/in/srinimerugu/)** | Background & contact |

### What I care about

- **Tool-use safety** — capability allowlists, untrusted-content envelopes, value caps; assume the model can be talked into anything and gate accordingly.
- **Determinism where it counts** — the model writes content; deterministic, verified pipelines do the irreversible steps.
- **Honest engineering** — self-grading systems, incidents turned into regression tests, adversarial review before shipping.

**Stack:** Node.js · Python · LLM tool-use & structured output · SQLite · pm2

*Open to Senior AI Engineer / LLM-systems roles — including forward-deployed work (shipping AI into real environments is exactly what this system is).*
