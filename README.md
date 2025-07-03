# 🤖 Agentic AI Chatbot – Modular, Scalable & Production-Ready

Welcome to the **Agentic AI Chatbot** project – an end-to-end, production-grade AI system built with **LangGraph**, **LangChain**, and **Grok/OpenAI**. This repo showcases real-world agent workflows with modular design, tool use, orchestration, and deployability.

> 🚀 This project is part of my personal journey to master Agentic AI and demonstrate deep skills in LLM engineering and AI tooling integration.

---

![Python](https://img.shields.io/badge/Python-3.10-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![LangGraph](https://img.shields.io/badge/LangGraph-enabled-brightgreen)
![CI/CD Ready](https://img.shields.io/badge/CI/CD-ready-success)

---

## 🎥 Demo (Coming Soon)
> _Demo GIF or screenshot of chatbot or UI will go here_

---

## 🧠 Key Highlights

✅ LangGraph-based Chatbot with persistent state and routing  
✅ Modular design using tools, memory, and multi-step workflows  
✅ News fetcher agent using real-time web scraping & Tavily API  
✅ FastAPI/Streamlit-based UI for user interaction  
✅ Full Git + CI/CD integration for cloud deployment  
✅ Built with open-source-first mindset (Grok > OpenAI where possible)  

---

## 📁 Project Structure

```
agentic_chatbot/
├── venv/               # Virtual environment (ignored in git)
├── main.py             # Main application logic
├── tools/              # Tool-based functions for agent
├── chains/             # LangGraph flows
├── config/             # API keys and env setup
├── requirements.txt    # Project dependencies
├── README.md           # You're reading this!
├── .gitignore          # Git exclusions
└── .env                # Environment variables (API keys etc.)
```

---

## 🛠️ Tech Stack

| Layer        | Tools/Libraries                             |
|--------------|---------------------------------------------|
| 💬 LLMs       | Groq, OpenAI (fallback)                     |
| 🧠 Frameworks | LangGraph, LangChain, LangChain Core        |
| 🔧 Tools      | Tavily, Custom Python Tools                 |
| 🌐 Interface  | Streamlit / FastAPI                         |
| ⚙️ DevOps     | Git, GitHub, CI/CD ready (Render/Vercel etc)|

---

## 🧪 Functional Milestones

### ✅ Phase 1: Basic Chatbot
- Modular flow using `@tool` decorators  
- Simple memory with LangChain Memory  

### ✅ Phase 2: Chatbot + Tools
- Tavily-powered web search tool  
- Calculation tool integration  
- Automatic tool routing using LangGraph  

### ✅ Phase 3: AI News Fetcher Agent
- `User:` “What’s the latest in AI today?”  
- `Bot:` Scrapes, summarizes, and responds using LLMs  

### ✅ Phase 4: UI + Deployment
- Streamlit-based web interface  
- FastAPI endpoint for backend  
- Deployable on Render / HuggingFace / Vercel  
- GitHub-integrated CI/CD  

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/agentic-chatbot.git
cd agentic-chatbot
conda activate ./venv      # or: python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
```

Create your `.env` file with API keys:

```env
OPENAI_API_KEY=your_openai_key
GROQ_API_KEY=your_groq_key
TAVILY_API_KEY=your_tavily_key
```

Run the project locally:

```bash
python main.py
```

---

## 🧪 Upcoming Features

- [ ] Chroma/FAISS vector DB support  
- [ ] Agent memory with Redis backend  
- [ ] PDF/File Upload + Q&A  
- [ ] LangServe integration for scalable APIs  

---

## 🧭 Agent Flow Diagram (Planned)

```text
User Input → LangGraph Flow →
     ├─ Tool Router
     │    ├─ Tavily Search Tool
     │    └─ Calculator Tool
     ↓
Memory / History → LLM → Output → UI / API
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👋 Connect With Me

I’m building in public — feel free to reach out or collaborate if you're into LLMs, agents, or deploying AI at scale!


- 🐦 [Twitter / X](https://x.com/besra_ai)
- 📧 Email: `debasish.besra.ai@gmail.com`

---

⭐️ **Star this repo** if you find it helpful — it motivates and helps others discover it!  






