# Hi, I'm Aayush Kumar 👋
AI Systems Engineer · Backend Engineer
Specializing in multi-agent orchestration and distributed LLM infrastructure.
Built production systems from scratch — no shortcuts, no black boxes.

## 🚀 What I've Built

**[LoomIQ](https://github.com/Aayush-engineer/LoomIQ)** — Multi-Agent AI Orchestration Engine · [Live Demo](https://mind-forge-three.vercel.app/)
- Production-grade engine routing tasks across multiple LLMs via a 6-factor scoring system (latency, cost, capability, success rate, complexity, idle state)
- 4 collaboration strategies: Sequential, Parallel, Hierarchical, Consensus
- Atomic execution locks, 3x exponential backoff, <50ms acknowledgment, SSE streaming with polling fallback
- Built without LangChain — to understand orchestration internals at the systems level

**[ChatFlux](https://github.com/Aayush-engineer/chatflux)** — Distributed Real-Time Chat Platform
- Socket.IO → Redis Pub/Sub → Kafka → MongoDB pipeline; horizontally scalable across instances
- Prometheus tracking 5 live metrics, Docker Compose, Nginx reverse proxy

**[RAG Support Engine](https://github.com/Aayush-engineer/rag-support-engine)** — Production-Style RAG Pipeline
- PDF → Gemini embeddings → Chroma vector DB → Groq LLaMA generation
- Cross-language retrieval (Hindi queries find English docs), grounded generation with correct refusal

## 🤝 Open Source — Mastra AI (22k+ ⭐ · YC-backed)

**9 PRs merged into @mastra/core · 2 active · Reviewed by CTO**

- **[PR #14466](https://github.com/mastra-ai/mastra/pull/14466)** — Fixed impact:high production bug in `prepareToolsAndToolChoice()` — structured-output agents were silently failing when workflow tools injected; fix unblocked Gemini structured output for all Mastra users
- **[PR #14306](https://github.com/mastra-ai/mastra/pull/14306)** — Added `prettyPrint` to `PinoLogger` — single-line JSON for Datadog/Loki/CloudWatch without rewiring all transports
- Active PRs: hybrid search fallback, JSON Schema draft-2020-12, configurable agent memory instructions, MCP request context

## 🛠️ Tech Stack
```
AI Systems:  Multi-Agent Orchestration · RAG · LLM Tool Use · Agent Memory · Embeddings · Vector DB · Evals
Backend:     Node.js · TypeScript · Express · Redis · Kafka · WebSockets · SSE · Docker · Microservices  
Databases:   PostgreSQL · MongoDB · Prisma · TypeORM
Languages:   TypeScript · JavaScript · Python · C++ · SQL
CS:          System Design · Distributed Systems · LLD · DSA · Concurrency
```

## 📊 Stats

[![LeetCode](https://img.shields.io/badge/LeetCode-600%2B%20problems-orange)](https://leetcode.com/u/ayush_kumar21_/)
[![GitHub followers](https://img.shields.io/github/followers/Aayush-engineer?style=social)](https://github.com/Aayush-engineer)

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/aayush-kumar-aba034239/) · aayushkumarsingh245@gmail.com · Open to remote and onsite India
