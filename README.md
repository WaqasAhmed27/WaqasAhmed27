<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24&height=200&section=header&text=Waqas%20Ahmed&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20%E2%80%94%20Data%20Science%20%E2%80%94%20Deployed%20Products&descAlignY=56&descSize=16&descColor=a0aec0" width="100%" />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2500&pause=900&color=4D9DE0&center=true&vCenter=true&random=false&width=640&lines=Real-time+FIM+Autocomplete+%E2%80%94+ExLlamaV2+%2B+GPU+Inference+%E2%9A%A1;F1+Race+Strategy+via+Machine+Learning+%F0%9F%8F%8E%EF%B8%8F;Multi-Agent+Financial+Research+%E2%80%94+LangGraph+%2B+Gemini+%F0%9F%94%AC;AI+Tutoring+Platform+%E2%80%94+Next.js+%2B+Gemini+%2B+OCR+%F0%9F%8E%93;Data+Science+Student+%7C+Islamabad%2C+Pakistan+%F0%9F%87%B5%F0%9F%87%B0)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/vvaqas-ahmed)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vvaqasahmed27@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=github&logoColor=white)](https://waqasahmed27.github.io)
[![Profile Views](https://komarev.com/ghpvc/?username=WaqasAhmed27&color=4D9DE0&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/WaqasAhmed27)

</div>

---

## 🧠 About Me

Data Science student from **Islamabad, Pakistan**. I build AI systems that go beyond Colab notebooks and into production. My work spans GPU inference backends, agentic pipelines, ML model training, and full-stack applications. I care about **clean architecture, real deployments, and models that actually generalize**.

- ⚡ Currently building a real-time FIM code autocomplete engine with ExLlamaV2 and Qwen2.5-Coder
- 🤖 Obsessed with multi-agent orchestration, LLM inference optimization, and applied ML
- 🚢 Strong bias toward *shipped products*. if it doesn't run, it doesn't count
- 🔭 Active private builds: **Proctor-Docs** (TypeScript), **Corvin** (Dart), **crocodile** (9 open issues)

---

## 🚀 Featured Projects

<br/>

<table>
<tr>
<td width="50%" valign="top">

### ⚡ Real-Time FIM Autocomplete Editor
*(NLP-PDC-project — updated last week)*

Production-grade **Fill-in-the-Middle code autocomplete** system. React + Lexical frontend streams ghost-text completions from a FastAPI WebSocket backend running **ExLlamaV2 with Qwen2.5-Coder-1.5B**. Sub-40ms TTFT fast path on RTX 4090, speculative rewrite with Flash Attention 2.5.7+, 8-bit KV cache, and a full test suite covering FIM prompt construction, payload parsing, and adversarial cases.

`Python` `FastAPI` `React` `Lexical` `ExLlamaV2` `WebSocket` `TypeScript`

[→ Repo](https://github.com/WaqasAhmed27/NLP-PDC-project)

</td>
<td width="50%" valign="top">

### 🏎️ F1 Strategy Simulator

ML system for predicting Formula 1 race finishing positions. Ingests multi-session telemetry (FP1–FP3, Q, R) via FastF1 and engineers **29+ features** across race pace deltas, pit strategy, penalties, driver form, and session adaptation. Best model: XGBoost with **CV MAE of 3.008** using 10 optimized features. Full CLI, Docker, deployed on Vercel.

`Python` `XGBoost` `CatBoost` `FastF1` `scikit-learn` `Docker`

[→ Repo](https://github.com/WaqasAhmed27/f1-strategy-sim) · [→ Live App](https://f1-strategy-sim.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 EDA Helper

Streamlit app that automates exploratory data analysis and baseline ML benchmarking. Upload any CSV → get stats, distributions, correlation heatmaps, model comparison (LR, RF, GBM, XGBoost), and **AI-powered recommendations via Google Gemini 2.5 Flash**. One-click feature engineering from AI suggestions. Deployed on Streamlit Cloud.

`Python` `Streamlit` `Gemini API` `scikit-learn` `Plotly` `XGBoost`

[→ Repo](https://github.com/WaqasAhmed27/EDA-Helper) · [→ Live App](https://auto-eda-ai.streamlit.app)

</td>
<td width="50%" valign="top">

### 🎓 ParhAI

Full educational platform built with **Next.js 14 + TypeScript + Supabase**. Integrates Google Gemini for content generation, Tesseract.js for OCR, Reveal.js + PPTXGenJS for presentations, and Uplift API for TTS/STT. Custom auth, educational theme, and CSV/image ingestion pipelines.

`Next.js 14` `TypeScript` `Supabase` `Gemini API` `Tesseract.js` `TTS/STT`

[→ Repo](https://github.com/WaqasAhmed27/ParhAI)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔬 Multi-Agent Company Research

Autonomous financial research pipeline orchestrated by a deterministic **LangGraph** state machine: Planner → Researcher → Financials → Synthesizer → Reporter. Tavily for live web search, yfinance for real-time market data, Gemini for LLM summaries. Schema validation at every node boundary with deterministic fallbacks — the pipeline never fails silently.

`Python` `LangGraph` `Gemini API` `Tavily` `yfinance`

[→ Repo](https://github.com/WaqasAhmed27/Multi-Agent-Company-Research)

</td>
<td width="50%" valign="top">

### 🛡️ Sentinel

Multi-agent logistics system built for a **hackathon**. Six specialized agents (Order, Planner, Monitor, Negotiator, Dispatcher, Auditor) coordinate via uAgents protocols with Redis state, MeTTa/AtomSpace knowledge graph, and SingularityNET AI services. Deployed via Docker Compose with FastAPI and PostgreSQL.

`Python` `FastAPI` `uAgents` `Redis` `MeTTa` `PostgreSQL` `Docker`

[→ Repo](https://github.com/WaqasAhmed27/Sentinel)

</td>
</tr>
</table>

---

## 🔧 Also Built

<div align="center">

| Project | What it is | Stack |
|---|---|---|
| 🤖 [NLP-Assistant](https://github.com/WaqasAhmed27/NLP-Assistant) | Modular NLP Streamlit app — AI workflow detection across 6 content types, VADER sentiment, batch CSV processing | Python · VADER · Plotly · Docker |
| 🗄️ [WalmartDW-HybridJoin-ETL](https://github.com/WaqasAhmed27/WalmartDW-HybridJoin-ETL) | Star-schema data warehouse with HYBRIDJOIN stream processing and a CustomTkinter GUI | Python · MySQL · Pandas |
| 🎯 [ApexQuiz](https://github.com/WaqasAhmed27/ApexQuiz) | C# WinForms quiz app — auth, flashcards, leaderboards, daily challenges, multiplayer | C# · WinForms · MySQL |
| ✈️ [Flight-delay](https://github.com/WaqasAhmed27/Flight-delay) | Flight delay prediction and pattern analysis | Python · Jupyter |
| 🌫️ [air-quality](https://github.com/WaqasAhmed27/air-quality) | Air quality EDA and forecasting | Python · Jupyter |

</div>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

[![Skills](https://skillicons.dev/icons?i=python,ts,js,cs,bash&theme=dark)](https://skillicons.dev)

**AI · ML · Inference**

[![Skills](https://skillicons.dev/icons?i=tensorflow,sklearn,pytorch&theme=dark)](https://skillicons.dev)

![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square)
![ExLlamaV2](https://img.shields.io/badge/ExLlamaV2-FF6B35?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-0052CC?style=flat-square)
![Gemini API](https://img.shields.io/badge/Gemini%20API-4285F4?style=flat-square&logo=google&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Web · Backend · Data**

[![Skills](https://skillicons.dev/icons?i=nextjs,fastapi,nodejs,react,mysql,postgres,redis,supabase,docker,git&theme=dark)](https://skillicons.dev)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats-salesp07.vercel.app/api?username=WaqasAhmed27&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&rank_icon=github" height="170" alt="GitHub Stats" />
&nbsp;
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=WaqasAhmed27&theme=tokyonight" height="170" alt="Top Languages" />

<br/><br/>

<img src="https://streak-stats.demolab.com?user=WaqasAhmed27&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" height="170" alt="GitHub Streak" />

</div>

---

## 🏆 Trophies

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=WaqasAhmed27&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&row=1&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 📈 Contribution Activity

<div align="center">

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=WaqasAhmed27&theme=tokyo-night&hide_border=true&area=true&area_color=4D9DE0)](https://github.com/ashutosh00710/github-readme-activity-graph)

</div>

---

<div align="center">

*"Data science student who breaks code until it finally works."*

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24&height=100&section=footer" width="100%" />
