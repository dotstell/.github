<div align="center">

<img src="https://raw.githubusercontent.com/dotstell/dotstell/main/public/logo-full.svg" alt="Dotstell" width="280" />

<br/>
<br/>

# Dotstell Labs

**Open source tools for connected thinking and application security.**

*We build the tools that used to require a six-figure enterprise contract.*

<br/>

[![Website](https://img.shields.io/badge/dotstell.com-7c6aff?style=flat-square&logo=google-chrome&logoColor=white)](https://dotstell.com)
[![App](https://img.shields.io/badge/dotstell.app-5b4de0?style=flat-square&logo=google-chrome&logoColor=white)](https://dotstell.app)
[![License](https://img.shields.io/badge/AGPL--3.0-10b981?style=flat-square)](https://github.com/dotstell/dotstell/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-a594ff?style=flat-square)](https://github.com/dotstell/dotstell/blob/main/CONTRIBUTING.md)
[![Contact](https://img.shields.io/badge/hello%40dotstell.com-333?style=flat-square&logo=gmail&logoColor=white)](mailto:hello@dotstell.com)

</div>

---

## About Dotstell Labs

Dotstell Labs is an independent open source software lab founded in Japan, focused on building tools that put enterprise-grade capabilities in the hands of every developer and team — for free.

**The problem we solve:** The best tools for knowledge management, application security, and developer productivity are locked behind expensive SaaS pricing or opaque enterprise contracts. Small teams and individual developers are left with fragmented, underpowered alternatives — not because better tools cannot exist, but because no one has built them openly.

**What we believe:**
- Open source is the right foundation for developer tooling — transparent, auditable, and community-owned
- Self-hostability is a right, not a premium feature
- The best security tools should not cost more than a junior developer salary
- Building in public builds trust

**How we work:** Every product ships as open source under AGPL-3.0. The code is public, the roadmap is public, and the community helps shape what gets built. We run a hosted SaaS tier to sustain development — but the core is always free, forever.

---

## Products

### [Dotstell](https://dotstell.app) — Personal Knowledge Graph

A single place to write notes, track people, manage tasks, save bookmarks, and connect everything through a visual graph. Most tools are built around capture. Dotstell is built around **connection**.

> *"Your knowledge is not lost. It just is not connected yet."*

| Feature | |
|---|---|
| 📑 Connected Notes | Rich text editor with `[[wikilinks]]` and automatic backlinks |
| ⬡ Knowledge Graph | Visual map that builds itself as you write |
| 👥 People & 1-on-1s | Track contacts with notes, tasks, and full context |
| 🔖 Smart Bookmarks | Save URLs — title, description and favicon auto-fetched |
| ✅ Tasks & Priorities | Kanban + list view with due dates and overdue alerts |
| 🔍 Universal Search | Ctrl+K across all notes, people, tasks and bookmarks |
| 🖥️ Desktop app | Native Windows + macOS via Tauri (~10 MB) |

**Stack:** `Next.js 16` · `React 19` · `TypeScript` · `Tailwind CSS v4` · `Supabase` · `Tiptap v3` · `React Flow` · `Tauri v2`

→ **[dotstell.app](https://dotstell.app)** · [Source](https://github.com/dotstell/dotstell) · AGPL-3.0

---

### Dotstell Radar — Application Security Posture Management *(coming soon)*

The open source alternative to Snyk, Veracode, and Wiz. Radar connects to your GitHub and GitLab organizations, aggregates findings from GHAS, Dependabot, secret scanning, SAST scanners, and SARIF uploads — then computes a posture score per repository and organization so you know exactly where your exposure is.

Enterprise ASPM tools cost $30k–$200k per year. Radar is free, self-hosted, and AGPL-3.0.

| Feature | |
|---|---|
| 🔗 Source connectors | GitHub (GHAS, Dependabot, secrets) · GitLab · SARIF upload |
| 📊 Posture scoring | 0–100 score per repo and org, severity-weighted, age-adjusted |
| 🧠 Knowledge graph | Repos → findings → CVEs → MITRE ATT&CK TTPs → compliance |
| 📋 Compliance mapping | SOC 2 · ISO 27001 · NIST CSF · CIS Controls |
| 🐳 Self-hosted | `docker compose up` — single command, no external dependencies |

**Stack:** `FastAPI` · `Python 3.11` · `Next.js 15` · `PostgreSQL` · `Redis` · `Docker Compose`

→ **radar.dotstell.app** *(coming soon)* · AGPL-3.0

---

## Repositories

| Repo | Description | Status |
|---|---|---|
| [dotstell/dotstell](https://github.com/dotstell/dotstell) | Personal knowledge graph app | ✅ Live |
| dotstell/dotstell-radar | OSS ASPM platform | 🔒 In development |
| dotstell/dotstell.com | Marketing & landing page | 🔒 Private |

---

## Get started

**Dotstell app:**
```bash
git clone https://github.com/dotstell/dotstell.git
cd dotstell && pnpm install
cp .env.local.example .env.local   # add Supabase keys
pnpm dev                           # http://localhost:3000
```

Or use the hosted version at **[dotstell.app](https://dotstell.app)** — free to start, no credit card required.

---

## Contributing

Contributions are welcome across all products — bug fixes, new features, UI improvements, documentation, and tests.

- **Bug reports & feature requests** → [open an issue](https://github.com/dotstell/dotstell/issues) on the relevant repo
- **Code contributions** → open an issue first for anything significant
- **Docs, design, accessibility** → always welcome without prior discussion

---

<div align="center">

**[dotstell.com](https://dotstell.com)** · **[dotstell.app](https://dotstell.app)** · **[hello@dotstell.com](mailto:hello@dotstell.com)**

<sub>© 2026 Dotstell Labs · Built in public · All products AGPL-3.0</sub>

</div>