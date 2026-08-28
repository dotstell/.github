<div align="center">

<img src="https://raw.githubusercontent.com/dotstell/.github/main/profile/banner.svg" alt="dotstell Labs" width="100%" />

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

Every domain of human work has the same structural problem: the information is there, the insight is not. Notes, people, tasks, code, vulnerabilities, decisions — they exist in separate systems, each one present and each one blind to the others. The picture you need does not live in any single tool. It lives in the connections between them.

dotstell Labs builds the connectors.

Each product we ship takes a specific domain where information sits in isolated silos — and connects it until the pattern becomes visible. The dots are different in every domain. The thesis is the same.

**What we stand for:**
- Open source is the foundation, not a marketing position — transparent, auditable, community-owned
- Self-hostability is a right, not a premium tier
- The best tools should not require a six-figure enterprise contract
- Building in public builds trust — roadmap, code, and decisions are all visible

Every product ships under AGPL-3.0. The core is always free, forever.

---

## Products

### [dotstell](https://dotstell.app) — Personal Knowledge Graph

**The dots:** Ideas, research, meeting notes, 1-on-1s, and everything worth remembering — scattered across your working memory and a dozen different apps.

**What they tell:** Capture it all, connect ideas, notes, people, tasks, and bookmarks, then ask AI that answers from your own knowledge and context.

**Capture → Connect → Ask**

Everything you write, everyone you know, everything you do — all linked in one living knowledge graph. Now with AI that understands all of it.

| | Feature | Description |
|---|---|---|
| 📑 | **Rich Text Notes** | Write in rich text with slash commands, tables, code blocks and checklists |
| ⬡ | **Wikilinks & Backlinks** | Type `[[` in any note to link it to another — backlinks update automatically |
| 📓 | **Notebooks** | Organise notes into named collections with colour-coded sidebar grouping |
| 👥 | **People & 1-on-1s** | Track contacts, attach notes, tasks and context directly to people — supports `@mention` in notes |
| 🔖 | **Smart Bookmarks** | Save any URL — title, description and favicon fetched automatically; bulk import from Chrome, Firefox or Safari |
| ✅ | **Tasks & Priorities** | Kanban board + list view with priorities, due dates and overdue alerts |
| 🌐 | **Knowledge Graph** | Visual map of everything — wikilinks and manual connections appear as live edges |
| 🔍 | **Universal Search** | Ctrl+K command palette across all notes, people, tasks and bookmarks |
| 🔗 | **Manual Linking** | Connect any entity to any other — note → person, bookmark → task, etc. |
| 🏠 | **Dashboard** | Unified home screen: overdue alerts, task progress, recent notes and bookmarks |
| ✨ | **AI — Chat, Write, Assist & Search** | RAG-grounded chat (notes, bookmarks, and tasks all in context), AI Writing Assistant, inline text assist, smart titles, auto-tagging, note summaries, AI Digest, Person Intelligence, semantic Related — works with Ollama (local/private), OpenAI, Anthropic, Gemini, or Groq |
| 🖥️ | **Desktop app** | Native Windows, macOS, and Linux via Tauri (~10 MB) |

