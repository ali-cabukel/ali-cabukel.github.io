---
title: "Ali Cabukel"
excerpt: "Lead AI Engineer — production LLM systems, agents, and ML platforms."
layout: single
author_profile: true
classes: wide
toc: true
toc_label: "On this page"
toc_sticky: true
---

<!--
  DRAFT — items marked TODO need your input before publishing.
  Search this file for "TODO" to find them all.
-->

## About

Lead AI Engineer with 15+ years across software, data science and ML/AI engineering — 7 of them building production systems on Google Cloud, 3 on Generative AI. I'm the technical lead for ML and GenAI products at **Vodafone Group in London**: end-to-end ML pipelines, RAG and agentic LLM applications, and the MLOps tooling that keeps them running.

Outside work I build small, useful apps on real-world data, and I write up what I learn on the [blog](/blog/).

- **Based in:** London, UK
- **Languages:** English, Turkish
- **Find me on:** [GitHub](https://github.com/ali-cabukel) · [LinkedIn](https://www.linkedin.com/in/alicabukel)

---

## Experience

### Senior Machine Learning Engineer — Vodafone Group
*London · 2021 – present*

Technical lead for reusable ML and GenAI systems used across Vodafone, spanning customer experience, contact centre, pricing and sales.

- **Pricing intelligence (Pricelytics)** — tech lead for agentic browser automation and AI extraction pipelines that track competitor prices across markets.
- **ML pipeline templates** — standard Kubeflow / Vertex AI training and prediction pipelines with CI/CD, now the blueprint for production ML use cases.
- **Product recommender** — ML models replacing a rules-based tariff engine for mobile, broadband and TV sales.
- **CX AI Platform** — GenAI translation, summarisation and tagging of customer feedback for CX teams, with LLMOps for deployment, evaluation and monitoring.
- **Agentic sales and contact-centre AI** — conversational sales agents, a role-play coaching assistant, retention signals for call-centre agents, and a RAG policy chatbot.
- **AI platform** — core developer on Vodafone's group-wide AI platform on GCP.

`Vertex AI` · `Kubeflow` · `BigQuery` · `GKE` · `LangGraph` · `Google ADK` · `Gemini` · `RAG` · `LLMOps` · `Playwright` · `Terraform` · `Cloud Build`

### Earlier

| Role | Company | Years |
| --- | --- | --- |
| Director & Principal Data Science Consultant | Naril Software & Consulting, London | 2019 – 2021 |
| Principal Big Data Consultant | Gtech, Istanbul | 2016 – 2019 |
| Senior Data Scientist | Turkcell Global Bilgi, Istanbul | 2015 – 2016 |
| Data Scientist | Türk Telekom, Istanbul | 2013 – 2015 |
| Software Developer | Cardtek, Istanbul | 2012 – 2013 |
| Software Developer | Yaz Information Systems, Istanbul | 2009 – 2011 |

### Education & certifications

- **BSc Statistics** — Hacettepe University, Ankara (2005–2009)
- **Google Cloud Professional** — Machine Learning Engineer · Data Engineer · Cloud Architect

---

## Projects

### Side projects

Products I build and run myself.

| Project | What it does |
| --- | --- |
| **[ppoll.uk](https://ppoll.uk)** | AI poll studio — design, target, publish and analyse polls with AI support |
| **[mekanize.uk](https://mekanize.uk)** | Chat to find the right local venue for birthdays, meetings, group workouts or team dinners, matched to city, budget and food needs |
| **[skailo.io](https://skailo.io)** | Open job-market analytics — in-demand skills, job levels, titles and daily posting trends across domains |

#### kayrazen.io

Bilingual (Turkish + English) apps and games I build and run myself under **[kayrazen.io](https://kayrazen.io)**, with **[narsync.io](https://narsync.io)** as the data and API layer behind them.

**Apps**

| Project | What it does |
| --- | --- |
| **[Deprem](https://deprem.kayrazen.io)** | Latest earthquakes in Türkiye and worldwide — merges AFAD, Kandilli, EMSC and USGS reports into one feed, always showing source and time |
| **[Hava](https://hava.kayrazen.io)** | "Should I run today?" — best running hours, air quality and pollen for 81 Turkish provinces and 39 world cities |
| **[Tatil](https://tatil.kayrazen.io)** | Turkish public holiday planner — the longest break for the least leave, with eves and bridge days |
| **[narsync.io](https://narsync.io)** | The engine room: FastAPI + SQLite pipelines that poll public data sources and serve the apps through `api.narsync.io` |

**Browser games**

| Game | What it is |
| --- | --- |
| **[Dondurma](https://dondurma.kayrazen.io)** | Can you outsmart the playful Maraş ice cream vendor? |
| **[Cabukebab](https://cabukebab.kayrazen.io)** | Pick your kebab and sauce at Ali Usta's counter and build the order |
| **[Tahsilat](https://tahsilat.kayrazen.io)** | Track friends' IOUs with a little math and a lot of humour |
| **[Kargo](https://kargo.kayrazen.io)** | Deliver parcels door to door in a cosy town and collect tips |
| **[Dino Zıp](https://dinazor.kayrazen.io)** | Jump over cacti with a chubby dino, collect cookies and hit rainbow mode |

### Open source

Everything below is on [GitHub](https://github.com/ali-cabukel).

**Featured**

- **[ecommerce-conversion-pipeline](https://github.com/ali-cabukel/ecommerce-conversion-pipeline)** — real-time purchase-conversion scoring as a full production stack: Kafka → Feast/Redis online features, dbt warehouse, Airflow training with a promotion gate, Evidently drift checks, BentoML serving, Prometheus + Grafana.
- **[crashquery](https://github.com/ali-cabukel/crashquery)** — agentic text-to-SQL over the UK STATS19 road casualty database, built around the ways text-to-SQL fails in production: schema as tools, a read-only role behind four guard layers, and behaviour-based evaluation.
- **[hailstorm](https://github.com/ali-cabukel/hailstorm)** — distributed hyperparameter search with Ray, Optuna and XGBoost, with leakage-safe temporal splits and documented distributed failure modes.

**Libraries**

| Project | What it does |
| --- | --- |
| **[jsonguard](https://github.com/ali-cabukel/jsonguard)** | Extract, repair, and validate JSON from LLM responses |
| **[promptreg](https://github.com/ali-cabukel/promptreg)** | Pytest-style regression tests for prompts |
| **[modeldebug](https://github.com/ali-cabukel/modeldebug)** | Diagnostic checks that explain why an ML model is failing |

**Agents & applications**

| Project | What it does |
| --- | --- |
| **[threadneedle](https://github.com/ali-cabukel/threadneedle)** | UK macro policy RAG over Bank of England, ONS and HM Treasury sources, with a LangGraph agent that pulls live ONS figures |
| **[waggle](https://github.com/ali-cabukel/waggle)** | Agentic web scraping platform — plan / execute / repair loop over Playwright, crawl4ai and remote CDP engines |
| **[klaxon](https://github.com/ali-cabukel/klaxon)** | Incident management desk — FastAPI + MCP tools and a LangGraph agent driven by Slack slash commands |
| **[tradenet-chat](https://github.com/ali-cabukel/tradenet-chat)** | Conversational agent generating read-only Cypher against a Neo4j trade graph |
| **[tissue-bot](https://github.com/ali-cabukel/tissue-bot)** | Collects GitHub repo and issue data, then analyses and resolves issues with LangGraph agents ([blog series](/blog/)) |
| **[marti-io](https://github.com/ali-cabukel/marti-io)** | Multi-agent personal assistant hub (FastAPI + LangGraph) |

**ML platform & training**

| Project | What it does |
| --- | --- |
| **[warp](https://github.com/ali-cabukel/warp)** | Copier template for Vertex AI Pipelines (KFP v2) projects on BigQuery ML, with Terraform and Cloud Build included |
| **[spider-lora](https://github.com/ali-cabukel/spider-lora)** | LoRA fine-tuning for text-to-SQL on Spider, graded by execution accuracy; runs on Apple Silicon or CUDA |

**Data & analysis**

| Project | What it does |
| --- | --- |
| **[tickhouse](https://github.com/ali-cabukel/tickhouse)** | Kafka trades into ClickHouse with live OHLCV candles, a GraphQL API and a dashboard |
| **[tradenet](https://github.com/ali-cabukel/tradenet)** | Bilateral trade data from UN Comtrade, modelled as a network |
| **[policritique](https://github.com/ali-cabukel/policritique)** | UK election results, MPs and party policy data for analysis |
| **[supamarkt](https://github.com/ali-cabukel/supamarkt)** | Intraday market data and rule-based trading signals |

---

## Skills

**Languages** · Python · SQL · TypeScript

**GenAI** · LangGraph · LangChain · Google ADK · Gemini · OpenAI · Anthropic · MCP (FastMCP) · RAG (Docling, chunking, incremental indexing) · text-to-SQL / text-to-Cypher agents · agentic browser automation · vector search (pgvector, Chroma) · LLM-as-judge and agent evaluation · fine-tuning and serving (LoRA/PEFT, vLLM, Transformers)

**ML & distributed training** · XGBoost · scikit-learn · PyTorch · Ray (Tune, Train, Data) · Optuna · ASHA

**MLOps & LLMOps** · Vertex AI Pipelines (KFP v2) · Airflow · dbt · Feast · MLflow · BentoML · Evidently · DVC · Copier

**Backend & data** · FastAPI · Flask · SQLAlchemy · PostgreSQL · SQLite · MongoDB · Neo4j · ClickHouse · Redis · Kafka · Celery · Spark · GraphQL

**Cloud & infra** · GCP (Vertex AI, BigQuery, Cloud Run, GKE, Dataflow, Pub/Sub) · Azure · Docker · Terraform · Cloud Build · GitHub Actions · Caddy · Prometheus · Grafana

**Frontend** · React · Next.js · TanStack Start

**Leadership** · architecture and roadmaps · technical hiring and mentoring · MLOps standards · AI governance

**Ways of working** · agentic coding (Claude Code, Cursor) · local inference (Ollama, LM Studio) · rapid prototyping (Lovable, v0, Supabase)

---

## Interests

<!-- TODO: edit freely — these are guesses based on your projects. -->

- **Public data as public good** — earthquakes, weather, air quality, elections and trade data turned into things people can actually use.
- **Making LLMs reliable** — evaluation, guardrails, and the quiet failure modes that only show up in production.
- **Markets and economics** — UK macro policy, trade networks, market microstructure.

---

## Latest from the blog

{% for post in site.posts limit:3 %}
- [{{ post.title }}]({{ post.url | relative_url }}) <small>· {{ post.date | date: "%-d %B %Y" }}</small>
{% endfor %}

[All posts →](/blog/)
