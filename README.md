<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0b3d5c,100:22E58B&height=200&section=header&text=Piyush%20Panigrahi&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Aspiring%20AI%20Engineer%20%7C%20Generative%20AI%20%26%20RAG%20Developer&descAlignY=60&descSize=18" width="100%" alt="Piyush Panigrahi"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=22E58B&center=true&vCenter=true&width=720&lines=Python+Developer+%7C+GenAI+Application+Developer;Hybrid+RAG+%7C+Reranking+%7C+LLM+Apps;LangChain+%7C+FastAPI+%7C+Qdrant;Turning+LLMs+into+reliable+products" alt="Typing SVG" />
</a>

<br/><br/>

<img src="https://img.shields.io/badge/Focus-GenAI%20%26%20RAG-00D9FF?style=for-the-badge&logo=openai&logoColor=white" alt="Focus"/>
<img src="https://img.shields.io/badge/B.Tech%20CSE-Data%20Science-0077FF?style=for-the-badge" alt="B.Tech CSE Data Science"/>
<img src="https://img.shields.io/badge/Graduating-2028-22E58B?style=for-the-badge&logoColor=black" alt="Graduating 2028"/>
<img src="https://img.shields.io/badge/Delhi-India-ff9933?style=for-the-badge" alt="Delhi, India"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Piyush21-03&label=Profile%20views&color=22e58b&style=flat-square" alt="Profile views"/>

</div>

<br/>

<h1 align="center">🎯 Aspiring AI Engineer · Generative AI &amp; RAG Developer</h1>

<p align="center"><i>I build LLM applications that give grounded, citation-backed answers instead of guesses.</i></p>

<p align="center">
  <img src="https://img.shields.io/badge/LLMs-00D9FF?style=flat-square" alt="LLMs"/>
  <img src="https://img.shields.io/badge/RAG-22E58B?style=flat-square&logoColor=black" alt="RAG"/>
  <img src="https://img.shields.io/badge/Reranking-8b949e?style=flat-square" alt="Reranking"/>
  <img src="https://img.shields.io/badge/Prompt_Engineering-0077FF?style=flat-square" alt="Prompt Engineering"/>
  <img src="https://img.shields.io/badge/Agentic_AI-FF6B6B?style=flat-square" alt="Agentic AI"/>
  <img src="https://img.shields.io/badge/Python_Backend-FFA116?style=flat-square" alt="Python Backend"/>
</p>

---

## 👋 About Me

I'm a third-year **B.Tech Computer Science (Data Science)** student at **ABES Engineering College** (AKTU), passionate about building intelligent, scalable, real-world AI applications. I like turning complex problems into practical, user-focused solutions by combining AI models with robust backend systems.

My main interests are **Generative AI, LLMs, Retrieval-Augmented Generation (RAG), Machine Learning and backend development**. I'm continuously exploring advanced AI architectures, agentic AI and production-oriented development while sharpening my problem-solving and software engineering skills.

```python
class Piyush:
    role      = "Python Developer | GenAI Application Developer"
    studying  = "B.Tech CSE (Data Science), ABES Engineering College, 2028"
    building  = ["Hybrid RAG systems", "LLM-powered apps", "FastAPI backends"]
    exploring = ["Agentic AI", "Advanced AI architectures", "Production-grade systems"]
    goal      = "Become an AI Engineer"
    seeking   = "Internships in AI Engineering, GenAI, ML and Python backend"
```

