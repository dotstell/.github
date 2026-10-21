<div align="center">

<img src="https://raw.githubusercontent.com/dotstell/.github/main/profile/banner.svg" alt="dotstell Labs" width="100%" />

<br/>
<br/>

[![Website](https://img.shields.io/badge/dotstell.com-7c6aff?style=flat-square&logo=google-chrome&logoColor=white)](https://dotstell.com)
[![App](https://img.shields.io/badge/dotstell.app-5b4de0?style=flat-square&logo=google-chrome&logoColor=white)](https://dotstell.app)
[![Release](https://img.shields.io/github/v/release/dotstell/dotstell?style=flat-square&color=10b981&label=release)](https://github.com/dotstell/dotstell/releases/latest)
[![MCP Registry](https://img.shields.io/badge/MCP%20Registry-com.dotstell%2Fdotstell-5b4de0?style=flat-square)](https://registry.modelcontextprotocol.io)
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

Everything you write, everyone you know, everything you do — all linked in one living knowledge graph. Now with AI that understands all of it, meetings you can talk into, and a way to let your own AI tools read it.

**Capture**

| | Feature | Description |
|---|---|---|
| 📑 | **Rich Text Notes** | Slash commands, tables, code blocks, checklists, images, table of contents and PDF export; sub-notes, tabs and colour labels |
| 📓 | **Notebooks** | Named, colour-coded collections; deleted notes stay in the Trash for 30 days |
| 🎙️ | **Meetings** | Paste or upload a Zoom, Teams or Meet transcript (or record the meeting) and get a summary, decisions, action items and open questions; action items become linked tasks |
| 🗣️ | **Voice dictation** | Speak into any note in 12 languages — *Fast* in your browser with spoken punctuation and automatic capitals, or *High accuracy* with Whisper-class models and your own key; works on a phone |
| 🔖 | **Smart Bookmarks** | Title, description and favicon fetched automatically; bulk import from Chrome, Firefox or Safari |
| ✅ | **Tasks & Priorities** | Kanban board and list view with priorities, due dates and times, reminders and overdue alerts |
| 👥 | **People & 1-on-1s** | Contacts with notes, tasks and context attached; `@mention` them in notes |

**Connect**

| | Feature | Description |
|---|---|---|
| ⬡ | **Wikilinks & Backlinks** | Type `[[` to link notes; backlinks and unlinked mentions update automatically |
| 🌐 | **Knowledge Graph** | A live map of everything, with AI-found missing links and clusters |
| 🔍 | **Universal Search** | Ctrl+K across notes, people, tasks and bookmarks, plus search by meaning |
| 🏠 | **Dashboard** | Overdue alerts, task progress, recent items, knowledge health and an AI digest |

**Ask**

| | Feature | Description |
|---|---|---|
| ✨ | **AI Chat, Write & Assist** | Chat grounded in your notes, bookmarks and tasks; drafting and rewriting; smart titles, tags and summaries; Person Intelligence. Works with **Ollama (local and private, including Qwen 3.5 and Gemma 4)**, OpenAI, Anthropic, Gemini or Groq |
| 🔌 | **MCP server** | Let Codex, Claude Code, Cursor and Claude Desktop search and read your knowledge with a revocable, read-only token. Listed in the [official MCP Registry](https://registry.modelcontextprotocol.io) as `com.dotstell/dotstell` (search “dotstell”) |

**Yours to keep**

| | Feature | Description |
|---|---|---|
| 📤 | **Export & Import** | One-click zip of Markdown, CSV and a full backup; bring in Obsidian, Notion, Evernote, Google Keep and contacts, with preview and undo |
| 🖥️ | **Everywhere** | Web, a ~10 MB desktop app for Windows, macOS and Linux, and phones and tablets; 12 themes |
| 🏠 | **Self-hostable** | Your own Supabase project and any Node.js host — [step-by-step guide](https://github.com/dotstell/dotstell/blob/main/docs/DEPLOYMENT.md) |

**What's new** — [v0.9.2](https://github.com/dotstell/dotstell/releases/tag/v0.9.2) local AI that works with reasoning models · [v0.9.1](https://github.com/dotstell/dotstell/releases/tag/v0.9.1) high-accuracy dictation, spoken punctuation, phone-friendly dictation · [v0.9.0](https://github.com/dotstell/dotstell/releases/tag/v0.9.0) MCP server · [v0.8.0](https://github.com/dotstell/dotstell/releases/tag/v0.8.0) meetings · [v0.7.0](https://github.com/dotstell/dotstell/releases/tag/v0.7.0) import & export. Full history in the [changelog](https://github.com/dotstell/dotstell/blob/main/CHANGELOG.md).

→ **[dotstell.app](https://dotstell.app)** · [Website](https://dotstell.com) · [Source](https://github.com/dotstell/dotstell) · AGPL-3.0

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
cd dotstell && pnpm install               # Node.js 20.9+
cp .env.local.example .env.local   # add your Supabase URL and anon key
                                   # run supabase/schema.sql in your Supabase project first
pnpm dev                           # http://localhost:3000
```

Or use the hosted version at **[dotstell.app](https://dotstell.app)** — free to start, no credit card required. Hosting it yourself? Follow the [self-hosting guide](https://github.com/dotstell/dotstell/blob/main/docs/DEPLOYMENT.md).

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
