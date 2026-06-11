# Pedro Monte

**AI Systems Engineer** — Multi-Agent Orchestration · LLM Systems · AWS · Production SaaS

📍 Porto, Portugal · Open to remote AI engineering contracts (EU/USA)

I build production-grade AI systems — from the orchestration layer that coordinates multi-agent pipelines to the end-user products running on top. Most of my code is proprietary client and product work, so this profile is the map, not the territory — happy to walk through any of these architectures in a call.

---

## What I'm building

### 🏥 MedTrack — Healthcare SaaS for shift doctors
**In production · 81 active users.** Doctors register shifts, track earnings and manage schedules — including through an AI-powered WhatsApp bot that parses natural language. Self-hosted Supabase (Docker) on a DigitalOcean VPS, PWA with offline support, multi-tenant data model with Row-Level Security.

`React 18` `TypeScript` `Supabase (self-hosted)` `PostgreSQL` `Edge Functions` `WhatsApp API` `nginx`

### 📊 Insight Agent — Multi-agent marketing intelligence
**Operational · syncing 99 client accounts / 105 ad accounts.** One orchestrator coordinating six specialist agents (campaign analysis, budget, creative, audience, bidding, alerting), built on the Anthropic Claude SDK. Includes an 8-stage ML pipeline — LightGBM models for CTR/CVR prediction, ROAS analysis and creative-fatigue scoring over time-series data.

`Python 3.12` `Claude SDK` `LightGBM` `FastAPI` `PostgreSQL` `TimescaleDB` `pgvector` `Redis` `Docker`

### ☎️ AWS AI Call Center — AI-native contact center infrastructure
**Architecture complete · build phase.** Real-time AI voice agents on Amazon Connect with intelligent escalation to human operators. Two-speed design: Amazon Nova Sonic 2 drives the live voice flow; Claude (via Bedrock) handles the complex reasoning moments. Knowledge grounding through Bedrock Knowledge Bases over Aurora Serverless (pgvector).

`Amazon Connect` `Bedrock (Claude)` `Nova Sonic 2` `Lambda` `DynamoDB` `Aurora Serverless` `S3`

### 🦾 Paperclip — Multi-agent control plane
**The infrastructure layer underneath my projects.** Orchestrates 24 Claude agents across 3 production project instances — cut per-agent context overhead by **96%** through layered skill caching and per-project plugin isolation.

---

## Stack

- **AI / ML:** Multi-agent systems · LLM orchestration · Anthropic Claude SDK & API · prompt engineering · RAG · LightGBM · PyTorch · time-series forecasting · anomaly detection · MLOps
- **Cloud & infra:** AWS (Bedrock, Connect, Lambda, SageMaker, DynamoDB, Aurora) · Supabase (incl. self-hosted) · DigitalOcean · Docker · PostgreSQL · TimescaleDB · Redis · nginx
- **Full-stack:** Python · TypeScript · React 18 · Vite · FastAPI · Node.js · Tailwind CSS

## Contact

[LinkedIn](https://www.linkedin.com/in/pedro-monte-a72489260) · pvomonte@gmail.com