→ **[dotstell.app](https://dotstell.app)** · [Source](https://github.com/dotstell/dotstell) · AGPL-3.0

---

### [dotstell Radar](https://github.com/dotstell/dotstell-radar) — Application Security Posture Management *(in development)*

**The dots:** security findings, repositories, CVEs, MITRE ATT&CK TTPs, compliance controls — scattered across GHAS, Dependabot, secret scanning, and a dozen other tools.

**What they tell:** your real security posture — the exposure you did not know you had because it was never in one place.

Most engineering teams have no affordable way to answer: *"What is our actual security exposure across all our code?"* Enterprise ASPM tools cost $30k–$200k per year and are opaque black boxes. Radar is free, self-hosted, and built in the open.

| | Feature |
|---|---|
| 🔗 | Source connectors — GitHub GHAS · Dependabot · secret scanning · SARIF upload |
| 📊 | Posture scoring — 0–100 per repo and org, severity-weighted, age-adjusted |
| 🧠 | Finding graph — repos → CVEs → MITRE ATT&CK TTPs → compliance controls |
| 📋 | Compliance mapping — SOC 2 · ISO 27001 · NIST CSF · CIS Controls |
| 🐳 | Self-hosted — `docker compose up`, single command, no external dependencies |

→ **[dotstell/dotstell-radar](https://github.com/dotstell/dotstell-radar)** · AGPL-3.0

---

## Repositories

| Repo | Description | Status |
|---|---|---|
| [dotstell/dotstell](https://github.com/dotstell/dotstell) | Personal knowledge graph app | ✅ Live |
| [dotstell/dotstell-radar](https://github.com/dotstell/dotstell-radar) | OSS ASPM platform | 🚧 In development |
| dotstell/dotstell.com | Marketing & ecosystem landing page | 🔒 Private |

---

## The name

**"dots"** — any isolated unit of meaning, in any domain. A piece of information that exists and has value, but cannot explain itself in isolation. Dots are everywhere: in every field of work, in every system, in every organization. Present, real, and waiting. But a dot alone cannot tell you anything.

**"tell"** — what happens when dots connect. The pattern surfaces. The story becomes visible. Not because new information was created, but because existing information was finally *related* — to context, to consequence, to other information. The insight was always latent. Connection makes it seen.

**dotstell** = the act of connecting isolated information until it reveals what could not be seen while everything was apart.

This is not a product description. It is the permanent thesis of dotstell Labs. Every product is a specific application of this thesis to a specific domain. The domains change. The thesis does not.

## The logo

The logo is not decoration. It is the thesis made visual — a complete argument in six elements.

Read it outside to inside:

**Five dots. Scattered. Isolated.** Each one a domain of information sitting alone — present, real, cut off from the others. This is the default state of almost every system ever built: information exists; connection does not.

**Then the dashed lines begin reaching inward.** The platform arrives — connections forming, not yet complete, but already in motion.

**At the center, once the connections close: a white dot appears.**

That white dot did not exist before. It could not exist before. It is the insight that only emerges when isolated things become a connected system. The thing you could not see. Now you cannot unsee it.

That white dot is what dotstell Labs builds toward — in every product, in every domain. To make visible what was always there, invisible only because it was disconnected.

**The geometry:**
- 5 perimeter nodes at 72° intervals — equal weight, no hierarchy, each a different kind of silo
- 1 center hub — the connector; equidistant from every silo, between them not above them
- Solid perimeter edges — connections already formed, opacity 0.6; present but not dominant
- Dashed spokes — connections still forming; potential, not yet permanent
- White dot at center — the emergent insight; what only exists once everything connects

The same mark appears across every dotstell product. The constellation does not change — only the name beside it does.

---

## Get started

```bash
# dotstell knowledge graph app
git clone https://github.com/dotstell/dotstell.git
cd dotstell && pnpm install
cp .env.local.example .env.local   # add Supabase keys
pnpm dev                           # http://localhost:3000
```

Or use the hosted version at **[dotstell.app](https://dotstell.app)** — free to start, no credit card required.

```bash
# dotstell Radar (ASPM)
git clone https://github.com/dotstell/dotstell-radar.git
cd dotstell-radar
cp .env.example .env               # add GitHub OAuth credentials
docker compose -f docker-compose.yml -f docker-compose.dev.yml up
# Dashboard: http://localhost:3100  API docs: http://localhost:8100/docs
```

---

## Contributing

All contributions are welcome — bug fixes, new features, UI improvements, documentation, and tests.

- **Bug reports & features** → open an issue on the relevant repo
- **Code contributions** → open an issue first for anything significant
- **Docs, design, accessibility** → always welcome without prior discussion

---

<div align="center">

**[dotstell.com](https://dotstell.com)** · **[dotstell.app](https://dotstell.app)** · **[hello@dotstell.com](mailto:hello@dotstell.com)**

<sub>© 2026 dotstell Labs · connecting dots until they tell a story · AGPL-3.0</sub>

</div>