> [!TIP]
> **Open to internships and collaborations.** Reach me at [piyushpanigrahi21@gmail.com](mailto:piyushpanigrahi21@gmail.com) or on [LinkedIn](https://www.linkedin.com/in/piyushpanigrahi-sde).

---

## 🚀 Projects

### 📄 PaperChat: AI-Powered Research & Document Intelligence Assistant

> Chat with your documents and get answers you can verify, with page-level source citations.

| | |
|---|---|
| **What it does** | Document-based conversational Q&A with page-level citations, conversational memory and document summarization |
| **Retrieval** | 5-stage hybrid RAG: query rewriting → dense vector search → BM25 → Reciprocal Rank Fusion → cross-encoder reranking |
| **Backend** | PDF ingestion, conversational Q&A, JWT authentication and persistent chat management (4 core capabilities) |
| **Stack** | `Python` `FastAPI` `LangChain` `Gemini 2.5 Flash` `Qdrant` `PostgreSQL` `SQLAlchemy` `Docker` |

```mermaid
flowchart TD
    Q([Question]) --> RW[Query rewriting]
    RW --> DV[(Dense search · Qdrant)]
    RW --> BM[BM25 search]
    DV --> RRF{Reciprocal Rank Fusion}
    BM --> RRF
    RRF --> CE[Cross-encoder reranking]
    CE --> LLM[Gemini 2.5 Flash]
    LLM --> ANS([Answer + page-level citations])
```

[![Code](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Piyush21-03)

### 🎓 CampusAI+: AI Student Support & Placement Predictor

> One platform for academic help, interview prep and career guidance, backed by a placement-prediction model.

| | |
|---|---|
| **What it does** | Flask-based AI platform with 2 modules: Gemini-powered student support and ML-based placement prediction |
| **Model** | 100-tree Random Forest classifier on 8 student-performance features, 80:20 train-test split, with probability scoring |
| **APIs** | REST endpoints for real-time predictions, placement status and personalized Gemini-generated career guidance |
| **Stack** | `Python` `Flask` `Gemini` `scikit-learn` |

[![Live Demo](https://img.shields.io/badge/Live_Demo-22E58B?style=for-the-badge&logo=googlechrome&logoColor=black)](https://github.com/Piyush21-03)
[![Code](https://img.shields.io/badge/View_Code-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Piyush21-03)

<!-- TODO: replace the three links above with the exact repo URLs and the CampusAI+ live demo URL -->

---

## 💡 Areas of Expertise

<table align="center">
  <tr>
    <td align="center" width="25%"><h3>🧠</h3><b>Generative AI</b><br/><sub>LLM apps, prompt engineering, LLM API integration</sub></td>
    <td align="center" width="25%"><h3>🔎</h3><b>RAG Systems</b><br/><sub>Hybrid retrieval, BM25, RRF, cross-encoder reranking, citations</sub></td>
    <td align="center" width="25%"><h3>⚙️</h3><b>Backend Development</b><br/><sub>FastAPI, Flask, REST APIs, JWT auth, PostgreSQL</sub></td>
    <td align="center" width="25%"><h3>📈</h3><b>Machine Learning</b><br/><sub>scikit-learn, Pandas, NumPy, model training</sub></td>
  </tr>
</table>

---

## 🛠️ Top Tools & Technologies

**💻 Languages**

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS"/>

**🧠 AI / ML**

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain"/>
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>

**⚙️ Backend & Databases**

<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white" alt="Qdrant"/>

**🧰 Tools**

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>

---

## 📊 Top Languages

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Piyush21-03&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" width="48%"/>
  <img src="https://github-readme-stats.vercel.app/api?username=Piyush21-03&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" width="48%"/>
</p>

---

## 🏆 Highlights & Experience

<table align="center">
  <tr>
    <td align="center" width="25%"><h3>💼</h3><b>Generative AI Intern</b><br/>IBM Virtual Internship<br/>Jun 2026 – Aug 2026</td>
    <td align="center" width="25%"><h3>🛡️</h3><b>Cybersecurity Intern</b><br/>IBM Virtual Internship<br/>Sep 2025 – Nov 2025</td>
    <td align="center" width="25%"><h3>🧩</h3><b>450+ DSA Problems</b><br/>100+ LeetCode<br/>350+ CodeChef</td>
    <td align="center" width="25%"><h3>🎓</h3><b>CGPA 7.7</b><br/>B.Tech CSE (Data Science)<br/>ABES Engineering College</td>
  </tr>
</table>

<details>
<summary><b>💼 IBM Generative AI Virtual Internship (Jun 2026 – Aug 2026)</b></summary>

<br/>

- Developed **Campus AI** with 5 AI-driven features and 4 core AI components to give context-aware responses to campus queries
- Integrated 2 LLM APIs and implemented 2 NLP/LLM workflows covering query processing, prompt handling and AI-generated responses
- Applied prompt engineering, NLP, LLM integration and API integration, taking a GenAI solution from concept to an application-ready implementation
- Completed IBM SkillsBuild's Generative AI program, covering LLM application design patterns and API-based integration workflows

</details>

<details>
<summary><b>🛡️ IBM Cybersecurity Virtual Internship (Sep 2025 – Nov 2025)</b></summary>

<br/>

- Completed 20+ hands-on cybersecurity labs through IBM SkillsBuild
- Covered network security, vulnerability assessment and secure software development practices
- Built a foundation in information security, digital threats and secure practices

</details>

---

## 🧮 DSA & Competitive Programming

<p align="center">
  <img src="https://img.shields.io/badge/LeetCode-100%2B_solved-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode 100+"/>
  <img src="https://img.shields.io/badge/CodeChef-350%2B_solved-5B4638?style=for-the-badge&logo=codechef&logoColor=white" alt="CodeChef 350+"/>
  <img src="https://img.shields.io/badge/Total-450%2B_problems-22E58B?style=for-the-badge&logoColor=black" alt="450+ problems"/>
</p>

<p align="center">
  <!-- Replace YOUR_LEETCODE_USERNAME with your LeetCode username -->
  <img src="https://leetcard.jacoblin.cool/YOUR_LEETCODE_USERNAME?theme=dark&font=Fira%20Code&ext=heatmap" alt="LeetCode stats" width="500"/>
</p>

---

## 🎓 Certifications

| Certification | Issuer |
|---|---|
| ☁️ AWS Cloud Architecting | AWS Academy |
| ☁️ AWS Cloud Foundations | AWS Academy |
| 🤖 IBM AI | IBM SkillsBuild |
| 🎯 Google AI Studio & Vibe Coding | Google |
| 📊 Exploratory Data Analysis | |
| 🐍 Python Development | |
| 🧪 GenAI Powered Data Analytics Job Simulation | |
| 🐍 Introduction to Programming Using Python | |

---

## 📈 GitHub Activity

<details open>
<summary>🔥 Streak & profile summary</summary>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Piyush21-03&theme=tokyonight&hide_border=true" alt="GitHub streak" width="48%"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Piyush21-03&theme=tokyonight" alt="GitHub profile summary" width="48%"/>
</p>

</details>

### 🌌 3D Contribution Graph

<p align="center">
  <img src="./profile-3d-contrib/profile-night-view.svg" alt="3D contribution graph" width="100%"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Piyush21-03&theme=onedark&no-frame=true&row=1&column=6" alt="GitHub trophies" width="100%"/>
</p>

---

## 🌱 Roadmap

- 🔭 Going deeper on **advanced RAG** and retrieval quality
- 🤖 Exploring **agentic AI** and tool-using LLM workflows
- 🏗️ Building **production-oriented** systems with Docker, auth and persistence
- 💼 Looking for **internships** in AI Engineering, Generative AI, ML and Python backend
- 🧩 Keeping up consistent DSA practice

---

## 🔗 Connect With Me

<p align="center">
  <a href="https://www.linkedin.com/in/piyushpanigrahi-sde"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://github.com/Piyush21-03"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <a href="mailto:piyushpanigrahi21@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
</p>

<p align="center"><sub>⭐ Thanks for stopping by. Explore my pinned repos or reach out through any link above.</sub></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22E58B,50:0b3d5c,100:0d1117&height=120&section=footer" width="100%" alt=""/>
