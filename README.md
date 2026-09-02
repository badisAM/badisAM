<div align="center">

# Ammar Bedis

**I turn operational data into deployed AI systems, from ERP exports to production-ready agents.**

Computer Engineering Student, Data Science & AI @ ESPRIT, Tunis 🇹🇳

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/bedis-ammar)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ammarbedis@gmail.com)
[![Open to PFE](https://img.shields.io/badge/Open%20to-PFE%20Internship%2C%20Jan%202027-1B998B?style=flat-square)]()

**Worked with**

![Sagemcom](https://img.shields.io/badge/Sagemcom-2D3142?style=flat-square)
![VITAL](https://img.shields.io/badge/VITAL-2D3142?style=flat-square)
![Tunisie Telecom](https://img.shields.io/badge/Tunisie%20Telecom-2D3142?style=flat-square)

</div>

---

## About

I move across three layers of the modern stack: building applications, orchestrating the AI systems inside them, and making sure the data feeding all of it is trustworthy.

Foundations → Development → AI Engineering is roughly how I got here: two years of math, algorithms and systems in the preparatory cycle, a year shipping full-stack applications, and now, designing agentic pipelines and applying ML to real data.

Today, that means I:
- Design multi-agent LLM systems: orchestration, tool-calling, RAG pipelines grounded in real evidence
- Build the data pipelines that feed them, from operational systems through ETL and warehousing to BI, and eventually, a working model
- Develop the full-stack applications that put both in front of a user

🎓 Looking for an end-of-studies internship (PFE), starting January 2027, open to AI engineering, data platform, or full-stack roles.

---

## Experience

**Sagemcom Software & Technologies**
*AI & Software Engineering Intern, Jul–Aug 2026*
Automated JIRA/Xray and internal RETRACK validation-report generation (Flask + Angular), cutting report time from 2h/day to under 2 minutes, and designed an 8-agent LLM/RAG pipeline to verify requirement-to-test coverage across 1,000+ Xray test cases.

---

## Featured projects

Three projects that best show how I put agentic AI and data systems together, end to end.

### Sagemcom RETRACK

An 8-agent coverage engine that checks whether every clause of a requirement is actually tested, and flags what's missing.

```mermaid
flowchart LR
    A["Analyse<br/>Requirement + Test Plan"] --> B["Indexation<br/>BM25 + Embeddings"]
    B --> C["Sélection<br/>Prefilter, Evidence, Rerank hybride"]
    C --> D["Vérification<br/>Agent LLM + Juge"]
    D --> E["Finalisation<br/>Verdicts, Gaps, Validate"]
```

Eight specialized agents (requirement decomposer, rules/evidence engine, hybrid reranker, LLM verifier, judge, synthesizer, coverage-gap finder) sit around a central orchestrator. Retrieval combines BM25 with embeddings to surface the right clauses, a local LLM (Ollama) verifies each match with a citation and a counter-argument pass, and a calibrated judge applies strict confirmation thresholds before anything is flagged. On the validation set, the system reached a recall of 0.67 with zero false positives.

### VITAL — Agent Produits

A product-recommendation agent built for VITAL's catalog, as part of a larger multi-agent platform.

```mermaid
flowchart LR
    A["Requête<br/>utilisateur"] --> B["Orchestrateur<br/>central"]
    B --> C["Recherche hybride RAG<br/>FAISS"]
    C --> D["Analyse contextuelle<br/>LLaMA 3"]
    D --> E["Scoring & décision<br/>métier"]
    E --> F["Recommandations<br/>511 références produits"]
```

Hybrid retrieval (FAISS) narrows the catalog down to relevant candidates, an LLM (LLaMA 3) reasons over them with structured prompting, and a scoring layer turns that into a business decision, ranked recommendations across VITAL's 511-reference product catalog.

### EduVision

Image captioning with a CNN encoder (ResNet-50) and a Transformer decoder, using beam search decoding to improve BLEU-score performance over greedy decoding.

---

## Tech stack

**Agentic AI & LLM orchestration**: multi-agent pipelines, RAG, tool-calling

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**Data science & machine learning**: classification, forecasting, anomaly detection

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Data engineering & BI**: Odoo, Talend, SQL Server, Power BI

![Odoo](https://img.shields.io/badge/Odoo-714B67?style=flat-square&logo=odoo&logoColor=white)
![Talend](https://img.shields.io/badge/Talend-FF6D70?style=flat-square&logo=talend&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Software engineering**: the applications everything else lives inside

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=flat-square&logo=symfony&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

---

## Certifications

- NVIDIA: AI for Anomaly Detection
- NVIDIA: Fundamentals of Deep Learning
- 365 Data Science: CNN with TensorFlow in Python

---

<div align="center">

Thanks for reading. Always happy to talk AI, data, or both.

</div>
