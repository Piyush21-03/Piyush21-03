<div align="center">

<img src="./profile/hero.svg" width="100%" alt="Piyush Panigrahi | AI and GenAI Developer"/>

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=FF4B4B&center=true&vCenter=true&width=650&lines=Python+Developer+%7C+GenAI+Application+Developer;LLMs+%7C+RAG+%7C+FastAPI;Building+useful+AI+products+%F0%9F%9A%80" alt="Typing SVG"/>
</a>

<br/>

<img src="https://img.shields.io/badge/Open%20to-AI%20%26%20Backend%20Internships-ff3b3b?style=for-the-badge&labelColor=111111" alt="Open to AI and Backend Internships"/>
<img src="https://img.shields.io/badge/B.Tech-2028-ff3b3b?style=for-the-badge&labelColor=111111" alt="B.Tech 2028"/>
<img src="https://img.shields.io/badge/Based%20in-India-ff3b3b?style=for-the-badge&labelColor=111111" alt="Based in India"/>

<br/><br/>

<img src="./profile/terminal.svg" width="85%" alt="Animated terminal intro"/>

</div>

<br/>

<a id="about"></a>
<h2 align="center">━━━ <code> 👋 ABOUT ME </code> ━━━</h2>
<p align="center"><sub><i>Building practical AI applications with strong backend foundations</i></sub></p>

<p align="center">
  <img src="./profile/about.svg" width="92%" alt="About Piyush Panigrahi"/>
</p>

> **Currently looking for:** internship and collaborative opportunities in Generative AI, AI Engineering, Machine Learning, and Python Backend Development.

<p align="center">
  📄 <b>GitHub Profile Repo:</b> <a href="https://github.com/Piyush21-03/Piyush21-03">Open repository</a>
  &nbsp;•&nbsp;
  💼 <a href="https://www.linkedin.com/in/piyushpanigrahi-sde">LinkedIn</a>
</p>

<br/>

<h2 align="center">━━━ <code> 🚀 FEATURED PROJECTS </code> ━━━</h2>
<p align="center"><sub><i>Projects focused on AI, retrieval, and real-world problem solving</i></sub></p>

