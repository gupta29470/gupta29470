# Hey, I'm Aakash 👋

**Flutter Engineer · 4+ years · Building apps at scale**

<br>

---

## 🏢 Production Work

Building and shipping features for a retail app with **1.5M+ monthly active users**.

<br>

| What I Built | Impact |
|---|---|
| Next-gen CMS-driven home screen (Contentful + GraphQL) | **56.7M+** page views *(as of March 2026)* |
| Shoppable UGC feed (Tolstoy SDK integration) | **1.73M+** video clicks · **5.25%** buy-to-detail rate · MAU **1.2M → 1.5M** |

<br>

> From architecture decisions to refactoring legacy codebases — blogs and deep dives coming soon.

<br>

---

## 🚀 Projects

<br>

### 1. Codewalk — AI-Powered Codebase Onboarding Tool

Point it at any repo → understand the entire codebase in hours, not weeks.

[🔗 GitHub](https://github.com/gupta29470/codewalk)

<br>

**What it does:**

| Feature | How it works |
|---|---|
| 🔍 Module Detection | Auto-groups files into packages/modules by directory structure |
| 🕸️ Dependency Graph | Parses imports across 15+ languages via tree-sitter |
| 💥 Blast Radius | BFS on reversed dependency graph → shows transitive impact of any change |
| 📖 Reading Order | Topological sort → optimal file reading sequence (dependencies first) |
| 🤖 AI Chat | LangGraph agent with 7 query tools, multi-turn conversation with memory |
| 🔎 Semantic Search | ChromaDB vector search on embedded code chunks (RAG) |
| 🔬 Code Review | Multi-stage review: test coverage, blast radius, guidelines RAG, LLM deep scan (OWASP) |
| 🔄 Incremental Reindex | Content hash comparison — only re-embeds changed files, skips unchanged |
| 🧩 MCP Server | 16 tools for VS Code Copilot / Claude Code / Cursor / Codex |
| ⚡ Parallel Embedding | Producer-consumer pipeline — CPU chunking overlaps with GPU embedding |
| 🔄 Execution Flow | Entry points, module-to-module dependency chains with Mermaid diagrams |

<br>

**Three interfaces, one backend:**

| Interface | What |
|---|---|
| **MCP Server** (FastMCP) | 16 tools — works in VS Code Copilot, Claude Code, Cursor, Codex |
| **REST API** (FastAPI) | 16 endpoints — `/analyze`, `/chat`, `/review`, `/incremental-reindex`, `/overview`, `/blast-radius`, `/reading-order`, `/execution-flow` |
| **Web UI** (Next.js) | Visual exploration — module browser, diagrams, blast radius viewer, code review, smart reindex |

<br>

**16 MCP Tools:**

| Tool | What it does |
|---|---|
| `codewalk_analyze_codebase` | Scan repo, detect modules + dependencies |
| `codewalk_scan_files` | Batch file listing for smart filtering |
| `codewalk_submit_filtered_files` | Submit relevant files for indexing |
| `codewalk_index_filtered_files` | Embed selected files into vector store |
| `codewalk_search_codebase` | RAG-powered semantic code search |
| `codewalk_get_module_info` | Module details — files, functions, dependencies |
| `codewalk_explain_function` | Line-by-line explanation + blast radius |
| `codewalk_get_overview` | Tech stack, modules, diagram, riskiest files |
| `codewalk_get_blast_radius_map` | Change risk analysis for any file/module |
| `codewalk_get_reading_order` | Dependency-sorted file reading sequence |
| `codewalk_get_execution_flow` | Flow diagram — module-level or file-level |
| `codewalk_incremental_reindex` | Re-embed only changed files (hash-based skip) |
| `codewalk_refresh_analysis` | Re-scan without re-embedding |
| `codewalk_review_diff` | Review git diff — security, bugs, style (LLM + pre-checks) |
| `codewalk_review_file` | Review file against codebase conventions |
| `codewalk_load_guidelines` | Load team coding standards for reviews |

<br>

**15+ languages supported:**

Python · JavaScript · TypeScript · Java · Go · Rust · Ruby · PHP · C# · C++ · C · Kotlin · Swift · Dart · YAML

<br>

**Tech stack:**

`Python` · `FastAPI` · `LangChain` · `LangGraph` · `ChromaDB` · `tree-sitter` · `Sentence Transformers` · `Jina Embeddings` · `Next.js` · `Tailwind` · `Mermaid.js`

**LLM providers:** Ollama (local) · OpenAI · Anthropic · Gemini · Groq · OpenRouter

<br>

---

### 2. Navica — AI Trip Planner

AI-powered trip planning app, shipped on all platforms.

[🌐 Web](https://navica-web.vercel.app) · [▶️ Android](https://play.google.com/store/apps/details?id=com.gupta.navica) · [🍎 iOS](https://apps.apple.com/us/app/navica-ai-trip-planner/id6759998334) · [✈️ Sample Trip](https://navica-web.vercel.app/trip/685a5691-4756-4162-98e0-3fb35567290e_share)

<br>

### 3. [`flutter-internals`](https://github.com/gupta29470/flutter-internals)

Rebuilt Flutter's ListView from scratch — virtualized rendering with fixed + dynamic height.

<br>

### 4. [`ios-practice`](https://github.com/gupta29470/ios-practice)

17 iOS apps built while learning Swift & UIKit.

<br>

### 5. [`local-first-notes`](https://github.com/gupta29470/local-first-notes)

Local-first notes app.

<br>

---

## 🛠 Tech

<br>

**Mobile:** `Flutter` · `Dart` · `BLoC` · `Clean Architecture` · `Swift` · `SwiftUI` · `Firebase`

**AI/ML:** `Python` · `FastAPI` · `LangChain` · `LangGraph` · `ChromaDB` · `RAG` · `tree-sitter` · `MCP` · `Embeddings`

**Web:** `Contentful` · `GraphQL`
