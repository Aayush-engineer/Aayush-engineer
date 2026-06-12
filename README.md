<div align="center">

# Aayush Kumar

**AI Systems Engineer · Backend Engineer · Agentic Infrastructure**

[![Email](https://img.shields.io/badge/email-aayushkumarsingh245%40gmail.com-informational?style=flat-square)](mailto:aayushkumarsingh245@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aayush-kumar-aba034239/)
[![LeetCode](https://img.shields.io/badge/LeetCode-600%2B-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/u/ayush_kumar21_/)
[![GitHub](https://img.shields.io/github/followers/Aayush-engineer?label=Follow&style=flat-square)](https://github.com/Aayush-engineer)

</div>

---

I build LLM infrastructure and multi-agent systems — evaluation pipelines, orchestration engines, and observability tooling. I avoid framework abstractions where possible and work at the systems level to understand what's actually happening.

**Open to:** Backend Engineer · Agentic AI Engineer · AI Systems Engineer *(not core ML/research)*

---

## Open Source — Mastra AI (24k ⭐ · YC-backed)

**18 PRs merged · #47 of 467 total contributors · #29 of 500+ in last 6 months**

| PR | Description |
|---|---|
| [#14466](https://github.com/mastra-ai/mastra/pull/14466) | Fixed `impact:high` bug in `prepareToolsAndToolChoice()` — structured-output agents silently failing when workflow tools injected; unblocked Gemini structured output for all users |
| [#14306](https://github.com/mastra-ai/mastra/pull/14306) | Added `prettyPrint` to `PinoLogger` — single-line JSON for Datadog/Loki/CloudWatch without rewiring transports |
| +10 more | Memory persistence across chained agent steps, browser thread init stability, JSON schema compatibility, production observability |

---

## Projects

### [TraceMind](https://github.com/Aayush-engineer/TraceMind) — LLM Observability & Eval Platform · [live ↗](https://tracemind.vercel.app)
`Python` `FastAPI` `React` `ChromaDB` `Groq` `asyncio`

- Parallel LLM-as-judge eval engine — 100 cases in 17s via `asyncio.Semaphore`
- Per-claim hallucination detector: extract → ground → score, 4 error types
- Mann-Whitney U A/B testing with bootstrap 95% CI — validated against scipy
- Multi-key Groq rotation (5 keys, auto-failover); bulk batching cuts LLM costs by 99%
- ReAct agent with ChromaDB semantic memory · response control hooks (block/retry/flag)
- **76/76 unit tests · 44/44 e2e checks passing · 11 GitHub stars**

### [LoomIQ](https://github.com/Aayush-engineer/LoomIQ) — Multi-Agent Orchestration Engine · [live ↗](https://mind-forge-three.vercel.app/)
`TypeScript` `Node.js` `PostgreSQL` `Groq` `Mistral` `SSE`

- Dynamic LLM routing via 6-factor scoring (latency, cost, capability, success rate, complexity, idle state) — no LangChain
- Zero duplicate executions under 100+ concurrent tasks via atomic execution lock
- 3× exponential backoff (1s → 2s → 4s) · <50ms HTTP ack before any LLM call
- 4 collaboration strategies: Sequential, Parallel, Hierarchical, Consensus
- JWT + RBAC (4 roles) · SSE streaming with polling fallback

### [ChatFlux](https://github.com/Aayush-engineer/chatflux) — Distributed Real-Time Chat
`Socket.IO` `Redis` `Kafka` `MongoDB` `Docker` `Prometheus`

- Socket.IO → Redis Pub/Sub → Kafka → MongoDB pipeline; horizontally scalable
- Prometheus tracking 5 live metrics · Docker Compose · Nginx reverse proxy

---

## Stack

```
AI / LLM   Multi-Agent Orchestration · RAG · LLM Tool Use · Evals · Observability · Vector DB · Agent Memory
Backend    Node.js · TypeScript · Python · FastAPI · Express · Redis · Kafka · WebSockets · SSE · Docker
Database   PostgreSQL · MongoDB · ChromaDB · Prisma · TypeORM
CS         System Design · Distributed Systems · LLD · DSA · Concurrency
```

---

## Experience

**ML / Data Pipeline Intern · IIT Jodhpur** *(Apr – Jun 2024)*
Python preprocessing pipelines for multilingual OCR datasets. OpenCV automation cut manual labeling by 50%. Processed 5,000+ training images.

**Software Developer Intern · DRDO Jodhpur** *(May – Jul 2023)*
REST APIs for vendor/bidding workflows (50+ active projects). JWT auth, RBAC, WebSocket notifications, MongoDB query optimization to sub-second response times.

---

B.Tech CSE · JIET Jodhpur · 2021–2025 · 600+ LeetCode (C++)

<div align="center">
<sub>aayushkumarsingh245@gmail.com · available for remote and onsite India</sub>
</div>
