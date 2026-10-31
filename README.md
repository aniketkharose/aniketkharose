<!-- ═══════════════ HEADER BANNER ═══════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=230&section=header&text=Aniket%20Kharose&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%2FML%20%E2%80%A2%20Embedded%20Systems%20%E2%80%A2%20Edge%20AI&descAlignY=60&descSize=20" alt="Aniket Kharose banner" />

<a href="https://github.com/aniketkharose">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=A78BFA&center=true&vCenter=true&width=820&height=50&lines=Building+AI+systems+that+work+in+the+real+world;From+computer+vision+to+embedded+hardware;Face+%E2%80%A2+Voice+%E2%80%A2+Pose+%E2%80%A2+Resume+Intelligence;Currently+exploring+Edge+AI+on+ESP32" alt="Typing animation" />
</a>

<br/>

![Open to](https://img.shields.io/badge/Open%20to-AI%2FML%20%26%20Embedded%20Internships-10B981?style=for-the-badge)
![Location](https://img.shields.io/badge/Based%20in-Pune%2C%20India-8B5CF6?style=for-the-badge)
[![Portfolio](https://img.shields.io/badge/Portfolio-View%20Live-0D1117?style=for-the-badge&logo=vercel&logoColor=white)](https://aniket-portfolio-lime.vercel.app/)

</div>

---

## 👋 Hey, I'm Aniket

Final-year **E&TC Engineering** student at **SKNCOE, Pune** (Savitribai Phule Pune University). I like building AI that you can actually *use*: apps that see faces, hear voices, watch your squat form and score your resume, all deployed and running live.

My sweet spot is where **machine learning meets hardware**: computer vision on one side, microcontrollers and embedded systems on the other.

```python
class Aniket:
    role      = "AI/ML + Embedded Systems Engineer (in the making)"
    college   = "SKNCOE, Pune"
    focus     = ["Computer Vision", "Edge AI", "Embedded Systems", "NLP"]
    loves     = ["shipping real projects", "turning ideas into live demos"]
    currently = "Running ML models on ESP32 and microcontrollers"
    looking   = "AI/ML and Embedded Systems internships"
```

---

## 🚀 Featured Projects

<table>
<tr>
<td width="33%" valign="top">

### 🧠 AI Resume ATS
*Know your score before the recruiter does.*

Analyzes a resume against a job description and returns an **ATS score, skill matching, feedback and recommendations**, with a downloadable PDF report.

`FastAPI` `Streamlit` `spaCy` `scikit-learn` `Supabase`

[🚀 Live Demo](https://ai-resume-ats-system-aniket.streamlit.app) · [💻 Code](https://github.com/aniketkharose/AI-Resume-ATS-System)

</td>
<td width="33%" valign="top">

### 📸 SnapClass
*Say cheese. You're marked present.*

AI attendance system using **face recognition** and **voice recognition**, with separate student and teacher portals.

`Dlib` `SVM` `Resemblyzer` `Streamlit` `Supabase`

[🚀 Live Demo](https://sanpclass-aniketkharose.streamlit.app/) · [💻 Code](https://github.com/aniketkharose/intelligent-ai-attendance)

</td>
<td width="33%" valign="top">

### 🏋️ AI Gym Coach
*A coach that watches every rep.*

Real-time **pose detection** with **form feedback** and **AI voice coaching** for workout tracking.

`MediaPipe` `OpenCV` `Streamlit` `Python`

[💻 Code](https://github.com/aniketkharose/ai-gym-coach-vision)

</td>
</tr>
</table>

<!--
═══════════════ 🎬 DEMO GIFS (OPTIONAL, DISABLED BY DEFAULT) ═══════════════
How to enable:
1. Record a 5-10 second screen recording of each project (ScreenToGif works well on Windows).
2. Create an "assets" folder in this repo and upload the GIFs with the names below.
3. Delete the opening and closing comment lines around this block so it renders.

### 🎬 See it in action

<div align="center">
<table>
<tr>
<td align="center"><img src="assets/snapclass-demo.gif" width="320" alt="SnapClass demo" /><br/><sub>📸 SnapClass: face + voice attendance</sub></td>
<td align="center"><img src="assets/gym-coach-demo.gif" width="320" alt="AI Gym Coach demo" /><br/><sub>🏋️ AI Gym Coach: live form feedback</sub></td>
</tr>
</table>
</div>
-->

### 🔬 What each project taught me

| Project | The interesting challenge |
|---|---|
| 🧠 **AI Resume ATS** | Deployed on a 512 MB free tier. Replaced a heavy transformer with a lightweight TF-IDF matcher to stop out-of-memory crashes. |
| 📸 **SnapClass** | Combined two biometric pipelines: Dlib embeddings with an SVM for faces, and Resemblyzer embeddings for voices. |
| 🏋️ **AI Gym Coach** | Turned live pose landmarks into real-time form feedback and spoken coaching. |

### 🧩 How they work (click to expand)

<details>
<summary><b>🧠 AI Resume ATS: architecture</b></summary>

<br/>

```mermaid
flowchart LR
    U["🖥️ Streamlit UI"] --> A["⚙️ FastAPI backend"]
    A --> N["🔎 spaCy text processing"]
    N --> T["📐 TF-IDF matching"]
    T --> S["🎯 ATS score and skill match"]
    S --> R["📥 Recommendations and PDF report"]
    A --> D["☁️ Supabase"]
```

</details>

<details>
<summary><b>📸 SnapClass: architecture</b></summary>

<br/>

```mermaid
flowchart LR
    C["📷 Camera"] --> F["Dlib face embedding"] --> S["SVM classifier"]
    V["🎤 Voice sample"] --> R["Resemblyzer voice embedding"]
    S --> M["✅ Attendance marked"]
    R --> M
    M --> D["☁️ Supabase"]
    D --> P["🧑‍🏫 Student and teacher portals"]
```

</details>

<details>
<summary><b>🏋️ AI Gym Coach: architecture</b></summary>

<br/>

```mermaid
flowchart LR
    W["🎥 Webcam"] --> O["OpenCV frames"] --> M["MediaPipe pose landmarks"]
    M --> A["📐 Form analysis"]
    A --> V["🖥️ Live feedback on Streamlit"]
    A --> S["🔊 AI voice coaching"]
```

</details>

---

## 🧭 The Pipeline I Keep Building

```mermaid
flowchart LR
    A["💡 Idea"] --> B["📊 Data and Models"]
    B --> C["🧠 AI Pipeline"]
    C --> D["🖥️ Streamlit App"]
    D --> E["☁️ Deploy"]
    E --> F["🔁 Debug and Improve"]
    F --> C
```

## 🔮 Where I'm Heading: Edge AI

```mermaid
flowchart LR
    S["🔌 Sensors"] --> M["⚙️ ESP32 / Microcontroller"]
    M --> I["🧠 On-device ML Inference"]
    I --> A["📱 Real-world Action"]
```

Right now I'm exploring how to run **ML models directly on ESP32 and microcontrollers**, bringing together my E&TC background and my AI work.

### 🛠️ Currently Building

<!-- Edit the statuses below as your work moves forward -->

| Status | What | Goal |
|---|---|---|
| 🟡 In progress | ESP32 + on-device ML (TinyML) | Run a small model directly on a microcontroller |
| 🔜 Next | First Edge AI demo project | Ship it live and feature it above |

---

## 🛠️ Tech Stack

**Languages and Core**

<p>
  <img src="https://skillicons.dev/icons?i=py,c,sklearn&theme=dark" alt="Python, C, scikit-learn" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" />
</p>

**ML, DL and Vision**

<p>
  <img src="https://skillicons.dev/icons?i=tensorflow,pytorch,opencv&theme=dark" alt="TensorFlow, PyTorch, OpenCV" />
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge&logo=google&logoColor=white" alt="MediaPipe" />
  <img src="https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white" alt="spaCy" />
</p>

**Backend, Apps and Data**

<p>
  <img src="https://skillicons.dev/icons?i=fastapi,supabase&theme=dark" alt="FastAPI, Supabase" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
</p>

**Embedded and Hardware**

<p>
  <img src="https://skillicons.dev/icons?i=arduino,matlab&theme=dark" alt="Arduino, MATLAB" />
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32" />
  <img src="https://img.shields.io/badge/PCB%20Design-2E7D32?style=for-the-badge" alt="PCB Design" />
</p>

**Tools**

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode&theme=dark" alt="Git, GitHub, VS Code" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter" />
</p>

---

## 💬 Ask Me About

- 👁️ Computer vision, face and pose detection
- 🧠 Building and deploying ML pipelines end to end
- 🔌 Embedded systems and Edge AI on ESP32
- ☁️ Getting apps to run inside free-tier limits

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=aniketkharose&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=8B5CF6&border_radius=12" alt="GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=aniketkharose&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&border_radius=12" alt="Top languages" />

<img src="https://streak-stats.demolab.com/?user=aniketkharose&theme=tokyonight&hide_border=true&background=0D1117&ring=8B5CF6&fire=A78BFA&currStreakLabel=A78BFA&border_radius=12" alt="Streak stats" />

</div>

### 🐍 My Contribution Snake

<!-- This image appears after the snake workflow has run once (see .github/workflows/snake.yml) -->

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aniketkharose/aniketkharose/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/aniketkharose/aniketkharose/output/github-snake.svg" />
  <img alt="Snake eating my GitHub contributions" src="https://raw.githubusercontent.com/aniketkharose/aniketkharose/output/github-snake-dark.svg" />
</picture>

</div>

---

## 📫 Let's Connect

I'm actively looking for **AI/ML and Embedded Systems internships**. If you're building something in computer vision, Edge AI or embedded AI, I'd love to chat.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aniket%20Kharose-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aniket-kharose-3287242a5)
[![Email](https://img.shields.io/badge/Email-aniketk8010%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aniketk8010@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-aniketkharose-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/aniketkharose)
[![Portfolio](https://img.shields.io/badge/Portfolio-aniket--portfolio--lime.vercel.app-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white)](https://aniket-portfolio-lime.vercel.app/)

<br/>

*⭐ If you like my projects, a star goes a long way!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer" alt="footer" />

</div>
