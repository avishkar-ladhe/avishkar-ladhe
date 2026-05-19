<!-- TYPING ANIMATION -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=6E40C9&center=true&vCenter=true&width=620&lines=Avishkar+Ladhe+%7C+SDE+%2B+AI%2FML+Engineer;Building+LLM+pipelines+%26+backend+systems;Hackathon+Winner+%C2%B7+Open+to+Remote" alt="Typing SVG" />
  </a>
</p>

<!-- STATUS BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/Open%20to%20Remote-22c55e?style=flat-square&logo=checkmarx&logoColor=white" />
  <img src="https://img.shields.io/badge/CGPA-9.05%2F10-6E40C9?style=flat-square" />
  <img src="https://img.shields.io/badge/Xenia%20Hackathon-Winner%202026-gold?style=flat-square" />
  <img src="https://img.shields.io/badge/SIH-Top%2045%20of%20900%2B-orange?style=flat-square" />
  <img src="https://komarev.com/ghpvc/?username=avishkar-ladhe&color=6E40C9&style=flat-square&label=Profile+Views" />
</p>

<!-- SOCIAL LINKS -->
<p align="center">
  <a href="https://linkedin.com/in/avishkar-ladhe">
    <img src="https://img.shields.io/badge/LinkedIn-avishkar--ladhe-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:avishkarladhe0@gmail.com">
    <img src="https://img.shields.io/badge/Email-avishkarladhe0%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/avishkar-ladhe/">
    <img src="https://img.shields.io/badge/LeetCode-avishkar--ladhe-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />
  </a>
</p>

---

## About

I'm a CS undergrad at VIIT Pune who builds things that actually work in production — not just Colab notebooks.

My projects tend to be **systems**: multi-agent LLM pipelines, behavioral auth engines, automated ML preprocessors. I care about clean APIs, measurable outcomes, and shipping code that someone else can actually run.

Strong in Gen AI, ML/DL, Java, OS, DBMS, CN, and SDLC. Comfortable on both the model side and the backend side. Looking for teams that move fast and care about craft.

Currently targeting **remote SDE, AI/ML, and backend roles** — internships available immediately, full-time from mid-2027.

---

## Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,java,js,react,fastapi,nodejs,express&perline=7" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=tensorflow,pytorch,sklearn,mongodb,postgres,mysql,git&perline=7" />
</p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,linux,vscode&perline=7" />
</p>

<details>
<summary><b>Full stack breakdown</b></summary>
<br/>

| Layer | Technologies |
|---|---|
| **Languages** | Python · Java · JavaScript · SQL · COBOL |
| **AI / ML** | LangGraph · Llama 3.1 · RAG · HuggingFace · Sentence Transformers · TensorFlow · PyTorch · Scikit-Learn · ChromaDB |
| **Backend** | FastAPI · Node.js · Express · RESTful APIs |
| **Frontend** | React · Next.js · TypeScript · TailwindCSS |
| **Databases** | ChromaDB (Vector DB) · PostgreSQL · MongoDB · MySQL · IBM DB2 · Supabase |
| **CS Fundamentals** | OS · DBMS · CN · SDLC · OOP · DSA |
| **DevOps & Tools** | Git · Docker · Linux · IBM z/OS · JCL · REXX |

</details>

---

## Achievements

| Award | Event |
|---|---|
| 🥇 **Winner** | Xenia Hackathon 2026 |
| 🎯 **Top 45 / 900+ teams** | Smart India Hackathon (SIH) — National Shortlist |

---

## Featured Projects

### SkillSync — RAG-Based Curriculum Gap Analyzer
> `Python` · `LangGraph` · `Llama 3.1 (8B)` · `ChromaDB` · `Sentence Transformers`

A **6-agent LLM pipeline** that mines job descriptions, maps extracted skills against university curriculum, and auto-generates compliance reports against 15 NBA/AICTE/UGC accreditation standards — replacing weeks of manual analyst work with a single pipeline run.

