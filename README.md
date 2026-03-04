<div align="center">

<img src="profile-banner.png" width="100%"/>

</div>

<br/>

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
<summary>Architecture</summary>
<br/>

```mermaid
graph TD
    A[".kgn / .kge files"] --> B["Parser"]
    B --> C["PostgreSQL + pgvector"]
    C --> D["Graph Query"]
    D --> E["Subgraph Extraction"]
    D --> F["Similarity Search"]
    C --> G["CLI"]
    C --> H["MCP Server<br/>(Claude)"]
    C --> I["LSP Server<br/>(VS Code)"]
    G --> J["GitHub Sync"]
    H --> J
    I --> J
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

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>

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
