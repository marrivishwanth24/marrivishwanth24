# Hi, I'm Vishwanth Marri 👋

Software Engineer @ Salesforce | M.Eng. Computer Science @ University of Cincinnati (2024–2026)

## 🛠️ What I Build
- **AI Agent Systems** — Production RAG and multi-step LangGraph agents using Claude API, LangChain, LangGraph, MCP, pgvector
- **Full-Stack Web Apps** — React, Next.js, TypeScript, FastAPI, Node.js, Express.js
- **Cloud Infrastructure** — AWS (EC2, S3, RDS, Lambda), Docker, Kubernetes, Terraform, CI/CD

## 🔧 Tech Stack
**Languages:** Python · Java · JavaScript · TypeScript · SQL

**Frontend:** React.js · Next.js · Tailwind CSS · Component-Based Architecture

**Backend:** FastAPI · Spring Boot · Node.js · Express.js · Kafka · REST APIs · OAuth 2.0 · JWT · Microservices

**AI/Generative AI:** LLMs · Claude API · LangChain · LangGraph · Model Context Protocol (MCP) · RAG · Vector Search · AI Agents · Structured Outputs · Prompt Engineering

**Databases:** PostgreSQL · MongoDB · MySQL · Redis · Elasticsearch · pgvector

**Cloud & DevOps:** AWS · Docker · Kubernetes · Terraform · GitHub Actions · CI/CD

**Testing:** Pytest · Jest · Unit/Integration Testing · Test Automation

## 💼 Experience

**Software Engineer — Salesforce** *(Jan 2026 – Present)*
Built scalable CRM automation and onboarding platforms with Python, REST APIs, and OAuth 2.0. Engineered webhook workflows for bi-directional data sync, reducing sync errors by 90%. Integrated Generative AI into onboarding workflows and built AI-enabled React/TypeScript interfaces, cutting frontend load times by 40%.

**Software Engineer Intern — Kontaktsource** *(Aug 2025 – Dec 2025)*
Built internal data-validation tools with Node.js and FastAPI, reducing incorrect data entries by ~20%. Engineered backend APIs and React-based frontend workflows for membership and event management systems.

**Full Stack Developer — Virtusa** *(Jun 2022 – Jul 2024)*
Enhanced a multi-tenant client operations platform using the MERN stack. Built resilient Node.js/Express.js backend services with structured error handling and async processing. Containerized services with Docker and automated AWS EC2 deployments via GitHub Actions, cutting release cycles by 35%. Optimized PostgreSQL performance through indexing, query optimization, and Redis caching.

## 📌 Featured Projects

### 🤖 [AI-Powered Document Q&A System](https://github.com/marrivishwanth24/rag-agent-platform)
`FastAPI` `pgvector` `LangGraph` `Claude API` `MCP` `TypeScript` `React`

Production document Q&A platform with two-stage retrieval (pgvector ANN search + Voyage AI reranking). The retrieval agent is a **LangGraph state machine** that grades its own results and retries with a widened search when context looks insufficient, rather than returning a weak answer outright. Includes real agentic tool calling (session-safe by construction — the model can request a tool, but never supplies the session identifiers it would need to misuse it), an isolated **MCP server**, a Claude-to-OpenAI fallback for provider outages, and real-time streaming via Server-Sent Events.
**[Live Demo →](https://rag-frontend-topaz.vercel.app)**

### 🔍 [Lead Enrichment & Outreach Agent](https://github.com/marrivishwanth24/lead-enrichment-agent)
`Python` `FastAPI` `LangGraph` `Claude API` `Structured Outputs` `Pytest`

A multi-step LangGraph agent that researches a company, qualifies it against configurable criteria, and drafts personalized outreach — with an independent grading step that verifies every claim against its source before a human ever sees it, and **fails closed** on any verification error instead of silently auto-approving unverified output.
**[Live Demo →](https://lead-enrichment-agent-production-7443.up.railway.app)**

## 🎓 Education
**Master of Engineering in Computer Science** — University of Cincinnati *(Aug 2024 – May 2026)*

## 📫 Contact
- Email: marrivishwanth06@gmail.com
- Phone: +1 (513) 348-0777
- Location: Dallas, TX
- LinkedIn: [linkedin.com/in/vishwanthmarri/](https://www.linkedin.com/in/vishwanth-marri/)
