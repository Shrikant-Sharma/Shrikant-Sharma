# Hi, I'm Shrikant 👋

Data Scientist with ~8 years building ML models, statistical systems, and data pipelines across pharma (Amgen) and financial services (American Express). Currently focused on ML engineering, NLP, and bringing models from notebooks to production.

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-3776AB?style=flat&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=flat)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)
![RAGAS](https://img.shields.io/badge/RAGAS-FF6F00?style=flat&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

## 🚀 Featured Projects: Currently building

### 🧬 [Clinical Trial Intelligence System]
RAG pipeline that ingests 500+ clinical trial protocols from ClinicalTrials.gov for natural language querying with source-cited responses. Evaluated retrieval quality using RAGAS metrics (precision@k, MRR, faithfulness) across 20+ test queries and 3 chunking strategies, achieving 85%+ retrieval relevance.

**Built with:** Python, LangChain, FAISS, OpenAI, Streamlit, RAGAS, Docker

---

### 🩺 [Patient Risk Stratification Pipeline]

End-to-end ML pipeline on the UCI Heart Disease dataset (303 patients, 13 clinical features). Trained 5 classification models (Logistic Regression, Random Forest, XGBoost, SVM, PyTorch NN) with MLflow experiment tracking; tuned top 3 via RandomizedSearchCV with 5-fold cross-validation. Tuned XGBoost reached 0.95 ROC-AUC with 0.93 recall at clinical operating threshold. Added SHAP TreeExplainer for global and per-patient explanations, calibration analysis (Brier score, reliability curves), and threshold tuning for clinical screening. Deployed as a REST API via FastAPI with /predict and /explain endpoints; containerized via multi-stage Docker.

**Built with: Python, Scikit-learn, XGBoost, PyTorch, SHAP, MLflow, FastAPI, Pydantic, Docker, Git

---

### 📊 [Pharma Compliance Spend Analytics]
Compliance spend analytics system built on real CMS Open Payments federal data. Engineered HCP-level features and applied statistical anomaly detection (z-score, IQR) to flag unusual payment patterns across specialties and regions. Visualized findings in Tableau with geographic heatmaps and flagged-provider drill-downs.

**Built with:** Python (Pandas, NumPy, SciPy), Tableau

---

## 🌱 Currently Deepening
MLOps · Model Deployment · Production ML Pipelines · Generative AI/LLMs

## 📫 Let's Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/shrikant-sharma)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:shrikant.sharma@myyahoo.com)
<!---
Shrikant-Sharma/Shrikant-Sharma is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
