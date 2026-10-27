<div align="center">

<!-- 1. Animated hero (self-hosted) -->
<img src="./profile/hero.svg" width="100%" alt="Piyush Panigrahi, Python and GenAI Application Developer"/>

<br/>

<!-- 2. Typing animation -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00D9FF&center=true&vCenter=true&width=650&lines=Python+Developer+%7C+GenAI+Applications;RAG+Pipelines+%7C+LLMs+%7C+Prompt+Engineering;Building+in+public+%F0%9F%9A%80" alt="Typing SVG" />
</a>

<br/>

<!-- 3. Status badges -->
<img src="https://img.shields.io/badge/Focus-GenAI-00D9FF?style=for-the-badge" alt="Focus: GenAI"/>
<img src="https://img.shields.io/badge/Batch-2028-0077FF?style=for-the-badge" alt="Batch 2028"/>
<img src="https://img.shields.io/badge/Based%20in-India-ff9933?style=for-the-badge" alt="Based in India"/>

<br/><br/>

<!-- 4. Animated terminal intro (self-hosted) -->
<img src="./profile/terminal.svg" width="85%" alt="Animated terminal intro"/>

</div>

<br/>

<a id="about"></a>
<h2 align="center">▰▰▰ <code>&nbsp;👋&nbsp;ABOUT&nbsp;</code> ▰▰▰</h2>
<p align="center"><sub><i>Who I am and what I'm building</i></sub></p>

<p align="center">
  <img src="./profile/about.svg" width="90%" alt="B.Tech CSE (Data Science), CGPA 7.7, two IBM virtual internships, 450+ DSA problems"/>
</p>

> [!TIP]
> **Let's talk GenAI, RAG and Python:** reach me at [piyushpanigiri21@gmail.com](mailto:piyushpanigiri21@gmail.com) or on [LinkedIn](https://www.linkedin.com/in/piyush-panigrahi-64117a330).

<br/>

<h2 align="center">▰▰▰ <code>&nbsp;🚀&nbsp;FEATURED PROJECTS&nbsp;</code> ▰▰▰</h2>
<p align="center"><sub><i>Cards flip on their own: overview ↔ technical details</i></sub></p>

<table align="center">
  <tr>
    <td align="center" valign="top">
      <img src="./profile/card-paperchat.svg" alt="PaperChat flip card" width="420"/>
    </td>
    <td align="center" valign="top">
      <img src="./profile/card-campusai.svg" alt="CampusAI+ flip card" width="420"/>
    </td>
  </tr>
</table>

<br/>

<!-- TODO: add your exact Live / Code links in the Links column -->

