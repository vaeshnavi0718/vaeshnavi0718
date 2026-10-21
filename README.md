# Hello, I'm Vaeshnavi Vella
I'm an **AI Engineer** building agentic systems people can trust: **multi-agent orchestration**, **RAG**, and the **evaluations** that prove they work. I'm currently a **Junior AI Engineer at Macro Software Solution**, building a LangGraph agent that qualifies leads and hands high-intent conversations to a person. Before that I was a Data Engineer at the Community Dreams Foundation, building PySpark and Airflow pipelines on AWS.

🔭 **Current Focus:** human-in-the-loop agents for high-stakes workflows, **LLM evaluation** (code graders, LLM-as-judge), and **reinforcement learning** for personalization.

🆕 **Latest builds:** a multi-agent credit underwriting harness with a CI eval suite ([live demo](https://loan-underwriting-pipeline.onrender.com)) and Reading Buddy, a contextual bandit for dyslexia-friendly reading ([live demo](https://vaeshnavi0718.github.io/reading-buddy/)) 👇

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

### 🏦 [Auditable Multi-Agent Credit Underwriting Harness](https://github.com/vaeshnavi0718/loan-underwriting-pipeline)
**Solo-built: architecture, agents, guardrails, evals, and deployment**
### 🔗 [Live Demo](https://loan-underwriting-pipeline.onrender.com) &nbsp;|&nbsp; 💻 [Source Code](https://github.com/vaeshnavi0718/loan-underwriting-pipeline)

An agentic underwriting system built around one hard rule: **the AI can analyze, but only a human can decide.**

* Architected an **Agent Harness** coordinating 4 specialized agents (document extraction, data enrichment, rule-based risk analysis, LLM-based review) through a 7-stage workflow with shared state, retries, and pause/resume.
* Enforced a guardrail so **no AI agent can ever issue a final approve/deny decision**: every agent status change goes through one function that refuses it, and tests prove only the human-only code path can decide.
* Built a reusable **LLM evaluation suite** (12 labeled scenarios × 3 runs): code graders in CI (schema, pipeline status, grounding of 300+ cited dollar amounts, decision language) and an **LLM judge whose quotes are verified in code**.
* Validated the judge with a negative control (0/14 absent facts accepted); the evals caught the agent **misreading a risk rating in 6 of 7 reports**.

*The free-tier demo sleeps when idle: the first load takes about 30 seconds.*

---

### 📖 [Reading Buddy](https://github.com/vaeshnavi0718/reading-buddy)
**Solo-built: a rebuild of a learning buddy for dyslexic readers I first tried to make four years ago**
### 🔗 [Live Demo](https://vaeshnavi0718.github.io/reading-buddy/) &nbsp;|&nbsp; 💻 [Source Code](https://github.com/vaeshnavi0718/reading-buddy)

* Framed personalized reading support as a **contextual bandit** choosing among 24 reading settings (font, spacing, chunking, read-aloud speed).
* Compared 7 strategies on 300 simulated readers × 20 seeds: **contextual Thompson sampling cut regret 56%** vs fixed defaults and raised comprehension success for new readers from 45% to 59%.
* Interactive demo: watch strategies race on a simulated reader, or be the reader and let it adapt to you.

---

### [Intelligent Digital Assets Assistant (IDAA)](https://github.com/AdityaNikhil/IDAA)
**Core Contributor for Advisor Agent**
* Architected a multi-agent system using **LangGraph** and **LangChain**, implementing a Supervisor LLM to route intent-based queries with 90% accuracy.
* Engineered an end-to-end **Agentic RAG pipeline** with **FAISS** vector indexing, achieving sub-200ms retrieval latency.
* Implemented **Redis caching** and **FastAPI** backends, reducing embedding computation by 60% during high-concurrency periods.
* Designed semantic retrieval logic (cosine similarity >0.75) for contextually accurate investment recommendations.

---

### ☁️ [read-to-me](https://github.com/vaeshnavi0718/read-to-me)
A cute, minimal page that reads PDFs and web articles aloud, with sentence highlighting, voice choice and speed control (React + TypeScript).

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
