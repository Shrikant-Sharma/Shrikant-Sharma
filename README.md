# Hi, I'm Shrikant 👋

Data Scientist with ~8 years across pharma (Amgen) and financial services (American Express). Building production ML and grounded RAG systems for regulated industries. Open to Senior Data Scientist, Decision Scientist, Applied Scientist, ML Engineer, and AI Engineer roles.

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=flat)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-3776AB?style=flat&logo=python&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0668E1?style=flat&logo=meta&logoColor=white)
![RAGAS](https://img.shields.io/badge/RAGAS-FF6F00?style=flat&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

## 🚀 Featured Projects

### 🧬 [Clinical Trial Intelligence System](https://github.com/Shrikant-Sharma/clinical-trial-rag) · [Live demo](https://shrikant-clinical-rag.streamlit.app)

Agentic RAG pipeline over 484 ClinicalTrials.gov oncology protocols (3,264 chunks). Phase 2 upgraded the baseline to a LangGraph-orchestrated **Corrective RAG (CRAG)** pattern with LLM-as-judge document relevance grading, query rewriting on poor retrieval, and bounded retries. Three independent refusal gates were empirically validated when gibberish input scored 0.91 cosine similarity but was correctly refused by the grader. PubMedBERT embeddings, FAISS retrieval, Groq Llama 3.3 70B with source-cited responses. Two-mode UI lets users A/B the agentic flow against the baseline pipeline. Evaluated retrieval and generation with RAGAS-equivalent metrics across a 25-query stress test and 3 chunking strategies.

**Built with:** Python, LangGraph, Sentence Transformers (PubMedBERT), Groq Llama 3.3 70B, FAISS, RAGAS, Streamlit, Git

---

### 🩺 [Patient Risk Stratification Pipeline](https://github.com/Shrikant-Sharma/patient-risk-stratification)

End-to-end ML pipeline on the UCI Heart Disease dataset (303 patients, 13 clinical features). Trained 5 classification models (Logistic Regression, Random Forest, XGBoost, SVM, PyTorch NN) with MLflow experiment tracking; tuned top 3 via RandomizedSearchCV with 5-fold cross-validation. Tuned XGBoost reached 0.95 ROC-AUC with 0.93 recall at clinical operating threshold. Added SHAP TreeExplainer for global and per-patient explanations, calibration analysis (Brier score 0.092, reliability curves), and threshold tuning for clinical screening. Deployed as a REST API via FastAPI with /predict and /explain endpoints; containerized via multi-stage Docker.

**Built with:** Python, Scikit-learn, XGBoost, PyTorch, SHAP, MLflow, FastAPI, Pydantic, Docker, Git

---

### 📊 [Pharma Compliance Spend Analytics](https://github.com/Shrikant-Sharma/pharma-compliance-spend-analytics) · [Live dashboards](https://public.tableau.com/shared/ZSDPNCN8B?:display_count=n&:origin=viz_share_link)

Compliance spend analytics on real CMS Open Payments data: 16M+ federal records ($13B). Sampled 989K transactions across 289K unique HCPs and engineered HCP-level features (payment frequency, total value, geographic concentration, company diversity). Applied within-specialty z-scores and global IQR with a $500 monetary floor and concentration logic; flagged the top 1.67% as a HIGH-tier triage queue. IQR caught 30,223 HCPs that z-score alone missed. Surfaced an orthopedic device-manufacturer concentration finding (Stryker, Arthrex, Zimmer Biomet, Boston Scientific). Two interactive Tableau Public dashboards.

**Built with:** Python (Pandas, NumPy, SciPy), Tableau, Git

---

## 🌱 Currently Deepening
Causal Inference · Survival Analysis · Apache Spark


## 📫 Let's Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/shrikant-sharma)
[![Tableau](https://img.shields.io/badge/Tableau_Public-E97627?style=flat&logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/shrikant.sharma)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:shrikant.sharma@myyahoo.com)
