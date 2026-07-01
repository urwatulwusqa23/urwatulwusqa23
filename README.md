# Urwa Tul Wusqa

Software Engineer · Full-Stack .NET Developer · AI Enthusiast

B.Sc Software Engineering, Punjab University FCIT (Graduated 2026) · Lahore, Pakistan

[Portfolio](https://urwatulwusqa23.github.io) · [LinkedIn](https://www.linkedin.com/in/urwatulwusqa) · [Email](mailto:urwatulwusqa23@gmail.com) · [GitHub](https://github.com/urwatulwusqa23)

---

## About

I'm a B.Sc Software Engineering graduate from Punjab University (FCIT) and a practicing Junior .NET Developer at NKU Technologies, where I build enterprise-grade, full-stack applications using ASP.NET Core, Entity Framework, and SQL Server.

My engineering approach spans the full delivery lifecycle — clean API design, relational data modelling, Angular/React frontends, and Docker-based deployment. I treat every system as a product: performance, security, and maintainability are built in, not bolted on.

I'm actively expanding into cloud-native DevOps on Azure and applied AI engineering, with hands-on experience building an AI fitness assistant (PyTorch, computer vision), an AI-powered job tracker, and integrating LLMs into production-ready web services.

**Open to:**
- Remote .NET Developer or Junior DevOps Engineer roles — Canadian companies preferred
- Full-stack or backend-focused contract engagements
- Open source collaboration in the .NET / Azure / AI ecosystem

---

## Tech Stack

**Languages** — C#, Python, TypeScript, JavaScript, C++

**Frontend** — React, Angular, HTML, CSS, Tailwind

**Backend & Databases** — ASP.NET Core, FastAPI, Node.js, PostgreSQL, MySQL, SQLite

**Cloud, DevOps & Tooling** — Azure, Docker, Kubernetes, GitHub Actions, Git, Linux, VS Code, Postman

---

## AI / ML

| Domain | Level | Details |
|:---|:---:|:---|
| Deep Learning | Intermediate | PyTorch, CNN architectures, model training pipelines |
| Computer Vision | Intermediate | Pose estimation, object detection, real-time inference |
| NLP & LLMs | Developing | Prompt engineering, LLM API integration, RAG fundamentals |
| Applied AI Products | Proficient | End-to-end AI feature integration in production web apps |
| AI-Assisted Dev | Proficient | GitHub Copilot, Claude Code, AI-augmented workflows |

---

## Projects

### Job Tracker AI — Intelligent Job Application Manager

A full-stack, AI-powered job application tracking system that eliminates manual data entry. Paste any job email or WhatsApp message and the AI extracts company, role, salary, and job description automatically. Scans multiple Gmail inboxes simultaneously, generates personalised interview prep kits, identifies skill gaps against the 2025 job market, and surfaces live remote job listings matched to your CV.

| Attribute | Detail |
|:---|:---|
| Stack | Python · Flask · Grok API (xAI) · SQLite · Vanilla JS · Docker |
| AI | Grok-3-mini via OpenAI-compatible SDK — extract, prep, skill analysis, job matching |
| Integrations | Gmail IMAP (multi-account) · Remotive live jobs API · pdfplumber CV parsing |
| Deployment | Dockerised · Fly.io (persistent volume) · Render-ready |
| Impact | Replaces a spreadsheet + 4 browser tabs with one tool; CV-aware interview Q&A in ~20s |

### Route Optimizer — Delivery Route Solver

A logistics route optimisation tool that solves the Travelling Salesman Problem for real-world delivery scenarios — the same class of problem solved by Amazon and DPD at scale. Fetches real drive-time matrices (not straight-line distances) from OpenStreetMap, solves the optimal stop order using Google OR-Tools with Guided Local Search metaheuristic, then renders the actual road-snapped route on an interactive Leaflet.js map with draggable pins.

| Attribute | Detail |
|:---|:---|
| Stack | Python · Flask · Google OR-Tools · OSRM API · Leaflet.js |
| Algorithm | TSP — PATH_CHEAPEST_ARC seed + Guided Local Search (5s budget) |
| Data | OSRM NxN duration matrix (real drive times) · GeoJSON road polyline |
| UX | Draggable map pins · real road route overlay · per-leg drive times in sidebar |
| Impact | Finds routes 15–30% shorter than naive nearest-neighbour on real geography |

### Campus Mart — Containerised Full-Stack Marketplace

A containerised student marketplace platform built for university environments. Designed for high availability with Docker-based deployment, clean REST API architecture, and a responsive frontend.

| Attribute | Detail |
|:---|:---|
| Stack | ASP.NET Core · SQL Server · React · Docker · GitHub Actions |
| Security | JWT authentication · role-based access control · input validation |
| Architecture | Separation of concerns across auth, catalogue, and order bounded contexts |
| Impact | Full deployment pipeline with Docker Compose; production-ready CI/CD |

### FitBot — AI Fitness Assistant with Computer Vision

An AI-powered personal fitness assistant combining PyTorch-based computer vision with a conversational interface. Analyses exercise form in real time across four independent functional modules — form analysis, rep counting, caloric estimation, and coaching feedback.

| Attribute | Detail |
|:---|:---|
| Stack | Python · PyTorch · OpenCV · FastAPI · React |
| AI | Real-time pose estimation · frame-level CNN inference |
| Architecture | Four independently maintained ML modules — sound modularity applied to ML systems |
| Impact | Final Year Project — presented to faculty panel; end-to-end AI product |

### RCA Intelligence Dashboard — Enterprise Angular Analytics

An enterprise Root Cause Analysis visualisation platform for internal engineering teams. Features Chart.js scatter plots, pie charts, and time-series graphs with a dual-mode (dark/light) theming system.

| Attribute | Detail |
|:---|:---|
| Stack | Angular · TypeScript · Chart.js · PrimeNG · ASP.NET Core · Entity Framework |
| Performance | Lazy-loaded chart modules · debounced filter interactions · N+1-free EF queries |
| Theming | CSS custom-property system covering 40+ variables across both colour modes |
| Impact | Replaced manual reporting with an interactive drill-down dashboard |

### AI Blog Summariser — LLM-Powered Content Pipeline

A production-grade content summarisation service integrating LLM APIs into a lightweight Python pipeline. Accepts long-form blog articles and returns structured, audience-appropriate summaries with configurable length and tone.

| Attribute | Detail |
|:---|:---|
| Stack | Python · FastAPI · LLM API · React |
| Features | Streaming response support · efficient token budget management · rate-limit-aware throttling |
| Impact | Demonstrates practical LLM integration patterns in a deployable web service |

### Mini Blogging Platform — RESTful CMS Backend

A clean, RESTful CMS backend with full CRUD operations, user authentication, and markdown rendering. Built as a reference implementation of .NET backend best practices.

| Attribute | Detail |
|:---|:---|
| Stack | ASP.NET Core · SQL Server · Entity Framework Core |
| Patterns | Repository pattern · service layer separation · global exception middleware |
| Security | JWT-based auth · hashed credentials · ownership guards |
| Docs | Full Swagger / OpenAPI documentation |

---

## Experience

**Junior .NET Developer** · NKU Technologies
Jan 2024 – Present · Lahore, Pakistan

Contributing to enterprise full-stack development across the complete application stack — SQL Server schema through to Angular frontend.

- Design and implement RESTful APIs in ASP.NET Core with Entity Framework Core
- Build interactive dashboards using Angular, TypeScript, and Chart.js / PrimeNG
- Author and optimise complex SQL Server queries — grouped aggregations, indexed views
- Implement dual-mode CSS theming systems using custom-property architectures
- Participate in code reviews, sprint planning, and production debugging across the full stack

**Software Engineering Intern** · Nexium
2023 · Lahore, Pakistan

- Built frontend components and integrated REST APIs in a React-based application
- Delivered sprint tickets while learning production-grade coding standards
- Participated in agile ceremonies and collaborated with senior engineers on code quality

**President, Event Management Society** · Punjab University FCIT
2025 – 2026

- Led the university's primary technical events society; 50+ student community
- Managed end-to-end planning of engineering workshops, hackathons, and industry speaker sessions
- Drove industry partnerships and coordinated guest speaker engagements

**General Secretary, Sports Society** · Punjab University FCIT
2025 – 2026

- Led the university's primary sports society; 200+ student community
- Managed end-to-end planning of mini-olympics

---

## Achievements

| Recognition | Details |
|:---|:---|
| Microsoft AI Skills Fest 2026 | Completed Microsoft's global AI skills challenge (June 2026) — Credly badge + exam voucher |
| GitHub Pull Shark ×2 | Consistently opening and merging pull requests that others review |
| GitHub Quickdraw | Closing issues and PRs within minutes of opening |
| Event Management Society President | Led 200+ student community across two academic semesters |
| Final Year Project — FitBot | AI fitness assistant with four integrated ML modules; presented to faculty panel |

---

## Coding

[LeetCode](https://leetcode.com/urwatulwusqa23)

---

## GitHub Analytics

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=urwatulwusqa23&show_icons=true&theme=transparent&hide_border=true&count_private=true&rank_icon=github)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=urwatulwusqa23&layout=compact&theme=transparent&hide_border=true&langs_count=8)
![Streak Stats](https://streak-stats.demolab.com?user=urwatulwusqa23&theme=transparent&hide_border=true)

---

## Current Focus

```yaml
learning:
  - Azure DevOps pipelines and infrastructure-as-code (Bicep / ARM)
  - Kubernetes fundamentals and container orchestration
  - GitHub Actions for multi-environment CI/CD workflows

building:
  - Azure-hosted DevOps portfolio (CI/CD, IaC, monitoring)
  - Production-ready .NET microservice reference architecture

exploring:
  - RAG patterns for enterprise .NET applications
  - LLM integration in ASP.NET Core API pipelines
  - OpenTelemetry for distributed tracing in .NET systems

open_to:
  - Remote .NET Developer roles — Canadian companies preferred
  - Junior DevOps Engineer positions (Azure-first)
  - Full-stack contract work in the .NET / React ecosystem
```

---

## Connect

[Email](mailto:urwatulwusqa23@gmail.com) · [LinkedIn](https://www.linkedin.com/in/urwatulwusqa) · [GitHub](https://github.com/urwatulwusqa23) · [Portfolio](https://urwatulwusqa23.github.io)
