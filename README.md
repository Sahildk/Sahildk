# Sahil Deore

**AI/ML Engineer · LLM Agents & NLP Pipelines · Python / FastAPI**  
Navi Mumbai, India · [Portfolio](https://sahil-portfolio-mauve.vercel.app/) · [GitHub](https://github.com/Sahildk) · [LinkedIn](https://linkedin.com/in/sahildeore)

---

AI/ML Engineer with a focus on LLM agents, NLP pipelines, and full-stack AI applications.  
Shipped 3 production systems integrating Gemini and Hugging Face APIs into real-world workflows.

---

## Projects

### [Nexus AI](https://github.com/Sahildk/ai-interviewer) — Adaptive AI Interview Agent
Gemini 3.0 Flash · Next.js 15 · Node.js / Express · MongoDB Atlas · Web Speech API · Docker

- STT → Gemini → TTS voice pipeline with sub-2s round-trip latency; strict JSON output via `responseMimeType` with server-side schema validation
- System instruction architecture for multi-turn interviewer persona — behavioral rules, role constraints, conversation guardrails
- Separate Gemini evaluation agent processes full transcripts into structured JSON scorecards (Technical Accuracy, Communication, Culture Fit)

🥉 **3rd Runner-Up — edQuest BuildWithAI Hackathon · 118 participants**

---

### [TenantWatch](https://github.com/Sahildk/astrix-developer) — NLP Complaint Triage System
Hugging Face Inference API · FastAPI · Motor ODM · MongoDB Atlas · Next.js 14 · Leaflet

- Zero-shot classification routes complaints into 4 categories (Maintenance, Safety, Harassment, Unfair Rent) with 90%+ accuracy — no labelled training data
- Confidence-threshold fallback: complaints below 65% flagged as Unassigned instead of misrouted
- Async FastAPI backend serves geocoded data to a Leaflet heatmap with category, severity, and date filtering

**Top 20 of 154 Teams — HackQuinox 2.0 · 600+ participants**

---

### [PulmoScreen AI](https://github.com/Sahildk/pulmoscreen) — ML Risk Prediction Engine
Python · scikit-learn · Pandas · SMOTE · Flask · React · Recharts

- 5-classifier pipeline over 309 clinical records; SMOTE resolves 87/13 class imbalance; best model auto-selected (Logistic Regression, 94.3% F1)
- Model serialized to `.pkl`, served via Flask REST API; React/Recharts dashboard shows Precision, Recall, Confusion Matrix

---

### [Gmail → Google Sheets Automation](https://github.com/Sahildk/gmail-to-sheets) — ETL Pipeline
Python · Gmail API · Google Sheets API · OAuth 2.0

- Idempotent email parsing pipeline with duplicate prevention and structured logging
- Serverless contact pipeline variant: AWS Lambda (Python 3.12) + API Gateway + SES with least-privilege IAM; 8 mock unit tests for offline validation

---

### [CreatorDesk](https://github.com/Sahildk/creatordesk) — AI Influencer Campaign Dashboard
React · TypeScript · Zustand · Vite

- AI relevance scoring engine for creator discovery — no LLM API dependency, pure ranking logic
- Kanban workflow, analytics dashboard, Google Sheets/CSV sync

---

### [Datastraw Support CRM](https://github.com/Sahildk/datastraw-crm) — E-commerce Ticket Intelligence
React · FastAPI · Supabase · PostgreSQL · Railway

- AI ticket triage with sentiment analysis and real-time sync

---

## Stack

**AI / ML** — Gemini API · Hugging Face · LLM Prompt Engineering · Zero-Shot Classification · RAG · STT/TTS · Fine-Tuning · Agent Persona Design  
**ML Libraries** — PyTorch · scikit-learn · Pandas · NumPy · SMOTE  
**Backend** — FastAPI · Flask · Node.js · Express · REST APIs · JWT · Async Motor ODM  
**Frontend** — React · Next.js · TypeScript · Tailwind CSS  
**Cloud & Infra** — AWS Lambda · API Gateway · SES · IAM · Docker · MongoDB Atlas · Vector DBs · Vercel  
**Tools** — Git · Cursor · Claude Code · Jenkins · CI/CD · SonarCloud

---

## Currently

- Co-Head, Website Team @ E-CELL SAKEC — 5-person team, 10+ events, zero downtime
- 4th-year B.Tech IT · SAKEC, Mumbai University · CGPA 8.18
- **Google Cloud: Generative AI** — Google Cloud Skills Boost

---

> Open to **AI Engineering** and **Full-Stack AI** roles — internships and full-time.
