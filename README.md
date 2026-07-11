<h1 align="center">Lucian-Adrian Gavril</h1>
<p align="center"><b>AI Systems Architect · Production LLM Agents, RAG & Automation</b></p>
<p align="center">Chișinău, Moldova · <a href="mailto:lucianadrian10@gmail.com">lucianadrian10@gmail.com</a> · <a href="https://www.linkedin.com/in/lucian-adrian">LinkedIn</a></p>

---

I design and ship end-to-end systems: relational schemas, API architecture, and agent orchestration first — then AI-accelerated implementation, reviewed and tested to production standards.

**Domains I've shipped in:** government (Ministry of Justice of Moldova), enterprise e-learning (Orange), EdTech (my own business — 74 students prepped for the BAC national exam, 71 hit their target grade), and real-time sales tooling.

## Selected work

| Project | What it is | Stack |
|---|---|---|
| [isomorph](https://github.com/Lucian-Adrian/isomorph) | Bidirectional DSL for software architecture diagrams — text ↔ canvas, formally specified grammar, 500+ tests. Team lead. | TypeScript, ANTLR4, React |
| [exocortex](https://github.com/Lucian-Adrian/exocortex) | AI knowledge-memory system with semantic search, RAG Q&A, commitment tracking — includes a RAG evaluation suite gated in CI (DeepEval) and LLM observability (Langfuse). | Python, pgvector, Gemini |
| **M-Petiție** (private) | AI petition-processing pipeline for public institutions: OCR → PII redaction → legal-citation RAG → drafted official response → immutable audit trail. RBAC, 12-table schema, tested .NET backend, k8s manifests. | React, ASP.NET Core 8, Gemini |
| [ghostwriter](https://github.com/Lucian-Adrian/ghostwriter) | Autonomous social-media agent: monitors news → generates posts → human-in-the-loop approval via Telegram. | Python, FastAPI, Ollama |
| [flower-chat-agent](https://github.com/Lucian-Adrian/flower-chat-agent) | Conversational-commerce chatbot (Telegram + Instagram): intent detection, vector product search, cart & payment flow. | Python, ChromaDB, Redis |
| **Sotto** (private) | Real-time voice AI sales copilot: live call audio → VAD → streaming STT → LLM guidance overlay. | Electron, TypeScript, Gemini |

Also: multilingual speech tooling (sherpa-onnx/SenseVoice, Azure STT with RO/RU/EN auto-detect), automated scraping pipelines (Playwright + BeautifulSoup against government portals, scrape→embed catalog pipelines), and [audio-toolkit](https://github.com/Lucian-Adrian/audio-toolkit) for ML dataset prep.

## How I work

- **Architecture is human, syntax is automated.** I design the schema, state machines, and failure modes; AI writes boilerplate at high velocity; everything is reviewed and tested before it ships.
- **Production means error handling.** Typed recoverable errors, graceful degradation, audit trails, evaluation suites in CI — not happy-path demos.

<p align="center">
  <img height="170em" src="https://github-readme-stats.vercel.app/api?username=Lucian-Adrian&show_icons=true&theme=dracula&include_all_commits=true&count_private=true&hide_border=true" alt="GitHub stats"/>
  <img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Lucian-Adrian&layout=compact&langs_count=8&theme=dracula&hide_border=true" alt="Top languages"/>
</p>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Lucian-Adrian/Lucian-Adrian/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Lucian-Adrian/Lucian-Adrian/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Lucian-Adrian/Lucian-Adrian/output/github-snake.svg" />
</picture>
</p>
