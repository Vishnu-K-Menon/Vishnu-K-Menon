<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/bento-dark.svg" />
  <img src="./assets/bento-light.svg" alt="Vishnu Krishnakumar Menon: AI/ML Engineer" width="100%" />
</picture>

## ✦ About

I build production-grade RAG systems, LLM orchestration platforms, and ML infrastructure. At C3 AI, I architected a multi-tenant inference platform supporting **20+ enterprise deployments** with **99.9% uptime**, and led the cloud migration that cut infrastructure costs by **35%** while reducing deployment cycles from 10 days to 2. At Glean, I optimized semantic ranking models, improving click-through rates by **9%** and cutting query latency by **40%**.

## ✦ Selected work

| Project | What it does | Impact | Stack |
|---------|-------------|--------|-------|
| **Multi-tenant LLM platform** | Separated retrieval, orchestration, and model-serving services on Kubernetes for **20+ enterprise deployments** | Maintained **99.9% uptime** serving **1M+ daily requests**; reduced p95 latency to **<300 ms** under 3× traffic | Kubernetes, LangGraph, Docker, MLflow, Prometheus, Grafana |
| **Cloud migration** | Containerized **12 legacy ML workloads** and migrated from on-premises to AWS with Terraform | Cut infrastructure costs by **35%** and deployment cycles from **10 days to 2 days** | AWS, Docker, Terraform, CI/CD |
| **Semantic ranking optimization** | Fine-tuned transformer-based ranking models with hard-negative mining and embedding tuning | Improved offline NDCG by **18%** and online click-through rates by **9%** | Transformers, Apache Airflow, INT8 quantization |
| **RAG retrieval tuning** | Experimented with chunk sizes, reranking, and citation-grounded prompting across **1,500-question benchmark** | Reduced hallucinated responses by **27%** | RAG, reranking, prompt engineering |
| **Demand forecasting** | Built XGBoost and Prophet ensemble with **60+ engineered features** | Improved forecast accuracy, reducing MAPE from **18% to 14%** | XGBoost, Prophet, Python, SQL |
| **NLP ticket classifier** | Deployed FastAPI service on Azure to automate support ticket routing | Automated **70%** of routing, saving **1,200 agent hours quarterly** | NLP, FastAPI, Docker, Azure |

<details>
<summary>Multi-tenant LLM platform, in depth</summary>

**The result**: The platform supports **20+ enterprise deployments** serving **1M+ daily requests** at **99.9% uptime**, with p95 latency below **300 ms** under **3× normal traffic**. Production incidents were reduced by **40%**.

</details>

<details>
<summary>Semantic ranking optimization, in depth</summary>

**The result**: Offline top-3 NDCG improved by **18%** and online click-through rates rose **9%**.

</details>

## ✦ Experience

| Period | Role | Company | Highlights |
|--------|------|---------|------------|
| *Aug 2025 – Present* | AI/ML Engineer | C3 AI | Architected multi-tenant LLM platform serving **1M+ daily requests** at **99.9% uptime**; led cloud migration cutting costs by **35%** and deployment time from **10 days to 2**; reduced production incidents by **40%** through automated drift monitoring. |
| *Jan 2023 – Jul 2024* | AI/ML Engineer | Glean | Optimized semantic ranking models, improving click-through rates by **9%** and offline NDCG by **18%**; cut query latency by **40%** through INT8 quantization and caching; reduced hallucinations by **27%** with RAG tuning. |
| *Aug 2021 – Dec 2022* | Data Scientist | Accenture | Built demand-forecasting model reducing MAPE from **18% to 14%**; deployed NLP ticket classifier automating **70%** of routing and saving **1,200 agent hours quarterly**; automated reporting saving **25 analyst hours weekly**. |
| *Jan 2021 – Jul 2021* | Associate Data Scientist | Accenture | Prototyped recommendation system increasing click-through rates by **12%**; trained churn models achieving **AUC 0.86**; validated BERT classifier reaching **91% F1** on **10K records**. |

## ✦ Credentials

- **M.S. Computer Science and Engineering**, University at Buffalo, SUNY · *Aug 2024 – Jan 2026* · GPA 3.53/4.0
- **B.Tech. Electronics and Communication**, SCMS School of Engineering and Technology · *Sep 2017 – Jun 2021*
- **AWS Certified Machine Learning Engineer Associate (MLA-C01)** · AWS
- **AWS Certified AI Practitioner (AIF-C01)** · AWS
- **Generative AI with LLMs, RAG** · DeepLearning.AI
- **Claude Code 101, Introduction to MCP** · Anthropic

## ✦ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,sklearn,pytorch,tensorflow,html,ts,js,fastapi,docker,kubernetes,terraform,githubactions,postgres,mysql,mongodb,prometheus&theme=dark&perline=8" alt="py, sklearn, pytorch, tensorflow, html, ts, js, fastapi, docker, kubernetes, terraform, githubactions, postgres, mysql, mongodb, prometheus" />
</p>

<p align="center"><a href="mailto:vishnumenon@myworkgmail.com"><b>Email</b></a> &nbsp;·&nbsp; <a href="http://www.linkedin.com/in/vkm47"><b>LinkedIn</b></a> &nbsp;·&nbsp; <a href="https://vkm47-theramind-ai.hf.space/"><b>Website</b></a> &nbsp;·&nbsp; <a href="https://github.com/Vishnu-K-Menon"><b>GitHub</b></a></p>

## Projects

- [driftguard-llm](https://github.com/Vishnu-K-Menon/driftguard-llm) — Teams ship RAG/LLM features to prod with no systematic way to detect when retrieval or output quality silently degrades as source data and query distributions s
- [agentops-sentinel](https://github.com/Vishnu-K-Menon/agentops-sentinel) — Teams building agentic features can't make multi-step agent workflows reliable, observable, and cost-bounded; failures are silent, costs spiral, and there's no
- [advanced-rag-llm-app](https://github.com/Vishnu-K-Menon/advanced-rag-llm-app) — This project is a self-contained summer-internship-level implementation of an advanced AI application that combines Retrieval-Augmented Generation (RAG), vector
- [agentgate](https://github.com/Vishnu-K-Menon/agentgate) — Companies adopting agentic AI need to safely expose internal APIs to LLM agents with per-agent auth, scoped permissions, spend/rate limits, and full audit logs
- [fraud-detection-system](https://github.com/Vishnu-K-Menon/fraud-detection-system) — Protecting $20B+ in annual e-commerce transactions with ML-powered fraud detection
- [sentinel-triage](https://github.com/Vishnu-K-Menon/sentinel-triage) — SOC analysts drown in alert fatigue — SIEMs generate thousands of low-fidelity alerts daily and Tier-1 analysts spend most of their time on manual log correlati
