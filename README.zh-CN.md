# Awesome Personal Knowledge Management 🧠 中文版

> 个人知识管理（PKM）工具精选列表。
> 按思维范式分类。深度调研。每个条目已验证。更新于 2026 年 6 月。

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

[English](README.md) | [中文](README.zh-CN.md)

---

## 本列表与众不同之处

大多数 awesome 列表只是链接堆砌。这份列表是一份**研究文档**：
- 每个工具都基于其范式、功能和定价进行了独立评估
- 按**思维范式**（你怎么思考）组织，而非功能清单
- 包含**对比矩阵**，助你快速决策
- 每个条目解释了**适合谁用**和**不适合谁用**

---

## 目录

- [快速决策指南](#快速决策指南)
- [对比矩阵](#对比矩阵)
- [AI 驱动型 PKM](#ai-驱动型-pkm)
- [本地优先 / 文件型](#本地优先--文件型)
- [对象与结构型](#对象与结构型)
- [视觉与空间思维型](#视觉与空间思维型)
- [开源 AI 研究助手](#开源-ai-研究助手)
- [学习与记忆型](#学习与记忆型)
- [开源 PKM](#开源-pkm)
- [方法论与延伸阅读](#方法论与延伸阅读)

---

## 快速决策指南

| 你想要… | 用什么 |
|---------|--------|
| 用 AI 搜索所有文档 | [NoteRich](#noterich)、[NotebookLM](#notebooklm) |
| 数据永久保存为纯文本文件 | [Obsidian](#obsidian)、[Logseq](#logseq) |
| 用数据库构建结构化的生活系统 | [Notion](#notion)、[AnyType](#anytype) |
| 在视觉画布上进行空间思考 | [Heptabase](#heptabase)、[Scrintal](#scrintal) |
| 记住你学到的东西（闪卡） | [RemNote](#remnote) |
| AI 深度融入知识管理各环节 | [Tana](#tana)、[Mem](#mem) |
| 完全开源不妥协 | [Logseq](#logseq)、[SiYuan](#siyuan) |
| 学术研究与论文写作 | [NoteRich](#noterich)、[Zettlr](#zettlr)、[Heptabase](#heptabase) |
| AI 论文问答与研究 | [PaperQA2](#paperqa2)、[STORM](#storm)、[RAGFlow](#ragflow) |
| 精美写作体验（Apple 生态） | [Craft](#craft)、[Bear](#bear) |
| 隐私优先加密笔记 | [Standard Notes](#standard-notes)、[AnyType](#anytype) |
| 开源且有精美移动端 | [Joplin](#joplin)、[AppFlowy](#appflowy) |
| 用开源工具与文档对话（隐私保护） | [AnythingLLM](#anythingllm)、[PrivateGPT](#privategpt)、[Kotaemon](#kotaemon) |
| 任务与笔记合一 | [Amplenote](#amplenote) |
| 视觉创意头脑风暴 | [Milanote](#milanote)、[Heptabase](#heptabase) |
| [AnythingLLM](#anythingllm) | AI 文档对话 | ✅ RAG | ✅ | ✅ MIT | ✅ | 免费 |
| [PrivateGPT](#privategpt) | AI 文档问答 | ✅ 本地 LLM | ✅ | ✅ Apache | ✅ | 免费 |
| [DocsGPT](#docsgpt) | 文档助手 | ✅ OpenAI | ✅ | ✅ MIT | ✅ | 免费 |
| [Quivr](#quivr) | 第二大脑 AI | ✅ 多模型 | ✅ | ✅ Apache | ✅ | 免费 |
| [Kotaemon](#kotaemon) | RAG 文档 QA | ✅ 本地 | ✅ | ✅ Apache | ✅ | 免费 |
| [Danswer](#danswer) | 企业问答 | ✅ 多模型 | ✅ | ✅ MIT | ✅ | 免费 |
| [RAGFlow](#ragflow) | RAG 引擎 | ✅ 深度 | ✅ | ✅ Apache | ✅ | 免费 |
| [PaperQA2](#paperqa2) | 学术 QA | ✅ Agent | ✅ | ✅ Apache | ✅ | 免费 |
| [STORM](#storm) | 研究生成 | ✅ LLM | ✅ | ✅ MIT | ✅ | 免费 |
| [GPT Researcher](#gpt-researcher) | 自动研究 | ✅ Agent | ✅ | ✅ MIT | ✅ | 免费 |

| [TiddlyWiki](#tiddlywiki) | 个人 Wiki | ❌ | ✅ | ✅ BSD | ✅ | 免费 |
| [Bear](#bear) | Apple 笔记 | ❌ | ✅ | ❌ | ✅ | $2.99/月 |
| [Craft](#craft) | 精美文档 | ✅ AI | ✅ | ❌ | ✅ | $10/月 |
| [Standard Notes](#standard-notes) | 加密笔记 | ❌ | ✅ | ✅ AGPL | ✅ | $7.50/月 |
| [Joplin](#joplin) | 笔记 + 待办 | ❌ | ✅ | ✅ AGPL | ✅ | 云同步 $2.99/月 |
| 用开源替代 Notion | [AppFlowy](#appflowy)、[AFFiNE](#affine)、[AnyType](#anytype) |
| 构建自托管知识库 | [Trilium](#trilium-notes)、[AFFiNE](#affine) |
| 预算友好（免费） | [Logseq](#logseq)、[AnyType](#anytype)、[SiYuan](#siyuan)、[Foam](#foam) |

---

## 对比矩阵

| 工具 | 范式 | AI | 离线 | 开源 | 免费套餐 | 付费价格 |
|------|----------|-----|---------|-------------|-----------|--------------|
| [NoteRich](#noterich) | AI + 文档 | ✅ RAG | ✅ | ❌ | ✅ | ¥288/年 |
| [NotebookLM](#notebooklm) | AI 研究 | ✅ 原生 | ❌ | ❌ | ✅ | 免费 |
| [Obsidian](#obsidian) | 本地 Markdown | 插件 | ✅ | ❌ | ✅ | 同步 $4-8/月 |
| [Logseq](#logseq) | 大纲 + 图谱 | 插件 | ✅ | ✅ AGPL | ✅ | 免费 |
| [Notion](#notion) | 块 + 数据库 | ✅ 附加 | ❌ | ❌ | ✅ | $10/月 |
| [Tana](#tana) | 超级标签 + AI | ✅ 深度 | ❌ | ❌ | 有限 | $8-14/月 |
| [Capacities](#capacities) | 对象型 | ✅ Pro | ✅ | ❌ | 有限 | $10/月 |
| [AnyType](#anytype) | 本地工作区 | ❌ | ✅ | ✅ | ✅ | 免费（测试期） |
| [Heptabase](#heptabase) | 视觉画布 | ✅ AI 导师 | ✅ | ❌ | ❌ | $8.99-17.99/月 |
| [Mem](#mem) | AI 原生 | ✅ 核心 | ❌ | ❌ | ❌ | $14.99/月 |
| [Reflect](#reflect) | AI 日记 | ✅ GPT | ❌ | ❌ | ❌ | $10/月 |
| [RemNote](#remnote) | 学习 + SRS | ✅ 导师 | 有限 | ❌ | 有限 | $8/月 |
| [Roam Research](#roam-research) | 大纲先驱 | 有限 | ❌ | ❌ | ❌ | $15/月 |
| [Scrintal](#scrintal) | 视觉画布 | ❌ | ❌ | ❌ | ❌ | 付费 |
| [SiYuan](#siyuan) | 本地 + 块 | ❌ | ✅ | ✅ AGPL | ✅ | 有 Pro 版 |
| [Zettlr](#zettlr) | 学术写作 | ❌ | ✅ | ✅ GPL | ✅ | 免费 |
| [Foam](#foam) | VSCode 集成 | ❌ | ✅ | ✅ | ✅ | 免费 |
| [Dendron](#dendron) | 层级结构 | ❌ | ✅ | ✅ | ✅ | 免费 |

---

## AI 驱动型 PKM

AI 是知识管理核心体验的工具 —— 而不仅仅是侧边栏聊天机器人。

### NoteRich

**官网：** [noterich.com](https://noterich.com)  
**范式：** AI + 文档优先  
**价格：** 免费套餐 / PRO ¥288/年  
**语言：** 41 种

NoteRich 是一款内置 **RAG（检索增强生成）搜索**的 AI 笔记工具。你可以导入文档——PDF、Word 文件、网页——然后用自然语言提问。AI 会搜索你的整个知识库，返回带来源引用的答案。

**优势：**
- 10,000+ 文档的 RAG 全库搜索
- 41 种语言的原生界面
- 本地存储 + AES-GCM 加密
- 扫描文档 OCR 识别
- P2P 同步，无需云端
- 支持 LaTeX 数学公式、Mermaid 流程图、ECharts 图表

**最适合：** 管理大量文档的研究者、多语言用户、想"和笔记对话"的人。  
**不适合：** 实时团队协作、偏好文件夹组织的用户。

---

### NotebookLM

**官网：** [notebooklm.google](https://notebooklm.google.com)  
**范式：** AI 研究助手  
**价格：** 免费  
**语言：** 英语为主

Google 的 AI 驱动研究与笔记工具。上传资料（PDF、Google Docs、URL、YouTube 视频），NotebookLM 会生成摘要、回答问题、创建学习指南——**严格基于你提供的来源**，降低幻觉风险。

**优势：**
- 来源锚定的 AI 回答（仅基于你的文档）
- 自动生成 FAQ、学习指南和简报文档
- 音频概览（AI 生成的播客式讨论）
- 免费、无使用限制
- 深度 Google 生态集成

**最适合：** 备考学生、做文献综述的研究者、需要可信 AI 回答的人。  
**不适合：** 通用笔记、长文写作、离线使用、非英语内容。

---

### Mem

**官网：** [get.mem.ai](https://get.mem.ai)  
**范式：** AI 原生笔记  
**价格：** $14.99/月  
**语言：** 英语

Mem 从底层就以 AI 为核心构建。没有文件夹，无需手动整理——AI 自动呈现相关笔记、建议关联、帮你查找信息。

**优势：**
- 零操作整理——AI 处理结构
- 全库语义搜索
- 引用你知识的 AI 对话
- 界面清爽快速

**最适合：** 讨厌整理笔记、想让 AI 代劳的用户。  
**不适合：** 想要文件控制权、离线访问或预算选项的用户。

---

### Tana

**官网：** [tana.inc](https://tana.inc)  
**范式：** 超级标签 + 大纲 + AI  
**价格：** 免费（有限）/ Plus $8/月 / Pro $14/月  
**语言：** 英语

由前 Roam 工程师打造，Tana 将大纲的灵活性与结构化**超级标签**（Supertags）结合——标签自动为节点添加属性、视图和行为。AI 深度集成，用于会议处理、内容提取和工作流自动化。

**优势：**
- 超级标签：PKM 领域最强大的结构化系统
- AI 指令节点实现工作流自动化
- 实时搜索查询作为动态仪表板
- Google Calendar 同步

**最适合：** 需要可编程结构的重度用户、会议密集的专业人士。  
**不适合：** 离线用户、移动优先用户、预算敏感用户、快速上手需求。

---

### Reflect

**官网：** [reflect.app](https://reflect.app)  
**范式：** AI 日记 + 笔记  
**价格：** $10/月  
**语言：** 英语

Reflect 将每日笔记与 GPT/Claude 驱动的 AI 搜索结合。你可以询问过去的笔记，AI 会找到相关信息——适合追踪跨时间的思考。

**优势：**
- AI 搜索整个笔记历史
- 每日笔记作为核心范式
- 端到端加密
- 移动端语音笔记

**最适合：** 每日写日记、希望 AI 呈现过往洞察的人。  
**不适合：** 文档密集工作流、需要文件夹的用户、非英语用户。

---

## 本地优先 / 文件型

数据以纯文件形式存储在你的设备上。你永远拥有自己的数据。

### Obsidian

**官网：** [obsidian.md](https://obsidian.md)  
**范式：** 本地 Markdown + 图谱  
**价格：** 免费 / 同步 $4-8/月 / 发布 $8/月  
**语言：** 社区翻译（30+）

最流行的本地优先 PKM 工具。笔记是磁盘上的纯 Markdown 文件。2,500+ 社区插件让你几乎可以构建任何工作流——从每日笔记到 Zettelkasten 到项目管理。图谱视图可视化笔记之间的连接。

**优势：**
- 数据主权：纯 Markdown 文件，你拥有一切
- 庞大的插件生态（2,500+）
- 图谱视图用于可视化知识连接
- Canvas 用于空间思维
- 2026 年改进的移动端体验
- Bases 功能：基于 YAML 的 GUI 数据库

**最适合：** 想建立 20 年知识档案的重度用户、插件爱好者。  
**不适合：** 想要开箱即用 AI、实时协作、简单设置的用户。

---

### Logseq

**官网：** [logseq.com](https://logseq.com)  
**范式：** 开源大纲 + 日记  
**价格：** 免费（AGPL-3.0）  
**语言：** 社区翻译

隐私优先的开源知识库。每一行是一个可被任意引用的块。日记优先设计：每天一个新页面。数据以纯 Markdown/Org 文件存储。

**优势：**
- 完全开源（AGPL-3.0）
- 块级引用——链接到任意要点
- 日记优先工作流
- 内置 PDF 批注
- 间隔重复闪卡
- 数据库版（v0.10+）提升大库性能

**最适合：** 开源拥护者、每日日记用户、块引用重度用户。  
**不适合：** 需要完善移动端、实时协作、AI 优先体验的用户。

---

### AnyType

**官网：** [anytype.io](https://anytype.io)  
**范式：** 本地优先工作区  
**价格：** 免费（测试期）  
**语言：** 英语、社区翻译

开源的本地优先 Notion 替代品。用自定义对象类型构建数据库、Wiki 和任务管理器——一切离线运行、加密、P2P 同步。

**优势：**
- Notion 般的强大功能 + 本地优先隐私保护
- 自定义对象类型和关系
- 多视图（网格、画廊、看板、列表）
- 连接图谱视图
- 开源，测试期间免费

**最适合：** 注重隐私的 Notion 用户、本地优先拥护者。  
**不适合：** 需要完善稳定体验、云同步、集成的用户。

---

## 对象与结构型

通过结构化对象、数据库或类型化实体组织知识的工具。

### Notion

**官网：** [notion.so](https://notion.so)  
**范式：** 块 + 数据库 + AI  
**价格：** 免费 / Plus $10/月 / 商务 $20/月  
**语言：** 20+

一体化工作空间。笔记、数据库、Wiki、日历，以及现在的 AI 工作流——全部在一个工具中。基于块的编辑器可以嵌入任何内容：表格、看板、日历、代码、图片。

**优势：**
- 一流的数据库和协作
- 庞大的模板生态
- 2026 年 AI 工作流和日历集成
- 优秀的移动和桌面端
- 1 亿+ 用户——庞大社区

**最适合：** 团队、项目经理、构建结构化生活系统的人。  
**不适合：** 需要离线访问、数据可移植性或开源保证的用户。

---

### Capacities

**官网：** [capacities.io](https://capacities.io)  
**范式：** 对象型 PKM  
**价格：** 免费（有限）/ Pro $10/月  
**语言：** 英语

不是空白页面，Capacities 会问："这是什么类型的东西？"你创建对象——`Book`、`Person`、`Meeting`、`Project`——每个都有各自的属性。精美、有立场、设计为使用而非配置。

**优势：**
- 精美优雅的界面
- 鼓励结构化思维的对象模型
- AI 助手（Pro）理解对象上下文
- 强大的移动端
- 平缓的学习曲线

**最适合：** 想要结构但不想折腾的视觉思考者、设计敏感的用户。  
**不适合：** 需要插件、纯文本数据或开源的重度用户。

---

## 视觉与空间思维型

让你在画布上"看见"知识的工具，空间化映射连接。

### Heptabase

**官网：** [heptabase.com](https://heptabase.com)  
**范式：** 视觉白板 + 卡片  
**价格：** $8.99-17.99/月  
**语言：** 英语、中文

在无限白板上放置笔记卡片，可视化映射概念。深度 PDF 批注。AI 导师解释来源。博士生和研究者中的口碑之选。

**优势：**
- PKM 中最佳的视觉白板
- 深度 PDF 批注与卡片提取
- AI 导师（2026）解释来源中的概念
- 优秀的复杂主题综合能力
- 离线优先、本地存储

**最适合：** 博士生、研究者、视觉/空间思考者。  
**不适合：** 快速记录、团队协作、预算有限的用户。

---

### Scrintal

**官网：** [scrintal.com](https://scrintal.com)  
**范式：** 视觉画布 + 卡片  
**价格：** 付费  
**语言：** 英语

创建画板、添加笔记卡片、在想法之间绘制视觉连接。在单张画布上以浮动标签页打开多个笔记。为构思和研究综合的早期阶段设计。

**优势：**
- 基于卡片的视觉笔记映射
- 多文档浮动标签页工作流
- 卡片间的真实反向链接
- 清爽现代界面

**最适合：** 创意专业人士、早期研究者、视觉头脑风暴者。  
**不适合：** 任务管理、快速记录、移动端使用。

---

### Roam Research

**官网：** [roamresearch.com](https://roamresearch.com)  
**范式：** 大纲 + 双向链接  
**价格：** $15/月  
**语言：** 英语

PKM 中双向链接的先驱。每个要点是一个可被任意引用的节点。每日笔记作为入口。启发 Obsidian、Logseq、Tana 等众多工具的开创者。

**优势：**
- 开创了双向链接
- 块引用——链接到任意要点
- 每日笔记工作流
- 强大的查询系统

**最适合：** 想要原始大纲 PKM 体验的用户、Roam 忠实粉丝。  
**不适合：** 预算用户（无免费套餐）、离线优先用户、需要现代 AI 功能的用户。

---

## 学习与记忆型

### RemNote

**官网：** [remnote.com](https://remnote.com)  
**范式：** 笔记 + 间隔重复  
**价格：** 免费（有限）/ Pro $8/月  
**语言：** 英语

唯一专为学习而构建的 PKM 工具。用简单语法将任意笔记转为闪卡（`概念 :: 定义`）。集成的间隔重复安排你的复习。PDF 批注可提取为闪卡。

**优势：**
- 无与伦比的闪卡-笔记集成
- 编辑器内置间隔重复
- AI 生成问题和导师（2026）
- PDF 高亮 → 闪卡流水线

**最适合：** 学生、终身学习者、备考。  
**不适合：** 通用项目管理、团队协作、视觉映射。

---

## 开源 PKM

完全开源代码库、社区驱动开发、无供应商锁定的工具。

### SiYuan（思源笔记）

**官网：** [b3log.org/siyuan](https://b3log.org/siyuan)  
**范式：** 本地块编辑器  
**价格：** 免费 / 有 Pro 版  
**语言：** 中文、英语

一款强大的国产 PKM 工具。块级引用、本地存储、富文本 + Markdown 混合编辑器。在中国拥有强大社区。

**优势：**
- 块式编辑器，支持富文本
- 本地优先，AGPL-3.0 许可
- 强大的中文支持
- 活跃开发，频繁更新

**最适合：** 中文用户、块编辑爱好者、开源拥护者。  
**不适合：** 需要英语优先体验、云同步、AI 功能的用户。

---

### Zettlr

**官网：** [zettlr.com](https://zettlr.com)  
**范式：** 学术 Markdown  
**价格：** 免费（GPL）  
**语言：** 30+

为学术写作设计的 Markdown 编辑器。Zettelkasten 友好，集成 Zotero 引用管理。用 Markdown 写作，导出为 Word/LaTeX/PDF。

**优势：**
- Zotero 引用集成
- Zettelkasten 工作流支持
- 导出为多种学术格式
- 免费开源

**最适合：** 学术写作者、论文学生、Zettelkasten 实践者。  
**不适合：** 移动端使用、非学术用户、AI 功能。

---

### Foam

**官网：** [foambubble.github.io](https://foambubble.github.io/foam)  
**范式：** VSCode 集成 PKM  
**价格：** 免费（开源）  
**语言：** 英语

基于 Visual Studio Code 构建的个人知识管理系统。使用 Markdown 文件，支持 [[wiki 链接]]、图谱可视化和每日笔记——全在代码编辑器内。

**优势：**
- 在 VSCode 内运行——无需安装新应用
- Git 友好：你的笔记是一个 Git 仓库
- 可通过 VSCode 扩展扩展
- 免费开源

**最适合：** 日常使用 VSCode 的开发者、基于 Git 的工作流爱好者。  
**不适合：** 非开发者、移动端用户、想要精美独立应用的用户。

---

### Dendron

**官网：** [dendron.so](https://dendron.so)  
**范式：** 层级结构 PKM  
**价格：** 免费（开源）  
**语言：** 英语

基于 VSCode 的层级笔记工具。使用灵活层级（如 `topic.subtopic.note`）组织笔记，具有强大的查找、重构和图谱功能。

**优势：**
- 灵活架构的层级组织
- 强大的查找和导航
- 笔记重构（重新组织而不破坏链接）
- VSCode 集成

**最适合：** 开发者、有大型结构化知识库的用户。  
**不适合：** 视觉思考者、移动端用户、不喜欢层级的用户。

---

| [Trilium Notes](#trilium-notes) | 层级 + 脚本 | LLM 对话 | ✅ | ✅ AGPL | ✅ | 免费 |
| [AFFiNE](#affine) | 文档 + 画布 | ✅ 多模态 | ✅ | ✅ AGPL | ✅ | 免费 |
| [AppFlowy](#appflowy) | 块 + 数据库 | ✅ AI | ✅ | ✅ AGPL | ✅ | 免费 |
| [Supernotes](#supernotes) | 卡片型 | ❌ | ✅ | ❌ | 有限 | $8/月 |
| [Amplenote](#amplenote) | 任务 + 笔记 | ❌ | ✅ | ❌ | ✅ | $7.99/月 |
| [Milanote](#milanote) | 视觉画板 | ❌ | ❌ | ❌ | 有限 | $12.50/月 |


---

---

## 开源 AI 研究助手

NotebookLM 的开源替代方案——与文档对话、提问、获得 AI 驱动的答案。全程本地运行或自托管。

### AnythingLLM

**官网：** [anythingllm.com](https://anythingllm.com)  
**仓库：** [Mintplex-Labs/anything-llm](https://github.com/Mintplex-Labs/anything-llm)  
**范式：** 通用文档对话  
**价格：** 免费（MIT 开源）/ 云端 $25/月起  
**语言：** 英语，多语言界面

最流行的开源文档对话工具。上传 PDF、Word、代码、音频、视频、网站——然后与它们对话。支持任何 LLM（OpenAI、Anthropic、本地 Ollama、LMStudio）。完整的 RAG 流程：嵌入、向量搜索和引用。

**优势：**
- 通用文档摄取（50+ 格式）
- 兼容任意 LLM——云端或本地
- 内置向量数据库（LanceDB）
- 多用户权限管理
- 自定义 AI 智能体
- 桌面应用（Mac/Windows/Linux）
- 活跃开发，GitHub 30K+ ⭐

**最适合：** 想要精致、全兼容文档对话工具的用户。  
**不适合：** 需要学术论文特定功能、企业 SSO 的用户。

---

### PrivateGPT

**官网：** [privategpt.io](https://privategpt.io)  
**仓库：** [zylon-ai/private-gpt](https://github.com/zylon-ai/private-gpt)  
**范式：** 隐私文档问答  
**价格：** 免费（Apache 2.0）  
**语言：** 英语、西班牙语、法语、德语等

生产就绪的完全本地文档问答。所有处理在你的机器上完成——数据不外泄。使用本地嵌入和本地 LLM。API 优先的集成设计。

**优势：**
- 100% 本地——无 API 调用，无数据泄露
- 生产级架构
- REST API 集成
- 支持 50+ 文档格式
- 完整的摄取流水线
- 活跃社区

**最适合：** 隐私关键环境、企业本地部署、受监管行业。  
**不适合：** 想要云端便捷性、快速 Web 设置的用户。

---

### DocsGPT

**官网：** [docsgpt.co](https://docsgpt.co)  
**仓库：** [arc53/DocsGPT](https://github.com/arc53/DocsGPT)  
**范式：** 文档助手  
**价格：** 免费（MIT）  
**语言：** 英语

专为技术文档构建的开源助手。基于你的文档训练，用户提问获得带来源的答案。为开发者文档门户设计。

**优势：**
- 专为文档问答构建
- 答案附带来源引用
- 集成现有文档站点
- Docker 部署
- 聊天历史和反馈

**最适合：** 需要文档 AI 的开源项目、开发者门户、API 文档站点。  
**不适合：** 通用个人知识管理、学术研究。

---

### Quivr

**官网：** [quivr.app](https://quivr.app)  
**仓库：** [QuivrHQ/quivr](https://github.com/QuivrHQ/quivr)  
**范式：** 第二大脑 AI  
**价格：** 免费（Apache 2.0）/ 云端可选  
**语言：** 英语、法语、西班牙语

上传任何内容——PDF、代码、网站、视频、音频——构建个人 AI 知识库。ChatGPT 式界面，引用你的内容。多 LLM 支持。

**优势：**
- 清爽的 ChatGPT 式界面
- 上传任意内容，获得 AI 回答
- 多 LLM（OpenAI、Anthropic、Mistral、本地）
- 知识库组织
- 自定义集成 API
- GitHub 35K+ ⭐

**最适合：** 想要精美界面的个人 AI 知识库用户。  
**不适合：** 企业部署、学术论文特定工作流。

---

### Kotaemon

**官网：** [cinnamon.github.io/kotaemon](https://cinnamon.github.io/kotaemon)  
**仓库：** [Cinnamon/kotaemon](https://github.com/Cinnamon/kotaemon)  
**范式：** RAG 文档问答  
**价格：** 免费（Apache 2.0）  
**语言：** 英语，多语言文档

开源、清爽的 RAG 文档对话工具。多用户 Web 界面。支持本地 LLM（Ollama、vLLM）和云端 API。内置 PDF 查看器，高亮引用来源。

**优势：**
- 清爽的 Gradio Web 界面
- 多用户支持
- PDF 查看器高亮引用
- 本地和云端 LLM 支持
- GraphRAG 复杂推理
- 多模态（文档中图片）

**最适合：** 想要自托管文档 QA 的团队、RAG 实验。  
**不适合：** 需要移动端、非技术设置的用户。

---

### Danswer

**官网：** [danswer.ai](https://danswer.ai)  
**仓库：** [danswer-ai/danswer](https://github.com/danswer-ai/danswer)  
**范式：** 企业知识问答  
**价格：** 免费（MIT）/ 云端可选  
**语言：** 英语

跨所有工作工具的统一搜索 + AI 问答。连接器覆盖 Slack、GitHub、Google Drive、Confluence、Notion 等 25+ 工具。用自然语言提问，获得基于组织知识的答案。

**优势：**
- 25+ 原生连接器（Slack、GitHub、Drive、Notion 等）
- 混合搜索（关键词 + 语义）
- AI 回答附带来源引用
- 基于角色的访问控制
- 分析仪表板
- 可自托管或云端

**最适合：** 需要内部知识 AI 问答的组织、企业搜索。  
**不适合：** 个人 PKM、小型个人知识库。

---

### RAGFlow

**官网：** [ragflow.io](https://ragflow.io)  
**仓库：** [infiniflow/ragflow](https://github.com/infiniflow/ragflow)  
**范式：** 深度文档 RAG 引擎  
**价格：** 免费（Apache 2.0）  
**语言：** 英语、中文

基于深度文档理解的开源 RAG 引擎。从复杂文档中提取知识——表格、图表、布局——而不仅仅是文本。企业级文档解析流水线。

**优势：**
- 深度文档解析（表格、图表、布局）
- 智能分块策略
- 多模型支持（LLM + 嵌入）
- 企业 RBAC
- 可视化流水线编辑器
- GitHub 25K+ ⭐

**最适合：** 处理复杂文档的组织、企业 RAG 流水线。  
**不适合：** 简单个人笔记问答、快速设置。

---

### PaperQA2

**官网：** [paperqa2.ai](https://paperqa2.ai)  
**仓库：** [Future-House/paper-qa](https://github.com/Future-House/paper-qa)  
**范式：** 科学论文问答  
**价格：** 免费（Apache 2.0）  
**语言：** 英语

专为科学文档设计的高精度 RAG。动态检索全文论文，迭代优化答案。发表于 ICLR。由 FutureHouse（生物技术 AI 实验室）构建。

**优势：**
- 科学论文优化 RAG
- 动态检索全文（非仅片段）
- 迭代答案优化
- 引用锚定的回答
- 顶级 AI 会议发表
- Agent 研究流程

**最适合：** 科学家、研究者、学术文献综述、循证问答。  
**不适合：** 通用文档、非学术内容、快速个人笔记。

---

### STORM

**官网：** [storm.genie.stanford.edu](https://storm.genie.stanford.edu)  
**仓库：** [stanford-oval/storm](https://github.com/stanford-oval/storm)  
**范式：** 知识策展系统  
**价格：** 免费（MIT）  
**语言：** 英语

斯坦福的 LLM 驱动知识策展系统，从头生成维基百科式文章。通过搜索网络、综合信息，产出结构化、带引用的文章。Co-STORM 增加了协作功能。

**优势：**
- 生成带引用的完整研究文章
- 多步研究：问题生成 → 搜索 → 综合
- Co-STORM 协作知识构建
- 斯坦福 OVAL 研究项目
- Web 界面和 API

**最适合：** 探索新主题的研究者、创建学习材料的教育者、知识综合。  
**不适合：** 个人笔记、实时问答、文档上传。

---

### GPT Researcher

**官网：** [gptr.dev](https://gptr.dev)  
**仓库：** [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher)  
**范式：** 自主研究智能体  
**价格：** 免费（MIT）  
**语言：** 英语，多语言

自主深度 Web 和本地研究智能体。生成 5-6 页带引用的事实性报告，支持 PDF/Docx/Markdown 导出。多智能体架构并行研究。

**优势：**
- 自主研究报告生成
- 多智能体并行研究
- Web + 本地文档搜索
- 导出 PDF/Docx/Markdown
- 可定制研究深度和广度
- GitHub 15K+ ⭐

**最适合：** 深度主题研究、市场调研、竞品分析。  
**不适合：** 快速文档问答、个人笔记、团队协作。

---

## 团队知识库


专为团队协作和共享知识设计的工具——不止于个人使用。

### Outline

**官网：** [getoutline.com](https://getoutline.com)  
**范式：** 团队 Wiki + AI  
**价格：** 免费（自托管）/ 云端 $10/月起  
**语言：** 20+

快速现代的团队 Wiki 和知识库。React + Node.js 构建。实时协作、斜杠命令、嵌套集合、Markdown 支持。Claude/MCP AI 集成用于智能搜索。

**优势：**
- 快速清爽的 Wiki 界面
- 实时协作编辑
- Claude 集成的 AI 搜索
- 可自托管（开源）
- 斜杠命令工作流
- OIDC/SAML SSO 支持

**最适合：** 需要清爽内部 Wiki 的团队、Confluence 替代方案。  
**不适合：** 个人 PKM、离线优先用户、视觉思考者。

---

### Docmost

**官网：** [docmost.com](https://docmost.com)  
**范式：** 协作文档  
**价格：** 免费（自托管）/ 云端可选  
**语言：** 英语

现代协作 Wiki 和文档平台。轻量部署（3 个 Docker 容器）。实时编辑、细粒度权限、行内评论和页面历史。

**优势：**
- 所有团队 Wiki 中最轻量的部署
- 实时协作编辑
- 细粒度权限和空间管理
- 行内评论和页面历史
- 开源核心

**最适合：** 需要轻量 Wiki 的小团队、文档优先的工作流。  
**不适合：** 个人 PKM、数据库密集型工作流。

---

## 更多工具

值得了解的更多 PKM 工具——各有独特角度。

### Supernotes

**官网：** [supernotes.app](https://supernotes.app)  
**范式：** 卡片型笔记  
**价格：** 免费（有限）/ Pro $8/月  
**语言：** 英语

与众不同的笔记方式：用卡片替代文档。每张卡片有字数限制，鼓励原子化思考。卡片可加标签、链接、组织成层级。强大的协作功能。

**优势：**
- 独特的卡片格式强制简洁
- 卡片实时协作
- 基于标签的组织
- 清爽快速的界面
- 支持数学公式（LaTeX）和代码

**最适合：** 复习闪卡式学习的学生、分享短知识的小团队、类 Twitter 的笔记方式。  
**不适合：** 长文写作、文件附件、离线优先。

---

### Amplenote

**官网：** [amplenote.com](https://amplenote.com)  
**范式：** 任务 + 笔记融合  
**价格：** 免费 / Pro $7.99/月  
**语言：** 英语

将笔记与任务管理融合。笔记中的任务会出现在统一任务视图中。每日 "Jots" 快速记录。富文本编辑器支持 Markdown。

**优势：**
- 统一的任务 + 笔记工作流
- 任务评分优先处理
- 每日 Jots 快速捕捉
- 网页剪藏用于研究
- 日历集成

**最适合：** 想要 GTD 风格任务管理的用户、项目导向的笔记者。  
**不适合：** 视觉思考者、AI 优先用户、想分离任务和知识的用户。

---

### Milanote

**官网：** [milanote.com](https://milanote.com)  
**范式：** 视觉灵感板 + 笔记  
**价格：** 免费（有限）/ Pro $12.50/月  
**语言：** 英语

组织创意项目的视觉工具。像 Pinterest 遇上笔记——在无限画板上拖放图片、链接、文本和文件。设计师、电影制作人和创意专业人士广泛使用。

**优势：**
- 精美的视觉画板界面
- 拖放任意内容类型
- 实时协作
- 网页剪藏
- 移动端相机捕捉

**最适合：** 创意专业人士、情绪板、视觉项目规划、设计研究。  
**不适合：** 文本密集型 PKM、结构化数据库、离线使用。

---

### Trilium Notes

**官网：** [triliumnotes.org](https://triliumnotes.org)（社区版：[TriliumNext](https://github.com/TriliumNext/Trilium)）  
**范式：** 层级 + 可编程  
**价格：** 免费（AGPL-3.0）  
**语言：** 英语、德语、西班牙语、法语、中文等

最强大的开源 PKM 工具之一。任意深度的树形层级结构，支持笔记克隆。内置 Excalidraw、思维导图、地理地图、电子表格（2026）和 OCR。JavaScript 脚本自动化。实测支持 100,000+ 笔记。

**优势：**
- 无限层级深度 + 笔记克隆
- 内置 OCR、电子表格、Excalidraw、思维导图、地理地图
- JavaScript 脚本自定义自动化
- 自托管同步服务器
- 单笔记加密
- 网页剪藏和 REST API
- LLM 对话集成（2026）

**最适合：** 自托管用户、需要可编程性的重度用户、大型知识库。  
**不适合：** 想要完善移动端的用户、实时协作、快速上手。

---

### AFFiNE

**官网：** [affine.pro](https://affine.pro)  
**范式：** 文档 + 无限画布  
**价格：** 免费（AGPL-3.0）  
**语言：** 英语、中文

雄心勃勃的开源项目，将文档和无限画布结合——相当于 Notion + Miro 合二为一。CRDT 驱动的实时协作。多模态 AI 助手。尚未发布 1.0 但创新速度极快。

**优势：**
- 独特的 Edgeless 模式：在文档和画布间切换
- CRDT 驱动的实时协作
- 多模态 AI（写作、绘图、思维导图、演示）
- 可自托管（3 个 Docker 容器）
- 反向链接和同步块

**最适合：** 会写代码的视觉思考者、早期采用者、需要 Notion + Miro 合体的用户。  
**不适合：** 生产关键工作、需要稳定性的用户、移动优先。

---

### AppFlowy

**官网：** [appflowy.io](https://appflowy.io)  
**范式：** 开源 Notion 替代  
**价格：** 免费（AGPL-3.0）  
**语言：** 英语、社区翻译

最精致的开源 Notion 替代品。Flutter + Rust 构建，原生性能。多种数据库视图（表格、看板、日历、画廊）。AI 会议转录。支持 Notion 导入。

**优势：**
- 快速原生桌面和移动端（Flutter）
- 多数据库视图（表格、看板、日历、画廊、图表）
- AI 会议笔记含说话人识别
- 保留数据库的 Notion 导入
- 活跃开发，稳定发布

**最适合：** 想要开源自由的 Notion 用户、需要数据库的团队、会议密集工作流。  
**不适合：** 视觉画布思考、图谱导航、纯文本纯粹主义者。

---



### Joplin

**官网：** [joplinapp.org](https://joplinapp.org)  
**范式：** 开源笔记 + 待办  
**价格：** 免费（AGPL-3.0）/ 云同步 $2.99/月  
**语言：** 30+

最受欢迎的开源笔记应用之一，GitHub 50K+ ⭐。Markdown 编辑器支持富文本。端到端加密。可自托管或使用 Joplin Cloud 同步。网页剪藏、移动端和插件系统。

**优势：**
- 完全开源，庞大社区
- 端到端加密（可选）
- 自托管同步或 Joplin Cloud
- 网页剪藏用于研究
- 移动端支持离线
- 插件生态
- 支持从 Evernote 导入

**最适合：** 开源拥护者、注重隐私的用户、跨平台需求。  
**不适合：** AI 优先功能、视觉画布、实时协作。

---

### Standard Notes

**官网：** [standardnotes.com](https://standardnotes.com)  
**范式：** 加密笔记  
**价格：** 免费 / Productivity $7.50/月 / Professional $12/月  
**语言：** 30+

隐私优先的加密笔记应用。默认端到端加密。支持 Markdown、电子表格、待办事项和主题扩展。注重长期使用——设计用于数十年跨度的使用。

**优势：**
- 默认端到端加密
- 长期主义理念
- 扩展生态（编辑器、主题）
- 跨平台（Web、Mac、Windows、Linux、iOS、Android）
- 离线访问
- 开源（AGPL-3.0）

**最适合：** 安全关键工作、记者、需要加密长期性的用户。  
**不适合：** AI 功能、视觉映射、数据库式组织。

---

### Craft

**官网：** [craft.do](https://craft.do)  
**范式：** 精美文档  
**价格：** 免费 / Plus $10/月 / Business $20/月  
**语言：** 英语

原生 Apple 优先的文档应用，设计惊艳。块式编辑器，支持内联图片、卡片和页面链接。强大的分享和协作功能。逐步增加反向链接等 PKM 特性。

**优势：**
- 精美原生界面（Apple 设计奖）
- 块式编辑 + 富媒体
- 强大的分享和发布
- 反向链接和页面链接
- 离线优先 + 同步
- Web、Mac、iOS、Windows

**最适合：** 设计敏感的 Apple 用户、精美文档创建、团队分享。  
**不适合：** 开源拥护者、图谱导航、预算用户。

---

### Bear

**官网：** [bear.app](https://bear.app)  
**范式：** Apple 优先写作  
**价格：** 免费 / Pro $2.99/月  
**语言：** 英语、中文、日语等

深受喜爱的 Apple 生态写作应用。清爽的 Markdown 编辑器配合标签系统。注重优美的写作体验而非复杂的 PKM 功能。Bear 2 新增了 Wiki 链接和反向链接。

**优势：**
- 优美、专注的写作体验
- 智能标签系统（嵌套标签）
- Apple 生态集成（iOS、Mac、Watch）
- 多格式导出
- Wiki 链接和反向链接（Bear 2）
- 亲民的 Pro 定价

**最适合：** Apple 写作用户、极简主义者、优美环境中的快速笔记。  
**不适合：** Windows/Android 用户、数据库功能、AI 搜索。

---

### TiddlyWiki

**官网：** [tiddlywiki.com](https://tiddlywiki.com)  
**范式：** 个人 Wiki  
**价格：** 免费（BSD）  
**语言：** 30+

原始的个人 Wiki——一个包含一切的 HTML 文件。每个"tiddler"是一张笔记卡片。古怪、便携、功能出奇强大，支持宏、过滤器和插件。自 2004 年活跃至今。

**优势：**
- 单个 HTML 文件——终极便携
- 丰富的宏和过滤系统
- 插件生态
- 任意浏览器离线使用
- Node.js 服务端版用于高级用途
- 20+ 年活跃社区

**最适合：** 极简黑客、单文件便携爱好者、Wiki 风格笔记系统。  
**不适合：** 现代 UI 期望、移动端应用、协作。

## 方法论与延伸阅读


### 什么是个人知识管理？

PKM 是捕获、组织和连接信息，将其转化为持久知识的实践。不同工具体现了不同哲学：

- **Zettelkasten（卢曼）：** 由链接连接的原子笔记。工具：Obsidian、Logseq、Zettlr。
- **第二大脑（Forte）：** PARA 方法——项目、领域、资源、归档。工具：Notion、Capacities。
- **数字花园：** 公开的、不断演化的笔记。工具：Obsidian Publish、Logseq。
- **AI 增强 PKM：** 让 AI 搜索、总结和连接。工具：NoteRich、NotebookLM、Mem。

### 选择你的范式

工具不如思维方法重要。选择前，问自己：
1. 我需要 AI 帮我发现和连接信息吗？
2. 我需要数据以纯文件形式永久受控吗？
3. 我是视觉思考者还是文本思考者？
4. 我需要与他人协作吗？

### 数据来源

所有价格、功能和语言支持均根据 2026 年 6 月官方信息验证。无推广链接。无付费位置。

---

## 贡献

参见 [CONTRIBUTING.md](CONTRIBUTING.md)。工具必须：
- 当前活跃并维护中
- 符合明确的 PKM 范式
- 具有经过验证的价格和功能声明

---

> **以真实研究维护。无虚假对比。**
