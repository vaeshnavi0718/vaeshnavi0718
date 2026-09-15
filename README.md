# Hello, I'm Vaeshnavi Vella
I'm an **AI/ML Engineer** building intelligent, agentic systems — from **RAG pipelines** and **multi-agent orchestration** to production-grade LLM applications. I'm currently a Data Engineer at the Community Dreams Foundation, building scalable ETL pipelines, alongside my core work as a Junior AI Engineer developing production agentic systems.

🔭 **Current Focus:** Building **human-in-the-loop + agentic** AI systems using **LangGraph** and **LangChain**.

🆕 **Latest build:** An auditable, human-in-the-loop multi-agent loan underwriting pipeline — [try the live demo](https://loan-underwriting-pipeline.onrender.com) 👇

📫 **Connect:** [LinkedIn](https://www.linkedin.com/in/vaeshnavi-vella) | vaeshvella18@gmail.com

---
## 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Render](https://img.shields.io/badge/Render-%23000000.svg?style=for-the-badge&logo=render&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-%23E25A1C.svg?style=for-the-badge&logo=apache-spark&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-%23017CEE.svg?style=for-the-badge&logo=Apache%20Airflow&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-%234479A1.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---
## 🚀 Featured Projects:

### 🏦 [Auditable Multi-Agent Loan Underwriting Pipeline](https://github.com/vaeshnavi0718/loan-underwriting-pipeline)
**Solo-built — architecture, agents, guardrails, and deployment**
### 🔗 [Live Demo](https://loan-underwriting-pipeline.onrender.com) &nbsp;|&nbsp; 💻 [Source Code](https://github.com/vaeshnavi0718/loan-underwriting-pipeline)

An agentic loan underwriting system built around one hard rule: **the AI can analyze, but only a human can decide.**

* Architected an **Agent Harness** — a central orchestration layer coordinating 4 specialized agents (document extraction, data enrichment, risk analysis, LLM-based review) through a 7-stage pipeline with shared state, routing, retries, and the ability to pause and resume incomplete applications.
* Enforced a hard guardrail so **no AI agent can ever issue a final approve/deny decision** — verified by an automated test that raises a `GuardrailViolation` if any agent attempts to override it. Final decision authority lives in a single, human-only code path, structurally decoupled from every agent and LLM call.
* Delivered explainable risk reports across 12 synthetic underwriting scenarios using a rule-based scoring engine spanning 5 risk dimensions: debt-to-income, credit risk, income stability, cash flow risk, and loan exposure.
* Backed by 11 automated backend tests (100% pass rate) and deployed live on Render — click through the demo above to run a full underwriting scenario yourself.

---

### [Intelligent Digital Assets Assistant (IDAA)](https://github.com/AdityaNikhil/IDAA)
**Core Contributor for Advisor Agent**
* Architected a multi-agent system using **LangGraph** and **LangChain**, implementing a Supervisor LLM to route intent-based queries with 90% accuracy.
* Engineered an end-to-end **Agentic RAG pipeline** with **FAISS** vector indexing, achieving sub-200ms retrieval latency.
* Implemented **Redis caching** and **FastAPI** backends, reducing embedding computation by 60% during high-concurrency periods.
* Designed semantic retrieval logic (cosine similarity >0.75) for contextually accurate investment recommendations.

---
## 📓 Tech Journal (upcoming)
I document everything I learn: concepts, paper summaries, interview prep, and weekly notes, in my open learning journal.
👉 [vaeshnavis-tech-journal](https://github.com/vaeshnavi0718/vaeshnavis-tech-journal)
*If you're studying AI/ML too, feel free to follow along or use it as a reference.*

---
## 🍰 Beyond the Code:
When I'm not shipping features or architecting agentic workflows, I'm likely:
* ☕ **Cafe Hopping:** Exploring the local coffee scene for the best matcha.
* 🎮 **Cozy Gaming:** Relaxing with low-stress, aesthetic games (Animal Crossing fans assemble!!)
* 🍓 **Strawberry Lover:** Always on the hunt for the perfect strawberry-themed dessert!
