<div align="center">

## 📊 GitHub Stats

![Shabdprakash's GitHub Stats](https://github-readme-stats.vercel.app/api?username=Shabdprakash-Thakkar&show_icons=true&hide_border=true&count_private=true&title_color=5865F2&icon_color=5865F2&text_color=555555&bg_color=00000000)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Shabdprakash-Thakkar&layout=compact&hide_border=true&title_color=5865F2&text_color=555555&bg_color=00000000)

![GitHub Streak](https://streak-stats.demolab.com?user=Shabdprakash-Thakkar&hide_border=true&ring=5865F2&fire=5865F2&currStreakLabel=5865F2)

</div>

---

# Hey, I'm Shabdprakash 👋

Developer focused on building things that actually work at scale — not prototypes, not demos. I build the whole thing locally until it's solid, then ship it.

Currently polishing **SupporterBot** into a production-ready, scalable Discord bot with a full Flask web dashboard. Also deep in development on a **JLPT N5 AI platform** (local, not pushed yet) that combines an AI generation engine with a rule-based system and curated N5 dataset to generate mock tests and quizzes.

- 🤖 **SupporterBot** → Production-grade Discord bot — 235 files, modular architecture, live at [supporterbot.online](http://www.supporterbot.online)
- 🇯🇵 **N5 AI Platform** → AI mock test + quiz generator for JLPT N5 — in local development, not on GitHub yet
- 📡 **Currently learning** → OpenTelemetry for observability & distributed tracing
- 🧠 **Exploring** → Local LLMs, RAG pipelines, and AST-based tooling
- 🎯 I don't chase commits — I build the full working thing, then push

---

## 🛠 Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Frameworks & Runtimes**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

**Libraries**

![discord.py](https://img.shields.io/badge/discord.py-5865F2?style=flat-square&logo=discord&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![asyncio](https://img.shields.io/badge/asyncio-3776AB?style=flat-square&logo=python&logoColor=white)
![aiohttp](https://img.shields.io/badge/aiohttp-2C5BB4?style=flat-square&logo=python&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-3776AB?style=flat-square&logo=python&logoColor=white)
![python-dotenv](https://img.shields.io/badge/python--dotenv-ECD53F?style=flat-square&logo=python&logoColor=black)

**Tools & Concepts**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![CLI](https://img.shields.io/badge/CLI-4D4D4D?style=flat-square&logo=gnubash&logoColor=white)
![AST](https://img.shields.io/badge/AST-3776AB?style=flat-square&logo=python&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-0077B6?style=flat-square)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)

**Environment**

![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Local LLM](https://img.shields.io/badge/Local_LLM-4D4D4D?style=flat-square)
![Antigravity](https://img.shields.io/badge/Antigravity-111111?style=flat-square)

---

## 🚀 Projects

### 🤖 [SupporterBot](https://github.com/Shabdprakash-Thakkar/Supporter_BOT) — *Production / Active*

> Full-stack Discord bot with a Flask web dashboard. Built to be modular, observable, and actually scalable — not a weekend script.

**What it does:**
- 📈 Leveling system with XP, leaderboards, and configurable rewards
- 📺 YouTube channel notifications with per-server configuration
- ⏰ Automated time-channel updates
- 🎟 Ticket system with transcript logging
- 🔒 Media & link control — slash command driven, admin-configurable
- 🖥 Full Flask dashboard: dev and consolidated production builds

**Architecture:**
```
Python_Files/   → 14 bot modules (leveling, analytics, YouTube, tickets...)
Flask_Frontend/ → Multi-page web dashboard (HTML/CSS/JS)
Flask_Frontend_Consolidated/ → Production build (merged pipeline)
Consolidate/    → Custom CSS/HTML/JS consolidation scripts
Runner_Files/   → Separate localhost & production entry points
```

`Python` `discord.py` `Flask` `HTML` `CSS` `JavaScript` `SQL` `asyncio`

🌐 [supporterbot.online](http://www.supporterbot.online) · 💬 [Discord Server](https://discord.gg/xEMEK9XV2V)

---

### 🇯🇵 JLPT N5 AI Platform — *In Development (local)*

> AI-powered mock test and quiz generator for Japanese Language Proficiency Test N5. Not on GitHub yet — building the full working version locally first, then it ships.

**What it will do:**
- 🤖 AI-generated mock tests and quizzes from a curated N5 dataset
- 📐 Rule-based system layered on top of generation for accuracy and JLPT spec compliance
- 🌐 Full web platform — not just a script, a proper learner-facing product

**Stack:** `Next.js` `React` `Python` `PostgreSQL` `RAG` `Local LLM`

---

### 💬 [ChatApp — RAG AI](https://github.com/Shabdprakash-Thakkar/chatapp)

> AI chat application using Retrieval-Augmented Generation. Context-aware conversations backed by document retrieval.

`Python` `RAG` `AI`

---

## 📫 Connect

<div align="center">

[![Website](https://img.shields.io/badge/Website-supporterbot.online-5865F2?style=for-the-badge)](http://www.supporterbot.online)
[![Discord](https://img.shields.io/badge/Discord_Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/xEMEK9XV2V)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/Shabdprakash-Thakkar)

</div>

---

<div align="center">
  <sub>Build the whole thing. Then commit. 🎯</sub>
</div>
