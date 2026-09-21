<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=180&section=header&text=Jose%20Bayon&fontSize=54&fontColor=ffffff&fontAlignY=35&desc=Fullstack%20Developer%20%C2%B7%20React%20%C2%B7%20TypeScript%20%C2%B7%20Python&descAlignY=58&descSize=16" alt="Jose Bayon" />

<p>
  <a href="https://linkedin.com/in/josebayondev"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:josebayondev@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=josebayondev&style=for-the-badge&color=2563eb&label=PROFILE+VIEWS" alt="Profile views" />
</p>

<sub>Building SaaS/ERP products by day · shipping my own apps by night · Murcia, Spain 🇪🇸</sub>

</div>

---

## 👋 About me

```ts
const jose = {
  role: "Fullstack Developer",
  focus: ["Product engineering", "AI-assisted workflows", "Shipping fast, safely"],
  daily: { frontend: "React + TypeScript", backend: "Python / FastAPI · Flask", db: "PostgreSQL" },
  currently: "Building a booking platform + an AI chatbot with RAG",
  philosophy: "AI writes drafts. I own the architecture, the review and the git history.",
} as const;
```

Sole developer with full ownership of the stack at a Madrid-based company — from database schema to CI/CD to the UI people actually click. I like small, boring, well-tested systems and I'm allergic to infrastructure nobody needs yet.

---

## 🧰 Tech Stack

<div align="center">

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Backend & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)

**Platform**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white)

</div>

---

## 🤖 How I work with Claude

I don't "vibe code". I run Claude Code as a **teammate with a contract**: it drafts, I review, and it never touches the parts where a mistake is expensive.

<table>
<tr>
<td width="50%" valign="top">

### ⚙️ My setup

- **`CLAUDE.md` per repo** — conventions, branch rules and hard boundaries committed with the code
- **MCP servers** — ClickUp, Google Drive and Neon wired in, so the agent reads the real backlog and the real schema
- **Custom skills & subagents** — reusable playbooks (TDD, systematic debugging, code review) in `~/.claude/skills`
- **`opusplan`** — Opus to plan, Sonnet to execute
- **Custom statusline** — context and quota always visible

</td>
<td width="50%" valign="top">

### 🚧 My rules

- 🔒 **Git is mine.** No agent runs `commit`, `push`, `merge` or `reset`
- 🔒 **Migrations are mine.** Alembic files are written and reviewed by hand
- ✅ **Plan first, code second.** No diff without an agreed plan
- ✅ **Tests in CI decide**, not the model's confidence
- ✅ **Every line gets read** before it reaches a PR

</td>
</tr>
</table>

> The interesting part of AI-assisted development isn't the code it writes — it's the guardrails you design around it.

<div align="center">

![Claude](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG%20%2B%20pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

---

## 🚀 What I'm building

| Project | What it is | Stack |
| :--- | :--- | :--- |
| **[booking-app](https://github.com/josebayondev/booking-app)** | Appointment booking platform — no login for customers (opaque tokens, no IDOR), admin panel with roles | FastAPI · SQLAlchemy · Alembic · React + Vite · Neon · Render |
| **AI Chatbot (RAG)** | Embedded widget that answers business questions from a private knowledge base | Python · pgvector · Neon · OpenAI-style function calling *(phase 2)* |
| **Live Dashboard** | Real-time metrics over **SSE** — no broker, because at this scale Redis pub/sub is infrastructure theatre | FastAPI · SSE · React |
| **Live Data Map** | Public-data map: earthquakes (USGS) first, flights (OpenSky) next | React + Vite · MapLibre |

---

## 📊 Stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=josebayondev&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=josebayondev&show_icons=true&hide_border=true&theme=default&include_all_commits=true&count_private=true" alt="GitHub stats" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=josebayondev&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=josebayondev&layout=compact&hide_border=true&theme=default&langs_count=8" alt="Top languages" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=josebayondev&theme=tokyo-night&hide_border=true&area=true" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=josebayondev&theme=minimal&hide_border=true&area=true" alt="Activity graph" />
</picture>

</div>

---

## 📫 Let's talk

Open to interesting products, freelance work and teams where code review is a habit, not a ceremony.

<div align="center">

<a href="https://linkedin.com/in/josebayondev"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:josebayondev@gmail.com"><img src="https://img.shields.io/badge/Write%20me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,100:0f172a&height=120&section=footer" alt="" />

</div>
