<div align="center">

<img src="https://raw.githubusercontent.com/dotstell/.github/main/profile/banner.svg" alt="Dotstell Labs" width="100%" />

<br/>
<br/>

[![Website](https://img.shields.io/badge/dotstell.com-7c6aff?style=flat-square&logo=google-chrome&logoColor=white)](https://dotstell.com)
[![App](https://img.shields.io/badge/dotstell.app-5b4de0?style=flat-square&logo=google-chrome&logoColor=white)](https://dotstell.app)
[![License](https://img.shields.io/badge/AGPL--3.0-10b981?style=flat-square)](https://github.com/dotstell/dotstell/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-a594ff?style=flat-square)](https://github.com/dotstell/dotstell/blob/main/CONTRIBUTING.md)
[![Contact](https://img.shields.io/badge/hello%40dotstell.com-333?style=flat-square&logo=gmail&logoColor=white)](mailto:hello@dotstell.com)

</div>

---

## About Dotstell Labs

**Your knowledge is scattered. Your security posture is invisible. Dotstell Labs connects both.**

We are an independent open source software lab — building the tools that used to require a six-figure enterprise contract and putting them in the hands of every developer, team, and company, for free.

We believe the best tools do not just store information — **they connect it**. The notes you take, the tasks you create, the people you work with, the code you ship, and the security risks you carry should not live in isolated silos.

**Our mission:** Connect the dots between how you think and how you build — safely.

**What we stand for:**
- Open source is the right foundation for developer tooling — transparent, auditable, and community-owned
- Self-hostability is a right, not a premium feature
- The best security tools should not cost more than a junior developer's salary
- Building in public builds trust

**How we work:** Every product ships under AGPL-3.0. The code is public, the roadmap is public, and the community shapes what gets built. We run a hosted SaaS tier to sustain development — the core is always free, forever.

---

## Products

### [Dotstell](https://dotstell.app) — Personal Knowledge Graph

One place for everything you know. Write notes, track people, manage tasks, save bookmarks, and watch it all connect through a living visual graph. Most tools are built around capture. Dotstell is built around **connection**.

> *"Your knowledge is not lost. It is just not connected yet."*

| | Feature |
|---|---|
| 📑 | Connected Notes — rich text with `[[wikilinks]]` and automatic backlinks |
| ⬡ | Knowledge Graph — visual map that builds itself as you write |
| 👥 | People & 1-on-1s — contacts with attached notes, tasks, and full context |
| 🔖 | Smart Bookmarks — title, description and favicon auto-fetched |
| ✅ | Tasks & Priorities — Kanban + list view, due dates, overdue alerts |
| 🔍 | Universal Search — Ctrl+K across notes, people, tasks and bookmarks |
| 🖥️ | Desktop app — native Windows + macOS via Tauri (~10 MB) |

**Stack:** `Next.js 16` · `React 19` · `TypeScript` · `Tailwind CSS v4` · `Supabase` · `Tiptap v3` · `React Flow` · `Tauri v2`

→ **[dotstell.app](https://dotstell.app)** · [Source](https://github.com/dotstell/dotstell) · AGPL-3.0

---

### Dotstell Radar — Application Security Posture Management *(in development)*

The open source alternative to Snyk, Veracode, and Wiz. Most engineering teams have no affordable way to answer: *"What is our actual security posture across all our code?"* Enterprise ASPM tools cost $30k–$200k per year and are opaque black boxes. Radar is free, self-hosted, and built in the open.

Connect your GitHub or GitLab organization and Radar aggregates findings from GHAS, Dependabot, secret scanning, SAST scanners, and SARIF uploads — then computes a **posture score** per repository so you know exactly where your exposure is.

| | Feature |
|---|---|
| 🔗 | Source connectors — GitHub GHAS · Dependabot · GitLab SAST · SARIF upload |
| 📊 | Posture scoring — 0–100 per repo and org, severity-weighted, age-adjusted |
| 🧠 | Knowledge graph — repos → findings → CVEs → MITRE ATT&CK TTPs → compliance |
| 📋 | Compliance mapping — SOC 2 · ISO 27001 · NIST CSF · CIS Controls |
| 🐳 | Self-hosted — `docker compose up`, single command, no external dependencies |

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

## The logo

The dotstell Labs mark is a **pentagon constellation** — five nodes connected on the perimeter, all feeding into a single glowing center hub.

It is not decorative. It is the idea made literal.

Knowledge, people, code, tasks, and security findings are the five points. The center hub is the connection that makes them meaningful. The dashed spokes represent the invisible threads — the relationships you have not discovered yet. The white dot at the core is the moment of clarity when a connection finally forms.

**The geometry:**
- 5 perimeter nodes at 72° intervals — equal weight, no hierarchy
- 1 center hub — the connector, the reason Dotstell exists
- Gradient perimeter edges fade at the endpoints — connections are directional but not one-sided
- Dashed spokes at 30% opacity — potential, not yet realised

The same mark appears across every Dotstell product. The constellation does not change — only the name beside it does.

---

## Get started

```bash
# Dotstell app
git clone https://github.com/dotstell/dotstell.git
cd dotstell && pnpm install
cp .env.local.example .env.local   # add Supabase keys
pnpm dev                           # http://localhost:3000
```

Or use the hosted version at **[dotstell.app](https://dotstell.app)** — free to start, no credit card required.

---

## Contributing

All contributions are welcome — bug fixes, new features, UI improvements, documentation, and tests.

- **Bug reports & features** → [open an issue](https://github.com/dotstell/dotstell/issues) on the relevant repo
- **Code contributions** → open an issue first for anything significant
- **Docs, design, accessibility** → always welcome without prior discussion

---

<div align="center">

**[dotstell.com](https://dotstell.com)** · **[dotstell.app](https://dotstell.app)** · **[hello@dotstell.com](mailto:hello@dotstell.com)**

<sub>© 2026 Dotstell Labs · A lab connecting the dots · AGPL-3.0</sub>

</div>