- Hybrid two-pass RAG with cosine similarity scoring (>0.70 matched / 0.45–0.70 partial / <0.45 gap)
- 200+ skills mapped across 10 categories
- Fully automated report generation against accreditation benchmarks

---

### SmartDetect — Multi-Factor Behavioral Authentication Engine
> `Python` · `FastAPI` · `MongoDB` · `OpenCV` · `Scikit-Learn`

A **4-factor behavioral auth system** — face recognition, voice verification, keystroke dynamics, and cursor analysis — fused into a single weighted risk score. Deployed as drop-in FastAPI endpoints.

- ROC-AUC threshold calibration per factor
- RESTful API with clean integration contract
- Production-ready architecture: stateless endpoints, MongoDB persistence

---

### InsightHub — AI-Powered Data Preparation Platform
> `Python` · `FastAPI` · `Next.js 14` · `TypeScript` · `Scikit-Learn` · `Supabase` · `TailwindCSS`

A **full-stack ML data preparation platform** — upload raw, messy datasets (CSV, Excel, JSON, or bulk ZIP) and get back a clean, processed dataset with zero manual effort. The platform profiles every column, recommends the optimal preprocessing strategy, and runs the full pipeline with per-column granular control.

- **Smart Imputation** — median, mean, KNN, MICE (IterativeImputer), regression, Random Forest
- **Outlier Handling** — Z-score, IQR, Winsorize, **Isolation Forest** (multivariate)
- **Indian Data Validation** — Aadhaar (Verhoeff checksum), PAN, phone, email, Age–DOB cross-check
- **AutoML endpoint** — trial RandomForest (classifier or regressor) with accuracy, F1, RMSE, R²
- **13 REST API endpoints** — full Swagger docs at `/docs`
- **Encoding & Scaling** — binary, one-hot, ordinal, frequency · StandardScaler, MinMaxScaler, RobustScaler

[![InsightHub](https://github-readme-stats.vercel.app/api/pin/?username=avishkar-ladhe&repo=InsightHub&theme=tokyonight&hide_border=true)](https://github.com/avishkar-ladhe/InsightHub)

---

### DataGuard-MF — Enterprise Mainframe Data Integrity Checker
> `COBOL` · `IBM DB2` · `JCL` · `REXX` · `IBM z/OS`

Production-style mainframe batch program with record-level validation across enterprise datasets, DB2 error logging with COMMIT/ROLLBACK atomicity, and full build lifecycle automation via REXX — Compile → Link-Edit → DB2 Bind → Execute in one job.

Built during VIIT's IBM mainframe curriculum — rare hands-on z/OS experience for an undergrad.

---

## GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=avishkar-ladhe&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&cache_seconds=86400" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=avishkar-ladhe&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&cache_seconds=86400" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=avishkar-ladhe&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D" />
</p>

---

## Activity Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=avishkar-ladhe&theme=tokyo-night&hide_border=true&area=true" />
</p>

---

## Contribution Snake

<p align="center">
  <img src="https://raw.githubusercontent.com/avishkar-ladhe/avishkar-ladhe/output/github-contribution-grid-snake-dark.svg" />
</p>

---

## Currently

- Pushing all projects to GitHub with READMEs, demo videos, and clean commit history
- Deepening LangGraph multi-agent architecture and production RAG patterns
- Building a portfolio site to host live project demos
- Actively looking for remote SDE, AI/ML, and backend roles

---

## Let's Connect

If you're building something interesting or need someone who ships and takes ownership — I'd genuinely love to talk.

<p align="center">
  <a href="https://linkedin.com/in/avishkar-ladhe">
    <img src="https://img.shields.io/badge/LinkedIn-Let's%20connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:avishkarladhe0@gmail.com">
    <img src="https://img.shields.io/badge/Email-Drop%20me%20a%20line-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<p align="center">
  <sub>📍 Pune, India · Open to remote worldwide · B.Tech CE @ VIIT Pune (2027) · Internships available now</sub>
</p>
