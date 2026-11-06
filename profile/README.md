<div align="center">

<img src="assets/banner.png" alt="NestLab Tech - a founder-led AI studio in Poland">

# NestLab Tech

**A founder-led AI studio in Poland. Four flagship SaaS products, one open-source project, AI automation services.**

<a href="https://nestlab.tech?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme"><img src="assets/badge-brand.svg" alt="NestLab Tech" height="28"></a>
<a href="https://nestlab.tech/book-a-call?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme"><img src="assets/badge-cta.svg" alt="Free 30-minute call" height="28"></a>

</div>

> NestLab Tech (nestlab.tech) is a founder-led AI studio operating from Poland (EU) since January 2025. It builds four flagship SaaS products, one public open-source project, and AI automation services for clients. Not to be confused with Nest Labs (the Google-owned smart-home brand), with NestLab S.R.L. in Romania, or with other unrelated uses of the same name: nestlab.eu (laboratory animal housing), nestlab.ro, nestlab.ca, nestlab.net, nestlabusa.com and nestlabdesign.com. Its GitHub organisation is NestLab-Tech.

[What we do](#what-we-do) · [The portfolio](#the-portfolio) · [How we work](#how-we-work) · [Open source](#open-source) · [Stack](#stack) · [Work with us](#work-with-us)

---

## What we do

Four ways to work with us. Each one starts with a few sentences about the problem.
Detail on [nestlab.tech/services](https://nestlab.tech/services?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme).

| Service | What it is |
|---|---|
| **AI workflow automation** | Lead routing and follow-up, document intake, reporting, internal alerts and approvals. Where a step needs judgement we add an LLM step with guardrails and a human-review path. |
| **Custom AI software development** | A production-ready first slice in four weeks: auth, one core flow, deployment, monitoring and backups wired from day one. Boring technology, no vendor lock-in. |
| **AI integration services** | Retrieval-augmented search, assistants and extraction added to software you already run, with evaluation and cost limits so the feature stays predictable. |
| **EU AI Act compliance** | We build and operate the [EU AI Act Scanner](https://nestlab.tech/products/euaigap), an automated assessment for Regulation 2024/1689, and apply the same method to client work. Preparation support, not legal advice. |

---

## The portfolio

Four products under our own brand, plus the open-source project they are built on.
Dated case studies on [nestlab.tech/work](https://nestlab.tech/work?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme).

| | Product | What it does | Status |
|---|---|---|---|
| <img src="assets/products/euaigap.svg" width="30" alt=""> | [**EU AI Act Scanner**](https://nestlab.tech/products/euaigap?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme) | Automated EU AI Act (Regulation 2024/1689) compliance assessment: 5-tier risk classification, 8-area scoring, 4 generated compliance documents. | Live |
| <img src="assets/products/propvectorai.svg" width="30" alt=""> | [**PropVector AI**](https://nestlab.tech/products/propvectorai?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme) | Commercial AI real-estate SaaS. ChromaDB vector search, MLS integration, 9 languages, ROI / CMA valuation, multi-year price forecast. In development. | In development |
| <img src="assets/products/checkcv.svg" width="30" alt=""> | [**CheckCV**](https://nestlab.tech/products/checkcv?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme) | Professional CV analysis for recruiting teams. Multi-format parsing, AI scoring, weighted rubric, candidate pipeline, white-label branding. In development. | In development |
| <img src="assets/products/tunecv.svg" width="30" alt=""> | [**TuneCV**](https://nestlab.tech/products/tunecv?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme) | AI-powered resume optimization for job seekers. ATS scoring, AI suggestions, cover-letter generation, interview prep, application tracker. In development. | In development |
| <img src="assets/products/openstore.svg" width="30" alt=""> | [**OpenStore**](https://nestlab.tech/products/openstore?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme) | Open-source AI real-estate search, MIT licensed. RAG with ChromaDB, 16 LLM providers, 9 languages. The open-source sibling of PropVector AI. | MIT |

---

## How we work

- **Fixed first milestone** — scoped and priced before kickoff, then written into the scope.
- **Founder-led delivery** — the person you contact stays with the work, from written scope through operation.
- **EU data residency by default** — product runtimes on our own infrastructure in Germany, France and Canada. DPA and subprocessor list published.
- **Daily written update, weekly call** — remote across the EU, based in Poland.

---

## Open source

The code we publish is the code we run. Every public repository, with its live demo where there is one.

The studio's published repositories live under the founder's account, AleksNeStu.

| Repository | What it is | Stars | Live |
|---|---|---|---|
| [**ai-real-estate-assistant**](https://github.com/AleksNeStu/ai-real-estate-assistant) | Open-source AI real estate search with RAG, vector search, multi-provider LLMs, FastAPI, Next.js, ChromaDB, and a live demo. | 321 | [open](https://realestate-web-dz1y.onrender.com/) |
| [**ai-news-scraper**](https://github.com/AleksNeStu/ai-news-scraper) | AI-powered news scraper with semantic search, RSS subscriptions, and AI-generated summaries. FastAPI + Next.js + ChromaDB monorepo. | 0 | [open](https://nestlab.tech?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme) |

**AleksNeStu/ai-real-estate-assistant** - 321 stars, 120 forks, MIT.

**AI-powered conversational platform for property search, analytics, and market insights.** Ask in natural language — *"2-bedroom apartment in Kraków under 500k"* — get matched listings. Try the live demo below, no signup needed.

Retrieval over 16 LLM providers behind one interface, in 9 languages.

[Live demo](https://realestate-web-dz1y.onrender.com/)

<img src="https://raw.githubusercontent.com/AleksNeStu/ai-real-estate-assistant/dev/assets/screenshots/home-dark.png" alt="OpenStore - property search" width="700">

---

## Stack

The stack the open-source project runs on, mirrored from its own Tech Stack table.

| Layer | Technology |
|---|---|
| Backend API | FastAPI (Python 3.12+) |
| Frontend | Next.js 16 + React 19 |
| Vector DB | ChromaDB (semantic search + MMR reranking) |
| Relational DB | PostgreSQL / SQLite |
| LLM Providers | OpenAI, Anthropic, Google, Grok, DeepSeek, OpenRouter, Together AI, Fireworks AI, HuggingFace, Groq, Mistral, Qwen, ZAI, Moonshot, OpenCode, local Ollama |
| Container | Docker / Docker Compose |
| Hosting (staging) | Render free tier |
| CI/CD | GitHub Actions (CI + GHCR + Render deploy) |
| Monitoring | Uptime Kuma + structured logs |

---
## Work with us

**Bring the real problem — we size it live.**

[Free 30-minute call](https://nestlab.tech/book-a-call?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme) &middot; [Start a project](https://nestlab.tech/contact?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme) &middot; [nestlab.tech](https://nestlab.tech?utm_source=github&utm_medium=referral&utm_campaign=product_showcase&utm_content=readme)

---
