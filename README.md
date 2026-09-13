![Mehul Vishwakarma — AI/ML Developer](banner.svg)

# Mehul Vishwakarma

**AI/ML Developer | Python | Machine Learning | FastAPI | GenAI**
B.Tech in Artificial Intelligence & Machine Learning · 2023–2027
Jabalpur, India

📧 [mehulvinodv@gmail.com](mailto:mehulvinodv@gmail.com) ·
🔗 [LinkedIn](https://www.linkedin.com/in/mehulvishwakarma13) ·
💻 [GitHub](https://github.com/mehulvish13) ·
🌐 [Portfolio](https://mv13.netlify.app/) ·
🐦 [X](https://x.com/MehulVish13)

> Open to AI/ML internships, software roles, hackathons, and collaborative projects.

---

## 📄 About Me

I'm Mehul, a B.Tech student specializing in Artificial Intelligence and Machine Learning at Shri Ram Institute of Technology, Jabalpur.

I mainly work with **Python, machine learning, FastAPI, SQL, and GenAI**, and I enjoy turning ideas into working applications rather than stopping at model training. My projects have involved areas such as agriculture, document processing, healthcare, and personalized learning.

As team leader of all my hackathon teams, I have led our teams at NexGen Hack Ghaziabad 2025 (Finalist — Top 15 out of 400 teams), VOID Hacks 7.0 (Finalist — Top 30 out of 250+ teams), and SRIJAN Hackathon (Participant). I've built and deployed ML prototypes and worked with APIs and databases. I'm currently focusing on strengthening my **DSA, SQL, backend development, and AI/ML fundamentals** while building projects that I can explain and defend technically.

**CGPA: 8.65**

---

## 🎓 Education

**B.Tech in Computer Science (Artificial Intelligence & Machine Learning)**
Shri Ram Institute of Technology, Jabalpur
Affiliated with Rajiv Gandhi Proudyogiki Vishwavidyalaya, Bhopal
2023–2027 · **CGPA: 8.65**

**Senior Secondary (12th) – PCM**
Central Academy Higher Secondary School, Shahdol
2022–2023 · **91.8%**

**Secondary (10th)**
Spring Dales Higher Secondary School, Shahdol
2020–2021 · **81.6%**

---

## 💼 Internship Experience

### ML Developer Intern

**AICTE & EduNet Foundation · 4 Weeks**

Worked on an ML-based smart irrigation system that uses soil, moisture, and environmental inputs to recommend irrigation actions.

* Built the prediction pipeline using **Python and Scikit-learn**.
* Worked with multiple sensor and environmental inputs to generate irrigation decisions.
* Developed a **Streamlit interface** to make the model usable as a simple decision-support tool.
* Prepared the project for demonstration and practical testing.

🔗 [Live Demo](https://mehulvish13-smart-irrigation-aicte-shell-app-ire8ba.streamlit.app/) · [Source Code](https://github.com/mehulvish13/smart-irrigation-mv)

---

## 🧑‍💼 Experience & Leadership

* **Google Developer Group SRIT — Volunteer (2024–Present)**
  Help with AI and cybersecurity workshops, peer learning sessions, and technical activities.

* **NexGen Devs — Core Member, AI Projects Team**
  Work with student teams on AI-focused projects and hackathons.

---

## 🛠️ Skills

<p align="center">
  <img src="https://skillicons.com/icons?i=python,fastapi,mysql,tensorflow,pytorch,git,github" alt="Tech stack" />
</p>

**Programming:**
Python, SQL, C++

**AI / Machine Learning:**
Scikit-learn, TensorFlow, Keras, PyTorch, Pandas, NumPy, Matplotlib

**Backend & Applications:**
FastAPI, Flask, Django, Streamlit

**Databases & Tools:**
MySQL, Git, GitHub, Jupyter

**GenAI:**
LLM applications, Prompt Engineering, RAG fundamentals

**Currently Learning:**
C#, .NET, ASP.NET Core, OOP, REST APIs

**Familiar With:**
Java, PHP, Arduino, Cisco Packet Tracer, MLflow, Weights & Biases

---

## 🚀 Featured Projects

### 🧭 PathFinder – AI-Powered Personalized Learning Path Recommender

A learning-path system that helps a user identify skill gaps for a target career and turn them into a structured learning roadmap.

The system takes a learner's profile and target career, compares their current skills with the required skills, considers prerequisite relationships, and generates a personalized roadmap.

**Flow:**
`Learner Profile → Skill Extraction → Skill Gap Analysis → Prerequisites → Roadmap Generation → Progress Tracking`

**Stack:** FastAPI, Python, SQL, LLM, Qdrant

**What I worked on:**

* Designed career, skill, and prerequisite data models.
* Built APIs for learner profiles and career paths.
* Implemented skill-gap analysis between current and target skills.
* Added prerequisite relationships to improve the order of recommended skills.
* Built the roadmap generation flow for personalized learning plans.

**Architecture:**

```
                 PATHFINDER
                     │
         ┌───────────┴───────────┐
         ↓                       ↓
   Learner Profile          Target Career
         │                       │
         └───────────┬───────────┘
                     ↓
              Skill Extraction
                     ↓
              Skill Gap Analysis
                     ↓
             Prerequisite Graph
                     ↓
             Roadmap Generator
                     ↓
          Personalized Learning Path
                     ↓
              Progress Tracking
```

<!-- Preview: add 1-3 screenshots here (input screen, generated roadmap, progress view) -->

🔗 [Source Code](https://github.com/mehulvish13/PathFinder)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

---

### 🗺️ FRA Atlas – Digitization & Decision Support Platform

A web application built to simplify the processing of Forest Rights Act (FRA) land claims by digitizing document information and helping map beneficiaries to relevant government schemes.

I built the backend using **FastAPI and MySQL**, with OCR used to extract information from uploaded documents. A rule-based layer then uses the extracted information to identify suitable scheme options.

**Flow:**

`Document → OCR → Extracted Data → Rule Engine → Scheme Mapping`

```
Document
   ↓
OCR
   ↓
Extracted Information
   ↓
Validation
   ↓
Rule Engine
   ↓
Government Scheme Mapping
```

<!-- Preview: add 1-2 screenshots here (upload screen, scheme mapping result) -->

**Stack:** FastAPI, MySQL, Tesseract OCR, Streamlit

**What it demonstrates:**

* REST API development
* Database integration
* OCR-based document processing
* Rule-based decision logic
* Connecting backend services with a simple frontend

🔗 [Live Demo](https://minor-project-am2.streamlit.app/) · [More Projects](https://github.com/mehulvish13?tab=repositories)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

---

### 🌾 AI-based Smart Irrigation System

A machine learning-based irrigation decision-support system that uses soil, moisture, and environmental inputs to recommend suitable irrigation actions.

The model was built in Python using Scikit-learn and exposed through a Streamlit application so the predictions could be tested through a simple interface.

**Flow:**
`Sensor / Environmental Inputs → ML Model → Irrigation Recommendation`

```
Soil + Moisture + Weather
            ↓
        ML Model
            ↓
   Irrigation Decision
            ↓
       Streamlit UI
```

<!-- Preview: add 1-2 screenshots here (input dashboard, recommendation output) -->

**Stack:** Python, Scikit-learn, Streamlit

**Outcome:** Working ML decision-support prototype for irrigation planning.

🔗 [Live Demo](https://mehulvish13-smart-irrigation-aicte-shell-app-ire8ba.streamlit.app/) · [Source Code](https://github.com/mehulvish13/smart-irrigation-mv)

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

---

### 🏥 HealthAI Guardian – Health Risk Assessment Prototype

A hackathon prototype exploring how machine learning, NLP, and sensor data can be combined for basic health-risk assessment.

The project accepts symptom-related information and other inputs, processes them using ML-based components, and presents the resulting risk assessment through the application.

**Stack:** Python, Scikit-learn, NLP, Arduino / IoT

**Features:**

* Symptom-based assessment
* Risk scoring
* Sensor-data integration
* Early-warning prototype

🔗 [Source Code](https://github.com/mehulvish13/HealthAI-Guardian--void-hacks7.0) · [Portfolio](https://mv13.netlify.app/)

---

### 💚 SehatSathi – Personal Health & Fitness Assistant

A student project that combines basic health and fitness tracking with ML-based analysis and a conversational interface.

The project explores features such as calorie estimation, workout suggestions, mood and stress-related inputs, and a simple health assistant.

**Stack:** Python, ML, Health Analytics

**Features:**

* Calorie estimation
* Workout suggestions
* Basic mood and stress analysis
* Conversational health assistant

🔗 [Portfolio](https://mv13.netlify.app/) · [All Repositories](https://github.com/mehulvish13?tab=repositories)

---

## 🧪 Live Demos

* 🌾 [Smart Irrigation](https://mehulvish13-smart-irrigation-aicte-shell-app-ire8ba.streamlit.app/) — ML-based irrigation decision support
* 🗺️ [FRA Atlas](https://minor-project-am2.streamlit.app/) — OCR and rule-based scheme mapping prototype
* 🧠 [Portfolio Projects](https://mv13.netlify.app/#projects) — More projects and experiments

---

## 🏆 Achievements

| Hackathon | Result |
| ------------------------------ | ------------------------------ |
| **NexGen Hack Ghaziabad 2025** | Finalist, Top 15 of 400 teams |
| **VOID Hacks 7.0** | Finalist, Top 30 of 250+ teams |
| **SRIJAN Hackathon** | Participant |

---

## 🏅 Certifications

* [Deloitte Australia Data Analytics Job Simulation – Forage](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/9PBTqmSxAf6zZTseP/io9DzWKe3PTsiS6GG_9PBTqmSxAf6zZTseP_yMSzRLqCKNkJGYm9k_1749615695464_completion_certificate.pdf)
* [CyberOps Associate – Cisco](https://www.credly.com/badges/83d56cef-8fb3-44b1-ab8c-67bf1a31243d/linked_in_profile)
* [Python Essentials 1 – Cisco](https://www.credly.com/badges/85ecfcea-5bf4-41d7-ba91-b495c2a93c99/linked_in_profile)
* [Junior Cybersecurity Analyst Career Path – Cisco](https://www.credly.com/badges/e21755f0-19a4-4535-bfb8-775ab2b92f31/linked_in_profile)
* [Artificial Intelligence Fundamentals – IBM](https://www.credly.com/badges/ef8ca76c-a308-4a1f-8e90-a6f471888eb1/linked_in_profile)
* [Cybersecurity Essentials – Cisco](https://www.credly.com/badges/76d8471f-559a-49dc-a994-0d7dd3f6a6de/linked_in_profile)

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=mehulvish13&show_icons=true&theme=default" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mehulvish13&layout=compact" alt="Top Languages" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mehulvish13&theme=default" alt="GitHub Streak" />
</p>

---

## 📄 Resume

[![View Resume](https://img.shields.io/badge/View%20Resume-PDF-blue?style=for-the-badge)](resume_MV.pdf)

---

## 🔗 Let's Connect

I'm always open to discussing AI/ML projects, hackathons, internships, and interesting technical ideas.

[LinkedIn](https://www.linkedin.com/in/mehulvishwakarma13) · [GitHub](https://github.com/mehulvish13) · [Portfolio](https://mv13.netlify.app/) · [Email](mailto:mehulvinodv@gmail.com)
