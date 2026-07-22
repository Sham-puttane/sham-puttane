<!-- ===================== HEADER ===================== -->
<h1 align="center">Hi, I'm Shambhavi 👋</h1>

<p align="center">
  <b>AI Engineer × Data Engineer</b> — I build LLM systems on top of pipelines I trust.
</p>

<p align="center">
  🎓 MS Data Science, Analytics & Engineering @ Arizona State University (4.0)<br/>
  📊 Data Analyst @ ASU Decision Theater Network &nbsp;•&nbsp; ⚙️ ex-Cloud Engineer @ HPE Aruba<br/>
  🤖 Multi-Agent AI • RAG • Tabular & GIS Intelligence
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shambhavi-puttane/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:pshambhavi2@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=Sham-puttane&style=for-the-badge&color=6E5494" alt="Profile views"/>
</p>

<hr/>

<!-- ===================== TWO SIDES ===================== -->
## 🧠 Two sides of the same problem

Most "AI" projects die because the data underneath them is a mess. I work both sides: the
**intelligence layer** and the **pipelines that feed it**.

<table>
<tr>
<th width="50%">🤖 &nbsp;AI / LLM Engineering</th>
<th width="50%">🧱 &nbsp;Data Engineering & Analytics</th>
</tr>
<tr valign="top">
<td>

- **Multi-agent orchestration** — LangGraph, LangChain, tool calling
- **RAG & hybrid retrieval** — ChromaDB, GraphRAG, vector + SQL
- **Evaluation that matters** — LLM-as-Judge, faithfulness checks, RAGAS
- **Fine-tuning & inference** — LoRA/PEFT, quantization, Intel Gaudi HPU
- **Agentic development** — Claude Code in the daily loop

</td>
<td>

- **Pipelines** — Airflow orchestration, Spark / PySpark, ETL & ELT
- **Warehousing & stores** — Snowflake, Redshift, S3, Glue, DuckDB; NoSQL (DynamoDB, MongoDB, ElasticSearch)
- **Modeling** — star & snowflake schemas, SCD Type 2, dbt
- **Quality & governance** — validation, PII-safe migrations, lineage
- **Streaming & ops** — Kafka, RabbitMQ, Docker, K8s, Grafana

</td>
</tr>
</table>

<hr/>

<!-- ===================== PROJECTS ===================== -->
## 🚀 Featured Projects

<table>
<tr valign="top">
<td width="50%">

### 🗺️ GIS-AI: Natural Language over Census Data
Ask Arizona Census data a question in plain English.
`TableGPT2-7B` + RAG (`ChromaDB`) with a semantic cache,
Streamlit front end, Highcharts + GeoJSON maps.
Inference tuned on **Intel Gaudi HPU** (BF16/FP16,
quantization, pipeline parallelism) for ~30% lower latency.

*Built at ASU Decision Theater, used by Arizona Census
and metro planning teams.*

</td>
<td width="50%">

### 🤖 [Multi-Agent Table Summarization](https://github.com/19Gautham/context-aware-summarization)
Router orchestrating specialist agents:
**TableGPT** (tabular QA), **Gemini** (text), **BLIP2** (vision),
**Gemma** (summary) with LoRA via HF Accelerate.
Chain-of-Thought + faithfulness verification, scored with an
**LLM-as-Judge** pipeline on TATQA & MMQA.

*📄 Paper under review.*

</td>
</tr>
<tr valign="top">
<td width="50%">

### 🏥 [Hospital Price Transparency QA](https://github.com/Sham-puttane/Decoding-Hospital-Bills---A-Smart-QA-System-for-Machine-Readable-Price-Transparency-Data)
Hospital prices are legally public and practically unreadable.
Scraped **97 machine-readable files across 120 AZ hospitals**
(~4GB), normalized wildly inconsistent schemas into one
queryable store, then layered **hybrid search** (vector + SQL)
and natural-language querying on top. Deployed via FastAPI.

</td>
<td width="50%">

### 💸 [PennyPath — GraphRAG Financial Planning](https://github.com/Sham-puttane/pennypath_innovationhack2.0)
Knowledge graph of **4,194 entities / 8,066 relations** built
from CFPB, FEMA, and State Farm sources. Persona-aware
retrieval + rule-based prioritization, with What-If scenarios
re-running in ~50ms behind Flask APIs.

