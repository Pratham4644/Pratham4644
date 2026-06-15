<div align="center">

# Prathamesh Shinde

**AI/ML Engineer · Computer Vision · RAG Systems · Edge AI**

*Third-year CSE student at ADCET — building AI that works in the real world, not just on benchmarks.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](http://www.linkedin.com/in/prathamesh-shinde-05942b288)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Pratham4644)
[![Portfolio](https://img.shields.io/badge/Portfolio-6366f1?style=flat&logo=vercel&logoColor=white)](#)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white)](#)
![Profile Views](https://komarev.com/ghpvc/?username=Pratham4644&color=6366f1&style=flat)

</div>

---

## About

I don't just use AI tools — I build them from the internals up. My work sits at the intersection of computer vision, retrieval-augmented generation, and systems that run offline or at the edge, because the most impactful AI often operates far from a cloud server.

Currently obsessed with multimodal RAG for agricultural applications and the question of how much you can do with a lightweight model and constrained hardware.

- 🌾 Long-term research direction: **multimodal AI for agriculture**
- 🔬 Philosophy: understand every layer before abstracting it away
- 📍 Shahuwadi, Maharashtra, India · ADCET (2023–2027)
- 🇯🇵 Preparing for MEXT 2027 — targeting NLP + multimodal RAG research track

---

## ML Model Performance

| Model / Task | Algorithm | Dataset | Metric | Score |
|---|---|---|---|---|
| Car Price Prediction | RF + GridSearchCV | Custom (8K rows) | R² / RMSE | **0.91** / ₹1.2L |
| Hotel Booking Classifier | XGBoost + GridSearchCV | Kaggle Hotel Bookings | F1 (macro) | **0.88** |
| Fashion MNIST CNN | CNN (TensorFlow/Keras) | Fashion MNIST (70K) | Accuracy | **93.4%** |
| Traffic Vehicle Detector | YOLOv8 Nano (50 epochs) | Custom traffic data | mAP@0.5 | **87.6%** |
| RAG Retrieval (Vasudha) | SentenceTransformers + FAISS | 30+ agri documents | Retrieval Acc. | **91%+** |

---

## Projects

### 🌿 Vasudha — Offline RAG Agriculture Chatbot
> *Agricultural knowledge for farmers — no internet, no paid API, no compromise.*

Built the complete software layer of a hardware+software team project. A fully offline RAG chatbot covering 4 crops and 30+ knowledge documents.

- Pipeline: PyMuPDF → chunking → SentenceTransformers embeddings → FAISS → Ollama (TinyLlama) streaming
- Retrieval accuracy **>91%** on agricultural domain queries
- Extending with crop schedule reminders, pesticide-day suggestions, and harvest tracking
- 🥈 **2nd place, ADCET Internal Hackathon** · 🏛️ **DIPEX State-Level Exhibition**

`Python` `SentenceTransformers` `FAISS` `Ollama` `TinyLlama` `PyMuPDF`

---

### 🚦 Green-Signale — Smart Traffic Monitoring
> *Real-time congestion analysis using computer vision.*

Trained YOLOv8 Nano on a custom-labelled dataset (5 vehicle classes, 50 epochs, 640px). Achieved **87.6% mAP@0.5**. Deployed real-time OpenCV detection on live video streams with adaptive signal control logic fast enough for edge deployment.

`Python` `YOLOv8` `OpenCV`

---

### 🤖 AI Automation Agent
> *One agent, many interfaces.*

AI agent that executes browser tasks (form filling, scraping, navigation) and desktop interactions from natural language commands. Exposed as a Flask REST API with Streamlit dashboard and CLI — reducing repetitive browser tasks to single-sentence commands.

`Python` `Flask` `Streamlit` `Selenium` `PyAutoGUI` `Gemini API`

---

### 🍽️ Mess ERP System
> *QR-code cafeteria management at scale.*

Handles **200+ daily scans** with real-time duplicate prevention, live meal counters, and webcam-based scanning. Admin panel supports CSV export and date-range attendance reports.

`Python` `Flask` `SQLite` `OpenCV`

---

## Experience

**Machine Learning Intern — TechnoHacks Solutions Pvt. Ltd.** *(Jun 2025 – Jul 2025)*

Built three end-to-end ML models with GridSearchCV tuning and metric-driven evaluation. Deployed a Flask web app for live model inference.

- Car price predictor — R²: **0.91**
- Hotel booking classifier — F1: **0.88**
- Fashion MNIST CNN — Accuracy: **93.4%**

---

## Skills

**Languages:** Python · Java · JavaScript · C

**AI / ML:** NumPy · Pandas · Scikit-learn · TensorFlow · Keras · OpenCV · YOLOv8 · CNNs · Random Forest · XGBoost

**GenAI & RAG:** SentenceTransformers · FAISS · LangChain · Ollama · Gemini API · OpenRouter · Composio · Prompt Engineering

**Web & Backend:** Flask · Node.js · Express.js · Streamlit · REST APIs · SQLite · MongoDB · MySQL

**Automation:** Selenium WebDriver · PyAutoGUI · BeautifulSoup

**Tools:** Git · GitHub · Postman · Linux

**CS Fundamentals:** DSA · OOP · DBMS · OS · Computer Networks

---

## Recognition

- 🥈 **Hackathon Winner** — 2nd place, ADCET Internal Hackathon (Vasudha)
- 🏛️ **DIPEX 2026** — State-level project exhibition representative
- 🌐 Member, **Google Developer Groups on Campus (GDGC)**
- ⚙️ Member, **e-Yantra ADCET**
- 📊 **Kaggle** — Machine Learning Badge · Data Analysis Badge

---

## What's Next

- Multimodal RAG with image + text retrieval
- Disease detection using vision-language models
- AI agents with structured tool use
- Edge-deployable, local-first AI applications
- Japanese NLP & machine translation research

---

<div align="center">

*"Build it from scratch. Understand every layer. Then make it useful."*

</div>
