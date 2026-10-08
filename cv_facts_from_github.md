# CV facts found on GitHub (motechbello1)

Collected 2026-10-08 from public repos. Only facts seen in the code or READMEs are listed.
Items marked **ASK** need Bello to confirm before they go on a CV or a job form.

## Strong projects (job-ready)

### 1. NaijaClimaGuard: flood warnings for Nigeria
- Repos: `naijaclimaguard` (app), `naijaclimaguard-ml-api` (model API), `naijaclimaguard-ml`, `NaijaClimaGuard-v1.0-NBTI-NextGen-2026`
- ML API: **FastAPI + XGBoost**, deployed on Render with Docker. Endpoints `/health` and `/v1/risk?latitude=..&longitude=..`.
- Model trained on 10,000+ samples across 5 Nigerian flood zones (2018-2023), using Open-Meteo rainfall data (NASA GPM IMERG derived).
- App: Next.js + TypeScript + Prisma, on Vercel. Warnings over WhatsApp, SMS, USSD and voice in English and Pidgin. Uses official NiMet / NIHSA / NEMA sources with human approval. "FloodPass" proof codes for banks, insurers and charities.
- Has automated GitHub Actions bots updating it (active as of 2026-10-08).
- Fits: ML Engineer, Applied AI, MLOps, FastAPI, Full-stack, AI Solutions, development-sector roles in Abuja.

### 2. SmartHire: AI CV ranking with fairness checks
- Repos: `smarthire-backend`, `smarthire-frontend`
- **FastAPI**, SQLAlchemy, Alembic, PostgreSQL, Pydantic, JWT auth, rate limiting (slowapi). Deployed on Railway with Docker.
- Ranks CVs against a job with a multilingual BERT model (sentence-transformers `paraphrase-multilingual-MiniLM-L12-v2`) and cosine similarity.
- LIME explanations, a fairness-evaluation API, active learning from recruiter feedback, and a Nigerian-CV parser (PDF and Word).
- Fits: Python Backend, FastAPI, NLP / Applied AI, Responsible AI.

### 3. XAI Risk Prediction: explainable credit risk
- Repo: `XAI-Risk-Prediction` (also older `Financial-Risk-Assessment-XAI`)
- XGBoost + TreeSHAP + constrained DiCE counterfactuals on the FICO HELOC data (10,459 applicants, 23 features). WoE, SMOTE, Optuna tuning, DeLong tests.
- Test AUC 0.7933, Gini 0.5865, KS 0.4433 (seed 42, reproducible).
- Live website on Vercel (Python API) plus a Streamlit app. Model export checked to match on all 10,459 profiles.
- **ASK:** The README says this is code for the MSc dissertation of **Jamal E.O. Obaseki (Baze University)**. What was your role? If you built it for him, the honest CV line is "Built the ML pipeline and web app for an MSc dissertation project", not your own research.
- Fits: Data Scientist, ML Engineer, fintech and bank roles.

### 4. Diagnova: app-quality diagnosis engine
- Repos: `diagnova-backend`, `diagnova-frontend`
- Rule-based expert system (Flask API, Python 3.11, Render) that scores mobile-app startup time, memory and frame rate and gives fixes.
- Fits: Python Backend, AI Solutions (expert systems).

### 5. ICT Department Portal and NBTI tools
- `ICT-Report-Portal`: Streamlit + Plotly app logging ICT work across 7 sectors (cybersecurity, network, cloud, hardware, software, database, VoIP) and events, writing weekly Word reports automatically.
- `NBTIICT-DEPARTMENT-ATTENDANCE-FACIAL-RECOGNITION`: face-recognition attendance.
- `NBTI-PRESENCE-`
- **ASK:** Do you work (or did you work) in the ICT department at NBTI? Job title, start date, and what you do there. This would be your main work experience on the CV.

### 6. Medical and other ML projects
- `MSC_THESIS`: Streamlit malaria app with CNN image model + Random Forest and Logistic Regression on clinical data, with SHAP. **ASK:** whose MSc is this, and did you complete an MSc? Which university, which year?
- `Malaria-Detection-using-CNN`, `Brain-Tumor-Detection-ML`, `Breast-cancer-Detection-ML`, `Breast-Cancer-Ensemble`, `Pest-Detection-In-Plant-ML`
- `churn-prediction-portfolio`, `Medical-Insurance-Cost-Predictor.`, `Project-Sentiment-Analysis-App-NLP-`, `Project-Computer-Vision-Image-Recognition-.`
- `redundant-paths-dijkstra` / `Redundant-Path-Optimzation-Algorithm`: graph path algorithm.
- `voting-dapp`: blockchain voting app (leave off for most roles).

## Skills with evidence in the code
Python, FastAPI, Flask, Streamlit, XGBoost, scikit-learn, TensorFlow/Keras, sentence-transformers (BERT), SHAP, LIME, DiCE, Optuna, pandas, NumPy, SQLAlchemy, PostgreSQL, Alembic, Docker, Render, Railway, Vercel, GitHub Actions, Next.js, TypeScript, Prisma, Tailwind.

## Claimed on the GitHub profile but not yet seen in code
PyTorch, R, Java, AWS, GCP, Kubernetes. **ASK:** keep these only if you can answer interview questions on them.

## Still missing (needed for applications)
1. Work history: employers, titles, dates.
2. Degree status: Middlesex BSc result (the 2021 CV says "awaiting result"), any MSc.
3. LinkedIn profile URL (not found by web search under "Bello Muhammed Mustapha" or "Bello Muhammad Mustapha").
4. Any teaching or training experience (needed for AI/ML Instructor and Trainer roles).
5. Live links for NaijaClimaGuard and SmartHire, if public.

## Quick fixes spotted
- GitHub profile README links to `linkedin.com/in/yourlinkedin/`, a placeholder. Replace with your real URL.
- Your name is spelled "Muhammed" on the CV and "Muhammad" in git commits. Pick one and use it everywhere, so recruiters can find you.
