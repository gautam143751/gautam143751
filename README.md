# Gotham · Product Manager & 0→1 App Builder

> I turn ambiguous problems into shipped products — fast.

---

## 🧭 Who I Am

I'm a **product manager who builds**. I work across the full arc from discovery to delivery: framing the right problem, making fast architecture decisions, writing real code, and shipping systems that work in production.

My edge is operating at the intersection of **product thinking and hands-on execution** — the person who writes the PRD on Monday and ships the working MVP by Friday.

📍 London, UK · 

[![GitHub](https://img.shields.io/badge/GitHub-gautam143751-181717?style=flat&logo=github)](https://github.com/gautam143751)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Add_Your_URL-0077B5?style=flat&logo=linkedin)](ADD_LINKEDIN_URL)

---

## ⚡ Core Stack

| Capability | Proof |
|---|---|
| **Product discovery & definition** | Problem framing, user journey mapping, success metrics, scope control |
| **0→1 building** | Rapid prototyping → testable MVP → launch-ready system |
| **AI-native product design** | Retrieval systems, LLM pipelines, document intelligence, multi-agent workflows |
| **Developer tooling** | CLI design, API abstraction layers, Git extensions |
| **Evaluation system design** | Ground-truth dataset creation, multi-provider benchmarking, quality metrics |
| **Self-starter execution** | Moves from idea → architecture → docs → tests → delivery independently |

---

## 🏗️ Build Evidence

### 🔎 WebSearchEval (Webscope) — Search API Evaluation Platform
**[→ gautam143751/WebSearchEval](https://github.com/gautam143751/WebSearchEval)**

**The product problem:** Choosing between web search API providers is guesswork without a structured evaluation harness. Teams waste weeks of integration time on the wrong provider.

**What I built:**
- Full-stack evaluation app (Vite frontend + FastAPI backend) for running Mirascope-style web search evaluations across **multiple providers simultaneously**
- Provider abstraction layer — swap or add providers without touching core evaluation logic
- Run history and provider configs persisted in local SQLite (`backend/data/webscope.db`)
- API keys scoped to browser localStorage only — zero server-side credential exposure
- 75-question evaluation dataset spanning 11 domains: ETFs, mutual funds, earnings data, health/biomedical, economic statistics, government spending, and more

**Why it matters as a PM signal:** This is a full product built to solve a real evaluation bottleneck. Defined the domain taxonomy, designed the dataset ground-truth methodology, and shipped the tool — start to finish. That's product ownership, not just execution.

**Stack:** Python 62% · JavaScript 32% · CSS · HTML

---

### 💳 creditExtract — Credit Data Extraction System
**[→ gautam143751/creditExtract](https://github.com/gautam143751/creditExtract)**

**The product problem:** Credit and financial documents are among the most information-dense and poorly structured document types — yet accurate extraction from them drives lending, risk, and compliance decisions.

**What I built:**
- Structured extraction pipeline targeting credit-specific document formats
- Designed to handle the ambiguity and variance in real-world financial documents
- Part of a broader pattern of building data extraction systems that close the gap between messy source material and clean, actionable records

**Why it matters as a PM signal:** Taking on financial data extraction — a domain with high accuracy requirements and real downstream consequences — shows product maturity and domain depth beyond generic AI demos.

---


### 🔬 DocVQA — Document Intelligence CLI
**[→ gautam143751/DocvQA](https://github.com/gautam143751/DocvQA)**

**The product problem:** Enterprise workflows drown in unstructured documents. Extracting structured data consistently and cheaply is unsolved for most teams.

**What I built:**
- CLI-first system for repeatable document question-answering at scale
- Provider abstraction layer (`llm` vs `document_ai`) to avoid vendor lock-in from day one
- Storage abstraction (Firestore or local JSON) so it runs in production *and* offline dev
- Full test suite: `tests/config`, `tests/data`, `tests/evaluation`, `tests/extractors`, `tests/pipeline`
- Operational docs covering dataset prep, configuration, and evaluation methodology

**Why it matters as a PM signal:** Every architecture decision here is a *product decision* — I chose extensibility and testability over speed-to-hack. That's 0→1 thinking, not just coding.

---

### 🤖 git-ai — AI Code Provenance for Real Teams
**[→ gautam143751/git-ai](https://github.com/gautam143751/git-ai)** *(forked from git-ai-project/git-ai, actively maintained)*

**The product problem:** As AI-generated code proliferates in real teams, there is no lightweight standard for tracking *which code was AI-assisted*. This matters for audits, IP, and quality control.

**My contribution:**
- Active maintenance and merged updates on the forked codebase (Rust)
- Product lens applied: AI governance, developer workflow integration, minimal friction adoption

**Why it matters as a PM signal:** Identifying a real, underserved problem in developer tooling and shipping a working solution is the definition of product-market fit thinking.

---

### 📊 DataAnalysis-LLM — Multi-Agent Research Workflow
**[→ gautam143751/DataAnalysis-LLM](https://github.com/gautam143751/DataAnalysis-LLM)** *(adapted from upstream)*

**Focus:** Multi-agent orchestration for analysis, visualization, and automated report generation.

**Product lens applied:**
- Designed the orchestration layer and quality-review loop
- Evaluated agent specialization vs. general-purpose routing trade-offs

*Note: Repository contains significant upstream authorship. Represented here as adaptation and product exploration, not greenfield ownership.*

---


### 🍎 Calorie — Mobile Consumer App
**[→ gautam143751/Calorie](https://github.com/gautam143751/Calorie)**

Consumer-facing app — evidence of end-to-end product thinking beyond developer tooling. Demonstrates UX sensitivity and the ability to build for non-technical end users.

---

## 🔁 My 0→1 Playbook

```
1. Define the user pain and the success metric (speed / quality / cost / adoption)
2. Build the thinnest testable MVP with clean interfaces
3. Instrument the workflow and collect real usage signals
4. Iterate on reliability, UX, and operational efficiency
5. Document for handoff or scale
```

This isn't a methodology I read about. It's how every repo above was built.

---

## 📐 Product Operating Principles

- **Start from user value, not feature volume**
- **Ship the smallest useful version fast** — learning beats planning
- **Prefer measurable outcomes** over vague output
- **Be explicit about trade-offs and ownership** (see attribution notes above)
- **Architecture = product decisions** — every abstraction choice has a user consequence

---

## 🎯 Current Focus Areas

- AI-native product workflows and retrieval systems
- Document understanding and structured extraction
- Developer productivity tooling
- 0→1 product builds in AI infrastructure

---

## 📬 Collaboration

I'm open to roles and projects where I own the full arc — from problem to shipped product.

- **GitHub:** [gautam143751](https://github.com/gautam143751)
- **LinkedIn:** [Add Your URL]
- **Email:** [Add Your Email]

---

## 📊 GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=gautam143751&show_icons=true&theme=default&hide_border=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=gautam143751&layout=compact&hide_border=true)

---

