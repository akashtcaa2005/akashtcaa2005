<div align="center">

# Hi, I'm Akash T 👋

### AI & Machine Learning Engineer (in progress) · Generative AI · Data Science

*Final-year AI & Data Science student building practical, end-to-end ML and GenAI systems.*

[![Portfolio](https://img.shields.io/badge/Portfolio-akashtcaa2005.github.io-0A66C2?style=flat-square)](https://akashtcaa2005.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Akash%20T-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/akash-t-845439314/)
[![Email](https://img.shields.io/badge/Email-akashtcaa.2005%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:akashtcaa.2005@gmail.com)

</div>

---

## About Me

I'm a 4th-year B.Tech student in **Artificial Intelligence & Data Science**, working toward roles as an **AI Engineer / ML Engineer / GenAI Engineer**. My focus is building things end-to-end rather than just running notebooks — data pipeline → model → API → working interface.

Most of what's below is reflected directly in the repositories on this profile; anything I couldn't verify from a public repo is marked accordingly rather than presented as finished work.

## 🚀 Currently Building

- Production-oriented ML/AI applications (FastAPI + scikit-learn + Docker)
- Generative AI / LLM / RAG systems
- Interview-level Data Structures & Algorithms (150+ LeetCode problems solved)
- Preparing for AI Engineer / ML Engineer / Data Scientist / SDE placement interviews

## 🧭 Engineering Philosophy

**Learn → Build → Evaluate → Deploy → Improve**

I prefer learning a concept by shipping a small working version of it, then iterating — rather than studying it in the abstract first.

---

## 🛠️ Tech Stack

**Languages**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**ML / Deep Learning**
![scikit-learn](https://img.shields.io/badge/-scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat-square&logo=keras&logoColor=white)

**Generative AI**
![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square)
![Hugging Face](https://img.shields.io/badge/-Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

**Data Science**
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat-square)

**Backend / Web**
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Databases / Cloud / Tools**
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 🌟 Featured Projects

### 🔍 [AI Insight Lab](https://github.com/akashtcaa2005/ai-insight-lab)
**End-to-end ML platform for CSV data analysis** — upload any CSV and get dataset profiling, data-quality checks, statistics, auto-generated visualizations, model training, and live prediction from a single dashboard.

- **Problem solved:** removes the notebook-and-manual-EDA cycle for tabular ML — one flow from raw CSV to a downloadable trained model
- **What I built:** FastAPI backend with a scikit-learn `Pipeline` + `ColumnTransformer` (imputation, scaling, one-hot encoding), 8 selectable models (Logistic Regression, Random Forest, SVM, KNN, Decision Tree for classification; Linear/Decision Tree/Random Forest for regression), auto EDA (correlations, outliers via IQR, skew/kurtosis), and a dependency-free vanilla-JS frontend served from the same FastAPI process
- **Key technical feature:** heuristic classification-vs-regression suggestion endpoint + downloadable `.joblib` model artifact
- **Stack:** Python · FastAPI · scikit-learn · Pandas · Matplotlib/Seaborn · Joblib
- 🔗 [Live demo](https://ai-insight-labs.streamlit.app/) · [Repository](https://github.com/akashtcaa2005/ai-insight-lab)

### 📈 [PredictX](https://github.com/akashtcaa2005/PredictX)
**Production-structured, asynchronous quantitative trading platform** for automated market analysis, strategy execution, and risk management via the Binance API.

- **Problem solved:** turns a trading strategy into a safely testable, monitorable automated system rather than a one-off script
- **What I built:** a modular pipeline (market data → strategy engine → risk engine → order manager → portfolio manager), a centralized risk engine (position/exposure/drawdown limits, duplicate-order prevention, kill switch), a fully isolated paper-trading mode, WebSocket + REST reconciliation, and structured logging/health monitoring
- **Key technical feature:** filesystem-based emergency kill switch and a strategy layer that's identical across paper and live trading, so strategies are validated risk-free before going live
- **Stack:** Python · FastAPI · PostgreSQL · React · Docker · Binance API (async)
- 🔗 [Repository](https://github.com/akashtcaa2005/PredictX)

### 💼 [Akash-T-Portfolio](https://github.com/akashtcaa2005/Akash-T-Portfolio)
AI-powered personal portfolio site showcasing projects, skills, and experience.
- **Stack:** HTML/CSS/JS
- 🔗 [Live](https://akashtcaa2005.github.io/) · [Repository](https://github.com/akashtcaa2005/Akash-T-Portfolio)

### 📊 [sales-analysis](https://github.com/akashtcaa2005/sales-analysis)
Python-based sales/customer data analysis project.
- 🔗 [Repository](https://github.com/akashtcaa2005/sales-analysis)

> **In progress (not yet a public repo):** **BioSense** — a wearable-data health monitoring concept with a future roadmap toward longitudinal trend analysis and explainable predictive insights. Currently design/prototype stage — not making any diagnostic claims.

---

## 🧗 AI Engineering Journey

```
Python
   ↓
Data Structures & Algorithms
   ↓
NumPy / Pandas / Statistics
   ↓
Machine Learning
   ↓
Deep Learning
   ↓
Generative AI / LLMs / RAG
   ↓
AI Agents
   ↓
Deployment (FastAPI, Docker)
```

---

## 💼 Experience

> ⚠️ A couple of internship names/dates below could not be cross-verified against a public repository and should be double-checked before this goes out — flagged inline.

**AI & ML Intern** — *(company name to verify)* · Recent
- Flask-based ML applications: Iris/Wine classification, house-price prediction (Random Forest, Linear Regression, Joblib)
- LLM applications, Transformers, U-Net, PDF/TXT RAG systems

**Machine Learning Intern** — *(company name to verify)*
- Supervised learning model development and evaluation

**AI & ML Intern** — *(company name to verify)*
- Computer vision project: Vision Transformer for a cats-vs-dogs classification task

**Data Science / AI & ML Intern — NXT Logic**
- Customer purchase behavior analysis

*(Note for Akash: your message for this README listed Taras Systems and Solutions / Mindenious EduTech / RV TECHLEARN / NXT Logic, while an earlier session on file has RV TECHLEARN / NXT Logic / VEI Technologies / Handshake AI (Project Lumiere) — pick the accurate current list and I'll lock in exact names and dates.)*

## 🏆 Achievements

- 🥇 **1st Prize — College Tech Day** (₹10,000)
- ✅ **150+ LeetCode problems** solved (Python)
- ✅ **HackerRank — Advanced SQL**
- 🎖️ **Microsoft Learn:** 25 badges, 2 trophies (Generative AI, Azure OpenAI, Responsible AI, Microsoft Fabric)

## 📚 Learning & Certifications

- Harvard **CS50: Introduction to AI with Python**
- **NPTEL — Introduction to Machine Learning** (IIT Kharagpur)
- **Hugging Face — AI Agents Course**
- **IIT Bombay — Programming in Java**
- HackerRank — Advanced SQL

**CS50 AI progress:** Degrees ✅ · Tic-Tac-Toe ✅ · Knights ✅ · Minesweeper ✅ · Heredity ✅ · PageRank (in progress)

## 🧩 DSA / LeetCode

150+ problems solved in Python, focused on interview-pattern coverage:

`Arrays` `Hash Maps` `Two Pointers` `Sliding Window` `Stack/Queue` `Binary Search` `Prefix Sum` `Recursion` `Linked Lists` `Trees` `Graphs` `Dynamic Programming`

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=akashtcaa2005&show_icons=true&theme=default&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=akashtcaa2005&layout=compact&hide_border=true)

</div>

---

## 📫 Connect With Me

[![Portfolio](https://img.shields.io/badge/Portfolio-akashtcaa2005.github.io-000000?style=for-the-badge&logo=github&logoColor=white)](https://akashtcaa2005.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/akash-t-845439314/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akashtcaa.2005@gmail.com)
