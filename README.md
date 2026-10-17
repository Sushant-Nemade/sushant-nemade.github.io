# Sushant Nemade

<p align="left">
  <a href="https://sushant-nemade.github.io/"><img src="https://img.shields.io/badge/Live%20Portfolio-sushant--nemade.github.io-1f4fe0?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Live Portfolio" /></a>
  <a href="https://linkedin.com/in/sushant-nemade1998"><img src="https://img.shields.io/badge/LinkedIn-Sushant%20Nemade-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:sushantnemade15@gmail.com"><img src="https://img.shields.io/badge/Email-sushantnemade15%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Location-Erlangen%2C%20Germany-f2c230?style=for-the-badge&labelColor=000000" alt="Location" />
</p>

> **Data, AI & Digital Transformation Professional** based in Erlangen, Germany.  
> Translating ambiguous business problems into end-to-end, trustworthy AI solutions, scalable data architectures, and automated enterprise workflows.

---

## 🧭 Overview

Most of my work sits at the intersection of two critical spaces: **where data & retrieval pipelines are engineered**, and **where process owners decide whether to trust and adopt them**. 

I specialize in taking AI initiatives from problem scoping and architecture through prototyping, stakeholder alignment, compliance reviews (GDPR, permission models, Responsible AI), and production rollout.

Alongside enterprise and research work, I publish AI reference implementations, geospatial computer-vision research, privacy-first developer tools and product prototypes. The website features four flagship engineering systems and a categorized catalog of nineteen additional public projects, with implementation status, verification evidence and integration boundaries kept explicit.

