## Lat Caesar

Engineer with 9.5+ years across full-stack automation, APIs, integrations, CI/CD and release quality. I take ownership of production systems, make them stable and dependable, then build the tools on top that save teams real time.

[LinkedIn](https://www.linkedin.com/in/lat-caesar-ctfl-at-33133ba6/) · [latczar@gmail.com](mailto:latczar@gmail.com)

### How I work

- I own work end to end: design, build, test, deploy, document and support.
- Stability comes first. Security, monitoring, backups and clean releases come before new features.
- Every project starts with a slow or risky manual process and is judged by the time and mistakes it removes.
- I use AI where it earns its place. The model handles the fuzzy part, plain code enforces the rules, and a person approves anything that matters.

### Selected projects

Most of my production work is under client NDA. These are public rebuilds of the same patterns, using made-up data.

---

#### Doctor Outreach

[Live demo](https://doctor-outreach.vercel.app/) · [Source](https://github.com/latczar/doctor-outreach-demo)

<img src="https://github.com/latczar/doctor-outreach-demo/raw/main/docs/screenshots/01-overview.png" width="49%"> <img src="https://github.com/latczar/doctor-outreach-demo/raw/main/docs/screenshots/03-review.png" width="49%">

Turns a research list full of duplicates and guessed addresses into personalised emails that a named person approves before anything is sent. Rules decide who is contacted, the model drafts, and every decision is logged.

Python, FastAPI, SQLite, Vercel

---

#### Automation Architect

[Live demo](https://ai-auto-architect.vercel.app) · [Source](https://github.com/latczar/automation-architect)

<img src="https://github.com/latczar/automation-architect/raw/main/docs/screenshots/02-map.png" width="49%"> <img src="https://github.com/latczar/automation-architect/raw/main/docs/screenshots/03-connections.png" width="49%">

Takes a manual business process described in plain English and returns a validated process map, a view of which steps can safely run unattended, and an importable n8n workflow. Steps that move money or cannot be undone are never marked safe, and an evaluation suite checks that this holds.

Python, FastAPI, React, Pydantic, n8n

---

#### AI Service Desk

[Source](https://github.com/latczar/agentic-qa-sd)

<img src="https://github.com/latczar/agentic-qa-sd/raw/main/docs/screenshots/01-overseer-floor.png" width="49%"> <img src="https://github.com/latczar/agentic-qa-sd/raw/main/docs/screenshots/02-console-pipeline.png" width="49%">

Support tickets from a web form, API or Telegram are queued with retries and a dead-letter queue, answered from a knowledge base, and passed to a person when the answer is uncertain or the request is sensitive. A live dashboard shows service health and each ticket's progress.

Python, FastAPI, RabbitMQ, PostgreSQL, pgvector, MCP, GitHub Actions

---

#### Test Generation Pipeline

[Source](https://github.com/latczar/agentic-qa-tcm)

<img src="https://github.com/latczar/agentic-qa-tcm/raw/main/docs/screenshots/02-review-run.png" width="49%"> <img src="https://github.com/latczar/agentic-qa-tcm/raw/main/docs/screenshots/03-gate-report.png" width="49%">

Picks up manual test cases marked ready, generates Playwright tests, and accepts one only after it passes six automated checks and runs for real. A person signs it off before it joins the suite.

TypeScript, Playwright, n8n, GitHub Actions

---

### Experience

| Area | |
| --- | --- |
| Build and integrate | Full-stack web apps, REST APIs, webhooks, databases, business-system and third-party integrations |
| Run in production | Troubleshooting, monitoring, retries and failure handling, root-cause analysis |
| Release safely | CI/CD, test automation frameworks, release validation, regression and UAT, change control |
| Automate | LLM tools, retrieval, MCP, n8n workflows, human approval steps, evaluations |
| Lead | Automation strategy, framework architecture, mentoring engineers, documentation for technical and non-technical readers |

### Web platforms and e-commerce

I'm comfortable picking up an existing production codebase, whatever it's built on, and making it secure, stable and easy to release. I'm currently expanding into e-commerce, online ordering and CMS platforms, building on:

- Full-stack web: React front ends, Python and Node back ends, REST APIs, deployments on Vercel and Docker
- Sales and ordering workflows: [test automation for a sales platform](https://github.com/latczar/SalesTestAutomation) and end-to-end customer journeys with Playwright and Selenium
- Business-system integrations: [Microsoft 365 / SharePoint automation](https://github.com/latczar/PlaywrightSharepointRepo), databases, queues and third-party APIs
- Running live sites: release pipelines, regression suites, monitoring and runbooks

### Tools

Python · TypeScript · JavaScript · Java · FastAPI · React · PostgreSQL · RabbitMQ · Docker · n8n · Playwright · Selenium · GitHub Actions · Azure DevOps · Jenkins · Vercel

### Certifications

ISTQB Advanced Level Test Analyst (CTAL-TA) · ISTQB Foundation Level Agile Tester (CTFL-AT) · ISTQB Foundation Level (CTFL)
