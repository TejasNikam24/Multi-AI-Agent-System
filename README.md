# 🤖 Multi-AI-Agent-System

An intelligent multi-agent research assistant that automates the process of searching, reading, analyzing, writing, and reviewing research reports using specialized AI agents.

Built with **LangChain**, **Mistral AI**, **Tavily Search**, **BeautifulSoup**, and **Streamlit**.

---

## 🚀 Live Demo

Streamlit deployment link:

```text
https://multi-ai-agent-system.streamlit.app/
```
https://multi-ai-agent-system.streamlit.app/

---

## 📌 Project Overview

Researching a topic manually often requires:

* Searching multiple sources
* Reading lengthy articles
* Extracting key insights
* Writing structured reports
* Reviewing and improving content

This project automates the entire workflow using a team of AI agents that collaborate to produce high-quality research reports.

---

## 🏗️ Multi-Agent Architecture

### 1️⃣ Search Agent

**Responsibility:**

* Searches the web for recent and relevant information
* Uses Tavily Search API
* Collects reliable sources and URLs

**Tool Used:**

* Tavily Search

---

### 2️⃣ Reader Agent

**Responsibility:**

* Selects relevant URLs from search results
* Scrapes webpage content
* Extracts detailed information

**Tool Used:**

* BeautifulSoup
* Requests

---

### 3️⃣ Writer Chain

**Responsibility:**

* Combines search results and scraped content
* Generates a structured research report

**Output Structure:**

* Introduction
* Key Findings
* Conclusion
* Sources

---

### 4️⃣ Critic Chain

**Responsibility:**

* Reviews the generated report
* Provides strengths and weaknesses
* Assigns a quality score

**Output Format:**

```text
Score: X/10

Strengths:
- ...

Areas to Improve:
- ...

Verdict:
...
```

---

## 🔄 Workflow

```text
User Topic
     │
     ▼
Search Agent
     │
     ▼
Reader Agent
     │
     ▼
Writer Chain
     │
     ▼
Critic Chain
     │
     ▼
Final Research Report
```

---

## 🛠️ Tech Stack

### AI & LLM

* Mistral AI
* LangChain
* Python

### Search & Retrieval

* Tavily Search API

### Web Scraping

* BeautifulSoup
* Requests

### Frontend

* Streamlit

### Backend

* Python

---

## 📂 Project Structure

```text
Multi-AI-Agent-System/
│
├── app.py
├── agents.py
├── pipeline.py
├── tools.py
├── requirements.txt
├── README.md
├── .gitignore
└── .env.example
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/TejasNikam24/Multi-AI-Agent-System.git

cd Multi-AI-Agent-System
```

### Create Virtual Environment

```bash
python -m venv .venv
```

Activate:

**Windows**

```bash
.venv\Scripts\activate
```

**Linux / Mac**

```bash
source .venv/bin/activate
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

```env
MISTRAL_API_KEY=your_mistral_api_key
TAVILY_API_KEY=your_tavily_api_key
```

---

## ▶️ Run Locally

```bash
streamlit run app.py
```

---

## 🧪 Example Research Topics

Try:

* Artificial Intelligence
* LLM Agents in 2025
* CRISPR Gene Editing
* Quantum Computing
* Fusion Energy Progress
* Autonomous Vehicles
* Climate Change Technologies

---

## 🎯 Key Features

✅ Multi-Agent Architecture

✅ Automated Web Research

✅ Real-Time Information Gathering

✅ Content Scraping & Analysis

✅ AI-Powered Report Writing

✅ Automated Report Critique

✅ Streamlit Web Interface

✅ Modular & Extensible Design

---

## 📈 Future Improvements

* PDF Report Export
* Citation Management
* Multiple Search Providers
* Research Memory
* Vector Database Integration
* Multi-LLM Support (OpenAI, Groq, Gemini, Claude)
* Report Comparison Mode
* Agent Monitoring Dashboard

---

## 👨‍💻 Author

**Tejas Nikam**

Aspiring AI Engineer | Data Analyst | Data Science Enthusiast

GitHub:
https://github.com/TejasNikam24

LinkedIn:
https://www.linkedin.com/in/tejasnikam24/

---

## ⭐ Support

If you found this project useful:

* Star the repository ⭐
* Fork the project 🍴
* Share feedback 💡

---