- 💼 **Current Role:** Working Student in Data Analytics & Data Science at **Siemens Healthineers** (Erlangen)
- 🔬 **Previous Experience:** Software Development at **Fraunhofer IIS** | Programmer Analyst at **Cognizant**
- 🎓 **Education:** M.Sc. in Information and Communication Technology at **FAU Erlangen-Nürnberg** (Grade: 1.8)
- 🌐 **Interactive Portfolio:** [sushant-nemade.github.io](https://sushant-nemade.github.io/)

---

## ⚡ Core Competencies

```
  ┌─────────────────────────┐     ┌─────────────────────────┐     ┌─────────────────────────┐
  │   Enterprise GenAI/RAG  │     │   Data & Analytics BI   │     │  Automation & Strategy  │
  ├─────────────────────────┤     ├─────────────────────────┤     ├─────────────────────────┤
  │ Azure OpenAI & Copilot  │ ──► │ MS SQL, Snowflake & ETL │ ──► │ Power Apps & Automate   │
  │ Retrieval Pipelines     │     │ Power BI / DAX Insights │     │ Responsible AI & GDPR   │
  │ Python / PyTorch / ML   │     │ Data Quality Frameworks │     │ Build-vs-Adopt Strategy │
  └─────────────────────────┘     └─────────────────────────┘     └─────────────────────────┘
```

---

## 💼 Professional Experience

### **Siemens Healthineers** — *Working Student, Data Analytics & Data Science*
`March 2025 – Present` | *Erlangen, Germany*
- **Enterprise GenAI & RAG Solutions:** Spearheaded AI use cases on Azure OpenAI and Microsoft Copilot Studio from problem formulation to validated internal deployment.
- **Data Engineering & Modelling:** Integrated structured and unstructured data sources across MS SQL, Snowflake, SharePoint, and Python with automated freshness and data-quality checks.
- **Business Intelligence & Executive Reporting:** Designed scalable Power BI dashboards and executive KPI views for operational, financial, and implementation tracking.
- **Process Automation:** Built low-code enterprise applications via Power Apps and Power Automate to eliminate manual bottlenecks and establish human-in-the-loop review flows.
- **AI Governance:** Guided build-vs-adopt technical trade-offs, GDPR alignment, permission models, and Responsible AI guardrails.

### **Fraunhofer IIS** — *Working Student, Software Development*
`April 2024 – March 2025` | *Erlangen, Germany*
- **RAG & Retrieval Benchmarking:** Evaluated state-of-the-art RAG architectures for unstructured document intelligence across accuracy, latency, and maintainability.
- **MLOps & Experiment Tracking:** Transitioned exploratory machine learning models into reproducible, scheduled workflows using Python, MLflow, GitLab CI/CD, and structured pull-request reviews.
- **Requirement Engineering:** Translated complex supply-chain and research specifications into robust technical architectures.

### **Cognizant Technology Solutions** — *Programmer Analyst*
`December 2020 – June 2022` | *India*
- **Enterprise ERP & E-Commerce:** Managed end-to-end SAP e-commerce operations, incident triage, root-cause investigations, and change request implementations.
- **Data Analytics:** Engineered Python and Power BI operational reporting pipelines over ERP layers to uncover supply and transactional insights.
- **Workflow Optimization:** Automated recurring manual workflows using Power Platform solutions.

---

## Featured Engineering Systems

| Project | Stack | Engineering Evidence | Status |
|---|---|---|---|
| [Applied AI Systems Portfolio](https://github.com/Sushant-Nemade/applied-ai-systems-portfolio) | Python, FastAPI, Ollama, SQLite, Docker configuration | Eight workflows in one application; authentication, bounded inputs, source provenance, tests and CI. | Tested reference implementation; not a live production deployment. |
| [ForgeAI Production Engine](https://github.com/Sushant-Nemade/forgeai-production-engine) | Python, FastAPI, PostgreSQL, Pydantic, Prometheus/Grafana | Typed contracts, persisted state transitions, fail-closed QA, migrations and telemetry. | Production-oriented architecture; the developer agent produces endpoint plans, not arbitrary applications. |
| [Security Checker](https://github.com/Sushant-Nemade/security-checker) | TypeScript, SARIF, GitHub Actions integration | Local credential screening, redacted findings, CLI SARIF and a browser text-file scanner. | Working developer tool; findings are screening signals, not security guarantees. |
| [Subscription Auditor](https://github.com/Sushant-Nemade/subscription-auditor) | TypeScript, Next.js, CSV/PDF processing | Browser-local statement analysis, sample data and documented detector assumptions. | Tested local-first application; estimates require review and scanned PDFs need OCR. |

### Applied AI, Computer Vision & Multi-Agent Systems

| Project | Implemented Scope | Boundary |
|---|---|---|
| [Urban Change Detection & Change Captioning](https://github.com/Sushant-Nemade/urban-change-detection-captioning) *(Master's Thesis)* | Dual-head SegFormer MiT-B1 + Transformer MCI model for bi-temporal satellite road/building segmentation and change captioning on LEVIR-MCI (10,077 original and 15,115 augmented pairs), bidirectional temporal-reversal ($A \leftrightarrow B$) augmentation for removal/deconstruction cases, `urban-change` CLI, Streamlit workbench, FastAPI predictor, 31 pytest/integration checks and SHA-256 verified weights ([Model](https://huggingface.co/sushantnemade/MCI_augmented) · [Dataset](https://huggingface.co/datasets/sushantnemade/LEVIR-MCI-augmented) · [Validation](https://github.com/Sushant-Nemade/urban-change-detection-captioning/blob/main/docs/results.md)). | Research implementation for aligned 256×256 urban satellite pairs; CPU inference and numerical equivalence ($\le 3.81 \times 10^{-6}$) verified, while full-dataset benchmark reproduction, GPU/AMP training and mixed upstream licensing (MIT Change-Agent/COCO-caption plus NVIDIA non-commercial SegFormer terms) remain documented boundaries. |
| [AI Werewolf Arena](https://github.com/Sushant-Nemade/ai-werewolf-arena) | Seven-agent social deduction arena with per-seat information asymmetry, TF-IDF episodic RAG memory, fail-closed structured-output guardrails, decision tracing, 27 deterministic tests and a batch ELO simulator. | Session state is in-memory and the default mock provider is a deterministic heuristic baseline; live multi-round LLM benchmarking requires Ollama or OpenAI configuration. |
| [NeuroDrive](https://github.com/Sushant-Nemade/neurodrive) | Browser-based self-driving neuroevolution arena where 180 ray-cast sensor agents evolve 8→12→2 neural policies live via tournament selection, crossover and mutation in TypeScript and HTML5 Canvas with zero ML frameworks. | Client-side kinematic simulation with `localStorage` policy checkpointing and JSON export/import; not a photorealistic vehicle dynamics engine. |

### Responsible Automation

| Project | Implemented Scope | Boundary |
|---|---|---|
| [AI Receptionist](https://github.com/Sushant-Nemade/ai-receptionist) | Signed Twilio webhook routes, FAQ lookup and escalation boundaries. | Integration prototype; real phone, storage, AI and escalation flows remain unverified. |
| [WhatsApp Business Assistant](https://github.com/Sushant-Nemade/whatsapp-assistant) | Meta webhook verification, HMAC validation, intent routing and optional order lookup. | Simulator sends no real messages; deduplication is in-memory and booking is not implemented. |
| [AI Chief of Staff](https://github.com/Sushant-Nemade/ai-chief-of-staff) | Protected Calendar/Gmail briefing route and optional email delivery. | Fictional public data; durable OAuth is not implemented and scheduling requires configuration. |
| [Voice Note Idea Catcher](https://github.com/Sushant-Nemade/voice-note-idea-catcher) | Browser recording, transcript editing, rules-based action extraction and optional model endpoints. | No configured authentication or permanent server-backed note archive. |
| [AI Blog Publisher](https://github.com/Sushant-Nemade/ai-blog-publisher) | Attributed BlogBoard derivative with private drafts, Pydantic validation, digest-bound human approval, local staged publication and a DOMPurify-sanitized [public reader](https://sushant-nemade.github.io/ai-blog-publisher/). | Tested reference implementation ([release evidence](https://github.com/Sushant-Nemade/ai-blog-publisher/blob/main/docs/RELEASE_STATUS.md)); displayed article is a synthetic fixture and live Groq, search and R2 integrations remain unverified. |

### Data Applications and Developer Tools

| Project | Implemented Scope | Boundary |
|---|---|---|
| [Money Dashboard](https://github.com/Sushant-Nemade/money-dashboard) | Prisma/SQLite income records, protected APIs and integer-cent revenue aggregation. | Single admin token and fictional public samples; Stripe, Shopify and QuickBooks are not connected. |
| [GitPulse Audience Workspace](https://github.com/Sushant-Nemade/gitpulse) | Original SQLite/FastAPI GitHub audience tracker with atomic snapshots, numeric-ID rename safety, append-only relationship events, refollow-safe lost followers and a [sample dashboard](https://sushant-nemade.github.io/gitpulse/). | Tested reference implementation ([release evidence](https://github.com/Sushant-Nemade/gitpulse/blob/main/docs/RELEASE_STATUS.md)); one public REST sync verified, while hosted private API and unattended scheduling remain unconfigured. |
| [Market Insight](https://github.com/Sushant-Nemade/MarketInsight) | Attributed GPLv3 financial research workbench with source-dated Yahoo Finance statements/history, Chart.js views, owner-authenticated SQLite report history, optional grounded synthesis and a [synthetic reference](https://sushant-nemade.github.io/MarketInsight/) ([release](https://github.com/Sushant-Nemade/MarketInsight/releases/tag/v0.2.0-reference)). | 37 Python and 20 browser checks plus real AAPL quote/history smoke pass ([release evidence](https://github.com/Sushant-Nemade/MarketInsight/blob/main/docs/RELEASE_STATUS.md)); paid AI inference and managed private hosting remain unverified; research only, not investment advice. |
| [Doclify](https://github.com/Sushant-Nemade/Doclify) | Attributed AGPLv3 documentation CLI (`doclify-portfolio`) with bounded source discovery, SHA-256 incremental caching and digest-bound reviewed README publication ([reference release](https://github.com/Sushant-Nemade/Doclify/releases/tag/v0.3.0-reference)). | Offline structural workflows, wheel packaging and Linux/Windows CI pass ([release evidence](https://github.com/Sushant-Nemade/Doclify/blob/main/docs/RELEASE_STATUS.md)); live Groq inference remains unverified. |
| [Software Intake Gatekeeper](https://github.com/Sushant-Nemade/software-intake-gatekeeper) | Read-only binary and application intake CLI & GitHub Action (`v0.2.2`): CycloneDX 1.6 SBOM from Go, npm/ASAR and NuGet manifests, Electron fuse/webPreferences rules, opt-in OSV lookup, version-diff update gate and SARIF output ([PyPI](https://pypi.org/project/software-intake-gatekeeper/) · [Marketplace](https://github.com/marketplace/actions/software-intake-gatekeeper)). | 113+ tests and Linux/Windows/macOS live-OSV action runs pass; findings are version-level and configuration evidence, not exploit reachability analysis. |
| [Privacy Flow Inspector](https://github.com/Sushant-Nemade/privacy-flow-inspector) | Offline HAR privacy gate (`v0.2.0`): persona matching across raw/hashed/Base64 forms, checksum-verified IBAN/Steuer-ID/KVNR detectors, health-data fields, third-party eTLD+1 inventory, SARIF and self-checked redacted HAR export ([PyPI](https://pypi.org/project/privacy-flow-inspector/) · [Marketplace](https://github.com/marketplace/actions/privacy-flow-inspector)). | Cross-platform CI with real Chromium HAR re-recording passes; provides technical evidence for GDPR/privacy reviews, not legal advice. |

### Product Prototype Lab

| Project | Implemented Scope | Boundary |
|---|---|---|
| [Comment Idea Generator](https://github.com/Sushant-Nemade/comment-idea-generator) | Browser-local pasted-comment classification, content outlines and CSV/Markdown export. | No connected social ingestion, model clustering or Notion export. |
| [Creator Collab Matchmaker](https://github.com/Sushant-Nemade/creator-collab-matchmaker) | Deterministic profile ranking by niche, goals and audience proximity. | Fictional profiles and local-only requests; no configured accounts, embeddings or messaging. |
| [AI Trip Planner](https://github.com/Sushant-Nemade/ai-trip-planner) | Itineraries from entered places and day counts, with Maps search links. | No active image AI, geocoding, route optimization or bookings. |
| [Public Ship Log](https://github.com/Sushant-Nemade/public-ship-log) | Browser-local timeline editing and time-zone-aware shipping streaks. | No shared database, administrator identity or automatic social posting. |
| [Custom Link in Bio](https://github.com/Sushant-Nemade/link-in-bio) | Local themes, link ordering and click counts. | Browser-only editing; not a shared authenticated CMS. |

### Portfolio Engineering and Learning Archive

- [GitHub Profile Systems Console](https://github.com/Sushant-Nemade/Sushant-Nemade): generated profile assets and automation.
- [Interactive Portfolio Source](https://github.com/Sushant-Nemade/sushant-nemade.github.io): this HTML/CSS/JavaScript website.
- [AI Project Gallery](https://github.com/Sushant-Nemade/ai-project-gallery): categorized AI project catalog, upstream attribution and [pending-work register](https://github.com/Sushant-Nemade/ai-project-gallery/blob/main/docs/PROJECT_STATUS_AND_PENDING_WORK.md).
- [DSSS Homework 2](https://github.com/Sushant-Nemade/dsss_homework_2): earlier Python mathematics-quiz coursework.

The inventory was reviewed on **October 18, 2026**: twenty-three public project repositories and four supporting/learning repositories. Repository publication dates do not establish development duration. Temporary Cloudflare Quick Tunnels are not durable deployments; stable repository links and verified GitHub Pages references are used instead. Tests, integrations and production readiness are documented per repository rather than assumed across all projects.

## 🔬 Research & Professional Case Studies

| Project | Tech Stack | Highlights |
|---|---|---|
| **[Urban Change Detection & Change Captioning](https://github.com/Sushant-Nemade/urban-change-detection-captioning)** *(Master's Thesis — FAU & Fraunhofer IIS)* | `Python` `PyTorch` `SegFormer MiT-B1` `Transformer` `LEVIR-MCI` `Streamlit` `FastAPI` | Adapted the dual-head MCI vision-language model for joint road/building change segmentation and captioning across 10,077 original and 15,115 augmented satellite image pairs; engineered bidirectional temporal-reversal ($A \leftrightarrow B$) augmentation for removal/deconstruction scenarios, packaged a reproducible CLI/Streamlit/FastAPI workflow with 31 pytest checks and SHA-256 verified weights ([HF Model](https://huggingface.co/sushantnemade/MCI_augmented) · [HF Dataset](https://huggingface.co/datasets/sushantnemade/LEVIR-MCI-augmented)). |
| **Enterprise GenAI & Agentic Workflows** | `Azure OpenAI` `Copilot Studio` `Prompt Engineering` `Human-in-the-loop` | Formulated and evaluated agentic assistants and RAG architectures against value, feasibility, and enterprise governance criteria. |
| **Glottal Area Segmentation** | `PyTorch` `U-Net` `Medical Imaging` `BAGLS Benchmark` | Developed a reproducible deep learning segmentation pipeline evaluated pixel-wise against the BAGLS medical imaging dataset. |
| **Autonomous Vehicle Control** | `PyTorch` `ResNet18` `LSTM` `OpenAI Gym` | Created a vision-based sequential driving decision model combining spatial CNN representations with temporal LSTM memory in closed-loop simulation. |
| **Solar Panel Fault Classification** | `PyTorch` `ResNet50` `Computer Vision` | Fine-tuned deep CNN architectures to classify cracked and inactive photovoltaic cells for predictive maintenance. |
| **Visible Light Communication (VLC)** | `Embedded C` `ARM MCU` `PWM` `Hardware` | Implemented 4-bit optical data transmission over visible light using PWM modulation and timer input capture. |

---

## 🛠️ Technical Skills

### **Enterprise and Research Skills**
- **Generative AI & LLMs:** Azure OpenAI, Microsoft Copilot Studio, Retrieval-Augmented Generation (RAG), Embeddings, Vector Search, Prompt Engineering
- **Machine Learning & Vision:** PyTorch, scikit-learn, CNNs (ResNet), U-Net, LSTM, Model Evaluation & Benchmarking
- **Programming & Scripting:** Python (pandas, NumPy, openpyxl), SQL (MS SQL, PL/SQL), Git, Shell
- **Data Platforms & BI:** Snowflake, Microsoft SQL Server, SharePoint, Power BI, DAX, Data Modelling, ETL
- **Enterprise Automation:** Power Automate, Power Apps, Approval Workflows
- **Engineering & MLOps:** Git, GitLab CI/CD, MLflow, Experiment Tracking, Code Reviews

### **Public Project Engineering**
- **AI & Vision-Language Services:** FastAPI, Ollama, LangGraph, SegFormer MiT-B1, Transformer decoders, local inference, RAG evaluation and guardrails
- **Web & Interactive Visualization:** TypeScript, React, Next.js, Express, Chart.js, HTML5 Canvas and browser-local processing
- **Persistence & Caching:** PostgreSQL, SQLite, Prisma, Alembic migrations and SHA-256 content-addressed caching
- **System & Privacy Boundaries:** API authentication, signed webhooks, CycloneDX 1.6 SBOMs, SARIF code scanning, offline HAR privacy gates and fail-closed QA
- **Operations & Packaging:** Docker configuration, GitHub Actions, PEP 740 PyPI provenance attestations and Prometheus/Grafana telemetry

These technologies are represented in public project implementations. They are not blanket claims of production deployment or verified provider integration.

### **Strategic & Governance Competencies**
- **AI Governance:** GDPR, Responsible AI Frameworks, Permission Models, Guardrails, Human-in-the-loop Oversight
- **Strategy & Delivery:** Use-Case Discovery & Scoping, Build-vs-Adopt Analysis, Value Cases, Agile Delivery

---

## 🎓 Education & Certifications

- **M.Sc. Information and Communication Technology** — Friedrich-Alexander-Universität Erlangen-Nürnberg (*Grade: 1.8*)
  - *Master's Thesis:* [Urban Change Detection & Change Captioning](https://github.com/Sushant-Nemade/urban-change-detection-captioning) — Bi-temporal satellite vision-language modeling with temporal reversal augmentation
  - *Focus:* Advanced Deep Learning, Pattern Recognition, Signal Processing ML, Connected Mobility & Autonomous Driving
- **B.Eng. Electronics and Telecommunication Engineering** — Savitribai Phule Pune University (*Grade: 1.6*)
- **Certifications:**
  - *Deep Learning Specialization* — DeepLearning.AI
  - *Python Data Structures* — University of Michigan
  - *Core Java & SQL/PL-SQL* — Cognizant Academy
  - *Raspberry Pi Essential Training for IoT* — LinkedIn Learning

---

## 💻 About the Live Portfolio Website

The portfolio at [sushant-nemade.github.io](https://sushant-nemade.github.io/) combines a static project showcase with the existing **interactive terminal interface**:

- **No framework or build step:** HTML, CSS and JavaScript remain in [index.html](index.html), with four local WebP evidence images. The Archivo and JetBrains Mono fonts are self-hosted in [assets/fonts](assets/fonts) under the SIL Open Font License 1.1, so the page makes no third-party requests.
- **Canonical project content:** Four featured articles and nineteen categorized project entries are ordinary semantic HTML. Terminal project output and the selected resume use this same markup, avoiding a separately maintained project dataset.
- **Interactive Terminal Shell:** Supports `about`, `work`, `projects`, `research`, `github`, `skills`, `education`, `contact`, `help`, `resume` and `clear`.
- **Content separation:** `projects` contains the twenty-three public engineering, research and product repositories; `research` preserves all six research and professional case studies (with direct repository and Hugging Face links for the published Master's thesis); `github` includes all twenty-seven public repository links.
- **Selected resume:** The plain-text export includes four featured public projects with repository URLs, all six research/professional case studies (including the Master's thesis repository and artifact links) and the existing professional sections. Smaller prototypes stay in the website catalog rather than the default resume.
- **Productivity & Accessibility:**
  - Tab auto-completion and command history recall (Up/Down arrow keys)
  - Interactive line highlighting with keyboard navigation
  - Instant plain-text resume download generation via client-side Blob API
  - Responsive desktop/mobile layouts, bounded terminal scrolling and visible keyboard focus
  - Native expandable case-study/scope details and reduced-motion support
  - All twenty-three project articles and their repository links remain readable without JavaScript; terminal commands require JavaScript

Open [index.html](index.html) directly in a browser. No local server, runtime GitHub API calls or provider keys are required. Preserve the relative `assets/projects` directory when publishing to GitHub Pages.

### Visual Evidence

The images are local captures of committed source/interfaces/documentation, created on October 1, 2026. They are not photographs of production deployments. The temporary preview domains were unavailable at capture time.

| Local Asset | Source and Capture Scope |
|---|---|
| [Applied AI](assets/projects/applied-ai.webp) | [Committed dashboard HTML](https://github.com/Sushant-Nemade/applied-ai-systems-portfolio/blob/main/src/ai_portfolio/static/index.html), rendered without a connected API or fabricated model response. |
| [ForgeAI](assets/projects/forgeai.webp) | [Actual State enum](https://github.com/Sushant-Nemade/forgeai-production-engine/blob/main/core_engine/orchestrator.py), parsed from source and rendered as a source excerpt. |
| [Security Checker](assets/projects/security-checker.webp) | [Committed browser scanner](https://github.com/Sushant-Nemade/security-checker/blob/main/web/index.html), executed against a clearly named synthetic placeholder file; no real secret or private file was used. |
| [Subscription Auditor](assets/projects/subscription-auditor.webp) | [README processing/limit excerpts](https://github.com/Sushant-Nemade/subscription-auditor/blob/main/README.md), rendered as documentation, not an invented dashboard. |

---

## 📬 Get in Touch

- 🌐 **Portfolio Website:** [sushant-nemade.github.io](https://sushant-nemade.github.io/)
- 💼 **LinkedIn:** [linkedin.com/in/sushant-nemade1998](https://linkedin.com/in/sushant-nemade1998)
- **GitHub:** [github.com/Sushant-Nemade](https://github.com/Sushant-Nemade)
- ✉️ **Email:** [sushantnemade15@gmail.com](mailto:sushantnemade15@gmail.com)
- 📍 **Location:** Erlangen, Bavaria, Germany
- 🗣️ **Languages:** English (C1), German (B1–B2), Hindi, Marathi

---
<p align="center"><sub>Designed and maintained by Sushant Nemade © 2026</sub></p>
