# 🔍 Automated Digital Forensics Reporter (ADFR)

## 📌 Overview

ADFR (Automated Digital Forensics Reporter) is an AI-powered system that automates the process of digital forensic analysis and report generation. It extracts artifacts from forensic data sources, analyzes them using intelligent techniques, and generates structured, court-ready reports.

---

## 🚀 Features

* 📂 Automated ingestion of forensic data (disk images, logs, Autopsy outputs)
* 🔍 Extraction of artifacts (file metadata, timestamps, registry data, hashes)
* 🧠 AI-powered analysis using Retrieval-Augmented Generation (RAG)
* 🔗 Evidence correlation and timeline reconstruction
* 📄 Automated generation of structured forensic reports
* 🌐 Simple web-based interface for interaction

---

## 🛠️ Tech Stack

* **Backend:** Python, FastAPI, Uvicorn
* **Forensics:** pytsk3 (The Sleuth Kit bindings)
* **AI/ML:** RAG architecture with LLM integration
* **Frontend:** HTML, CSS
* **Environment Management:** python-dotenv

---

## 📁 Project Structure

```
backend/
│── main.py                 # FastAPI entry point
│── autopsy_parser.py       # Extracts forensic artifacts
│── rag_engine.py           # AI + RAG processing
│── report_generator.py     # Generates final reports
│── requirements.txt
│── .env.example

frontend/
│── index.html              # Main UI
│── login.html              # Login page
│── loading.html            # Processing screen
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2️⃣ Create virtual environment

```
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install dependencies

```
cd backend
pip install -r requirements.txt
```

### 4️⃣ Setup environment variables

Create a `.env` file in the backend folder and add:

```
OPENAI_API_KEY=your_api_key_here
```

---

## ▶️ Running the Project

### Start Backend Server

```
python main.py
```

OR

```
uvicorn main:app --reload
```

### Open Frontend

* Open `frontend/index.html` in browser
* Or use Live Server in VS Code

---

## 🔄 Workflow

1. Upload forensic data
2. Parse and extract artifacts
3. Preprocess and structure data
4. Classify and correlate evidence
5. Apply RAG-based AI analysis
6. Generate and download forensic report

---

## 📊 Output

* Structured forensic report including:

  * Executive Summary
  * Methodology
  * Evidence Analysis
  * Timeline Reconstruction
  * Technical Findings

---

## 🎯 Objective

To automate digital forensic investigations by reducing manual effort, improving accuracy, and generating legally reliable reports.

---

## ⚠️ Disclaimer

This tool is intended for educational and research purposes only. It should not replace professional forensic investigation tools in legal scenarios.

---

## 👩‍💻 Author

**Naseha Jabeen**
