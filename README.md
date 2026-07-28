<div align="center">

# Vijay Sai Chigullapally

**AI / Machine Learning Engineer** &nbsp;·&nbsp; Agentic AI &amp; GenAI Systems &nbsp;·&nbsp; Data Engineering

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3200&pause=900&color=0D9488&center=true&vCenter=true&width=650&lines=AI+%2F+Machine+Learning+Engineer;Agentic+AI%2C+LLMs+%26+RAG+Systems;Data+Engineering+at+Production+Scale;M.S.+Computer+Science+%40+UNT;2%2B+Years+Building+ML+in+Production" alt="AI / Machine Learning Engineer · Agentic AI, LLMs and RAG Systems · Data Engineering at Production Scale · M.S. Computer Science at UNT" />

![Open to Work](https://img.shields.io/badge/Open%20to%20Work-Full--Time%20Roles-0D9488?style=flat-square)
![Location](https://img.shields.io/badge/Denton%2C%20TX-United%20States-475569?style=flat-square&logo=googlemaps&logoColor=white)
![Education](https://img.shields.io/badge/M.S.%20Computer%20Science-UNT%20%C2%B7%20GPA%204.0-475569?style=flat-square&logo=googlescholar&logoColor=white)

[![Portfolio](https://img.shields.io/badge/Portfolio-0D9488?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-omega-six-j3zgm8e9ul.vercel.app)
[![Resume](https://img.shields.io/badge/Resume-B91C1C?style=flat-square&logo=readdotcv&logoColor=white)](https://portfolio-omega-six-j3zgm8e9ul.vercel.app/#resume)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vijay-sai-chigullapally-63558521b/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:vijaysaichigullapally1@gmail.com)

</div>

## About

I'm an **AI / Machine Learning Engineer with 2+ years of industry experience** shipping models that run in production, not just in notebooks. I'm currently an ML Research Assistant at the **University of North Texas** (M.S. Computer Science, 4.0 GPA), and I previously worked as a **Data Scientist at Kanerika** and a **Data Engineer at Saras Analytics**.

My work covers both halves of the problem. On the model side, I design and optimize CNNs, Transformers, and ensembles, using quantization and pruning to cut inference latency by 30%. On the infrastructure side, I build the pipelines they depend on, from Kafka ELT feeding Snowflake to ETL processing 500GB+ of unstructured data.

Right now I'm focused on **agentic AI**: LLM systems that operate on their own instead of waiting for someone to click "run." My silver-price predictor is the clearest example: five LLM specialists reason over an XGBoost ensemble's forecast and publish the result every night, entirely unattended, on GitHub Actions.

## Experience

**ML Research Assistant** · University of North Texas - Denton, TX · *2025-2026*
- Designed and optimized CNN & Transformer architectures in PyTorch for **15% accuracy gains**
- Applied quantization and pruning to reduce **inference latency by 30%**
- Built automated ETL pipelines over **500GB+** of unstructured research data, **+40% throughput**

**Data Scientist** · Kanerika - Hyderabad, India · *2024*
- Built hybrid LSTM + Isolation Forest ensembles for real-time anomaly detection across **500K+ daily telemetry records**
- Improved rare-event recall by **20%** with SMOTE; cut false positives **15%** across 200+ concurrent sensor streams

**Data Engineer** · Saras Analytics - Hyderabad, India · *2023*
- Engineered high-throughput ELT pipelines with **Apache Kafka** consolidating **200+ e-commerce sources** into **Snowflake**, reducing ingestion latency **40%**
- Developed **70+ dbt models** transforming raw commerce data into structured analytics layers

## Currently

```console
$ cat now.md

▸ shipping   silver-predictor  —  autonomous multi-agent forecaster
             XGBoost ensemble + 5 LLM specialists, nightly on Actions
▸ building   F1 Spec RAG Agent  —  article-level citation accuracy
▸ learning   LLM evaluation & observability for agentic systems
▸ open to    AI/ML · GenAI · Data Engineering roles (US, full-time)
```

## Featured Projects

### [Silver Predictor](https://github.com/vijaysai1102/silver-predictor) — autonomous multi-agent forecaster

`XGBoost` `Groq / Llama` `Multi-Agent` `GitHub Actions` `Time Series`

Five LLM specialists reason over an XGBoost ensemble's SI=F and SLV forecast, and the pipeline publishes a dated prediction every night with no human in the loop.

**Engineering note:** this is a scheduled production system rather than a notebook — every run is dated and archived, so past predictions can be scored against what actually happened.

[![Live Dashboard](https://img.shields.io/badge/Live%20Dashboard-0D9488?style=flat-square&logo=githubpages&logoColor=white)](https://vijaysai1102.github.io/silver-predictor/) &nbsp;[Source →](https://github.com/vijaysai1102/silver-predictor)

### [2026 F1 Spec RAG Agent](https://github.com/vijaysai1102/2026_F1_Spec_RAG_Agent) — RAG with enforced citations

`RAG` `LangChain` `ChromaDB` `Gemini API` `Streamlit`

Answers technical questions about the 2026 FIA Formula 1 Technical Regulations with precise Article-number citations, through both a CLI and a Streamlit interface.

**Engineering note:** citations are enforced, not hoped for — every answer must ground itself in a retrieved article, which is the difference between a demo chatbot and a tool an engineer would actually trust.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-0D9488?style=flat-square&logo=streamlit&logoColor=white)](https://f1-2026-rag-agent.streamlit.app/) &nbsp;[Source →](https://github.com/vijaysai1102/2026_F1_Spec_RAG_Agent)

### [WeatherScope AI](https://github.com/vijaysai1102/WeatherScope-AI) — end-to-end forecasting pipeline

`Prophet` `XGBoost` `SHAP` `Anomaly Detection` `Streamlit`

Global weather trend forecasting and spatial climate analysis, covering the full path from ingestion and EDA through forecasting, anomaly detection, and an interactive app.

**Engineering note:** Prophet and XGBoost are evaluated against each other rather than assumed, and SHAP supplies attribution — so the forecast ships with an explanation instead of a bare number.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-0D9488?style=flat-square&logo=streamlit&logoColor=white)](https://weatherscope-ai.streamlit.app/) &nbsp;[Source →](https://github.com/vijaysai1102/WeatherScope-AI)

### [Pneumonia Detection](https://github.com/vijaysai1102/Biomedical_Image_Classifier) — explainable medical imaging

`PyTorch` `ResNet-50` `Transfer Learning` `Grad-CAM` `SHAP` `LIME`

Pneumonia detection from chest X-rays using a CNN and fine-tuned ResNet-50, deployed on Hugging Face Spaces.

**Engineering note:** three independent explainability methods corroborate each prediction, which is the working bar for clinical ML — an unexplained output is an unusable one.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-0D9488?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/spaces/Vijaysai16/pneumonet) &nbsp;[Source →](https://github.com/vijaysai1102/Biomedical_Image_Classifier)

**Also worth a look** — [Bayesian Marketing Mix Model](https://github.com/vijaysai1102/bayesian-marketing-mix-model): PyMC and MCMC causal inference that estimates channel ROI *with uncertainty* and simulates budget reallocation · [AI NPC Agent](https://github.com/vijaysai1102/AI_NPC_Agent): LLM characters with persistent memory and evolving relationships ([live](https://vijaysai1102-ai-npc-agent-app-fjs6j1.streamlit.app/)) · [New-Grad Job Scanner](https://github.com/vijaysai1102/newgrad-job-scanner): scans ~87k postings across 1,300+ ATS boards, dating each from the ATS's own first-published field


## Tech Stack

**GenAI & LLM Systems**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-334155?style=flat-square)
![Multi-Agent Systems](https://img.shields.io/badge/Multi--Agent%20Systems-334155?style=flat-square)
![Google Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq%20%2F%20Llama-334155?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-1F2937?style=flat-square&logo=huggingface&logoColor=FFD21E)
![Vector DBs](https://img.shields.io/badge/Vector%20DBs%20%C2%B7%20ChromaDB-334155?style=flat-square)

**Machine Learning & Deep Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-334155?style=flat-square)
![PyMC](https://img.shields.io/badge/PyMC%20%C2%B7%20Bayesian-334155?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Data Engineering**

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Cloud, MLOps & Tooling**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)


