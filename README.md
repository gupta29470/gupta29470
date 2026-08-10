# Hey, I'm Aakash 👋

**AI / GenAI and Mobile Engineer · 4+ years of mobile engineering · Building production systems**

I’m a software engineer with 4+ years of experience shipping consumer products at scale. I’m now focused on **Applied AI / GenAI**, building systems around retrieval, fine-tuning, real-time voice, agents, and code intelligence.

---

## 🏢 Production Experience

Currently working as a **Mobile Engineer at Anko GCC**, building for Kmart & Target Australia.

- Retail platform serving **3.74M active users**
- WebView memory: **2GB → 400MB**
- Token clearing: **2,000ms → 10ms**
- PLP first load: **6–9s → 131ms**
- PDP logged-in: **3,054ms → 231ms**
- Next-Gen Home Screen: **38.9M sessions**
- Shoppable UGC: **17M events · 923K users · 24% conversion among interactors**
- Connectivity recovery improved by **2–7s**
- Ran engineering/code-quality sessions for **10–12 engineers**

Earlier, I worked across startups and product teams building consumer applications, including social investing and digital dining platforms.

---

# 🚀 AI / GenAI Projects

## 1. VoiceFlow — Real-Time Voice AI Platform

**Real-time AI phone-call platform with streaming STT → LLM → TTS pipelines.**

[GitHub](https://github.com/gupta29470/voice-flow) · [Demo Video](https://youtu.be/WMqto41-tRw)

### What I built

- **Cascaded streaming pipeline:** Twilio Media Streams → Deepgram STT → Grok/Kimi → Cartesia/ElevenLabs TTS
- **Barge-in & turn-taking:** endpointing, cancellable speech tasks, and Twilio clear events
- **Latency engineering:** sentence-level LLM → TTS streaming with per-turn avg/p95 latency tracking
- **Real phone calls:** 8kHz μ-law audio over WebSockets
- **Configurable workflows:** loan recovery, EMI, banking, and sales
- **Structured captures:** promise-to-pay, lead qualification, escalation
- **Multilingual:** English, Hindi, and Hinglish with language-aware STT/TTS

**Stack:** `Python` `FastAPI` `WebSockets` `Twilio` `Deepgram` `Grok` `Cartesia` `ElevenLabs` `SQLite` `Next.js`

---

## 2. Codewalk — AI Code Intelligence Platform

**Point it at a repository → understand the codebase, dependencies, risks, execution flows, and changes.**

[GitHub](https://github.com/gupta29470/codewalk) · [Website](https://www.codewalk.xyz/) · [Demo Video](https://youtu.be/bqmJnED7GMk)

### What it does

- **Corrective RAG:** parent-child chunking, semantic search, symbol lookup, graph expansion, and query rewriting
- **AI code review:** repository-aware diff review, language-specific rubrics, blast-radius analysis, and test-verified fix suggestions
- **MCP server:** **39 tools** for VS Code Copilot, Claude Code, and Cursor
- **Graph intelligence:** DuckDB + igraph for PageRank, blast radius, cycle detection, and dependency analysis
- **Agentic workflows:** LangGraph chat, human-in-the-loop gates, and deep-research fan-out
- **Code parsing:** tree-sitter across **15+ languages**
- **Incremental reindexing:** only changed files are re-processed
- **Multi-provider LLM layer:** **7 providers** with retry and fallback
- **Semantic code search:** vector retrieval over repository code
- **Execution flow:** entry points and module/file dependency chains

**Stack:** `Python` `LangChain` `LangGraph` `ChromaDB` `DuckDB` `igraph` `tree-sitter` `FastAPI` `Next.js` `Docker`

### Interfaces

| Interface | Description |
|---|---|
| **MCP Server** | 39 tools for AI coding agents |
| **REST API** | Repository analysis, chat, review, indexing, graph intelligence |
| **Web UI** | Visual repository exploration, diagrams, blast radius, reviews |

---

## 3. EcomBot — Fine-Tuned AI Customer Support Assistant

**Fine-tuned small language model + deterministic business logic for customer support.**

[GitHub](https://github.com/gupta29470)

### What I built

- Fine-tuned **Qwen 2.5 0.5B Instruct** with **LoRA**
- Used **PEFT + TRL**
- Trained on **385 customer-support conversations**
- Covered orders, returns, and refunds
- **Hybrid inference:** LLM extracts structured intent while Python performs catalog/order lookups
- Keeps business-critical responses grounded in actual application data

**Stack:** `Python` `FastAPI` `PyTorch` `Transformers` `PEFT` `TRL` `Qwen 2.5`

---

# 📱 Other Projects

### Navica — AI Trip Planner

AI-powered trip planning application shipped across web, Android, and iOS.

[Web](https://navica-web.vercel.app) · [Android](https://play.google.com/store/apps/details?id=com.gupta.navica) · [iOS](https://apps.apple.com/us/app/navica-ai-trip-planner/id6759998334) · [Sample Trip](https://navica-web.vercel.app/trip/685a5691-4756-4162-98e0-3fb35567290e_share)

### flutter-internals

Rebuilt Flutter's `ListView` from scratch with virtualized rendering supporting fixed and dynamic heights.

[GitHub](https://github.com/gupta29470/flutter-internals)

### ios-practice

17 iOS applications built while learning Swift and UIKit.

[GitHub](https://github.com/gupta29470/ios-practice)

### local-first-notes

A local-first notes application.

[GitHub](https://github.com/gupta29470/local-first-notes)

---

# 🧠 AI / Engineering Focus

### AI / GenAI
`RAG` · `LangChain` · `LangGraph` · `MCP` · `Embeddings` · `ChromaDB` · `PEFT / LoRA` · `TRL` · `PyTorch` · `Prompt Engineering` · `Function Calling` · `Real-time Voice` · `LLM Evaluation` · `Langfuse`

### Backend
`Python` · `FastAPI` · `WebSockets` · `REST` · `Docker` · `PostgreSQL` · `DuckDB` · `SQLite` · `CI/CD`

### Mobile
`Flutter` · `Dart` · `BLoC` · `SwiftUI` · `Firebase` · `Platform Channels`

### Languages
`Python` · `Dart` · `Swift`

---

# 📊 Production Engineering

I care about measurable engineering outcomes, not just shipping features.

| Area | Result |
|---|---|
| WebView memory | **2GB → 400MB** |
| Token clearing | **2,000ms → 10ms** |
| PLP first load | **6–9s → 131ms** |
| PDP logged-in | **3,054ms → 231ms** |
| Home Screen | **38.9M sessions** |
| Shoppable UGC | **17M events · 923K users** |
| Connectivity recovery | **2–7s faster** |
| Engineering enablement | **10–12 engineers** |

---

# 🔗 Connect

- **GitHub:** https://github.com/gupta29470
- **LinkedIn:** https://www.linkedin.com/in/aakash98gupta/
- **Email:** aa.1998.gupta@gmail.com

---

## 🎯 Currently

Building production-grade **Applied AI / GenAI systems** and looking for opportunities where I can combine my software engineering background with AI systems engineering.

**Interested in:** RAG · Agents · LLM applications · Voice AI · AI infrastructure · Model fine-tuning · Developer tools
