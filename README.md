<div align="center">

# Ketan Shukla

### Building agentic AI systems — and shipping real products with them

**MCP servers · agent loops · human-in-the-loop guardrails**

<br>

[![Portfolio](https://img.shields.io/badge/ketanshukla.dev-0F172A?style=for-the-badge&logo=vercel&logoColor=D4A843)](https://ketanshukla.dev)
[![LinkedIn](https://img.shields.io/badge/linkedin-1E293B?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ketankshukla)
[![Location](https://img.shields.io/badge/San%20Diego,%20CA-334155?style=for-the-badge&logo=googlemaps&logoColor=white)](#)
[![Open to work](https://img.shields.io/badge/open%20to%20opportunities-047857?style=for-the-badge)](#)

</div>

---

## 🤖 Agentic AI — what I'm building now

Most of my recent work is about one question: **what does it take to let a model actually do things, safely?** Not demos — hosts that own the loop, gate irreversible actions, and can prove afterward what happened and what it cost.

### The MCP series

Five projects built in sequence, each adding one capability the previous one couldn't do. There's a companion course that teaches the protocol through all five.

| # | Project | The capability it adds | Live |
|:-:|:--------|:-----------------------|:----:|
| **1** | [**learn-mcp-5-year-old**](https://github.com/ketankshukla/learn-mcp-5-year-old) | A complete, working MCP **server** — the protocol from first principles | [↗](https://learn-mcp-5-year-old.vercel.app) |
| **2** | [**learn-mcp-agent-loop**](https://github.com/ketankshukla/learn-mcp-agent-loop) | An MCP **host** that owns the agent loop — picks tools across servers, calls them, loops until done | [↗](https://learn-mcp-agent-loop.vercel.app) |
| **3** | [**learn-mcp-agent-guard**](https://github.com/ketankshukla/learn-mcp-agent-guard) | **Human-in-the-loop approval gates** — stops before anything it can't undo. Postgres persistence, evals, replay | [↗](https://learn-mcp-agent-guard.vercel.app) |
| **4** | [**learn-mcp-agent-crew**](https://github.com/ketankshukla/learn-mcp-agent-crew) | **Sub-agents** — recursive agent loops where every gated call bubbles to one human queue | [↗](https://learn-mcp-agent-crew.vercel.app) |
| **5** | [**learn-mcp-agent-ledger**](https://github.com/ketankshukla/learn-mcp-agent-ledger) | **Sampling** — the server borrows the host's model. Cost ledger, spend gates, replayable runs | [↗](https://learn-mcp-agent-ledger.vercel.app) |

> 📘 **[mcp-five](https://github.com/ketankshukla/mcp-five)** — the written course tying all five together · **[read it ↗](https://mcp-five-sandy.vercel.app)**

### Production-shaped agent work

| Project | What it does |
|:--------|:-------------|
| [**spendguard-mcp**](https://github.com/ketankshukla/spendguard-mcp) | FinOps monorepo: investigate cloud-spend anomalies, draft a savings action, get independent approval, execute through a deterministic simulated provider. Survives retries and restarts, emits an authoritative receipt. **[demo ↗](https://spendguard-mcp-web.vercel.app)** |
| [**async-agent-workspace**](https://github.com/ketankshukla/async-agent-workspace) | Durable background agent runs on Inngest + Supabase, with a live run timeline. **[demo ↗](https://async-agent-workspace.vercel.app)** |
| [**ai-knowledge-base**](https://github.com/ketankshukla/ai-knowledge-base) | Signed-in RAG knowledge base — upload documents, chat grounded in your own content. **[demo ↗](https://ai-knowledge-base-red.vercel.app)** |
| [**research-agent**](https://github.com/ketankshukla/research-agent) | Plans research steps, calls web tools, reports back. **[demo ↗](https://research-agent-rouge-omega.vercel.app)** |
| [**rag-qa-assistant**](https://github.com/ketankshukla/rag-qa-assistant) | Retrieval-augmented Q&A that answers only from a supplied corpus. **[demo ↗](https://rag-qa-assistant-wheat.vercel.app)** |
| [**ai-data-extractor**](https://github.com/ketankshukla/ai-data-extractor) | Messy invoice / receipt / email text in, clean structured JSON out. **[demo ↗](https://ai-data-extractor-seven.vercel.app)** |

---

## 📚 AI-native publishing — 22 books shipped

I built an agentic pipeline that takes a book from concept to finished product — manuscript, covers, metadata, EPUB, print PDF, and generated audiobook — and then used it to publish **three complete series**.

<table>
<tr><th>Series</th><th align="center">Books</th><th>What it is</th></tr>
<tr>
<td><a href="https://github.com/ketankshukla/aztec-samurai-adventures"><b>⚔️ Aztec Samurai Adventures</b></a></td>
<td align="center"><b>12</b></td>
<td>Epic fantasy fusing Mesoamerican warrior traditions with samurai philosophy. 3 acts, 288 chapters, 30 characters. <a href="https://aztec-samurai-adventures.vercel.app">site ↗</a></td>
</tr>
<tr>
<td><a href="https://github.com/ketankshukla/reality-without-belief"><b>🌑 Reality Without Belief</b></a></td>
<td align="center"><b>5</b></td>
<td>Non-fiction on belief, clarity, and engaging reality directly. <a href="https://reality-without-belief.vercel.app">site ↗</a></td>
</tr>
<tr>
<td><a href="https://github.com/ketankshukla/repetition-mother-of-mastery"><b>🔁 Repetition — Mother Of Mastery</b></a></td>
<td align="center"><b>5</b></td>
<td>Non-fiction on the science of repetition, habit systems, and fast learning. <a href="https://repetition-mother-of-mastery.vercel.app">site ↗</a></td>
</tr>
</table>

**The pipeline itself, in three generations:**
[`v1`](https://github.com/ketankshukla/agentic-development) documented agent workflow → [`v2`](https://github.com/ketankshukla/agentic-development-v2) IDE-driven, six output formats → [`v3`](https://github.com/ketankshukla/agentic-development-v3) standalone Node.js CLI, 13 genres, no IDE required.

A fourth series — [**Quick Draw**](https://github.com/ketankshukla/quick-draw-series), a five-book spaghetti western — is architected and in production.

📖 Catalogue: **[ketanshukla.com](https://ketanshukla.com)** · [author-portfolio repo](https://github.com/ketankshukla/author-portfolio)

---

## 🏢 Businesses I run

| Business | What it does |
|:---------|:-------------|
| [**Metronagon Media**](https://metronagon.com) | Book publishing services — covers, series branding, full production pipelines, children's picture books |
| [**Surplus Recoveries**](https://surplusrecoveries.com) | Helps former homeowners claim surplus funds left after foreclosure sales. [Site + 30-chapter operator course](https://github.com/ketankshukla/SRWebsite) |
| [**Microflipping Properties**](https://microflippingproperties.com) | Real estate |

---

## 🧰 Toolbox

**Languages** · TypeScript · Python · JavaScript · Dart · SQL

**AI / Agents** · Model Context Protocol · agent loops & tool orchestration · RAG & embeddings · human-in-the-loop approval · evals & replay · sampling and cost control

**Web** · Next.js (App Router) · React · Tailwind CSS · Node.js

**Data** · PostgreSQL · Supabase · Drizzle · pgvector · ETL pipelines

**Infra** · Vercel · Inngest · GitHub Actions · Vitest · Docker

---

## 🎓 Also on the shelf

- [**ISTQB**](https://github.com/ketankshukla/ISTQB) — exam-focused self-study courses for ISTQB certifications, served through a Next.js reader with timed mock exams. **[live ↗](https://istqb-umber.vercel.app)**
- [**python-course**](https://github.com/ketankshukla/python-course) — 13-notebook beginner Python course, each module backed by a pytest suite running in CI
- [**modern-js**](https://github.com/ketankshukla/modern-js) — modern JavaScript course: 11 lessons, 7 exercise sets, starter and capstone apps
- [**water-sort**](https://github.com/ketankshukla/water-sort) · [**crossword-quest**](https://github.com/ketankshukla/crossword-quest) · [**task-flow**](https://github.com/ketankshukla/task-flow) — smaller apps, built for the craft

---

<div align="center">

**San Diego, CA** · Open to opportunities in agentic AI and full-stack engineering

**[ketanshukla.dev](https://ketanshukla.dev)** · [linkedin.com/in/ketankshukla](https://www.linkedin.com/in/ketankshukla) · [ketanshukla.com](https://ketanshukla.com) (books)

</div>
