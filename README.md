# 🤖 Agentic AI Chatbot – Modular, Scalable & Production-Ready

Welcome to the **Agentic AI Chatbot** project – an end-to-end, production-oriented AI system built with **LangGraph**, **LangChain**, and **Grok/OpenAI**, focused on modularity, real-world capabilities, and deployability.

> 🚀 This project is part of my personal journey to master Agentic AI and demonstrate deep skills in modern LLM engineering, orchestration, and tool integration.

---

## 🧠 Key Highlights

- ✅ **LangGraph-based Chatbot** with persistent state and routing
- ✅ Modular design using **tools**, **memory**, and **multi-step workflows**
- ✅ **News fetcher agent** using real-time web scraping & Tavily API
- ✅ FastAPI/Streamlit-based UI for web interface
- ✅ Full **Git + CI/CD** integration for cloud deployment
- ✅ Built with **open-source alternatives** (Grok > OpenAI where possible)

---

## 📁 Project Structure

agentic_chatbot/
├── venv/ # Virtual environment (ignored in git)
├── main.py # Main application logic
├── tools/ # Tool-based functions for agent
├── chains/ # LangGraph flows
├── config/ # API keys and env setup
├── requirements.txt # Project dependencies
├── README.md # You're reading this!
├── .gitignore # Git exclusions
└── .env # Environment variables (API keys etc.)


---

## 🛠️ Tech Stack

| Layer            | Tools/Libraries                      |
|------------------|---------------------------------------|
| 💬 LLMs           | Groq, OpenAI (fallback)               |
| 🧠 Frameworks     | LangGraph, LangChain, LangChain Core |
| 🔧 Tools & APIs   | Tavily, Custom Python Tools          |
| 🌐 Interface      | Streamlit / FastAPI                  |
| 🧪 DevOps         | Git, GitHub, CI/CD pipeline ready    |

---

## 🚀 Functional Milestones

### ✅ Phase 1: Basic Chatbot with LangGraph  
- Modular flow using `@tool` decorators  
- Simple memory support using LangChain memory

### ✅ Phase 2: Chatbot with Tools  
- Add search tool using Tavily  
- Add calculation/math tool  
- Route requests to the right tool automatically

### ✅ Phase 3: AI News Fetcher Agent  
- User can ask: *“What’s the latest in AI today?”*  
- Bot scrapes + summarizes top news using LLM

### ✅ Phase 4: UI + Deployment  
- Streamlit-based simple UI  
- FastAPI endpoint for agent API  
- Deployment to Render/HuggingFace/Vercel  
- GitHub → CI/CD setup

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/agentic-chatbot.git
cd agentic-chatbot
conda activate ./venv
pip install -r requirements.txt

Set your environment variables in .env:

OPENAI_API_KEY=your_openai_key
GROQ_API_KEY=your_groq_key
TAVILY_API_KEY=your_tavily_key

Run locally:

python main.py


🧪 Upcoming Features
 Custom vector DB support (Chroma)

 Agent memory with Redis

 PDF/file upload + Q&A

 LangServe integration


 📄 License
This project is open-source under the MIT License.


👋 Connect With Me
Feel free to reach out or collaborate if you're building in LLMs, agents, or deploying AI in production.

🔗 LinkedIn: https://www.linkedin.com/in/debasish-besra-80537b361/
🐦 Twitter/X: https://x.com/besra_ai
📧 Email: debasish.besra.ai@gmail.com


⭐ Star this repo if you find it helpful, and watch for more updates as I build advanced Agentic AI systems in public.



---




