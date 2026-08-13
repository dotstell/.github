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

## About dotstell Labs

**A lab connecting the dots for curious minds and ambitious builders.**

Every domain of work has the same problem: the information is there. The insight is not. Notes, people, tasks, code, vulnerabilities, decisions — they exist in separate silos, each one present and each one blind to the others. The picture you need does not live in any single tool. It lives in the connections between them.

dotstell Labs builds the connectors.

Each product we ship takes a specific set of scattered dots — knowledge, security posture, whatever comes next — and connects them until they tell a story. The product names change. The mission stays the same: make visible what was always there, invisible only because it was disconnected.

**What we stand for:**
- Open source is the foundation, not a marketing position — transparent, auditable, community-owned
- Self-hostability is a right, not a premium feature
- The best tools should not require a six-figure enterprise contract
- Building in public builds trust — roadmap, code, and decisions are all visible

**How we work:** Every product ships under AGPL-3.0. The core is always free, forever. A hosted SaaS tier sustains the work.

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
| [dotstell/dotstell-radar](https://github.com/dotstell/dotstell-radar) | OSS ASPM platform | 🚧 In development |
| dotstell/dotstell.com | Marketing & landing page | 🔒 Private |

---

## The name

**"dots"** — individual points of information. A note. A finding. A person. A repository. A task. Left alone, they are just dots — present but meaningless without context.

**"tell"** — to reveal, to narrate, to give meaning. When you connect the dots, they tell you something. The pattern that emerges is the story you could not see before.

**dotstell = connecting dots until they tell a story.**

## The logo

The logo is not decoration. It is a complete argument in six nodes.

Read it outside to inside:

**Five dots. Scattered. Isolated.** Each one a silo — a note, a person, a codebase, a finding, a task. Valuable on its own. But not talking to anything else.

Then a platform reaches out — dashed lines forming, connections not yet complete but already moving.

And at the center, once the connections close: **a white dot appears.**

That white dot did not exist before. It could not exist before. It is the insight that only emerges when silos become a system. The thing you could not see. Now you cannot unsee it.

That white dot is what dotstell Labs builds toward. Every product — the knowledge graph, the security posture platform, whatever comes next — exists to produce that white dot. To make visible what was always there, invisible only because it was disconnected.

**The geometry:**
- 5 perimeter nodes at 72° intervals — equal weight, no hierarchy
- 1 center hub — the connector, the reason dotstell exists
- Gradient perimeter edges — connections are directional but not one-sided
- Dashed spokes at 30% opacity — potential, not yet realised

The same mark appears across every dotstell product. The constellation does not change — only the name beside it does.

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
