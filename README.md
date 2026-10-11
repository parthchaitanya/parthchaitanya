<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Parth%20Chaitanya&fontSize=52&fontColor=00ffd0&animation=fadeIn&fontAlignY=38&desc=LLM%20apps%20%E2%80%A2%20Agentic%20RAG%20%E2%80%A2%20ML%20pipelines&descAlignY=60&descSize=18" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1000&color=00FFD0&center=true&vCenter=true&width=600&lines=%24+whoami+%E2%86%92+B.Tech+AI+%26+ML+student;%24+building+--agents+--rag+--pipelines;%24+status+%E2%86%92+shipping+with+Docker+%2B+CI%2FCD;%24+open_to+%E2%86%92+internships+%26+collabs" alt="Typing SVG" />
</a>

</div>

---

## `~/boot.log`

```console
[  OK  ] Loaded module      : Python, FastAPI, LangGraph, Pinecone
[  OK  ] Mounted            : B.Tech AI & ML @ Galgotias College of Engineering & Technology (2024 → now)
[  OK  ] Started service    : Program Management Intern @ NeGD, MeitY
[  OK  ] Started service    : Technical Coordinator @ GeeksForGeeks CB
[  OK  ] Reached target     : 500+ students engaged, 2 hackathons organized
[ INFO ] Hallucinations     : bounded retries enabled
[ INFO ] Current mode       : build → test → containerize → ship
```

---

## 🧠 My workflow, as an agent graph

```mermaid
flowchart LR
    A([💡 Idea]) --> B{Route}
    B -->|needs data| C[(Retrieve<br/>Pinecone)]
    B -->|needs logic| D[Build<br/>FastAPI]
    C --> E{Grade<br/>evidence}
    E -->|weak| F[Rewrite query]
    F --> C
    E -->|good| G[Generate]
    D --> G
    G --> H[🧪 pytest]
    H --> I[🐳 Docker]
    I --> J[⚙️ GitHub Actions]
    J --> K([🚀 Shipped])
```

---

## 🚀 Deployed services

### 🔎 RemoteHunt: AI Job-Search Assistant &nbsp; [`🌐 Live Demo`](#)
> *Finds the jobs, scores the match, fixes the resume.*

| Component | What it does |
|---|---|
| **Ingestion** | Plugin-based system for 20+ sources (Greenhouse, Lever, Ashby), ~40 company boards, with API budgets, 429 back-off and health checks |
| **Pipeline** | 6 stages: dedupe → scam detection → eligibility → match scoring, ranked by MiniLM similarity, skill overlap and seniority fit |
| **Resume engine** | 0–100 ATS score, LLM suggestions, skill-gap analysis and a **truthfulness guardrail** that blocks fabricated claims |
| **Automation** | Gmail API (OAuth) + APScheduler |
| **Quality** | 60+ pytest tests in CI, public demo running in **<512 MB RAM** |

`Python` `FastAPI` `SQLAlchemy` `sentence-transformers` `Groq` `React` `Tailwind` `Docker` `GitHub Actions`

---

### 🏢 Enterprise HR Policy Copilot: Agentic RAG &nbsp; [`📂 Repo`](#)
> *An agent that says "I don't know" instead of making things up.*

- **LangGraph** workflow: query routing → LLM evidence grading → query rewriting → bounded retries
- **Private-first retrieval** on Pinecone + OpenAI embeddings, answered without falling back to Tavily web search
- **FastAPI** endpoints, secured ingestion, SQLite audit trail, Dockerized, validated on 4 end-to-end scenarios

`LangGraph` `FastAPI` `Pinecone` `OpenAI` `Tavily` `SQLite` `Docker`

---

### 🔥 Forest Fire Index Predictor &nbsp; [`📂 Repo`](#)
> *Benchmarked 4+ algorithms on 5,000+ weather records.*

```diff
+ R² > 0.98
+ ~22% lower RMSE
+ <1s prediction latency in a live Streamlit dashboard
```

`Scikit-learn` `Pandas` `NumPy` `Matplotlib` `Streamlit`

---

## 🏛️ Experience

**Program Management Intern @ NeGD, Ministry of Electronics & IT (MeitY)** `Jun – Jul 2026`
- Built a dual-interface portal (Project Manager + developer views) for project tracking
- Built an LLM-powered document reader that scores project health from SharePoint data
- Tested 6 government websites end to end (DPDP, LBSNAA, MoSJE, SPORTS, MoTA, UPSC) and helped design Suvidha sites

---

## 🧰 Tech stack

<div align="center">

![Python](https://img.shields.io/badge/Python-0f2027?style=for-the-badge&logo=python&logoColor=00ffd0)
![Java](https://img.shields.io/badge/Java-0f2027?style=for-the-badge&logo=openjdk&logoColor=00ffd0)
![JavaScript](https://img.shields.io/badge/JavaScript-0f2027?style=for-the-badge&logo=javascript&logoColor=00ffd0)
![SQL](https://img.shields.io/badge/SQL-0f2027?style=for-the-badge&logo=postgresql&logoColor=00ffd0)

![FastAPI](https://img.shields.io/badge/FastAPI-203a43?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-203a43?style=for-the-badge&logo=flask&logoColor=white)
![React](https://img.shields.io/badge/React-203a43?style=for-the-badge&logo=react&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-203a43?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-203a43?style=for-the-badge&logo=streamlit&logoColor=white)

![OpenAI](https://img.shields.io/badge/OpenAI-2c5364?style=for-the-badge&logo=openai&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-2c5364?style=for-the-badge&logo=langchain&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-2c5364?style=for-the-badge&logo=pinecone&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-2c5364?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2c5364?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-2c5364?style=for-the-badge&logo=numpy&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-0f2027?style=for-the-badge&logo=docker&logoColor=00ffd0)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-0f2027?style=for-the-badge&logo=githubactions&logoColor=00ffd0)
![MySQL](https://img.shields.io/badge/MySQL-0f2027?style=for-the-badge&logo=mysql&logoColor=00ffd0)
![MongoDB](https://img.shields.io/badge/MongoDB-0f2027?style=for-the-badge&logo=mongodb&logoColor=00ffd0)
![SQLite](https://img.shields.io/badge/SQLite-0f2027?style=for-the-badge&logo=sqlite&logoColor=00ffd0)

</div>

---

## 📊 Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0f2027" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true&bg_color=0f2027" />

<img src="https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=tokyonight&hide_border=true&background=0f2027" />

</div>

---

## 📡 Connect

<div align="center">

[![Email](https://img.shields.io/badge/Email-chaitanyaparth.17@gmail.com-00ffd0?style=for-the-badge&logo=gmail&logoColor=black)](mailto:chaitanyaparth.17@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Twitter](https://img.shields.io/badge/Twitter-Follow-1da1f2?style=for-the-badge&logo=x&logoColor=white)](#)

```console
$ echo "Let's build something that doesn't hallucinate."
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" />

</div>
