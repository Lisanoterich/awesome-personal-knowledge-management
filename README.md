# Awesome Personal Knowledge Management 🧠

> A high-quality curated list of Personal Knowledge Management (PKM) tools.
> Deeply researched. Organized by paradigm. Every entry verified. Updated June 2026.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

[English](README.md) | [中文](README.zh-CN.md)

---

## What Makes This List Different

Most "awesome" lists are link dumps. This one is a **curated research document**:
- Every tool personally evaluated against its paradigm, features, and pricing
- Organized by **thinking paradigm** (how you think), not feature checklist
- Includes a **comparison matrix** for quick decision-making
- Each entry explains **who the tool is for** and **who should avoid it**

---

## Table of Contents

- [Quick Decision Guide](#quick-decision-guide)
- [Comparison Matrix](#comparison-matrix)
- [AI-Powered PKM](#ai-powered-pkm)
- [Local-First / File-Based](#local-first--file-based)
- [Object & Structure-Based](#object--structure-based)
- [Visual & Spatial Thinking](#visual--spatial-thinking)
- [Open-Source AI Research Assistants](#open-source-ai-research-assistants)
- [Learning & Memorization](#learning--memorization)
- [Open Source PKM](#open-source-pkm)
- [Methodology & Further Reading](#methodology--further-reading)

---

## Quick Decision Guide

| You want to... | Use |
|---------------|------|
| Search across all your documents with AI | [NoteRich](#noterich), [NotebookLM](#notebooklm) |
| Own your data as plain text files forever | [Obsidian](#obsidian), [Logseq](#logseq) |
| Build a structured life OS with databases | [Notion](#notion), [AnyType](#anytype) |
| Think spatially on a visual canvas | [Heptabase](#heptabase), [Scrintal](#scrintal) |
| Remember what you learn (flashcards) | [RemNote](#remnote) |
| Use AI woven into every aspect of PKM | [Tana](#tana), [Mem](#mem) |
| Open source with no compromises | [Logseq](#logseq), [SiYuan](#siyuan) |
| Academic research & thesis writing | [NoteRich](#noterich), [Zettlr](#zettlr), [Heptabase](#heptabase) |
| Budget-friendly (free) | [Logseq](#logseq), [AnyType](#anytype), [SiYuan](#siyuan), [Foam](#foam) |
| AI research paper Q&A | [PaperQA2](#paperqa2), [STORM](#storm), [RAGFlow](#ragflow) |
| Chat with your documents privately (open source) | [AnythingLLM](#anythingllm), [PrivateGPT](#privategpt), [Kotaemon](#kotaemon) |
| Combine tasks with notes | [Amplenote](#amplenote) |
| Visual creative brainstorming | [Milanote](#milanote), [Heptabase](#heptabase) |
| [AnythingLLM](#anythingllm) | AI Doc Chat | ✅ RAG | ✅ | ✅ MIT | ✅ | Free |
| [PrivateGPT](#privategpt) | AI Doc Q&A | ✅ Local LLM | ✅ | ✅ Apache | ✅ | Free |
| [DocsGPT](#docsgpt) | Doc Assistant | ✅ OpenAI | ✅ | ✅ MIT | ✅ | Free |
| [Quivr](#quivr) | Second Brain AI | ✅ Multi | ✅ | ✅ Apache | ✅ | Free |
| [Kotaemon](#kotaemon) | RAG Doc QA | ✅ Local | ✅ | ✅ Apache | ✅ | Free |
| [Danswer](#danswer) | Enterprise Q&A | ✅ Multi | ✅ | ✅ MIT | ✅ | Free |
| [RAGFlow](#ragflow) | RAG Engine | ✅ Deep | ✅ | ✅ Apache | ✅ | Free |
| [PaperQA2](#paperqa2) | Academic QA | ✅ Agent | ✅ | ✅ Apache | ✅ | Free |
| [STORM](#storm) | Research Gen | ✅ LLM | ✅ | ✅ MIT | ✅ | Free |
| [GPT Researcher](#gpt-researcher) | Auto Research | ✅ Agent | ✅ | ✅ MIT | ✅ | Free |

| [TiddlyWiki](#tiddlywiki) | Personal Wiki | ❌ | ✅ | ✅ BSD | ✅ | Free |
| [Bear](#bear) | Apple Notes | ❌ | ✅ | ❌ | ✅ | $2.99/mo |
| [Craft](#craft) | Beautiful Docs | ✅ AI | ✅ | ❌ | ✅ | $10/mo |
| [Standard Notes](#standard-notes) | Encrypted Notes | ❌ | ✅ | ✅ AGPL | ✅ | $7.50/mo |
| [Joplin](#joplin) | Note + To-Do | ❌ | ✅ | ✅ AGPL | ✅ | Cloud $2.99/mo |
| Replace Notion with open source | [AppFlowy](#appflowy), [AFFiNE](#affine), [AnyType](#anytype) |
| Build a self-hosted knowledge base | [Trilium](#trilium-notes), [AFFiNE](#affine) |

---

## Comparison Matrix

| Tool | Paradigm | AI | Offline | Open Source | Free Tier | Price (Paid) |
|------|----------|-----|---------|-------------|-----------|--------------|
| [NoteRich](#noterich) | AI + Documents | ✅ RAG | ✅ | ❌ | ✅ | $39.90/yr |
| [NotebookLM](#notebooklm) | AI Research | ✅ Native | ❌ | ❌ | ✅ | Free |
| [Obsidian](#obsidian) | Local Markdown | Plugin | ✅ | ❌ | ✅ | Sync $4-8/mo |
| [Logseq](#logseq) | Outliner + Graph | Plugin | ✅ | ✅ AGPL | ✅ | Free |
| [Notion](#notion) | Block + Database | ✅ Add-on | ❌ | ❌ | ✅ | $10/mo |
| [Tana](#tana) | Supertags + AI | ✅ Deep | ❌ | ❌ | Limited | $8-14/mo |
| [Capacities](#capacities) | Object-Based | ✅ Pro | ✅ | ❌ | Limited | $10/mo |
| [AnyType](#anytype) | Local Workspace | ❌ | ✅ | ✅ | ✅ | Free (beta) |
| [Heptabase](#heptabase) | Visual Canvas | ✅ Tutor | ✅ | ❌ | ❌ | $8.99-17.99/mo |
| [Mem](#mem) | AI-Native | ✅ Core | ❌ | ❌ | ❌ | $14.99/mo |
| [Reflect](#reflect) | AI Journaling | ✅ GPT | ❌ | ❌ | ❌ | $10/mo |
| [RemNote](#remnote) | Learning + SRS | ✅ Tutor | Limited | ❌ | Limited | $8/mo |
| [Roam Research](#roam-research) | Outliner Pioneer | Limited | ❌ | ❌ | ❌ | $15/mo |
| [Scrintal](#scrintal) | Visual Canvas | ❌ | ❌ | ❌ | ❌ | Paid |
| [SiYuan](#siyuan) | Local + Block | ❌ | ✅ | ✅ AGPL | ✅ | Pro available |
| [Zettlr](#zettlr) | Academic Writing | ❌ | ✅ | ✅ GPL | ✅ | Free |
| [Foam](#foam) | VSCode-Based | ❌ | ✅ | ✅ | ✅ | Free |
| [Dendron](#dendron) | Hierarchical | ❌ | ✅ | ✅ | ✅ | Free |

---

## AI-Powered PKM

Tools where AI is a core part of the knowledge management experience — not just a sidebar chatbot.

### NoteRich

**Website:** [noterich.com](https://noterich.com)  
**Paradigm:** AI + Document-First  
**Pricing:** Free tier / PRO $39.90/year  
**Languages:** 41

NoteRich is an AI-powered note-taking app with **built-in RAG (Retrieval-Augmented Generation) search**. You import documents — PDFs, Word files, web pages — and ask questions in natural language. The AI searches across your entire knowledge base and returns answers with source citations.

**Strengths:**
- RAG search across 10,000+ documents
- Native UI in 41 languages — not just keyboard input
- Local storage with AES-GCM encryption
- OCR for scanned documents
- P2P sync without cloud dependency
- LaTeX math, Mermaid diagrams, ECharts support

**Best for:** Researchers managing large document collections, multilingual users, anyone who wants to *talk to their notes*.  
**Not for:** Real-time team collaboration, users who prefer folder-based organization.

---

### NotebookLM

**Website:** [notebooklm.google](https://notebooklm.google.com)  
**Paradigm:** AI Research Assistant  
**Pricing:** Free  
**Languages:** English (primary)

Google's AI-powered research and note-taking tool. Upload sources (PDFs, Google Docs, URLs, YouTube videos) and NotebookLM generates summaries, answers questions, and creates study guides — **strictly from your provided sources**, reducing hallucination risk.

**Strengths:**
- Source-grounded AI (only answers from your documents)
- Automatic FAQ, study guide, and briefing doc generation
- Audio overviews (AI-generated podcast-style discussions)
- Free, no usage limits
- Deep Google ecosystem integration

**Best for:** Students preparing for exams, researchers doing literature reviews, anyone who needs AI answers they can trust.  
**Not for:** General note-taking, long-form writing, offline use, non-English content.

---

### Mem

**Website:** [get.mem.ai](https://get.mem.ai)  
**Paradigm:** AI-Native Notes  
**Pricing:** $14.99/month  
**Languages:** English

Mem is built from the ground up with AI at its core. There are no folders, no manual organization — the AI automatically surfaces related notes, suggests connections, and helps you find information.

**Strengths:**
- Zero-effort organization — AI handles structure
- Semantic search across all notes
- AI chat that references your knowledge
- Clean, fast interface

**Best for:** Users who hate organizing notes and want AI to do it.  
**Not for:** Users who want file-based control, offline access, or budget options.

---

### Tana

**Website:** [tana.inc](https://tana.inc)  
**Paradigm:** Supertags + Outliner + AI  
**Pricing:** Free (limited) / Plus $8/mo / Pro $14/mo  
**Languages:** English

Built by ex-Roam engineers, Tana combines the flexibility of an outliner with structured **Supertags** — tags that automatically add properties, views, and behaviors to nodes. AI is deeply integrated for meeting processing, content extraction, and workflow automation.

**Strengths:**
- Supertags: the most powerful structuring system in PKM
- AI command nodes for workflow automation
- Live search queries as dynamic dashboards
- Google Calendar sync

**Best for:** Power users who want programmable structure, meeting-heavy professionals.  
**Not for:** Offline users, mobile-first users, budget-conscious users, quick onboarding.

---

### Reflect

**Website:** [reflect.app](https://reflect.app)  
**Paradigm:** AI Journaling + Notes  
**Pricing:** $10/month  
**Languages:** English

Reflect combines daily notes with GPT/Claude-powered AI search. You can ask questions about your past notes, and the AI finds relevant information — useful for tracking thoughts across time.

**Strengths:**
- AI search across your entire note history
- Daily notes as the central paradigm
- E2E encryption
- Voice notes via mobile

**Best for:** Daily journalers who want AI to surface past insights.  
**Not for:** Document-heavy workflows, users who need folders, non-English users.

---

## Local-First / File-Based

Tools that store your data as plain files on your device. You own your data, forever.

### Obsidian

**Website:** [obsidian.md](https://obsidian.md)  
**Paradigm:** Local Markdown + Graph  
**Pricing:** Free / Sync $4-8/mo / Publish $8/mo  
**Languages:** Community translations (30+)

The most popular local-first PKM tool. Notes are plain Markdown files on your disk. 2,500+ community plugins let you build almost any workflow — from daily notes to Zettelkasten to project management. The graph view visualizes connections between notes.

**Strengths:**
- Data sovereignty: plain Markdown files, you own everything
- Massive plugin ecosystem (2,500+)
- Graph view for visual knowledge mapping
- Canvas for spatial thinking
- Strong mobile app (improved in 2026)
- "Bases" feature: GUI database on top of YAML frontmatter

**Best for:** Power users who want a 20-year knowledge archive, plugin enthusiasts.  
**Not for:** Users who want AI out of the box, real-time collaboration, simple setup.

---

### Logseq

**Website:** [logseq.com](https://logseq.com)  
**Paradigm:** Open-Source Outliner + Journal  
**Pricing:** Free (AGPL-3.0)  
**Languages:** Community translations

A privacy-first, open-source knowledge base. Every line is a block that can be referenced anywhere. Journal-first design: each day gets a new page. Stores data as plain Markdown/Org files.

**Strengths:**
- Fully open source (AGPL-3.0)
- Block-level referencing — link to any bullet
- Journal-first workflow
- PDF annotation built in
- Flashcards for spaced repetition
- Database Edition (v0.10+) for large vaults

**Best for:** Open-source advocates, daily journalers, block-reference power users.  
**Not for:** Users who want polished mobile apps, real-time collaboration, AI-first experience.

---

### AnyType

**Website:** [anytype.io](https://anytype.io)  
**Paradigm:** Local-First Workspace  
**Pricing:** Free (beta)  
**Languages:** English, community translations

An open-source, local-first alternative to Notion. Build databases, wikis, and task managers with custom object types — everything works offline, encrypted, and synced P2P.

**Strengths:**
- Notion-like power with local-first privacy
- Custom object types and relations
- Multiple views (grid, gallery, board, list)
- Graph view for connections
- Open source, free during beta

**Best for:** Privacy-conscious Notion users, local-first advocates.  
**Not for:** Users who need polish and stability, cloud sync, integrations.

---

## Object & Structure-Based

Tools that organize knowledge through structured objects, databases, or typed entities.

### Notion

**Website:** [notion.so](https://notion.so)  
**Paradigm:** Block + Database + AI  
**Pricing:** Free / Plus $10/mo / Business $20/mo  
**Languages:** 20+

The all-in-one workspace. Notes, databases, wikis, calendars, and now AI workflows — all in one tool. The block-based editor lets you embed anything: tables, kanban boards, calendars, code, images.

**Strengths:**
- Best-in-class databases and collaboration
- Massive template ecosystem
- AI Workflows and Calendar integration (2026)
- Excellent mobile and desktop apps
- 100M+ users — huge community

**Best for:** Teams, project managers, anyone building a structured life OS.  
**Not for:** Users who need offline access, data portability, or open-source guarantees.

---

### Capacities

**Website:** [capacities.io](https://capacities.io)  
**Paradigm:** Object-Based PKM  
**Pricing:** Free (limited) / Pro $10/mo  
**Languages:** English

Instead of blank pages, Capacities asks: "What *type* of thing is this?" You create objects — `Book`, `Person`, `Meeting`, `Project` — each with its own properties. Beautiful, opinionated, and designed to be *used*, not configured.

**Strengths:**
- Polished, beautiful UI
- Object model that encourages structured thinking
- AI Assistant (Pro) that understands object context
- Strong mobile apps
- Gentle learning curve

**Best for:** Visual thinkers who want structure without tinkering, design-conscious users.  
**Not for:** Power users who want plugins, plain-text data, or open source.

---

## Visual & Spatial Thinking

Tools that let you *see* your knowledge on a canvas, mapping connections spatially.

### Heptabase

**Website:** [heptabase.com](https://heptabase.com)  
**Paradigm:** Visual Whiteboard + Cards  
**Pricing:** $8.99-17.99/month  
**Languages:** English, Chinese

Place note "cards" on an infinite whiteboard to visually map concepts. Deep PDF annotation. AI Tutor explains sources. A cult favorite among PhD students and researchers who need to see the big picture.

**Strengths:**
- Best visual whiteboard in PKM
- Deep PDF annotation with card extraction
- AI Tutor (2026) explains concepts from your sources
- Excellent for complex topic synthesis
- Offline-first, local storage

**Best for:** PhD students, researchers, visual/spatial thinkers.  
**Not for:** Quick capture, team collaboration, budget users.

---

### Scrintal

**Website:** [scrintal.com](https://scrintal.com)  
**Paradigm:** Visual Canvas + Cards  
**Pricing:** Paid  
**Languages:** English

Create boards, add note cards, and draw visual connections between ideas. Open multiple notes in floating tabs on a single canvas. Designed for the early stages of ideation and research synthesis.

**Strengths:**
- Visual card-based note mapping
- Multi-doc floating tab workflow
- Real backlinks between cards
- Clean, modern UI

**Best for:** Creative professionals, early-stage researchers, visual brainstormers.  
**Not for:** Task management, quick capture, mobile use.

---

### Roam Research

**Website:** [roamresearch.com](https://roamresearch.com)  
**Paradigm:** Outliner + Bidirectional Links  
**Pricing:** $15/month  
**Languages:** English

The pioneer of bidirectional linking in PKM. Every bullet is a node that can be referenced anywhere. Daily notes as the entry point. The tool that inspired Obsidian, Logseq, Tana, and many others.

**Strengths:**
- Pioneered bidirectional linking
- Block referencing — link to any bullet
- Daily notes workflow
- Strong query system

**Best for:** Users who want the original outliner PKM experience, Roam cult followers.  
**Not for:** Budget users (no free tier), offline-first users, users who want modern AI features.

---

## Learning & Memorization

### RemNote

**Website:** [remnote.com](https://remnote.com)  
**Paradigm:** Notes + Spaced Repetition  
**Pricing:** Free (limited) / Pro $8/month  
**Languages:** English

The only PKM tool purpose-built for learning. Turn any note into a flashcard with simple syntax (`Concept :: Definition`). Integrated spaced repetition schedules your review. PDF annotation with flashcard extraction.

**Strengths:**
- Unmatched flashcards-to-notes integration
- Spaced repetition built into the editor
- AI-generated questions and tutor (2026)
- PDF highlighting → flashcard pipeline

**Best for:** Students, lifelong learners, exam preparation.  
**Not for:** General project management, team collaboration, visual mapping.

---

## Open Source PKM

Tools with fully open codebases, community-driven development, and no vendor lock-in.

### SiYuan (思源笔记)

**Website:** [b3log.org/siyuan](https://b3log.org/siyuan)  
**Paradigm:** Local Block-Based  
**Pricing:** Free / Pro available  
**Languages:** Chinese, English

A powerful Chinese-developed PKM tool. Block-level referencing, local storage, rich text + Markdown hybrid editor. Strong community in China.

**Strengths:**
- Block-based editor with rich text
- Local-first, AGPL-3.0 licensed
- Strong Chinese language support
- Active development, frequent updates

**Best for:** Chinese-speaking users, block-editing fans, open-source advocates.  
**Not for:** Users who need English-first UX, cloud sync, AI features.

---

### Zettlr

**Website:** [zettlr.com](https://zettlr.com)  
**Paradigm:** Academic Markdown  
**Pricing:** Free (GPL)  
**Languages:** 30+

A Markdown editor designed for academic writing. Zettelkasten-friendly with Zotero integration for citation management. Write in Markdown, export to Word/LaTeX/PDF.

**Strengths:**
- Zotero citation integration
- Zettelkasten workflow support
- Export to multiple academic formats
- Free and open source

**Best for:** Academic writers, thesis students, Zettelkasten practitioners.  
**Not for:** Mobile use, non-academic users, AI features.

---

### Foam

**Website:** [foambubble.github.io](https://foambubble.github.io/foam)  
**Paradigm:** VSCode-Based PKM  
**Pricing:** Free (open source)  
**Languages:** English

A personal knowledge management system built on top of Visual Studio Code. Uses Markdown files, supports [[wiki-links]], graph visualization, and daily notes — all within your code editor.

**Strengths:**
- Works inside VSCode — no new app to install
- Git-friendly: your notes are a Git repo
- Extensible via VSCode extensions
- Free, open source

**Best for:** Developers who live in VSCode, Git-based workflow fans.  
**Not for:** Non-developers, mobile users, users who want a polished standalone app.

---

### Dendron

**Website:** [dendron.so](https://dendron.so)  
**Paradigm:** Hierarchical PKM  
**Pricing:** Free (open source)  
**Languages:** English

A hierarchical note-taking tool built on top of VSCode. Uses flexible hierarchies (e.g., `topic.subtopic.note`) to organize notes, with powerful lookup, refactoring, and graph features.

**Strengths:**
- Hierarchical organization with flexible schemas
- Powerful lookup and navigation
- Note refactoring (restructure without breaking links)
- VSCode integration

**Best for:** Developers, users with large structured knowledge bases.  
**Not for:** Visual thinkers, mobile users, users who dislike hierarchies.

---

| [Trilium Notes](#trilium-notes) | Hierarchical + Scripting | LLM Chat | ✅ | ✅ AGPL | ✅ | Free |
| [AFFiNE](#affine) | Docs + Canvas | ✅ Multi | ✅ | ✅ AGPL | ✅ | Free |
| [AppFlowy](#appflowy) | Block + Database | ✅ AI | ✅ | ✅ AGPL | ✅ | Free |
| [Supernotes](#supernotes) | Card-Based | ❌ | ✅ | ❌ | Limited | $8/mo |
| [Amplenote](#amplenote) | Task + Notes | ❌ | ✅ | ❌ | ✅ | $7.99/mo |
| [Milanote](#milanote) | Visual Board | ❌ | ❌ | ❌ | Limited | $12.50/mo |

---
---

## Open-Source AI Research Assistants

The open-source answer to NotebookLM — chat with your documents, ask questions, get AI-powered answers. All run locally or self-hosted.

### AnythingLLM

**Website:** [anythingllm.com](https://anythingllm.com)  
**Repository:** [Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm)  
**Paradigm:** Universal Document Chat  
**Pricing:** Free (MIT, open source) / Cloud from $25/mo  
**Languages:** English, multi-language UI

The most popular open-source document chat tool. Upload PDFs, Word docs, code, audio, videos, websites — then chat with them. Supports any LLM (OpenAI, Anthropic, local via Ollama, LMStudio). Full RAG pipeline with embedding, vector search, and citation.

**Strengths:**
- Universal document ingestion (50+ formats)
- Works with any LLM — cloud or local
- Built-in vector database (LanceDB)
- Multi-user with permissions
- Custom AI agents
- Desktop app (Mac/Windows/Linux)
- Active development, 30K+ GitHub stars

**Best for:** Users who want a polished, works-with-everything document chat.  
**Not for:** Users who need academic paper-specific features, enterprise SSO out of the box.

---

### PrivateGPT

**Website:** [privategpt.io](https://privategpt.io)  
**Repository:** [zylon-ai/private-gpt](https://github.com/zylon-ai/private-gpt)  
**Paradigm:** Private Document Q&A  
**Pricing:** Free (Apache 2.0)  
**Languages:** English, Spanish, French, German, and more

Production-ready, fully local document question-answering. All processing happens on your machine — no data leaves. Uses local embeddings and local LLMs. API-first design for integration.

**Strengths:**
- 100% local — no API calls, no data leaks
- Production-grade architecture
- REST API for integration
- Supports 50+ document formats
- Ingestion pipeline with chunking and embedding
- Active community

**Best for:** Privacy-critical environments, enterprise local deployment, regulated industries.  
**Not for:** Users who want cloud convenience, quick web-based setup.

---

### DocsGPT

**Website:** [docsgpt.co](https://docsgpt.co)  
**Repository:** [arc53/DocsGPT](https://github.com/arc53/DocsGPT)  
**Paradigm:** Documentation Assistant  
**Pricing:** Free (MIT)  
**Languages:** English

Open-source assistant purpose-built for technical documentation. Train on your docs, then users ask questions and get sourced answers. Designed for developer documentation portals.

**Strengths:**
- Purpose-built for documentation Q&A
- Source citations in answers
- Integrates with existing doc sites
- Docker deployment
- Chat history and feedback

**Best for:** Open source projects needing doc AI, developer portals, API documentation sites.  
**Not for:** General-purpose personal knowledge management, academic research.

---

### Quivr

**Website:** [quivr.app](https://quivr.app)  
**Repository:** [QuivrHQ/quivr](https://github.com/QuivrHQ/quivr)  
**Paradigm:** Second Brain AI  
**Pricing:** Free (Apache 2.0) / Cloud available  
**Languages:** English, French, Spanish

Upload anything — PDFs, code, websites, videos, audio — and build a personal AI knowledge base. ChatGPT-like interface that references your content. Multi-LLM support.

**Strengths:**
- Clean ChatGPT-like interface
- Upload any content, get AI answers
- Multi-LLM (OpenAI, Anthropic, Mistral, local)
- Knowledge base organization
- API for custom integrations
- 35K+ GitHub stars

**Best for:** Users wanting a personal AI knowledge base with a polished interface.  
**Not for:** Enterprise deployment, academic paper-specific workflows.

---

### Kotaemon

**Website:** [cinnamon.github.io/kotaemon](https://cinnamon.github.io/kotaemon)  
**Repository:** [Cinnamon/kotaemon](https://github.com/Cinnamon/kotaemon)  
**Paradigm:** RAG Document QA  
**Pricing:** Free (Apache 2.0)  
**Languages:** English, multi-language documents

An open-source, clean RAG-based tool for chatting with documents. Multi-user web interface. Supports local LLMs via Ollama, vLLM, and cloud APIs. Built-in PDF viewer with citation highlighting.

**Strengths:**
- Clean, Gradio-based web UI
- Multi-user support
- PDF viewer with citation highlight
- Local and cloud LLM support
- GraphRAG for complex reasoning
- Multi-modal (images in documents)

**Best for:** Teams wanting a self-hosted document QA tool, RAG experimentation.  
**Not for:** Users wanting mobile apps, non-technical setup.

---

### Danswer

**Website:** [danswer.ai](https://danswer.ai)  
**Repository:** [danswer-ai/danswer](https://github.com/danswer-ai/danswer)  
**Paradigm:** Enterprise Knowledge Q&A  
**Pricing:** Free (MIT) / Cloud available  
**Languages:** English

Unified search + AI Q&A across all your work tools. Connectors for Slack, GitHub, Google Drive, Confluence, Notion, and 25+ more. Ask questions in natural language and get answers backed by your organization's knowledge.

**Strengths:**
- 25+ native connectors (Slack, GitHub, Drive, Notion, etc.)
- Hybrid search (keyword + semantic)
- AI answers with source citations
- Role-based access control
- Analytics dashboard
- Self-hosted or cloud

**Best for:** Organizations wanting AI Q&A over internal knowledge, enterprise search.  
**Not for:** Individual PKM, small personal knowledge bases.

---

### RAGFlow

**Website:** [ragflow.io](https://ragflow.io)  
**Repository:** [infiniflow/ragflow](https://github.com/infiniflow/ragflow)  
**Paradigm:** Deep Document RAG Engine  
**Pricing:** Free (Apache 2.0)  
**Languages:** English, Chinese

An open-source RAG engine built on deep document understanding. Extracts knowledge from complex documents — tables, charts, layouts — not just text. Enterprise-grade document parsing pipeline.

**Strengths:**
- Deep document parsing (tables, charts, layouts)
- Intelligent chunking strategies
- Multi-model support (LLM + embedding)
- Enterprise RBAC
- Visual pipeline editor
- 25K+ GitHub stars

**Best for:** Organizations processing complex documents, enterprise RAG pipelines.  
**Not for:** Simple personal note Q&A, quick setup.

---

### PaperQA2

**Website:** [paperqa2.ai](https://paperqa2.ai)  
**Repository:** [Future-House/paper-qa](https://github.com/Future-House/paper-qa)  
**Paradigm:** Scientific Paper Q&A  
**Pricing:** Free (Apache 2.0)  
**Languages:** English

High-accuracy RAG specifically for scientific documents. Dynamically retrieves full-text papers, iterates on answers. Published at ICLR. Built by FutureHouse (biotech AI lab).

**Strengths:**
- Scientific paper-optimized RAG
- Dynamically retrieves full papers (not just chunks)
- Iterative answer refinement
- Citation-grounded responses
- Published at top AI conferences
- Agent-based research workflow

**Best for:** Scientists, researchers, academic literature review, evidence-based Q&A.  
**Not for:** General documents, non-academic content, quick personal notes.

---

### STORM

**Website:** [storm.genie.stanford.edu](https://storm.genie.stanford.edu)  
**Repository:** [stanford-oval/storm](https://github.com/stanford-oval/storm)  
**Paradigm:** Knowledge Curation System  
**Pricing:** Free (MIT)  
**Languages:** English

Stanford's LLM-powered system that generates Wikipedia-like articles from scratch. Researches a topic by searching the web, synthesizing information, and producing a structured, cited article. Co-STORM adds collaborative features.

**Strengths:**
- Generates full research articles with citations
- Multi-step research: question generation → search → synthesis
- Co-STORM for collaborative knowledge building
- Stanford OVAL research project
- Web interface and API

**Best for:** Researchers exploring new topics, educators creating learning materials, knowledge synthesis.  
**Not for:** Personal note-taking, real-time Q&A, document upload.

---

### GPT Researcher

**Website:** [gptr.dev](https://gptr.dev)  
**Repository:** [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher)  
**Paradigm:** Autonomous Research Agent  
**Pricing:** Free (MIT)  
**Languages:** English, multi-language

An autonomous agent for deep web and local research. Generates 5-6 page factual reports with citations in PDF, Docx, or Markdown. Multi-agent architecture for parallel research.

**Strengths:**
- Autonomous research report generation
- Multi-agent parallel research
- Web + local document search
- Export to PDF/Docx/Markdown
- Customizable research depth and breadth
- 15K+ GitHub stars

**Best for:** In-depth research on any topic, market research, competitive analysis.  
**Not for:** Quick document Q&A, personal note-taking, team collaboration.

---

## Team Knowledge Bases


## Team Knowledge Bases

Tools designed for team collaboration and shared knowledge — not just personal use.

### Outline

**Website:** [getoutline.com](https://getoutline.com)  
**Paradigm:** Team Wiki + AI  
**Pricing:** Free (self-hosted) / Cloud from $10/mo  
**Languages:** 20+

A fast, modern team wiki and knowledge base. Built with React and Node.js. Real-time collaboration, slash commands, nested collections, and markdown support. Claude/MCP AI integration for intelligent search.

**Strengths:**
- Fast, clean wiki interface
- Real-time collaborative editing
- AI-powered search with Claude integration
- Self-hosted option (open source)
- Slash command workflow
- OIDC/SAML SSO support

**Best for:** Teams needing a clean internal wiki, Confluence alternative.  
**Not for:** Personal PKM, offline-first users, visual thinkers.

---

### Docmost

**Website:** [docmost.com](https://docmost.com)  
**Paradigm:** Collaborative Documentation  
**Pricing:** Free (self-hosted) / Cloud available  
**Languages:** English

A modern collaborative wiki and documentation platform. Lightweight deployment (3 Docker containers). Real-time editing, granular permissions, inline comments, and page history.

**Strengths:**
- Lightest deployment of any team wiki
- Real-time collaborative editing
- Granular permissions and spaces
- Inline comments and page history
- Open source core

**Best for:** Small teams wanting a lightweight wiki, documentation-first workflows.  
**Not for:** Personal PKM, database-heavy workflows.

---

## Additional Tools

More PKM tools worth knowing — each with a unique angle.

### Supernotes

**Website:** [supernotes.app](https://supernotes.app)  
**Paradigm:** Card-Based Notes  
**Pricing:** Free (limited) / Pro $8/month  
**Languages:** English

A different take on notes: notecards instead of documents. Each note is a card with a character limit, encouraging atomic thinking. Cards can be tagged, linked, and organized into hierarchies. Strong collaboration features.

**Strengths:**
- Unique notecard format enforces conciseness
- Real-time collaboration on cards
- Tag-based organization
- Clean, fast interface
- Math (LaTeX) and code support

**Best for:** Students reviewing flashcards-style, teams sharing short-form knowledge, Twitter-like note-taking.  
**Not for:** Long-form writing, file attachments, offline-first.

---

### Amplenote

**Website:** [amplenote.com](https://amplenote.com)  
**Paradigm:** Task + Notes Fusion  
**Pricing:** Free / Pro $7.99/month  
**Languages:** English

Blends note-taking with task management. Notes can contain tasks that appear in a unified task view. Daily "Jots" for quick capture. Rich text editor with Markdown support.

**Strengths:**
- Unified task + notes workflow
- Task scoring prioritizes what to work on next
- Daily Jots for quick capture
- Web clipper for research
- Calendar integration

**Best for:** Users who want GTD-style task management inside their notes, project-oriented note-takers.  
**Not for:** Visual thinkers, AI-first users, users who separate tasks from knowledge.

---

### Milanote

**Website:** [milanote.com](https://milanote.com)  
**Paradigm:** Visual Mood Board + Notes  
**Pricing:** Free (limited) / Pro $12.50/month  
**Languages:** English

A visual tool for organizing creative projects. Think Pinterest meets notes — drag and drop images, links, text, and files onto infinite boards. Used widely by designers, filmmakers, and creative professionals.

**Strengths:**
- Beautiful visual board interface
- Drag-and-drop any content type
- Real-time collaboration
- Web clipper
- Mobile app with camera capture

**Best for:** Creative professionals, mood boards, visual project planning, design research.  
**Not for:** Text-heavy PKM, structured databases, offline use.

---

### Trilium Notes

**Website:** [triliumnotes.org](https://triliumnotes.org) (community fork: [TriliumNext](https://github.com/TriliumNext/Trilium))  
**Paradigm:** Hierarchical + Programmable  
**Pricing:** Free (AGPL-3.0)  
**Languages:** English, German, Spanish, French, Chinese, and more

One of the most powerful open-source PKM tools. Arbitrarily deep tree hierarchy with note cloning. Built-in Excalidraw, mind maps, geo maps, spreadsheets (2026), and OCR. JavaScript scripting for automation. Tested with 100,000+ notes.

**Strengths:**
- Unlimited hierarchy depth with note cloning
- Built-in OCR, spreadsheets, Excalidraw, mind maps, geo maps
- JavaScript scripting for custom automation
- Self-hosted sync server
- Per-note encryption
- Web clipper and REST API
- LLM chat integration (2026)

**Best for:** Self-hosters, power users who want programmability, large knowledge bases.  
**Not for:** Users wanting polished mobile apps, real-time collaboration, quick setup.

---

### AFFiNE

**Website:** [affine.pro](https://affine.pro)  
**Paradigm:** Docs + Infinite Canvas  
**Pricing:** Free (AGPL-3.0)  
**Languages:** English, Chinese

An ambitious open-source project combining documents and infinite canvas — think Notion + Miro in one tool. CRDT-based real-time collaboration. Multimodal AI copilot. Pre-1.0 but innovating fast.

**Strengths:**
- Unique Edgeless mode: switch between document and canvas
- CRDT-based real-time collaboration
- Multimodal AI (write, draw, mind-map, present)
- Self-hostable (3 Docker containers)
- Backlinks and synced blocks

**Best for:** Visual thinkers who code, early adopters, Notion + Miro combo users.  
**Not for:** Production-critical work, users who need stability, mobile-first users.

---



### Joplin

**Website:** [joplinapp.org](https://joplinapp.org)  
**Paradigm:** Open-Source Note + To-Do  
**Pricing:** Free (AGPL-3.0) / Cloud $2.99/mo  
**Languages:** 30+

One of the most popular open-source note apps with 50K+ GitHub stars. Markdown editor with rich text support. E2E encryption. Self-host or use Joplin Cloud for sync. Web clipper, mobile apps, and plugin system.

**Strengths:**
- Fully open source with massive community
- E2E encryption (opt-in)
- Self-hosted sync or Joplin Cloud
- Web clipper for research
- Mobile apps with offline support
- Plugin ecosystem
- Import from Evernote

**Best for:** Open source advocates, privacy-conscious users, cross-platform needs.  
**Not for:** AI-first features, visual canvas, real-time collaboration.

---

### Standard Notes

**Website:** [standardnotes.com](https://standardnotes.com)  
**Paradigm:** Encrypted Notes  
**Pricing:** Free / Productivity $7.50/mo / Professional $12/mo  
**Languages:** 30+

Privacy-first, encrypted note app. E2E encryption by default. Extensions for Markdown, spreadsheets, to-dos, and themes. Longevity-focused — designed to be used for decades.

**Strengths:**
- E2E encryption by default
- Longevity-first philosophy
- Extensions ecosystem (editors, themes)
- Cross-platform (Web, Mac, Windows, Linux, iOS, Android)
- Offline access
- Open source (AGPL-3.0)

**Best for:** Security-critical work, journalists, users who need encrypted longevity.  
**Not for:** AI features, visual mapping, database-style organization.

---

### Craft

**Website:** [craft.do](https://craft.do)  
**Paradigm:** Beautiful Documents  
**Pricing:** Free / Plus $10/mo / Business $20/mo  
**Languages:** English

Native Apple-first document app with stunning design. Block-based editor, inline images, cards, and page linking. Strong sharing and collaboration. Increasingly adding PKM features like backlinks.

**Strengths:**
- Gorgeous native UI (Apple Design Award)
- Block-based editing with rich media
- Strong sharing and publishing
- Backlinks and page linking
- Offline-first with sync
- Web, Mac, iOS, Windows

**Best for:** Design-conscious Apple users, beautiful document creation, team sharing.  
**Not for:** Open source advocates, graph-based navigation, budget users.

---

### Bear

**Website:** [bear.app](https://bear.app)  
**Paradigm:** Apple-First Writing  
**Pricing:** Free / Pro $2.99/month  
**Languages:** English, Chinese, Japanese, and more

Beloved Apple-ecosystem writing app. Clean Markdown editor with tagging system. Focus on beautiful writing experience over complex PKM features. Recently added backlinks and wiki links.

**Strengths:**
- Beautiful, focused writing experience
- Smart tagging system (nested tags)
- Apple ecosystem integration (iOS, Mac, Watch)
- Export to multiple formats
- Wiki links and backlinks (Bear 2)
- Affordable Pro pricing

**Best for:** Apple users who write, minimalists, quick note capture in a beautiful environment.  
**Not for:** Windows/Android users, database features, AI search.

---

### TiddlyWiki

**Website:** [tiddlywiki.com](https://tiddlywiki.com)  
**Paradigm:** Personal Wiki  
**Pricing:** Free (BSD)  
**Languages:** 30+

The original personal wiki — a single HTML file that contains everything. Each "tiddler" is a note card. Quirky, portable, and surprisingly powerful with macros, filters, and plugins. Active since 2004.

**Strengths:**
- Single HTML file — ultimate portability
- Rich macro and filter system
- Plugin ecosystem
- Works offline in any browser
- Node.js server version for advanced use
- Active community for 20+ years

**Best for:** Minimalist hackers, single-file portability fans, wiki-style note systems.  
**Not for:** Modern UI expectations, mobile apps, collaboration.

### AppFlowy

**Website:** [appflowy.io](https://appflowy.io)  
**Paradigm:** Open-Source Notion Alternative  
**Pricing:** Free (AGPL-3.0)  
**Languages:** English, community translations

The most polished open-source Notion alternative. Built with Flutter + Rust for native performance. Multiple database views (grid, kanban, calendar, gallery). AI meeting transcription. Notion importer.

**Strengths:**
- Fast native desktop and mobile (Flutter)
- Multiple database views (table, kanban, calendar, gallery, chart)
- AI meeting notes with speaker identification
- Notion import preserving databases
- Active development with stable releases

**Best for:** Notion users wanting open-source freedom, teams needing databases, meeting-heavy workflows.  
**Not for:** Visual canvas thinking, graph-based navigation, plain-text purists.

---

## Methodology & Further Reading


### What is Personal Knowledge Management?

PKM is the practice of capturing, organizing, and connecting information to turn it into lasting knowledge. Different tools embody different philosophies:

- **Zettelkasten (Luhmann):** Atomic notes connected by links. Tools: Obsidian, Logseq, Zettlr.
- **Second Brain (Forte):** PARA method — Projects, Areas, Resources, Archives. Tools: Notion, Capacities.
- **Digital Garden:** Public, evolving notes. Tools: Obsidian Publish, Logseq.
- **AI-Augmented PKM:** Let AI search, summarize, and connect. Tools: NoteRich, NotebookLM, Mem.

### Choosing Your Paradigm

The tool matters less than the thinking method. Before choosing, ask:
1. Do I want AI to help me find and connect information?
2. Do I need my data as plain files I control forever?
3. Am I a visual thinker or a text thinker?
4. Do I collaborate with others?

### Data Sources

All pricing, features, and language support verified against official websites as of June 2026. No affiliate links. No sponsored placements.

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Tools must be:
- Currently active and maintained
- Fit within a clear PKM paradigm
- Have verified pricing and feature claims

---

> **Maintained with real research. No fabricated comparisons.**