| Project | What it does | Stack | Links |
|---|---|---|---|
| **PaperChat** | AI research assistant for document-based conversational Q&A with page-level source citations, using a 5-stage hybrid RAG pipeline | Python, FastAPI, LangChain, Gemini 2.5 Flash, Qdrant | [Code](https://github.com/Piyush21-03?tab=repositories) |
| **CampusAI+** | Student support and ML-based placement prediction, with REST APIs and personalized Gemini-generated career guidance | Flask, Gemini, scikit-learn | [Code](https://github.com/Piyush21-03?tab=repositories) |

<br/>

<h3 align="center"><code>&nbsp;🧩&nbsp;Architecture&nbsp;</code></h3>

<details>
<summary><b>PaperChat</b> architecture</summary>

```mermaid
flowchart LR
    U["User question"] --> Q["Query rewriting"]
    Q --> D["Dense vector search<br/>Qdrant"]
    Q --> B["BM25 retrieval"]
    D --> R["Reciprocal Rank Fusion"]
    B --> R
    R --> X["Cross-encoder reranking"]
    X --> G["Gemini 2.5 Flash"]
    G --> A["Answer with page-level citations"]
```

</details>

<details>
<summary><b>CampusAI+</b> architecture</summary>

```mermaid
flowchart LR
    A["Student"] -->|REST| B["Flask API"]
    B --> C["ML placement model<br/>scikit-learn"]
    B --> D["Gemini<br/>student support + career guidance"]
    C --> E["Prediction and placement status"]
    D --> F["Personalized guidance"]
```

</details>

<br/>

<h2 align="center">▰▰▰ <code>&nbsp;💡&nbsp;CORE FOCUS&nbsp;</code> ▰▰▰</h2>
<p align="center"><sub><i>Front: the area · Back: the details</i></sub></p>

<p align="center">
  <img src="./profile/focus-cards.svg" width="90%" alt="Core focus areas flip cards"/>
</p>

<br/>

<h2 align="center">▰▰▰ <code>&nbsp;🛠️&nbsp;TECH STACK&nbsp;</code> ▰▰▰</h2>
<p align="center"><sub><i>Tools I build with</i></sub></p>

<p align="center"><b>💻 Languages & Web</b></p>
<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" height="32"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" height="32"/>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" height="32"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" height="32"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" height="32"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" height="32"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" height="32"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" height="32"/>
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" height="32"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" height="32"/>
</p>

<p align="center"><b>🧠 AI / Data</b></p>
<p align="center">
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" height="32"/>
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white" alt="Qdrant" height="32"/>
<img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini" height="32"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" height="32"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" height="32"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn" height="32"/>
</p>

<p align="center"><b>🧰 Tools & Deploy</b></p>
<p align="center">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" height="32"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" height="32"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" height="32"/>
</p>

<br/>

<h2 align="center">▰▰▰ <code>&nbsp;🏆&nbsp;HIGHLIGHTS&nbsp;</code> ▰▰▰</h2>
<p align="center"><sub><i>Milestones so far</i></sub></p>

<table align="center">
  <tr>
    <td align="center" width="33%">
      <h3>💼</h3>
      <b>GenAI Intern</b><br/>
      IBM Virtual Internship<br/>Jun 2026 – Aug 2026
    </td>
    <td align="center" width="33%">
      <h3>🛡️</h3>
      <b>Cybersecurity Intern</b><br/>
      IBM Virtual Internship<br/>Sep 2025 – Nov 2025
    </td>
    <td align="center" width="33%">
      <h3>🧩</h3>
      <b>450+ DSA Problems</b><br/>
      100+ LeetCode and<br/>350+ CodeChef
    </td>
  </tr>
</table>

<br/>

<h2 align="center">▰▰▰ <code>&nbsp;🎓&nbsp;CERTIFICATIONS&nbsp;</code> ▰▰▰</h2>
<p align="center"><sub><i>Learning, verified</i></sub></p>

<table align="center">
  <tr><td align="center">☁️ <b>AWS Cloud Architecting</b> — AWS Academy Graduate</td></tr>
  <tr><td align="center">☁️ <b>AWS Cloud Foundations</b> — AWS Academy Graduate</td></tr>
  <tr><td align="center">🤖 <b>IBM AI</b> — IBM SkillsBuild</td></tr>
  <tr><td align="center">🎯 <b>Google AI Studio & Vibe Coding</b></td></tr>
  <tr><td align="center">📊 <b>Exploratory Data Analysis</b></td></tr>
  <tr><td align="center">🐍 <b>Python Development</b></td></tr>
</table>

<br/>

<h2 align="center">▰▰▰ <code>&nbsp;🎯&nbsp;CURRENT FOCUS&nbsp;</code> ▰▰▰</h2>
<p align="center"><sub><i>What I'm going deeper on</i></sub></p>

<p align="center">
<img src="https://img.shields.io/badge/LLMs-00D9FF?style=for-the-badge" alt="LLMs"/>
<img src="https://img.shields.io/badge/RAG-0077FF?style=for-the-badge" alt="RAG"/>
<img src="https://img.shields.io/badge/Reranking-8b949e?style=for-the-badge" alt="Reranking"/>
<img src="https://img.shields.io/badge/Prompt_Engineering-00A8E8?style=for-the-badge" alt="Prompt Engineering"/>
</p>

<br/>

<h2 align="center">▰▰▰ <code>&nbsp;📊&nbsp;STATS DASHBOARD&nbsp;</code> ▰▰▰</h2>
<p align="center"><sub><i>Numbers and activity</i></sub></p>

<p align="center">
  <img src="https://leetcard.jacoblin.cool/piyush_200621?theme=dark&font=Fira%20Code&ext=heatmap" alt="LeetCode stats" width="500"/>
</p>

<details>
<summary>📊 GitHub stats</summary>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Piyush21-03&theme=tokyonight&hide_border=true" alt="GitHub streak" width="48%"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Piyush21-03&theme=tokyonight" alt="GitHub profile summary" width="48%"/>
</p>

</details>

<p align="center">
  <img src="profile-3d-contrib/profile-night-view.svg?v=2" alt="Contribution graph" width="100%"/>
</p>

<br/>

<h2 align="center">▰▰▰ <code>&nbsp;⚡&nbsp;DAILY MOTIVATION&nbsp;</code> ▰▰▰</h2>

<table align="center" border="1" cellpadding="20">
  <tr>
    <td align="center">
      <!-- DAILY_QUOTE_START -->
<br/>
<h3>💭 “Hardships often prepare ordinary people for an extraordinary destiny.”</h3>
<p><b>— C. S. Lewis</b></p>
<br/>
<!-- DAILY_QUOTE_END -->
    </td>
  </tr>
</table>

<br/>

<h2 align="center">▰▰▰ <code>&nbsp;🔗&nbsp;CONNECT&nbsp;</code> ▰▰▰</h2>
<p align="center"><sub><i>Let's talk</i></sub></p>

<p align="center">
  <a href="https://www.linkedin.com/in/piyush-panigrahi-64117a330" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/Piyush21-03" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="mailto:piyushpanigiri21@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="tel:+918144038125" target="_blank">
    <img src="https://img.shields.io/badge/Call-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Call"/>
  </a>
</p>

<p align="center">
  <sub>⭐️ Thanks for stopping by. Explore my pinned repos or drop a message via any link above.</sub>
  <br/>
  <a href="#about"><sub>↑ Back to top</sub></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:161b22&height=120&section=footer&text=Thanks%20for%20visiting!%20%F0%9F%9A%80&fontSize=20&fontColor=00D9FF&animation=fadeIn" width="100%"/>