| Project | What it does | Tech stack | Links |
|---|---|---|---|
| **PaperChat** | AI-powered research assistant for PDF-based Q&A, source citations, conversational memory, and document understanding. Uses a 5-stage hybrid RAG pipeline with query rewriting, dense retrieval, BM25, Reciprocal Rank Fusion, and cross-encoder reranking. | Python, FastAPI, LangChain, Gemini 2.5 Flash, Qdrant, PostgreSQL, SQLAlchemy, Docker | [Code](https://github.com/Piyush21-03/Paperchat) |
| **CampusAI+** | AI student-support platform combining a Gemini-powered assistant with an ML-based placement predictor and personalized career guidance. | Python, Flask, Gemini API, scikit-learn, Random Forest, Pandas | [Live demo](https://campus-ai-project.onrender.com) |
| **AQI Prediction & Hotspot Analysis** | Academic project exploring air-quality data processing, prediction, and hotspot analysis using data-driven methods. | Python, Pandas, NumPy, scikit-learn, APIs / sensor-data concepts | [GitHub repositories](https://github.com/Piyush21-03?tab=repositories) |

<br/>

<h3 align="center"><code> 🧩 Architecture </code></h3>

<details>
<summary><b>PaperChat — Hybrid RAG pipeline</b></summary>

```mermaid
flowchart LR
    A["PDF Upload"] --> B["PyPDFLoader"]
    B --> C["Text Splitting"]
    C --> D["MiniLM Embeddings"]
    D --> E[("Qdrant Vector Search")]
    Q["User Question"] --> R["Query Rewriting"]
    R --> E
    R --> BM["BM25 Retrieval"]
    E --> F["Reciprocal Rank Fusion"]
    BM --> F
    F --> G["Cross-Encoder Reranking"]
    G --> H["Gemini 2.5 Flash"]
    H --> I["Answer + Source Citations"]
    DB[("PostgreSQL")] --- J["Chat History & Auth"]
```

</details>

<details>
<summary><b>CampusAI+ — Student support and placement prediction</b></summary>

```mermaid
flowchart LR
    U["Student"] --> UI["Web Interface"]
    UI --> API["Flask REST API"]
    API --> AI["Gemini-powered Student Assistant"]
    API --> ML["Random Forest Placement Predictor"]
    DATA[("Student Performance Dataset")] --> ML
    AI --> OUT["Context-aware Guidance"]
    ML --> OUT2["Prediction + Probability Score"]
    OUT --> UI
    OUT2 --> UI
```

</details>

<br/>

<h2 align="center">━━━ <code> 🛠️ TECH STACK </code> ━━━</h2>
<p align="center"><sub><i>Tools and technologies I work with</i></sub></p>

<p align="center"><b>💻 Languages & Web</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=111111" alt="Python"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white&labelColor=111111" alt="Java"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white&labelColor=111111" alt="C++"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&labelColor=111111" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=111111" alt="SQL"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white&labelColor=111111" alt="HTML5"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white&labelColor=111111" alt="CSS3"/>
</p>

<p align="center"><b>🧠 AI, ML & Backend</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Generative%20AI-FF3030?style=for-the-badge&labelColor=111111" alt="Generative AI"/>
  <img src="https://img.shields.io/badge/RAG-CC2222?style=for-the-badge&labelColor=111111" alt="RAG"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white&labelColor=111111" alt="LangChain"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white&labelColor=111111" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Flask-FFFFFF?style=for-the-badge&logo=flask&logoColor=black&labelColor=111111" alt="Flask"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white&labelColor=111111" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white&labelColor=111111" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white&labelColor=111111" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Gemini%20API-8E75B2?style=for-the-badge&labelColor=111111" alt="Gemini API"/>
</p>

<p align="center"><b>🗄️ Databases, Tools & Deployment</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white&labelColor=111111" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&labelColor=111111" alt="Qdrant"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white&labelColor=111111" alt="MySQL"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=111111" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white&labelColor=111111" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-FFFFFF?style=for-the-badge&logo=github&logoColor=black&labelColor=111111" alt="GitHub"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=111111" alt="Docker"/>
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black&labelColor=111111" alt="Render"/>
</p>

<br/>

<h2 align="center">━━━ <code> 🏆 EXPERIENCE & HIGHLIGHTS </code> ━━━</h2>

<table align="center">
  <tr>
    <td align="center" width="50%">
      <h3>🤖</h3>
      <b>Generative AI Virtual Internship</b><br/>
      IBM SkillsBuild<br/>
      <sub>June 2026 – August 2026</sub>
    </td>
    <td align="center" width="50%">
      <h3>🛡️</h3>
      <b>Cybersecurity Virtual Internship</b><br/>
      IBM SkillsBuild<br/>
      <sub>September 2025 – November 2025</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <h3>💻</h3>
      <b>100+ LeetCode Problems</b><br/>
      <sub>Problem-solving practice</sub>
    </td>
    <td align="center" width="50%">
      <h3>⚡</h3>
      <b>350+ CodeChef Problems</b><br/>
      <sub>Competitive programming practice</sub>
    </td>
  </tr>
</table>

<br/>

<h2 align="center">━━━ <code> 🎯 CURRENT FOCUS </code> ━━━</h2>
<p align="center">
  <img src="https://img.shields.io/badge/Generative%20AI-FF3030?style=for-the-badge&labelColor=111111" alt="Generative AI"/>
  <img src="https://img.shields.io/badge/RAG%20%26%20LLMs-CC2222?style=for-the-badge&labelColor=111111" alt="RAG and LLMs"/>
  <img src="https://img.shields.io/badge/Python%20Backend-FF4B4B?style=for-the-badge&labelColor=111111" alt="Python Backend"/>
  <img src="https://img.shields.io/badge/SQL%20%26%20Databases-8B0000?style=for-the-badge&labelColor=111111" alt="SQL and Databases"/>
  <img src="https://img.shields.io/badge/DSA-FF3030?style=for-the-badge&labelColor=111111" alt="Data Structures and Algorithms"/>
</p>

<br/>

<h2 align="center">━━━ <code> 📊 STATS DASHBOARD </code> ━━━</h2>
<p align="center"><sub><i>GitHub activity and coding practice</i></sub></p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Piyush21-03&show_icons=true&hide_border=true&bg_color=0d0000,1a0000,260000&title_color=ff4b4b&text_color=eeeeee&icon_color=ff3030&ring_color=ff3030" height="180" alt="Piyush's GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Piyush21-03&layout=compact&hide_border=true&bg_color=0d0000,1a0000,260000&title_color=ff4b4b&text_color=eeeeee" height="180" alt="Most used languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Piyush21-03&hide_border=true&background=0d0000&ring=ff3030&fire=ff4b4b&currStreakLabel=ff4b4b&sideLabels=eeeeee&dates=aaaaaa&sideNums=eeeeee&currStreakNum=eeeeee" width="75%" alt="GitHub contribution streak"/>
</p>

<!-- 3D contribution graph: generated daily by the GitHub Actions workflow in .github/workflows/profile-3d.yml -->
<p align="center">
  <img src="https://raw.githubusercontent.com/Piyush21-03/Piyush21-03/profile-3d-contrib/profile-green-animate.svg" width="100%" alt="3D GitHub contribution graph"/>
</p>

<p align="center">
  <img src="https://leetcard.jacoblin.cool/Piyush21-03?theme=dark&font=Fira%20Code&ext=heatmap" width="500" alt="LeetCode stats (if the username matches the LeetCode profile)"/>
</p>

<br/>

<h2 align="center">━━━ <code> 🔗 CONNECT </code> ━━━</h2>
<p align="center"><sub><i>Always happy to learn, build, and collaborate</i></sub></p>

<p align="center">
  <a href="https://www.linkedin.com/in/piyushpanigrahi-sde">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-FF3030?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=111111" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/Piyush21-03">
    <img src="https://img.shields.io/badge/GitHub-Follow-FF3030?style=for-the-badge&logo=github&logoColor=white&labelColor=111111" alt="GitHub"/>
  </a>
  <a href="mailto:piyushpanigrahi21@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-FF3030?style=for-the-badge&logo=gmail&logoColor=white&labelColor=111111" alt="Email"/>
  </a>
</p>

<p align="center">
  <sub>⭐ Thanks for visiting! Explore my repositories and feel free to connect.</sub><br/>
  <a href="#about"><sub>↑ Back to top</sub></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:080000,40:300000,100:ff3030&height=130&section=footer&text=Thanks%20for%20visiting!%20%F0%9F%9A%80&fontSize=22&fontColor=ffffff&animation=fadeIn" width="100%" alt="Red and black gradient footer"/>
