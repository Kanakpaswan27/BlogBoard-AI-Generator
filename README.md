# 🤖 BlogBoard — Autonomous AI Article Generator & Publisher  


---

## 🎯 Project Overview  
**BlogBoard** is an end-to-end, fully automated blogging infrastructure that entirely eliminates human dependency from content delivery pipelines. Powered by a stateful multi-agent system, it autonomously researches global tech trends, writes production-grade technical articles, formats them cleanly, and instantly deploys the content directly onto a live static frontend server.

> **✨ Developed For:** FutureTech HackFest 2026  
> **👩‍💻 Developer:** Kanak Kumari (BCA 2nd Year)  

---

## 📸 Product Screenshots & Walkthrough  

Explore the system UI, agent runtime operations, and dynamic content layouts below:

### 1. Main Dashboard & AI Blog Feed
<!-- INSERT YOUR MAIN WEBSITE HOMEPAGE SCREENSHOT HERE -->
<p align="center">
  <img width="1583" height="787" alt="image" src="https://github.com/user-attachments/assets/c94c7bb3-d879-4a52-8b0b-60b4ec7822f8" />

</p>

### 2. Multi-Agent AI Response & Content Generation
<!-- INSERT YOUR VS CODE TERMINAL RUNTIME SCREENSHOT HERE -->
<p align="center">
  <img width="1581" height="793" alt="image" src="https://github.com/user-attachments/assets/b5b2ebe2-9e7f-4760-a68b-1ab2c2d61a08" />

</p>

### 3. Fully Responsive Technical Blog Layout
<!-- INSERT A SCREENSHOT OF A FULLY OPENED BLOG POST ARTICLE HERE -->
<p align="center">
  <img width="1579" height="791" alt="image" src="https://github.com/user-attachments/assets/0d922082-0e44-4f34-bbf2-2f38561243f5" />

</p>

---

## 🚀 Key Features & Innovation  
* 🧠 **Stateful Multi-Agent Workflow:** Replaces fragile linear prompts with cyclical agent graphs (Research, Writer, Formatter) that critique and iteratively refine data quality.
* ⚡ **Blazing Fast Inference:** Integrated directly with the **Groq LLM Engine** to complete deep technical web compilations within fractions of a second.
* 🔄 **DevOps Automation:** Seamlessly bridges generative models with web architecture by updating frontend assets without manual intervention or staging.

---

## 🛠️ Tech Stack  
* **Core Language:** Python 3.12+
* **Agent Orchestration:** LangGraph Framework
* **Inference Layer:** Groq API Engine (Langchain-Groq)
* **Frontend UI:** HTML5, CSS3, JavaScript (Responsive Static Wireframes)

---

## 📂 Project Architecture  
The platform orchestrates operations via 3 isolated, specialized agent entities:
1. 🔍 **Research Agent:** Targets structured technical data arrays and scans for high-signal technological trends.
2. ✍️ **Writer Agent:** Synthesizes raw research datasets into deep-dive, zero-fluff, production-grade text drafts.
3. 🎨 **Formatter Agent:** Sanitizes inline code blocks, organizes technical sub-headings, and formats the output into clean Markdown syntax.

---

## 📦 Local Setup Instructions (For Evaluators & Judges)  

### 1. Clone the Repository
```bash
git clone https://github.com
cd YOUR_REPO_NAME
```

### 2. Create and Activate Virtual Environment
```bash
python -m venv .venv
# On Windows:
.venv\Scripts\activate
# On Linux/Mac:
source .venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install langgraph groq python-dotenv sentry-sdk langchain-groq langchain-core
```

### 4. Configuration (.env Setup)
Create a `.env` file in the root project folder and securely append your Groq access key:
```env
GROQ_API_KEY=your_groq_api_key_here
```

### 5. Run the System Execution Pipelines
```bash
# To start the backend agent infrastructure pipeline:
python -m blogboard.run

# To serve frontend web structures locally (Alternatively, double-click web/index.html):
python -m http.server 8000 --directory web
```

---
📄 **License:** Distributed under the MIT License. See `LICENSE` for more details.
