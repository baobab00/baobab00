<div align="center">

<img src="profile-banner.png" width="100%"/>

</div>

<br/>

<div align="center">
  <img src="hireme.gif" width="100" alt="Hire Me"/>
  <br/>
  <b>Actively seeking opportunities to grow and contribute!</b>
</div>

<br/>

## 🐣 About Me

Born in the spring of 2000, right as the millennium began.
Maybe that's why I'm always thinking about *what comes next.*

I'm currently preparing for my career. And strangely enough, this might be the most exciting time of my life. Ideas that used to float around vaguely in my head are finally taking shape, one by one, with a little help from AI.

Complex syntax, unfamiliar architectures, difficult engineering concepts... I'm learning firsthand that these are all just tools for bringing ideas into the world.

There are a lot of similar things out there. Slightly different angles on something you've seen before. That's not necessarily a bad thing, but sometimes it feels like a ceiling. So every now and then, I ask myself:

> *"Could people 100 years ago have even imagined a smartphone?"*

Computers, the internet, AI... all of these were once *absurd ideas.* We're here today because someone held on to those ideas and refused to let go. I want to be that kind of person.

New ideas, collaboration, or just an interesting conversation — I'm always open. 😄

<br/>

---

## 🧐 What I Build By

### `Backend Architecture`

I'm drawn to designing the structural foundation of a service. Not just code that works — but code where roles and responsibilities are clearly separated. When I define boundaries between domains and ensure consistency in API design, I'm always asking: *"How does this technical decision affect scalability and stability?"*

### `AI-driven Services`

Through consistent use of AI services like ChatGPT and Gemini, I've developed a deep interest in what real value AI can deliver to users. I also look at the other side — hallucination, privacy risks, cost structures, and other business-level constraints. I want to build services that maximize user-perceived value while honestly reflecting the limitations of the technology in their design.

### `Product Thinking`

I have a habit of asking *"Why is this feature needed?"* before anything else. Rather than jumping straight into code when given requirements, I try to understand the user context and business purpose behind them. Technology is the means, not the end — I believe a product only becomes good when it delivers tangible value to its users.

<br/>

---

## 📌 Featured Project

### [KGN — Knowledge Graph Node](https://github.com/baobab00/kgn)

A CLI + MCP server that gives AI agents **persistent, queryable memory** — backed by PostgreSQL and pgvector.

[![CI](https://github.com/baobab00/kgn/actions/workflows/ci.yml/badge.svg)](https://github.com/baobab00/kgn/actions/workflows/ci.yml)
[![PyPI](https://img.shields.io/pypi/v/kgn-mcp)](https://pypi.org/project/kgn-mcp/)
[![codecov](https://codecov.io/gh/baobab00/kgn/graph/badge.svg)](https://codecov.io/gh/baobab00/kgn)
[![VS Code](https://img.shields.io/badge/VS%20Code-Extension-007ACC?logo=visualstudiocode)](https://marketplace.visualstudio.com/items?itemName=baobab00.vscode-kgn)

- Custom `.kgn`/`.kge` file format parser for structured knowledge nodes and edges
- PostgreSQL + pgvector storage with semantic similarity search
- MCP server that plugs directly into Claude and other AI agents
- LSP server + VS Code extension for IDE-level editing support
- Multi-agent task orchestration with conflict detection and lease management
- GitHub sync for version-controlled knowledge export

`Python` `PostgreSQL` `pgvector` `FastMCP` `LSP` `Typer` `Pydantic` `GitHub Actions`

<details>
<summary>Architecture — 16 Mermaid diagrams inside  →  <a href="https://github.com/baobab00/kgn/blob/master/ARCHITECTURE.md">Deep Dive</a></summary>
<br/>

```mermaid
graph LR
    A[".kgn / .kge"] --> B["Parser"]
    B --> C["IngestService"]
    C --> D[("PostgreSQL + pgvector")]
    D --> E["CLI · MCP · LSP · Web"]
    E --> F["Git / GitHub Sync"]
```

</details>

<br/>

---

## ✨ Live Services

| Service | Description |
|---|---|
| **[MeNode](https://menode.app)** | Structures records with @node and #date tags, explores context through relationship visualization |
| **[YT Insights](https://ytinsights.dev)** | Analyzes YouTube Most Replayed heatmaps to quantify viewer behavior patterns |
| **[Pokuzzle](https://www.pokuzzle.com)** | A strategy puzzle web game — form poker hands from adjacent tiles on an 8x8 grid |

<br/>

---

## 👽 Open Source

| Project | Description |
|---|---|
| [lecture-summarizer](https://github.com/baobab00/lecture-summarizer) | Lecture summarization tool |
| [chatgpt-blur-extension](https://github.com/baobab00/chatgpt-blur-extension) | Browser extension for blurring ChatGPT conversations · [Chrome Web Store](https://chromewebstore.google.com/detail/chatgpt-blur/ghageddlnooippamdabmohhaaccimkfo) |
| [yt-heatmap](https://github.com/baobab00/yt-heatmap) | YouTube heatmap visualization tool |

<br/>

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Database**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**Infra & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

<br/>

---

## 🐾 Stats

<div align="center">

<a href="https://github.com/baobab00">
  <img src="https://github-readme-stats-eta-eosin-34.vercel.app/api?username=baobab00&show_icons=true&theme=default&hide_border=true&count_private=true&include_all_commits=true&hide_rank=true" height="160" alt="GitHub Stats"/>
</a>
&nbsp;
<a href="https://github.com/baobab00">
  <img src="https://github-readme-stats-eta-eosin-34.vercel.app/api/top-langs/?username=baobab00&layout=compact&hide_border=true&count_private=true" height="160" alt="Top Langs"/>
</a>

</div>

<br/>

---

<div align="center">

[![Blog](https://img.shields.io/badge/Blog-baobab00.github.io-333?style=flat-square&logo=github)](https://baobab00.github.io)
[![Email](https://img.shields.io/badge/Email-phn00dev@gmail.com-333?style=flat-square&logo=gmail&logoColor=white)](mailto:phn00dev@gmail.com)

</div>
