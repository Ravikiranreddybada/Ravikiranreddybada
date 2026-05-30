# Hi, I'm Ravi Kiran Reddy 👋

**B.Tech CSE (AI & ML) · NIIT University · 3rd Year**

I build production-grade agentic AI systems — ReAct agents, RAG pipelines, async FastAPI backends. I care about systems thinking: understanding how things work at the execution level, not just through framework abstractions.

---

## What I've built

### 🤖 [AgentPilot](https://github.com/Ravikiranreddybada/agentpilot) — Multi-Agent AI Platform
> Autonomous task execution via a from-scratch ReAct loop. No LangChain — built to understand orchestration deeply.

- Implemented ReAct (Reason + Act) loop from scratch — agent decomposes queries into tool calls, observes results, synthesizes answers
- Async FastAPI backend integrating 5 external systems (Slack, Tavily, MongoDB, Pinecone, HTTP) via custom tool dispatcher
- RAG pipeline with Jina embeddings + Pinecone for hallucination-free document Q&A
- **Stack:** Python · FastAPI · asyncio · Pydantic · Pinecone · MongoDB · Docker · Groq · React.js

### 🔬 [DermaSmart](https://github.com/Ravikiranreddybada/dermasmart) — AI Skin Diagnosis System
> 4-stage safe-audit pipeline built for a hallucination-sensitive domain.

- HSV neural image gating → MobileNetV2 classification (23+ conditions) → ethical hard-intercept → Gemini 2.0 reasoning
- In-memory byte-stream processing — images never persisted to disk (deliberate privacy trade-off)
- **Stack:** Python · FastAPI · TensorFlow · MobileNetV2 · OpenCV · Gemini 2.0 · React 18 · TypeScript · Auth0

### ⚙️ [MergeMind](https://github.com/Ravikiranreddybada/MergeMind) — Autonomous GitHub PR Agent
> Converts GitHub issues into reviewed, production-ready PRs with real-time SSE streaming and human-in-the-loop gates.

- Agentic state machine: issue fetch → repo analysis → AI fix generation → human approval → PR open
- Two-stage HITL gates prevent unsafe auto-merge
- Real-time SSE streaming surfaces intermediate agent reasoning to the client
- **Stack:** Python · FastAPI · asyncio · Pydantic v2 · Groq LLaMA 3.1-70B · SSE · Next.js 14 · TypeScript

---

## Tech stack

```
Languages    Python · TypeScript · JavaScript · SQL
Backend      FastAPI · asyncio · Pydantic v2 · httpx · REST APIs
LLM/Agents   ReAct orchestration · RAG pipelines · Groq · Gemini · OpenAI-pattern APIs
Databases    Pinecone (vector DB) · MongoDB · MySQL
Frontend     React.js · Next.js · Tailwind CSS
DevOps       Docker · Git · Render · Vercel · AWS (Cloud Practitioner certified)
```

---

## Currently

- 🎓 3rd year B.Tech CSE (AI & ML) at NIIT University
- 🔍 Looking for a **6–12 month AI/ML or backend internship** (remote or Bangalore/Hyderabad)
- 🏗️ Building more production agentic systems

---

## Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://ravikiran-portfolio-theta.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/ravikiranreddybada)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:badaravikiranreddy@gmail.com)
