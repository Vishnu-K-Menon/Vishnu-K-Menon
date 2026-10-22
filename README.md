<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/bento-dark.svg" />
  <img src="./assets/bento-light.svg" alt="Vishnu Krishnakumar Menon: AI/ML Engineer" width="100%" />
</picture>

## ✦ Selected work

| Project | What it does | Impact | Stack |
|---------|-------------|--------|-------|
| **LEDGER** | Self-verifying RAG system that decomposes answers into atomic claims, checks each against source evidence, and rewrites unsupported statements | Raised table-cell accuracy from **30.5%** to **100%**; **223** automated tests in CI | Docling, OpenTelemetry, Arize Phoenix, AWS EC2 |
| **TheraMind** | Fine-tuned from Llama 3.2-3B with ChromaDB-based RAG | Improved ROUGE-L from **0.40** to **0.78** in **19.5 minutes** on RTX 4090 using QLoRA and DPO on **9,250** dialogues | Llama 3.2-3B, QLoRA, DPO, ChromaDB, FastAPI, Docker |
| **agentops-sentinel** | Supervisor/critique agent framework for support-ticket triage | Reliable, cost-bounded triage with OpenTelemetry tracing | LangGraph, FastAPI, Redis, OpenTelemetry, Python |
| **driftguard-llm** | Automated regression detection for RAG and LLM quality before production deployment | Catches silent quality regressions in CI/CD | Python, MLflow, Prometheus |
| **agentgate** | API gateway for LLM agents with per-agent auth, scoped permissions, spend/rate limits, and audit logs | Safe internal API exposure for agentic AI | FastAPI, PostgreSQL, Redis, OpenTelemetry, Docker |
| **advanced-rag-llm-app** | End-to-end RAG application combining vector search, document ingestion, prompt orchestration, and LLM APIs | Internship-level implementation of production RAG patterns | Python, FastAPI, Docker |

<details>
<summary>LEDGER, in depth</summary>

Docling table parsing failed on **5.5%** of table cells.

Diagnosed the Docling defect and implemented PDF text-layer reconstruction. Added distributed tracing with OpenTelemetry and Arize Phoenix on AWS EC2.

Raised held-out table-cell accuracy from **30.5%** to **100%** on Economic Report of the President tables. Integrated **223** automated tests into GitHub Actions CI.

</details>

<details>
<summary>TheraMind, in depth</summary>

Fine-tuned Llama 3.2-3B using QLoRA and Direct Preference Optimization (β = 0.1) on **9,250** clinical dialogues and **49** preference pairs. Built a ChromaDB-based RAG architecture.

Improved ROUGE-L from **0.40** to **0.78** with a **19.5-minute** training runtime on RTX 4090.

</details>

## ✦ Experience

| Period | Role | Company | Highlights |
|--------|------|---------|------------|
| *Aug 2025 – Present* | AI/ML Engineer | C3 AI | Architected multi-tenant LLM platform serving **1M+ daily requests** with **99.9%** uptime; reduced infrastructure costs by **35%** and deployment cycles from **10 days** to **2 days** |
| *Jan 2023 – Jul 2024* | AI/ML Engineer | Glean | Improved semantic ranking top-3 relevance by **18%** and click-through rates by **9%**; reduced p95 query latency by **40%** (820 ms to 490 ms) |
| *Aug 2021 – Dec 2022* | Data Scientist | Accenture | Built retail demand-forecasting model reducing MAPE from **18%** to **14%**; automated ticket routing saving **1,200 agent hours** quarterly and **25 analyst hours** weekly |
| *Jan 2021 – Jul 2021* | Associate Data Scientist | Accenture | Prototyped recommendation system achieving **12%** CTR increase; trained churn models reaching **0.86 AUC** and BERT classifier achieving **91% F1** on **10K** records |

## ✦ Credentials

### Education
- **M.S. Computer Science and Engineering**, University at Buffalo, SUNY (*Aug 2024 – Jan 2026*) – GPA: 3.53/4.0
- **B.Tech. Electronics and Communication**, SCMS School of Engineering and Technology, Kerala (*Sep 2017 – Jun 2021*)

### Certifications
- **AWS Certified Machine Learning Engineer Associate (MLA-C01)** – AWS
- **AWS Certified AI Practitioner (AIF-C01)** – AWS
- **Generative AI with LLMs, RAG** – DeepLearning.AI
- **Claude Code 101, Introduction to MCP** – Anthropic

## ✦ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,sklearn,pytorch,tensorflow,dart,ts,html,fastapi,docker,kubernetes,terraform,githubactions,postgres,mysql,mongodb,prometheus&theme=dark&perline=8" alt="py, sklearn, pytorch, tensorflow, dart, ts, html, fastapi, docker, kubernetes, terraform, githubactions, postgres, mysql, mongodb, prometheus" />
</p>

<p align="center"><a href="mailto:vishnumenon@myworkgmail.com"><b>Email</b></a> &nbsp;·&nbsp; <a href="http://www.linkedin.com/in/vkm47"><b>LinkedIn</b></a> &nbsp;·&nbsp; <a href="https://vkm47-theramind-ai.hf.space/"><b>Website</b></a> &nbsp;·&nbsp; <a href="https://github.com/Vishnu-K-Menon"><b>GitHub</b></a></p>

## ✦ Projects

- [driftguard-llm](https://github.com/Vishnu-K-Menon/driftguard-llm) — Catch silent RAG/LLM quality regressions before your users do.
- [agentops-sentinel](https://github.com/Vishnu-K-Menon/agentops-sentinel) — A supervisor/critique agent framework for support-ticket triage, reliable, cost-bounded, and fully traced.
- [advanced-rag-llm-app](https://github.com/Vishnu-K-Menon/advanced-rag-llm-app) — This project is a self-contained summer-internship-level implementation of an advanced AI application that combines Retrieval-Augmented Generation (RAG)…
- [agentgate](https://github.com/Vishnu-K-Menon/agentgate) — Companies adopting agentic AI need to safely expose internal APIs to LLM agents with per-agent auth, scoped permissions, spend/rate limits, and full audit logs…
- [fraud-detection-system](https://github.com/Vishnu-K-Menon/fraud-detection-system) — Protecting $20B+ in annual e-commerce transactions with ML-powered fraud detection
- [sentinel-triage](https://github.com/Vishnu-K-Menon/sentinel-triage) — Cut mean-time-to-triage without teaching your SOC to cry wolf.
- [pointintime](https://github.com/Vishnu-K-Menon/pointintime) — A feature store where point-in-time correctness is enforced, proved by a planted leaking feature the store refuses to serve.
- [vuln-priority-engine](https://github.com/Vishnu-K-Menon/vuln-priority-engine) — Turn a scanner's flat CVE dump into a risk-ranked, SLA-bucketed remediation queue using EPSS exploit-probability + CISA KEV + asset criticality.
- [github-repository-intelligence](https://github.com/Vishnu-K-Menon/github-repository-intelligence) — Ingests GitHub repository metadata, commit history, and issue trends via REST + GraphQL APIs.
- [receiptlens](https://github.com/Vishnu-K-Menon/receiptlens) — A privacy-first Flutter receipt scanner: on-device OCR and a TFLite line-item classifier with fully local encrypted storage and CSV/QuickBooks export, with no…
