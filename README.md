## Hi, I'm Ranjith Guggilla

**Gen AI / ML Engineer** · building LLM applications, RAG systems, and production machine learning pipelines on Azure and AWS.

I build Retrieval-Augmented Generation apps with Azure OpenAI, LangChain, and Azure AI Search, ship ML models behind FastAPI services, and care about the parts that make AI trustworthy in production: grounding, guardrails, evaluation, and monitoring.

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-0078D4?logo=microsoftazure&logoColor=white)](https://azure.microsoft.com/products/ai-services/openai-service)
[![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-232F3E?logo=amazonwebservices&logoColor=white)](https://aws.amazon.com/bedrock/)
[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)](https://www.langchain.com/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)

---

### What I work on

- **Generative AI:** RAG over enterprise documents with Azure OpenAI, LangChain, LangGraph, Prompt Flow, and Azure AI Search; prompt engineering with grounding, conversation memory, and guardrails that cut hallucinations by 20%.
- **Document AI:** ingestion pipelines with Azure AI Document Intelligence, OCR, and chunking for semantic and vector search.
- **Machine learning:** supervised models for risk, fraud, segmentation, and forecasting with scikit-learn, XGBoost, and Amazon SageMaker, tracked with MLflow.
- **Production:** FastAPI and Flask inference APIs, Docker, Azure App Service, AWS Lambda, CI/CD with GitHub Actions and Azure DevOps, plus monitoring in Azure Monitor, CloudWatch, and Power BI.

---

### Featured ML projects

<table>
<tr>
<td width="50%" valign="top">

#### [churn-radar](https://github.com/ranjithguggilla/churn-radar)
Customer churn early-warning system. Compares logistic regression, random forest, and XGBoost (ROC-AUC 0.845), reaches 50% of churners by calling the top 20% of risk scores, and serves predictions with plain-language risk drivers through a FastAPI service.

![FastAPI](https://img.shields.io/badge/FastAPI-API-009688)
![XGBoost](https://img.shields.io/badge/XGBoost-model-orange)
![Docker](https://img.shields.io/badge/Docker-image-2496ED)
![MLflow](https://img.shields.io/badge/MLflow-tracking-0194E2)
![CI](https://github.com/ranjithguggilla/churn-radar/actions/workflows/ci.yml/badge.svg)

</td>
<td width="50%" valign="top">

#### [riskbeacon](https://github.com/ranjithguggilla/riskbeacon)
Credit-risk early warning for two-year financial distress. Class-weighted CatBoost beats a logistic baseline (test ROC-AUC 0.867), and the approve/decline threshold minimizes expected loss in dollars instead of defaulting to 0.5.

![CatBoost](https://img.shields.io/badge/CatBoost-gradient_boosting-yellow)
![imbalanced-learn](https://img.shields.io/badge/imbalanced--learn-SMOTE-blue)
![Gradio](https://img.shields.io/badge/Gradio-UI-F97316)
![CI](https://github.com/ranjithguggilla/riskbeacon/actions/workflows/ci.yml/badge.svg)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [forgewatch](https://github.com/ranjithguggilla/forgewatch)
Predictive maintenance for a CNC milling cell. A glass-box failure model, conformal triage bands with a measured coverage guarantee, survival-based tool-life budgets, and cost-optimal alert thresholds.

![Explainable AI](https://img.shields.io/badge/explainable-AI-6f42c1)
![MAPIE](https://img.shields.io/badge/MAPIE-conformal-blue)
![lifelines](https://img.shields.io/badge/lifelines-survival-green)
![CI](https://github.com/ranjithguggilla/forgewatch/actions/workflows/ci.yml/badge.svg)

</td>
<td width="50%" valign="top">

#### [pedalcast](https://github.com/ranjithguggilla/pedalcast)
Hourly bike-share demand forecasting. LightGBM reaches R² 0.91 and cuts mean error from 102 to 43 bikes per hour against the seasonal baseline, validated on a strictly chronological hold-out.

![LightGBM](https://img.shields.io/badge/LightGBM-forecasting-9ACD32)
![Polars](https://img.shields.io/badge/Polars-data-CD792C)
![Streamlit](https://img.shields.io/badge/Streamlit-dashboard-FF4B4B)
![CI](https://github.com/ranjithguggilla/pedalcast/actions/workflows/ci.yml/badge.svg)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [curecast](https://github.com/ranjithguggilla/curecast)
Concrete compressive-strength regression (R² 0.93), run in reverse to find the lowest-carbon mix that still meets a target strength.

![scikit-learn](https://img.shields.io/badge/scikit--learn-regression-F7931E)
![Optimization](https://img.shields.io/badge/inverse-optimization-purple)
![CI](https://github.com/ranjithguggilla/curecast/actions/workflows/ci.yml/badge.svg)

</td>
<td width="50%" valign="top">

#### [fieldwise](https://github.com/ranjithguggilla/fieldwise)
Crop recommendation engine (99.5% held-out accuracy) with an advisory layer that explains soil-nutrient shortfalls in plain language. Optuna tuning and Pandera data validation.

![Optuna](https://img.shields.io/badge/Optuna-tuning-2C5BB4)
![Pandera](https://img.shields.io/badge/Pandera-validation-green)
![CI](https://github.com/ranjithguggilla/fieldwise/actions/workflows/ci.yml/badge.svg)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

#### [EDITH-voice-assistant](https://github.com/ranjithguggilla/EDITH-voice-assistant)
Python conversational voice assistant with speech recognition, text-to-speech, and NLP-driven intent handling for weather, news, Wikipedia, messaging, translation, and system control.

![NLP](https://img.shields.io/badge/NLP-intents-blue)
![Speech](https://img.shields.io/badge/speech-recognition-teal)

</td>
</tr>
</table>

<details>
<summary><b>Data engineering and scientific data projects</b></summary>

<br>

- [gulf-buoy-etl](https://github.com/ranjithguggilla/gulf-buoy-etl): autonomous ETL for Gulf of Mexico buoy data into NetCDF and Parquet, with DuckDB analytics and Prometheus metrics
- [iso19115-validator](https://github.com/ranjithguggilla/iso19115-validator): metadata compliance engine with XSD, Schematron, a YAML rules DSL, and a FastAPI dashboard
- [glider-data-curation](https://github.com/ranjithguggilla/glider-data-curation): glider mission pipeline with QC, packaging, and DOI metadata
- [ctd-cast-processor](https://github.com/ranjithguggilla/ctd-cast-processor): sensor processing pipeline from raw CTD files to validated NetCDF
- [ocean-curation-pipeline-toolkit](https://github.com/ranjithguggilla/ocean-curation-pipeline-toolkit): plugin-based ingest, transform, validate, and publish framework with checksum verification
- [species-report-quality-assistant-demo](https://github.com/ranjithguggilla/species-report-quality-assistant-demo): image-assisted report QA with PyTorch and OpenCV

</details>

---

### Tech stack

| Category | Tools |
|---|---|
| **Generative AI** | Azure OpenAI, Azure AI Studio, Azure AI Search, LangChain, LangGraph, Prompt Flow, RAG, prompt engineering, function calling, embeddings, AI agents |
| **Machine learning** | scikit-learn, XGBoost, TensorFlow, PyTorch, MLflow, feature engineering, hyperparameter tuning, model evaluation |
| **NLP and document AI** | Azure AI Document Intelligence, OCR, tokenization, sentiment analysis, entity recognition, summarization |
| **Vector databases** | FAISS, ChromaDB, Azure AI Search vector index |
| **Languages** | Python, SQL, Java, JavaScript |
| **Frameworks** | FastAPI, Flask, Streamlit, Gradio |
| **AWS** | SageMaker, Bedrock, Lambda, EC2, S3, IAM, CloudWatch, Glue |
| **Azure** | OpenAI, AI Search, Machine Learning, Functions, Blob Storage, SQL Database, Key Vault, App Service, Monitor |
| **Data engineering** | PySpark, Pandas, NumPy, ETL, SQL Server, PostgreSQL, MySQL, MongoDB |
| **MLOps and DevOps** | Docker, GitHub Actions, Azure DevOps, CI/CD, pytest, Git |
| **Visualization** | Power BI, Matplotlib, Plotly |

---

### Certifications

- AWS Cloud Foundations
- AWS Machine Learning Foundations
- PCAP: Certified Associate in Python Programming
- MySQL Basics

### Education

- **M.S. Computer Science**, Texas A&M University–Corpus Christi
- **B.Tech. Computer Science and Engineering (AI & ML)**, Vaagdevi College of Engineering

---

### Contact

[![Email](https://img.shields.io/badge/Email-guggillaranjith17%40gmail.com-EA4335?logo=gmail&logoColor=white)](mailto:guggillaranjith17@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ranjithguggilla-0A66C2?logo=linkedin)](https://www.linkedin.com/in/ranjithguggilla/)
[![GitHub](https://img.shields.io/badge/GitHub-ranjithguggilla-181717?logo=github)](https://github.com/ranjithguggilla)