*🥉 3rd place — Innovation Hack 2.0*

</td>
</tr>
<tr valign="top">
<td width="50%">

### 🏛️ [RateMyRep — Agents + Claude Code](https://github.com/Sham-puttane/rate_my_rep)
HackASU 2026. Agent pipeline turning legislator PDFs and voter
guides into structured, queryable records: **Claude Code** for
parsing, Gemini 2.5 Flash for batched classification across
12 policy areas, TinyFish for scraping, PostgreSQL storage.
Scores what reps *say* against how they *vote*.

</td>
<td width="50%">

### 🔐 [Explainable Threat & Fraud Detection](https://github.com/Sham-puttane/Threat-Detection-with-Explanaible-AI)
Credit-card fraud and anomaly detection with **XGBoost** and
scikit-learn (+20% over baseline), made interpretable with
**SHAP** and **LIME** so an analyst can see *why* a
transaction was flagged.

</td>
</tr>
</table>

<details>
<summary><b>More projects</b> — sensors, statistics, NLP, full-stack</summary>

<br/>

| Project | What it is | Stack |
|---|---|---|
| [CMI BFRB Detection](https://github.com/Sham-puttane/BFRB-detection-Kaggle-competition-_CSE572) | Multimodal wrist-sensor time-series pipeline (IMU, thermopile, ToF) detecting body-focused repetitive behaviors — **96.02% Binary F1** | Conv1D, windowing, normalization |
| [AI/NLP 3D Interior Modeling](https://github.com/Sham-puttane/3d-interior-model) | Text → room layouts. Basis of my published paper | BERT, GCN, GAN, TensorFlow |
| [US Mass Shooting Analysis](https://github.com/Sham-puttane/US-Mass-Shooting-Analysis) | Classical statistics done properly: ANOVA, chi-square, regression diagnostics, SARIMA forecasting | Python, R, statsmodels |
| [Geo-Distributed NoSQL Benchmarking](https://github.com/Sham-puttane/Comparative-Analysis-of-Geo-Distributed-NoSQL-Databases-for-Location-Aware-Recommendation-Systems) | Comparative analysis of geo-distributed NoSQL stores for location-aware recommendation systems, with a UI over the results | DynamoDB, ElasticSearch, MongoDB, Python |
| [Workplace Mental-Health Analysis](https://github.com/Data-Analytics-Team-PESU/OSMI-Data-Analysis) | Classical ML breadth on survey data | Regression, SVM, KNN, AdaBoost, LightGBM |

</details>

<hr/>

<!-- ===================== TECH STACK ===================== -->
## 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP%20%2F%20LIME-8A2BE2?style=flat-square)
![Claude](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white)

**Data Engineering**

![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

**Databases & Serving**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![ElasticSearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

**Visualization**

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![PowerBI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Highcharts](https://img.shields.io/badge/Highcharts-8087E8?style=flat-square&logo=highcharts&logoColor=white)

<hr/>

<!-- ===================== PUBLICATION ===================== -->
## 📄 Publication

**Kulkarni, R. P., & Puttane, S. M.** (2024). *Framework for Home Layout Design by Semantic Parsing of Text.*
Advances in Computational Intelligence and Its Applications, 195.

*Second paper on multi-agent table summarization currently under review.*

<hr/>

<!-- ===================== FOCUS ===================== -->
## 🎯 Currently working on

```text
▸ Retrieval-Augmented Generation over structured & tabular data
▸ Multi-agent orchestration and agent evaluation pipelines
▸ Tabular LLM fine-tuning and inference optimization
▸ Data platforms that make AI outputs trustworthy, not just fast
```

<hr/>

<!-- ===================== STATS ===================== -->
## 📊 GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Sham-puttane&show_icons=true&hide_border=true&title_color=6E5494&icon_color=6E5494" alt="GitHub stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sham-puttane&layout=compact&hide_border=true&title_color=6E5494" alt="Top languages"/>
</p>

<hr/>

<!-- ===================== FOOTER ===================== -->
<p align="center">
  ⭐ If you're building LLM systems, RAG, or tabular AI — I'd love to talk.<br/>
  <a href="https://www.linkedin.com/in/shambhavi-puttane/">LinkedIn</a> •
  <a href="mailto:pshambhavi2@gmail.com">Email</a>
</p>
