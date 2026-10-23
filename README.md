# Lat Caesar

**Engineer who builds and owns production systems: web apps, integrations, AI tools and the testing that keeps them reliable.**

9.5+ years across full-stack automation, APIs, integrations, CI/CD and release quality. I take a platform from "fragile" to "boring and dependable", then build the tools on top that save people real time.

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lat-caesar-ctfl-at-33133ba6/)
[![Email](https://img.shields.io/badge/-latczar@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:latczar@gmail.com)

---

## How I work

- **Own it end to end.** Design, build, test, deploy, document, support. No handing problems over the wall.
- **Stability first, then growth.** Security, monitoring, backups and clean releases come before new features.
- **Tie the work to the business.** Every project below starts with a real, slow or risky manual process and ends with fewer hours spent and fewer mistakes made.
- **AI where it earns its place.** The model handles the fuzzy part; plain code enforces the rules; a person approves anything that matters.

---

## Featured projects

> Most of my production work is under client NDA. These are public, working rebuilds of the same patterns, using made-up data.

### 📨 Doctor Outreach: messy spreadsheet to approved, sent emails
[**Live demo →**](https://doctor-outreach.vercel.app/) · [Code](https://github.com/latczar/doctor-outreach-demo)

<img src="https://github.com/latczar/doctor-outreach-demo/raw/main/docs/screenshots/01-overview.png" width="49%"> <img src="https://github.com/latczar/doctor-outreach-demo/raw/main/docs/screenshots/03-review.png" width="49%">

Turns a research list full of duplicates and guessed emails into personalised drafts a named person signs off before anything is sent. Rules decide who is contacted, the AI writes, and every decision and send is logged.
**Shows:** customer-facing workflow design, audit trails, safe sending, a business process made faster without losing control.
`Python` `FastAPI` `SQLite` `LLM` `Vercel`

---

### ⚙️ Automation Architect: which steps are safe to automate?
[**Live demo →**](https://ai-auto-architect.vercel.app) · [Code](https://github.com/latczar/automation-architect)

<img src="https://github.com/latczar/automation-architect/raw/main/docs/screenshots/02-map.png" width="49%"> <img src="https://github.com/latczar/automation-architect/raw/main/docs/screenshots/03-connections.png" width="49%">

Describe a manual job in plain English and get a validated process map, a judgement on which steps can run unattended, and an importable n8n workflow. Steps that move money or can't be undone are never marked safe, and an eval suite checks that this holds.
**Shows:** spotting automation opportunities, integration planning across business systems, guardrails on AI output.
`Python` `FastAPI` `React` `Pydantic` `n8n` `Gemini`

---

### 🎧 AI Service Desk: support tickets triaged, answered and escalated
[Code](https://github.com/latczar/agentic-qa-sd)

<img src="https://github.com/latczar/agentic-qa-sd/raw/main/docs/screenshots/01-overseer-floor.png" width="49%"> <img src="https://github.com/latczar/agentic-qa-sd/raw/main/docs/screenshots/02-console-pipeline.png" width="49%">

Tickets from a web form, API or Telegram are queued with retries and a dead-letter queue, answered from a knowledge base, and passed to a person when the model is unsure or the request is sensitive. A live dashboard shows service health and every ticket's progress.
**Shows:** production reliability (queues, retries, crash recovery), monitoring dashboards, internal tools for support teams.
`Python` `FastAPI` `RabbitMQ` `PostgreSQL` `pgvector` `MCP` `Ollama` `CI`

---

### 🧪 Agentic QA: manual test cases to approved Playwright tests
[Code](https://github.com/latczar/agentic-qa-tcm)

<img src="https://github.com/latczar/agentic-qa-tcm/raw/main/docs/screenshots/02-review-run.png" width="49%"> <img src="https://github.com/latczar/agentic-qa-tcm/raw/main/docs/screenshots/03-gate-report.png" width="49%">

Picks up test cases marked ready, generates Playwright tests, and only accepts one after it passes six automated quality gates and runs for real. A person approves it before it joins the suite.
**Shows:** test and release discipline, CI gates, change control, using AI daily in development without lowering quality.
`TypeScript` `Playwright` `n8n` `Ollama` `GitHub Actions`

---

## What I bring to a platform

| Area | Experience |
| --- | --- |
| **Build & integrate** | Full-stack web apps, REST APIs, webhooks, databases, third-party and business-system integrations |
| **Keep it running** | Production troubleshooting, monitoring, retries and failure handling, root-cause analysis |
| **Ship safely** | CI/CD, test automation frameworks, release validation, regression and UAT, change control |
| **AI & automation** | LLM tools, RAG, MCP, n8n workflows, human-in-the-loop approval, evals |
| **Lead** | Automation strategy, framework architecture, mentoring engineers, clear docs for technical and non-technical readers |

## Web platforms & e-commerce

I'm comfortable picking up an existing production codebase, whatever it's built on, and making it secure, stable and easy to release. I'm currently expanding into **Social Stack** and similar commerce and CMS platforms, building on what I already use day to day:

- **Full-stack web:** React front ends, Python/FastAPI and Node back ends, REST APIs, webhooks, deployments on Vercel and Docker
- **Ordering & sales workflows:** test automation for sales platforms ([SalesTestAutomation](https://github.com/latczar/SalesTestAutomation)), and customer journeys checked end to end with Playwright and Selenium
- **Business-system integrations:** Microsoft 365 / SharePoint automation ([PlaywrightSharepointRepo](https://github.com/latczar/PlaywrightSharepointRepo)), databases, queues and third-party APIs
- **Running live sites:** release pipelines, regression suites, monitoring, failure handling and clear runbooks

## Tech

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![n8n](https://img.shields.io/badge/-n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Selenium](https://img.shields.io/badge/-Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/-Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)
![Jenkins](https://img.shields.io/badge/-Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

## Certifications

- ISTQB Certified Tester, Advanced Level: Test Analyst (CTAL-TA)
- ISTQB Certified Tester, Foundation Level: Agile Tester (CTFL-AT)
- ISTQB Certified Tester, Foundation Level (CTFL)
