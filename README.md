<p align="center">
  <img src="banner.gif" alt="Banner" width="100%">
</p>

<div align="center">

[![Full-Stack Developer](https://img.shields.io/badge/Full--Stack_Developer-6e40c9?style=for-the-badge&labelColor=0d1117)]()
[![Search Engines & IR](https://img.shields.io/badge/Search_Engines_%26_IR-1f6feb?style=for-the-badge&labelColor=0d1117)]()
[![AI Agents & RAG](https://img.shields.io/badge/AI_Agents_%26_RAG-238636?style=for-the-badge&labelColor=0d1117)]()
[![CCC 42 — 6th place](https://img.shields.io/badge/CCC_42-6th_place_·_solo-FFD500?style=for-the-badge&labelColor=0d1117)](https://github.com/EduhxH/ccc-42-nanofabricator)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eduardo-carvalho-dev)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:eduardo.carvalho.pt.dev@gmail.com)
[![Followers](https://img.shields.io/github/followers/EduhxH?label=Follow&style=for-the-badge&color=6e40c9&logo=github&logoColor=white)](https://github.com/EduhxH)
[![Lisboa, Portugal](https://img.shields.io/badge/Lisboa,_Portugal-30363d?style=for-the-badge)]()

*Student developer in Portugal. I build systems end to end — from the crawler and the index to the page students actually open — and I measure every decision before I keep it.*

</div>

---

> [!IMPORTANT]
> **October 2026:** 6th place, competing solo, at my first hackathon — the [42nd Classic Cloudflight Coding Contest](https://github.com/EduhxH/ccc-42-nanofabricator). Meanwhile, [Verum Search](https://github.com/EduhxH/Verum-Search) v1.0 has been in closed beta with real students since 15 September 2026.

---

## 🧩 About

I started with desktop apps in C# and full-stack CRUDs, moved into AI agents, MCP servers and RAG pipelines, and then built a search engine from scratch, from the crawler to the ranking. Most of what I build is for people I can actually talk to: my class, my school's teachers, my friends.

- 🔭 Running the closed beta of **Verum Search**, a search engine for my school
- 🤖 Building **HNCHBOT**, a chatbot that answers from a school's regulations and cites the article it came from
- 🏆 Just finished my first hackathon: **6th place, solo**, at CCC 42
- 💬 Portuguese and English

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔎 [Verum Search](https://github.com/EduhxH/Verum-Search)

[![Status](https://img.shields.io/badge/Status-v1.0%20Beta-2ea043?style=for-the-badge)](https://github.com/EduhxH/Verum-Search)
[![Tests](https://img.shields.io/badge/Tests-727%20passing-2ea043?style=for-the-badge)](https://github.com/EduhxH/Verum-Search)
[![MRR](https://img.shields.io/badge/MRR-0.849-1f6feb?style=for-the-badge)](https://github.com/EduhxH/Verum-Search)

A vertical search engine built from scratch for one school. No Google, no Bing, no search APIs: every result is computed on one machine.

- 🕷️ Web crawler (robots.txt, rate limits, sitemaps) plus an authenticated **Moodle connector**
- 📚 Inverted index and **TF-IDF** ranking in **SQLite**: 1,822 documents, single-digit milliseconds per query
- 📏 Every ranking change is measured against real student queries: the right document comes first for 37 of 47
- 🛠️ Admin panel, per-student invite codes, 101 security probes, self-hosted behind a **Cloudflare Tunnel**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

</td>
<td width="50%" valign="top">

### 🏆 [CCC 42 — Nanofabricator](https://github.com/EduhxH/ccc-42-nanofabricator)

[![Result](https://img.shields.io/badge/Result-6th%20place%20·%20solo-FFD500?style=for-the-badge)](https://github.com/EduhxH/ccc-42-nanofabricator)
[![First hackathon](https://img.shields.io/badge/First-hackathon-6e40c9?style=for-the-badge)](https://github.com/EduhxH/ccc-42-nanofabricator)
[![Final score](https://img.shields.io/badge/Final%20score-15,826-2ea043?style=for-the-badge)](https://github.com/EduhxH/ccc-42-nanofabricator)

My solution to the 42nd Classic Cloudflight Coding Contest (23 October 2026, 4 hours, GLS Portugal venue), competing solo against teams of up to three. Level 6 is pure optimization: write the shortest programs that make a laser fabricator build 540 patterns.

- ✂️ Line stamping, a **NumPy-vectorized beam search** scoring all 4,096 moves per cycle, and reuse of copies
- 📉 From a 72,936-line baseline to **17,436 lines** with this repo's code alone (−76%), 0 failed patterns
- 🤝 Final leaderboard score of **15,826**, built together with friends during the contest

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

</td>
</tr>
</table>

---

## 🤖 AI, Agents & RAG

| Project | What it does | Stack | Status |
|---|---|---|---|
| **[HNCHBOT](https://github.com/EduhxH/HNCHBOT)** | Chatbot over the official documents of a school group, built at a teacher's request. BM25 retrieval over 274 articles; every answer cites the article, number and page, and every quote is checked against the source PDF. | Python · Streamlit · Groq · PyMuPDF | 🚧 56/62 on its test set, before fixes |
| **[AYANAMI-AGENT](https://github.com/EduhxH/AYANAMI-AGENT)** | Modular agent system: a GitHub agent for repo analysis, an email agent over Gmail OAuth, and a FastAPI backend orchestrating Groq calls behind a Next.js interface. | Python · FastAPI · Next.js · Groq · MongoDB | 🟢 [Live](https://ayanami-agent.vercel.app) |
| **[MCP-SERVER-PRO](https://github.com/EduhxH/MCP-SERVER-PRO)** | MCP server that plugs any agent into Pinecone, Gmail, Google Cloud, Excel and the IDE, with async tools via FastMCP. | Python · FastMCP · Pinecone | 🚧 In development |
| **[IA-agent-with-tools](https://github.com/EduhxH/IA-agent-with-tools---)** | Fully local ReAct agent: reasons, picks a tool, runs it and loops until it has an answer. File upload, IDE project reader and MCP integration. | Python · Ollama · FastAPI · React 19 | 🟢 [Live](https://ia-agent-with-tools.vercel.app) |
| **[AGENTE-IA](https://github.com/EduhxH/AGENTE-IA)** | 100% offline RAG agent: semantic chunking, MD5 deduplication, and a relevance threshold that stops hallucination before generation. | Python · LangChain · ChromaDB · Ollama | 📦 [v1.0.0](https://github.com/EduhxH/AGENTE-IA/releases/tag/v1.0.0) |

---

## 🌐 Full-Stack & Web

| Project | What it does | Stack | Status |
|---|---|---|---|
| **[Reisolari](https://github.com/EduhxH/reisolari)** | Peer-to-peer solar energy marketplace and photovoltaic simulator for Portugal: draw a roof on a satellite map, get a report from real PVGIS data, buy or sell through Stripe Connect. | Next.js · FastAPI · MongoDB · Redis · Stripe · Mapbox | 🟢 [Live](https://reisolari.vercel.app) · 🚧 |
| **[EUROEXPLORER](https://github.com/EduhxH/EUROEXPLORER)** | Interactive atlas of the 27 EU member states on Mapbox: explore, collect stamps, and generate a digital passport. | JavaScript · FastAPI · Mapbox | 🟢 [Live](https://euroexplorer.vercel.app) · ⭐ Graded 20/20 |
| **[fullstack-crud](https://github.com/EduhxH/fullstack-crud)** | User management system with JWT auth, Zod validation, Prisma over MongoDB Atlas, and pagination. | React · Express · MongoDB | 🟢 [Live](https://fullstack-crud-pearl.vercel.app) |

---

## 📱 Mobile & Desktop

| Project | What it does | Stack | Status |
|---|---|---|---|
| **[AYANAMI-LEARN](https://github.com/EduhxH/ayanami-learn)** | English learning platform: a native Android app backed by a Kotlin/Ktor API, with Firebase auth and real-time WebSockets. Group project for English class. | Kotlin · Ktor · Jetpack Compose · Firebase · MongoDB | 📦 [v1.0.0](https://github.com/EduhxH/ayanami-learn/releases/tag/1.0.0) |
| **[Rei Launcher](https://github.com/EduhxH/rei-launcher)** | Minimalist Minecraft launcher inspired by Rei Ayanami: Microsoft OAuth and offline login, automatic Java detection, auto-updates. | Electron · Node.js | 🚧 In development |
| **[Zenit](https://github.com/EduhxH/Zenit)** | Desktop project manager with a Kanban board, a to-do list and a dashboard fed by external APIs. Built for PSI class. | C# · WinForms · MS Access | 🚧 In development |
| **[Dryloud](https://github.com/EduhxH/Dryloud)** | Windows music player with user accounts, playlists and file search. | C# · .NET 8 · WinForms | 🚧 In development |

---

## 🛠️ Tech Stack

**💻 Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=dotnet&logoColor=white)

**⚙️ Backend & Data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Ktor](https://img.shields.io/badge/Ktor-087CFA?style=for-the-badge&logo=ktor&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

**🎨 Frontend & Apps**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**🤖 AI & Retrieval**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-7C3AED?style=for-the-badge)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-6e40c9?style=for-the-badge)

**🧪 Tools & Infra**

![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🧠 How I Work

- **Measure before keeping.** In Verum, every ranking change is run against real student queries first. Semantic search and always-on synonyms were both measured and rejected, because they made results worse.
- **Build the core myself.** Verum's crawler, tokenizer, inverted index and ranking are written from scratch in Python, with no search framework and no search API.
- **Verify the output.** Verum's index is tested against a naive-search oracle, HNCHBOT checks every quote it produces, and in CCC 42 nothing went to the leaderboard without passing the contest's own engine.
- **Write down the limits.** My READMEs have a *Known Limitations* section, because a project is easier to trust when it says where it breaks.

---

## 📈 GitHub Stats

<p align="center">
  <img height="155" src="https://github-readme-stats.vercel.app/api?username=EduhxH&show_icons=true&theme=github_dark&count_private=true&hide_border=true&bg_color=0d1117" />
  <img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=EduhxH&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&hide=html,css" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=EduhxH&theme=github-dark-blue&hide_border=true&background=0d1117" />
</p>

---

<div align="center">

[![PT & EN](https://img.shields.io/badge/PT_%26_EN-30363d?style=for-the-badge)]()
[![Open to opportunities](https://img.shields.io/badge/Open_to_opportunities-238636?style=for-the-badge)]()

Made with 💜 by <a href="https://github.com/EduhxH">EduhxH</a>

</div>
