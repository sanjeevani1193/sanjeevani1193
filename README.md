
<div align="center">

# Hi, I'm Sanjeevani! 👋

### AI/ML Engineering | Data Science & Analytics

MSc Data Science @ Universität Mannheim 🇩🇪  
First-Class Honors BSc Computer Science (Data Science) @ Heriot-Watt University

[LinkedIn](https://www.linkedin.com/in/sanjeevani-rajpurohit-690103144/) · [Email](mailto:sanjeevani1109@gmail.com) · [Repositories](https://github.com/sanjeevani1193?tab=repositories)

</div>

---

### 🌱 About Me

I enjoy building **AI, machine learning, and data science systems that go beyond the notebook** — from data engineering and model development to statistical experimentation, evaluation, cloud deployment, and interactive applications.

I'm currently completing my **MSc in Data Science at the University of Mannheim** (expected March 2027), with interests spanning **AI/ML Engineering, Data Science, NLP, LLMs, and applied analytics**.

- 🔬 **Currently researching:** Low-resource **Odia machine translation**, exploring multilingual transfer, model adaptation, and data augmentation for English–Odia and Hindi–Odia translation.
- 📈 **Recently shipped:** [GrowthLab](https://github.com/sanjeevani1193/GrowthLab), an end-to-end customer intelligence platform combining predictive ML, causal analysis, A/B experimentation, reward economics, and personalized product ranking. [**Live Demo ↗**](https://growthlab-decision-studio.streamlit.app/)
- ⚙️ **ML Engineering:** Built [CityPulse AI](https://github.com/sanjeevani1193/CityPulse-AI), a large-scale urban mobility ML platform featuring forecasting, agentic analytics, cloud deployment, and CI/CD. Its five-workspace Decision Studio is now publicly accessible. [**Live Demo ↗**](https://citypulse-ai-decision-studio.streamlit.app/)
- 📊 **Industry background:** Data analytics and technical project management, with experience in business intelligence, reporting, and cross-functional collaboration.
- 🎯 **Interested in:** AI/ML Engineering, Data Science, applied AI research, and building reliable systems that solve meaningful problems.

### 🛠️ Technical Toolkit

| Area | Technologies & Methods |
|---|---|
| **Languages & Data** | Python, SQL, R, pandas, NumPy, DuckDB, SQLite, Parquet |
| **Machine Learning & Statistics** | scikit-learn, XGBoost, SciPy, statsmodels, A/B Testing, Causal Inference, Uplift Modeling, Learning to Rank |
| **Deep Learning & NLP** | PyTorch, TensorFlow, Hugging Face Transformers, SentenceTransformers, LoRA/QLoRA |
| **LLMs & Agentic AI** | vLLM, LangChain, LangGraph, MCP, ChromaDB |
| **Backend & MLOps** | FastAPI, REST APIs, Docker, Docker Compose, MLflow, GitHub Actions (CI/CD), pytest |
| **Cloud & Analytics** | GCP, Cloud Run, Cloud Storage, Cloud Build, Terraform, Streamlit, Plotly, Matplotlib, Power BI, Excel |
| **Collaboration** | Git/GitHub, Jira, Notion, Agile/Scrum |

### 🚀 Selected Projects

### 📈 [GrowthLab — Predictive Analytics, Experimentation & Decision Intelligence](https://github.com/sanjeevani1193/GrowthLab) | [Live Demo ↗](https://growthlab-decision-studio.streamlit.app/)

*Customer Analytics · Predictive ML · A/B Testing · Causal Inference · Personalized Ranking · Decision Intelligence*

An end-to-end **customer intelligence and decision-support platform** combining predictive modeling, statistical experimentation, causal analysis, reward economics, and personalized product recommendations.

- Engineered customer-level purchase prediction pipelines from **20.7M e-commerce events**, achieving **0.8487 held-out ROC-AUC** and **5.92× top-decile lift** using XGBoost.
- Analyzed **45.8M historical purchase-item records** and a **200K-customer SMS treatment/control dataset**; evaluated S-/T-Learner uplift models using held-out policy comparisons and bootstrap confidence intervals, finding no statistically established targeting improvement over random selection.
- Developed a reproducible **A/B experimentation framework** with statistical power analysis, randomization, SRM checks, and A/A–A/B simulations; built a reward economics engine for profitability, break-even, and sensitivity analysis.
- Built a two-stage **personalized product recommendation system** with ML reranking, achieving **18.42% macro Recall@10** and **0.2163 NDCG@10** on a 370K-customer temporal holdout.
- Developed and deployed a **seven-workspace Streamlit Decision Studio**, containerized with Docker and validated with **353 passing automated tests**.

**Stack:** Python, SQL, DuckDB, XGBoost, scikit-learn, SciPy, statsmodels, Streamlit, Plotly, Docker.

**🔗 [Live Application](https://growthlab-decision-studio.streamlit.app/) · [GitHub Repository](https://github.com/sanjeevani1193/GrowthLab)**

---

### 🚲 CityPulse AI — ML Forecasting, Agentic AI & MLOps

**[Live Demo ↗](https://citypulse-ai-decision-studio.streamlit.app/) · [GitHub](https://github.com/sanjeevani1193/CityPulse-AI)**

*Data Engineering · Time-Series Forecasting · Deep Learning · Agentic AI · Cloud · MLOps*

An end-to-end urban mobility ML platform combining historical NYC Citi Bike data engineering, station-level forecasting, agentic analytics, and reproducible synthetic experimentation.

- Engineered **DuckDB/Parquet ETL** processing approximately **90M accepted ride starts over 24 months** into **19.36M station-hour records**, with validation, DST-aware aggregation, memory-bounded processing, and recoverable checkpoints.
- Benchmarked **six forecasting approaches** across 100 stations: XGBoost, PyTorch MLP/TFT, TensorFlow LSTM, and lag-24/lag-168 seasonal baselines. XGBoost achieved **26.9% lower held-out MAE than lag-24** across **220,800 test targets**; experiments tracked with **MLflow**.
- Independently developed **SQLPilot** using **LangGraph, MCP client/server tools, and Groq-hosted LLM inference**, with guarded read-only SQL validation, bounded error recovery, and reference-query evaluation. The public demo executes curated read-only SQL; it does **not** call a live LLM or run an agent/MCP session.
- Developed **ExperimentLab** for reproducible **synthetic A/B experimentation** using Welch's t-test, CUPED, confidence intervals, and power analysis. These are simulated outcomes, not real-world intervention results.
- Deployed authenticated, **Dockerized XGBoost inference on GCP Cloud Run** with **Terraform, Cloud Build, GitHub Actions CI/CD**, and exact saved-validation local/cloud prediction parity. Subsequently published an independently hosted **Streamlit + Plotly Decision Studio** with **Overview, Forecast Explorer, Model Comparison, SQLPilot, and ExperimentLab & Methodology**. The public app explores saved forecasts and research evidence without a GCP runtime dependency; the historical cloud CD workflow is now disabled.

**Stack:** Python, SQL, DuckDB, Parquet, XGBoost, PyTorch, TensorFlow, LangGraph, MCP, Groq, FastAPI, Docker, MLflow, GCP, Cloud Build, Terraform, GitHub Actions CI/CD, Streamlit, Plotly.

---

### 🔐 Master's Thesis — Multilingual LLM Systems & Odia Machine Translation

*Natural Language Processing · Low-Resource Machine Translation · Multilingual LLMs · Model Adaptation*

My MSc research focuses on improving machine translation for **Odia**, a low-resource Indic language, building on earlier work developing a self-hosted multilingual LLM system for privacy-sensitive documents.

- Investigating **English↔Odia and Hindi↔Odia translation**, multilingual transfer from related Indic languages, and low-resource adaptation strategies.
- Researching **supervised fine-tuning, continued pretraining, back-translation, and multilingual data augmentation**, with emphasis on systematic benchmarking and reproducible evaluation.
- Previously developed a self-hosted multilingual LLM prototype with a quantized **Gemma 3 4B** model served through vLLM, a FastAPI backend, Streamlit frontend, and document retrieval.

**Stack:** Python, PyTorch, Hugging Face Transformers, vLLM, FastAPI, Streamlit, ChromaDB.

---

### 💡 More Projects

| Project | Highlights |
|---|---|
| [Book Recommendation System — Bachelor's Thesis](https://github.com/sanjeevani1193/Book-Recommendation-System-Using-Machine-Learning-Techniques) | Benchmarked 4 recommendation approaches across 2 datasets with ~7.1M user ratings, including collaborative, content-based, and hybrid filtering. |
| [Conversational Book Recommendation Assistant](https://github.com/sanjeevani1193/Conversational-Book-Recommendation-Assistant-using-RAG) | LLM-powered conversational recommendations using RAG, semantic retrieval, LangChain, LangGraph, and API integration. |
| [Sentiment Analysis & AI Summarization](https://github.com/sanjeevani1193/Sentiment-Analysis-AI-Summarization-of-User-Reviews) | Analyzed 568,454 Amazon product reviews using VADER sentiment analysis, transformer-based summarization, and visualizations. |
| [Automotive Warranty & Service Analytics](https://github.com/sanjeevani1193/Automotive-Warranty-Service-KPI-Dashboard---German-Market) | Python/SQL analytics across 3 interconnected synthetic datasets, with 5 operational KPIs and business reporting. |

---

### ☕ Beyond Code

Outside technology, I enjoy reading, writing poetry, hiking and strength training. I'm always excited to learn something new, collaborate on interesting problems, and connect with people who enjoy building things.

### 📫 Let's Connect!

I'm exploring opportunities in **AI/ML Engineering, Data Science, and Analytics** and am open to relocation.

📍 Mannheim, Germany

💼 [LinkedIn](https://www.linkedin.com/in/sanjeevani-rajpurohit-690103144/) · 📧 [Email](mailto:sanjeevani1109@gmail.com)

