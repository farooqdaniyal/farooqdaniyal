<h1 align="center">Hi <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="32px"> I'm Muhammad Farooq</h1>

<p align="center">
  <b>AI & Data Science Student</b> · Karachi, Pakistan 🇵🇰<br/>
  <i>Machine Learning · Deep Learning · Computer Vision · Generative AI · Agentic Workflows</i>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/farooqdaniyal"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:farooqdaniyal151@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open%20to-AI%2FML%20%26%20Data%20Science%20Internships-22c55e?style=for-the-badge" alt="Open to internships"/>
</p>

---

## 👨‍💻 About Me

I build **end-to-end AI applications**: from training a model, to wrapping it in an API or dashboard, to deploying it.
My work spans classical ML, deep learning, computer vision and LLM-based agent workflows (RAG + LangGraph).
I enjoy projects where AI has to be **explainable and keep a human in control**.

---

## 🚀 Featured Project: SOC Control Room

> **An AI-powered Security Operations Center that detects network attacks, scores their risk, groups alerts into incidents and keeps a human analyst in control of critical decisions.**

[🔗 **Live demo**](https://cyberproject-thujuvcaz9atghprq5bjod.streamlit.app/) · [📂 **Source code**](https://github.com/YOUR_GITHUB_USERNAME/cyber_project)

<!-- Add a screenshot: put dashboard.png in a /docs folder of the repo, then uncomment the next line -->
<!-- ![SOC Control Room dashboard](https://raw.githubusercontent.com/YOUR_GITHUB_USERNAME/cyber_project/main/docs/dashboard.png) -->

**What it does**
- 🛡️ **Detection:** Random Forest classifier trained on the CICIDS2017 network-intrusion dataset (BENIGN + 6 attack types).
- 🤖 **Agentic investigation:** a **LangGraph** supervisor routes work between agents (investigation, risk scoring, correlation, verification, report, audit). A **RAG** agent (ChromaDB + HuggingFace embeddings) retrieves the matching response playbook and a **Groq-hosted LLM** writes the incident report.
- 📊 **Risk engine:** 0–100 score from attack severity × model confidence × asset criticality.
- 🔗 **Incident correlation:** related alerts are grouped by attack family, asset and time window.
- 🧑‍⚖️ **Human-in-the-loop:** critical attacks always wait for an analyst's approve/reject decision, and every run and decision is saved in an audit log.
- ⚡ **Automation:** n8n webhook logs each result to Google Sheets.
- 🎙️ **Voice assistant:** ask questions by voice (Whisper speech-to-text) and get spoken answers and a spoken shift briefing (gTTS), built from live audit data.
- 🔐 **Secure login:** SQLite, salted PBKDF2 password hashing, account lockout and invite-only signup.
- 🖥️ **Multi-page Streamlit dashboard:** incidents, threat intelligence, MITRE ATT&CK stage mapping, response center and audit logs.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square"/>
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square"/>
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white"/>
</p>

---

## 📁 More Projects

| Project | What it does | Tech |
|---|---|---|
| 🩺 **AI-Powered Medical Diagnosis System** | CNN for chest X-ray pneumonia detection and ANN for heart-disease risk prediction, with **Grad-CAM** and **SHAP** explanations, a Doctor Review Panel (human-in-the-loop) and automated PDF reports | TensorFlow/Keras, Streamlit, SHAP, ReportLab |
| 👁️ **Real-Time Object Detection** | Detects everyday objects from a live webcam feed with bounding boxes and confidence scores | YOLOv11, OpenCV, Python |
| 💰 **Income Prediction API** | ML classifier that predicts income level, served as a REST API (`/predict`) with an interactive front end | scikit-learn, FastAPI, Streamlit, joblib |

---

## 🛠️ Tech Stack

**AI / ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

**GenAI & Agents**

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)

**Apps, APIs & Visualization**

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

**Data, Web & Tools**

![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

## 📊 My AI & Data Science Learning Journey

### ✅ Completed
- [x] **Python Foundations** (Variables, OOP, File Handling, Projects), *May 2026*
- [x] **Python for Data Science** (NumPy, Pandas, Matplotlib, Seaborn, Plotly), *May 2026*
- [x] **Statistics & Math for ML** (Probability, Hypothesis Testing, Linear Algebra), *May 2026*
- [x] **Machine Learning Core** (Regression, Classification, Feature Engineering, Pipelines), *June 2026*
- [x] **Deep Learning** (ANN, CNN, Computer Vision, Explainable AI with Grad-CAM & SHAP)
- [x] **Generative AI / LLMs** (RAG, Vector Databases, LLM integration)
- [x] **Agentic AI** (multi-agent workflows with LangGraph)

### ⏳ In Progress & Next
- [ ] **MLOps** (Docker, MLflow, CI/CD) 🛠️
- [ ] **More agent frameworks** (CrewAI, AutoGen) 🤝
- [ ] **Big Data & Cloud** (Apache Spark, AWS/Azure) ☁️

---

## 📈 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages"/>
</p>

---

## 🤝 Let's Connect

I'm open to **AI/ML and Data Science internships** and to collaborating on interesting data projects.

<a href="https://www.linkedin.com/in/farooqdaniyal"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:farooqdaniyal151@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://instagram.com/faarooqdaniyal"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>

---

## ⚡ Fun Fact

I once tried to train a machine learning model to predict my exam grades, but it just returned: `"Error: Need more sleep and less caffeine!"` ☕🤖

```python
# My profile as code 😉

class MuhammadFarooq:
    def __init__(self):
        self.name = "Muhammad Farooq"
        self.role = "AI & Data Science Student"
        self.location = "Karachi, Pakistan"
        self.skills = ["Machine Learning", "Deep Learning", "Computer Vision", "RAG", "LangGraph"]
        self.featured_project = "SOC Control Room: AI-powered security operations center"
        self.currently_learning = ["MLOps (Docker, MLflow, CI/CD)", "Cloud"]
        self.open_to = "AI/ML & Data Science internships"

    def say_hi(self):
        print("Hello World! Building AI systems that explain themselves and keep humans in control.")

me = MuhammadFarooq()
me.say_hi()
```
