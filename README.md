<div align="center">

# Hi, I'm Zainah 👋

<a href="https://github.com/e0-qr">
<img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=22&duration=3000&pause=1200&color=2E6A57&center=true&vCenter=true&width=520&lines=Computer+Science+Student;AI+Developer;Data+Analysis+%26+Web+Development;Building+Arabic-first+products" alt="Typing SVG" />
</a>

<p>
<a href="https://www.linkedin.com/in/zainh1"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:zynhalamry5@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

</div>

---

Final-year Computer Science student working in **AI application development, data analysis, and web development**.
I combine academic study with hands-on practice through hackathons, technical competitions, and complete end-to-end projects, alongside field experience from a professional co-op placement.

🏆 **1st place out of 70+ teams** — Zero to MVP Hackathon, Google Developer Groups · Qassim University
📊 **23 professional certifications** — Google Cloud, Kaggle × Google, IBM SkillsBuild, Cisco, MCIT
🤝 **471 verified volunteer hours** — National Center for Non-Profit Sector

---

## 🛠️ Tech Stack

<details open>
<summary><b>Languages</b></summary>
<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)

</details>

<details open>
<summary><b>AI &amp; Data</b></summary>
<br>

![Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)

`Multi-Agent Systems` · `Prompt Engineering` · `RAG` · `LLM Integration` · `Data Cleaning`

</details>

<details open>
<summary><b>Frameworks &amp; Tools</b></summary>
<br>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

</details>

---

## 🚀 Projects

### 🏆 Hack The Hack — 1st Place

**AI-powered hackathon & competition management platform** · Team of 5 · 2026

Won **first place out of 70+ teams** at the Zero to MVP Hackathon, organised by Google Developer Groups at Qassim University.
A single platform that replaces the scattered mix of spreadsheets, forms and chat groups used to run hackathons — covering registration, teams, challenges, judging and results.

My role: co-built the platform, shaped the product concept, and prepared the submission.

> Source code is private — the repository belongs to the full team.

---

### 🧠 VentureForge AI

**Multi-agent venture advisory platform** · Kaggle × Google Capstone · 2026

A virtual board of **10 specialised AI agents** that evaluates a startup idea and returns a structured recommendation: **GO / GO WITH CONDITIONS / NO-GO**.

<details>
<summary><b>What it does</b></summary>
<br>

- **10 agents** — research, market, competitor, finance, branding, marketing, risk, red team, investor, CEO
- **Simulated 3-round board meeting** — agents propose, challenge each other, then vote
- **Red team analysis** — attacks the idea's weaknesses rather than validating it
- **Investor readiness scoring** across five dimensions
- **Bilingual output** (Arabic / English) with cached translations

</details>

<details>
<summary><b>Engineering notes</b></summary>
<br>

- Dynamic Gemini model resolution — queries the `ListModels` endpoint, filters for `generateContent`, and ranks by priority with in-memory caching
- Retry with exponential backoff on `429` / `503`, then automatic model fallback
- Full offline fallback layer so a failed API call never returns a blank screen
- Async throughout with `httpx.AsyncClient`; typed request/response models via Pydantic

</details>

`Python` `FastAPI` `Pydantic` `httpx` `SQLite` `Gemini API` `Multi-Agent AI`

---

### 🗺️ خُطاك — Khutak

**AI travel planner for Saudi Arabia** · AI Champions Challenge, Tuwaiq Academy × Google for Developers · Team of 4 · 2026

Generates personalised, realistic itineraries that adapt to the traveller — interests, budget, energy level and mood — while respecting prayer times, weather, opening hours and real distances. One tap rebuilds the whole schedule when plans change.

My role: co-built the platform, shaped the product concept, and prepared the submission.

`React + Vite` `Node.js` `TypeScript` `Gemini API` `Google Maps & Places` `Weather / Prayer APIs`

> Source code is private — the repository belongs to the full team.

---

### 📖 رسوخ — Rusookh

**Quran memorisation retention web app** · 2026

Students finish memorising, then lose it — because there is no review system that fits around their day. Rusookh schedules spaced reviews that tighten on weak pages and widen on strong ones, and surfaces commonly confused similar verses before they cause mistakes.

Submitted to the Eastern Province Quran Memorization Society competition. Designed, built and deployed end to end.

`HTML` `CSS` `JavaScript` `Netlify`

---

### 🥐 Aura Bakery

**Full-stack bakery e-commerce store** · Two-person university project · 2025

Storefront, session-based cart, checkout, and an admin panel for managing products — built over five related tables with foreign keys.

**Security:** prepared statements (PDO) against SQL injection, and server-side price recalculation so totals can't be tampered with from the browser.

`PHP` `SQLite` `PDO` `JavaScript` `HTML` `CSS`

<details>
<summary><b>Credits</b></summary>
<br>

The front-end layout is adapted from a free open-source web template (original source no longer identifiable). All back-end functionality — database schema, session cart, checkout flow, order handling and the product admin panel — was written by the project team.

</details>

---

### 📊 Power BI Analytics Dashboards

**Four interactive dashboards** · 2025 — from data preparation and cleaning through to metric design

| Dashboard | Focus |
|---|---|
| High-school student performance | Factors driving academic outcomes |
| Social media & wellbeing | Effect on mental health and academic performance |
| Sales & performance | Revenue, profit and category breakdown by city |
| Event attendance | Registration vs. attendance across cities and days |

`Power BI` `Data Cleaning` `KPI Design`

---

### ⚙️ Zainah LifeOS AI

**Personal AI productivity system** · Personal project

Goals, learning, planning and progress tracking in one dashboard, with AI-driven recommendations and daily insights.

`Next.js` `TypeScript` `Tailwind CSS` `Supabase` `AI`

> Personal project — not publicly released.

---

## 💼 Experience

**Co-op Trainee** — Namirah General Hospital, Makkah Healthcare Cluster · Jan–Jun 2026
Managed scheduling and referrals for 50+ patients in the CareWare hospital information system, and built a weekly Excel/Power BI report tracking department KPIs.

**Head of Public Relations & Media Committee** — Tuwaiq Club, Al-Baha University · Jun 2026 – Present
Lead a 30+ member committee: assign design work, review and approve output, and coordinate with other committees.

---

## 📈 GitHub

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=e0-qr&show_icons=true&hide_border=true&title_color=2E6A57&icon_color=2E6A57&text_color=333&bg_color=ffffff" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=e0-qr&layout=compact&hide_border=true&title_color=2E6A57&text_color=333&bg_color=ffffff" />

</div>
<div align="center">

### Building ideas into technology.

<a href="https://www.linkedin.com/in/zainh1"><img src="https://img.shields.io/badge/Let's_connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>

</div>
