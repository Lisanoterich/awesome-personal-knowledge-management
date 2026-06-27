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
