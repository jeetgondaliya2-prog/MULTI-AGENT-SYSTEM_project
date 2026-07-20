# 🔍  Multi-Agent AI Research System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11+-blue.svg">
  <img src="https://img.shields.io/badge/LangChain-Agentic_AI-green">
  <img src="https://img.shields.io/badge/Mistral-AI-orange">
  <img src="https://img.shields.io/badge/Tavily-Web_Search-red">
  <img src="https://img.shields.io/badge/License-MIT-yellow">
</p>

> **DeepDive** is an AI-powered **Multi-Agent Research System** built using **LangChain**, **Mistral AI**, **Tavily Search**, and **BeautifulSoup**. It autonomously researches any topic by coordinating multiple specialized AI agents and generates a professional research report with critical evaluation.

---

## 🚀 Features

- 🔎 Intelligent Web Search Agent
- 📖 Automatic Website Reader & Scraper
- ✍ AI Report Writer
- 🧐 AI Research Critic
- 🌐 Live Web Search using Tavily API
- 📄 Structured Research Reports
- 🔍 Automatic Source Collection
- ⚡ Modular Multi-Agent Pipeline
- 🧩 Easy to Extend
- 🤖 Powered by LangChain Agents

---

# 🧠 Multi-Agent Workflow

```
                  User Query
                       │
                       ▼
          🔎 Search Agent (Tavily)
                       │
                       ▼
        📖 Reader Agent (Web Scraper)
                       │
                       ▼
          ✍ Writer Chain (LLM)
                       │
                       ▼
        🧐 Critic Chain (Evaluation)
                       │
                       ▼
            📄 Final Research Report
```

---

# 🏗 Project Structure

```
MULTI-AGENT-SYSTEM_project
│
├── DeepDive.py          # Main Application
├── pipeline.py          # Research Pipeline
├── agents.py            # Agent Definitions
├── tools.py             # Search & Scraping Tools
├── requirements.txt
├── .gitignore
└── README.md
```

---

# ⚙ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| LangChain | Multi-Agent Framework |
| Mistral AI | LLM |
| Tavily API | Web Search |
| BeautifulSoup | Web Scraping |
| Requests | HTTP Requests |
| dotenv | Environment Variables |

---

# 🤖 Agents Overview

## 🔎 Search Agent

Responsible for:

- Searching recent information
- Finding reliable sources
- Returning URLs and summaries

**Tool Used**

- Tavily Search API

---

## 📖 Reader Agent

Responsible for:

- Selecting the best URL
- Scraping webpage
- Cleaning HTML
- Extracting important text

**Tool Used**

- BeautifulSoup

---

## ✍ Writer Chain

Responsible for:

- Combining research
- Writing structured reports

Report includes:

- Introduction
- Key Findings
- Conclusion
- Sources

---

## 🧐 Critic Chain

Evaluates the generated report by providing:

- Research Score
- Strengths
- Weaknesses
- Improvement Suggestions
- Final Verdict

---

# 📦 Installation

Clone the repository

```bash
git clone https://github.com/jeetgondaliya2-prog/MULTI-AGENT-SYSTEM_project.git
```

Move into the project

```bash
cd MULTI-AGENT-SYSTEM_project
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file.

```env
TAVILY_API_KEY=your_tavily_api_key
MISTRAL_API_KEY=your_mistral_api_key
```

---

# ▶ Run the Project

```bash
python DeepDive.py
```

or

```bash
python pipeline.py
```

---

# 💬 Example

Input

```
Artificial Intelligence in Healthcare
```

Pipeline

```
Search Agent
      ↓
Reader Agent
      ↓
Writer Chain
      ↓
Critic Chain
```

Output

```
✔ Detailed Research Report

✔ Sources

✔ Research Score

✔ Suggestions
```

---

# 🌟 Future Improvements

- Streamlit Dashboard
- LangGraph Integration
- Memory Support
- PDF Export
- Multi-source Reading
- Citation Generation
- Image Extraction
- Report Download
- Multi-LLM Support
- Agent Monitoring

---

# 📸 Screenshots

> Add screenshots of your application here after building the Streamlit interface.

```
screenshots/
    home.png
    pipeline.png
    report.png
```

---

# 🛠 Requirements

- Python 3.11+
- Tavily API Key
- Mistral API Key

---

# 📈 Learning Objectives

This project demonstrates:

- Multi-Agent AI Systems
- Agent Collaboration
- LangChain Agents
- Prompt Engineering
- Tool Calling
- Web Search Integration
- Web Scraping
- AI Report Generation
- AI Evaluation Pipelines

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# ⭐ Support

If you found this project useful,

⭐ Star this repository

🍴 Fork it

📢 Share it with others

---

# 👨‍💻 Author

**Jeet Gondaliya**

- 🎓 Electronics & Communication Engineering Student
- 💡 AI • GenAI • LangChain • Machine Learning
- 🚀 Passionate about Multi-Agent Systems and AI Automation

---

## 📜 License

This project is licensed under the **MIT License**.

---

<p align="center">
Made with ❤️ using LangChain, Mistral AI, Tavily & Python
</p>
