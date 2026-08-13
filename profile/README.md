<div align="center">

<img src="https://raw.githubusercontent.com/dotstell/dotstell/main/public/logo-full.svg" alt="Dotstell" width="320" />

<br/>

### Every dot tells a story.

**Dotstell Labs builds open source tools that give individuals and teams clarity — over their knowledge, their code, and their security.**

<br/>

[![Website](https://img.shields.io/badge/dotstell.com-7c6aff?style=flat-square&logo=google-chrome&logoColor=white)](https://dotstell.com)
[![App](https://img.shields.io/badge/dotstell.app-5b4de0?style=flat-square&logo=google-chrome&logoColor=white)](https://dotstell.app)
[![License](https://img.shields.io/badge/AGPL--3.0-10b981?style=flat-square)](https://github.com/dotstell/dotstell/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-a594ff?style=flat-square)](https://github.com/dotstell/dotstell/blob/main/CONTRIBUTING.md)
[![Contact](https://img.shields.io/badge/hello%40dotstell.com-333?style=flat-square&logo=gmail&logoColor=white)](mailto:hello@dotstell.com)

</div>

---

## About Dotstell Labs

Dotstell Labs is an independent open source lab building tools that used to be locked behind enterprise pricing.

**Mission:** Make powerful tools accessible to every developer, team, and company — not just those who can afford six-figure licenses.

**Vision:** A world where individuals have the same clarity over their thinking and security posture that Fortune 500 teams do today.

**How we work:** Everything we build is open source first. The code is public, the roadmap is public, and the community shapes what gets built. We build in public, ship early, and iterate with users.

---

## Products

### [Dotstell](https://dotstell.app) — Personal Knowledge Graph

A single place to write notes, track people, manage tasks, save bookmarks, and connect everything through a visual graph. Most tools are built around capture. Dotstell is built around **connection**.

> *"Your knowledge is not lost. It just is not connected yet."*

| Feature | |
|---|---|
| 📑 Connected Notes | Rich text editor with `[[wikilinks]]` and automatic backlinks |
| ⬡ Knowledge Graph | Visual map that builds itself as you write |
| 👥 People & 1-on-1s | Track contacts with notes, tasks, and context |
| 🔖 Smart Bookmarks | Save URLs — title, description and favicon auto-fetched |
| ✅ Tasks & Priorities | Kanban + list view with due dates and overdue alerts |
| 🔍 Universal Search | Ctrl+K across all notes, people, tasks and bookmarks |
| 🖥️ Desktop app | Native Windows + macOS via Tauri (~10 MB) |

**Stack:** `Next.js 16` · `React 19` · `TypeScript` · `Tailwind CSS v4` · `Supabase` · `Tiptap v3` · `React Flow` · `Tauri v2`

→ **[dotstell.app](https://dotstell.app)** · [Source](https://github.com/dotstell/dotstell) · AGPL-3.0

---

### [Dotstell Radar](https://github.com/dotstell/dotstell-radar) — Application Security Posture Management

The OSS alternative to Snyk, Veracode, and Wiz. Radar connects to your GitHub and GitLab organizations, aggregates findings from GHAS, Dependabot, secret scanning, SAST scanners, and SARIF uploads — then computes a **posture score** per repository and organization.

Enterprise ASPM tools cost $30k–$200k per year and are opaque black boxes. Radar is free, self-hosted, and open source.

| Feature | |
|---|---|
| 🔗 Source connectors | GitHub (GHAS, Dependabot, secret scanning) · GitLab · SARIF upload |
| 📊 Posture scoring | 0–100 score per repo and org, severity-weighted, age-adjusted |
| 🧠 Knowledge graph | Repos → findings → CVEs → ATT&CK TTPs → compliance controls |
| 📋 Compliance mapping | SOC 2 · ISO 27001 · NIST CSF · CIS Controls |
| 🐳 Self-hosted | Single `docker compose up` — no external dependencies |

**Stack:** `FastAPI` · `Python 3.11` · `Next.js 15` · `PostgreSQL` · `Redis` · `Docker Compose`

→ **[radar.dotstell.app](https://radar.dotstell.app)** *(coming soon)* · [Source](https://github.com/dotstell/dotstell-radar) · AGPL-3.0

---

## Repositories

| Repo | Description | Status |
|---|---|---|
| [dotstell/dotstell](https://github.com/dotstell/dotstell) | Personal knowledge graph app | ✅ Live |
| [dotstell/dotstell-radar](https://github.com/dotstell/dotstell-radar) | OSS ASPM platform | 🚧 Building |
| [dotstell/dotstell.com](https://github.com/dotstell/dotstell.com) | Marketing & landing page | ✅ Live |

---

## Get started

**Dotstell app:**
```bash
git clone https://github.com/dotstell/dotstell.git
cd dotstell && pnpm install
cp .env.local.example .env.local   # add Supabase keys
pnpm dev                           # http://localhost:3000
```

**Dotstell Radar:**
```bash
git clone https://github.com/dotstell/dotstell-radar.git
cd dotstell-radar && cp .env.example .env
docker compose up                  # http://localhost:3100
```

---

## Contributing

All contributions are welcome across both products — bug fixes, new scanner sources, UI improvements, compliance mappings, and documentation.

- **Bug reports & features** → [open an issue](https://github.com/dotstell/dotstell/issues) on the relevant repo
- **Code contributions** → open an issue first for significant changes
- **Docs, design, tests** → always welcome without prior discussion

---

<div align="center">

**[dotstell.com](https://dotstell.com)** · **[dotstell.app](https://dotstell.app)** · **[hello@dotstell.com](mailto:hello@dotstell.com)**

<sub>© 2026 Dotstell Labs · All projects AGPL-3.0</sub>

</div>
