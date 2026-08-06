<div align="center">

<img src="https://raw.githubusercontent.com/dotstell/dotstell/main/public/logo-full.svg" alt="Dotstell" width="320" />

<br/>

### Every dot tells a story.
**Open source tools for thinking, connecting and remembering.**

<br/>

[![Website](https://img.shields.io/badge/dotstell.com-7c6aff?style=flat-square&logo=google-chrome&logoColor=white)](https://dotstell.com)
[![App](https://img.shields.io/badge/dotstell.app-5b4de0?style=flat-square&logo=google-chrome&logoColor=white)](https://dotstell.app)
[![License](https://img.shields.io/badge/AGPL--3.0-10b981?style=flat-square)](https://github.com/dotstell/dotstell/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-a594ff?style=flat-square)](https://github.com/dotstell/dotstell/blob/main/CONTRIBUTING.md)

</div>

---

## What is Dotstell?

Dotstell is an open source personal knowledge graph — a single place to write notes, track people, manage tasks, save bookmarks, and connect everything together through a visual graph.

Most productivity tools are built around **capture**. Dotstell is built around **connection**.

> *"Your knowledge is not lost. It's just not connected yet."*

---

## Repositories

| Repo | Description | License |
|---|---|---|
| [dotstell/dotstell](https://github.com/dotstell/dotstell) | The main app — Next.js, Supabase, Tiptap, React Flow | AGPL-3.0 |
| [dotstell/dotstell.com](https://github.com/dotstell/dotstell.com) | Marketing & landing page — static Next.js | MIT |

---

## The app

| Feature | |
|---|---|
| 📑 Connected Notes | Rich text editor with `[[wikilinks]]` and automatic backlinks |
| ⬡ Knowledge Graph | Visual map that builds itself as you write |
| 👥 People & 1-on-1s | Track contacts with attached notes, tasks and context |
| 🔖 Smart Bookmarks | Save URLs — title, description and favicon fetched automatically |
| ✅ Tasks & Priorities | Kanban + list view with due dates and overdue alerts |
| 🔍 Universal Search | Ctrl+K across all notes, people, tasks and bookmarks |
| 🖥️ Desktop app | Native Windows + macOS app via Tauri (~10 MB installer) |

---

## Tech stack

`Next.js 16` · `React 19` · `TypeScript 5` · `Tailwind CSS v4` · `Supabase` · `Tiptap v3` · `React Flow v11` · `Tauri v2`

---

## Get started

```bash
git clone https://github.com/dotstell/dotstell.git
cd dotstell
pnpm install
cp .env.local.example .env.local   # add your Supabase keys
pnpm dev
```

Or use the hosted app at **[dotstell.app](https://dotstell.app)** — free to start, no credit card required.

---

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](https://github.com/dotstell/dotstell/blob/main/CONTRIBUTING.md) for guidelines.

- **Bug reports & feature requests** → [open an issue](https://github.com/dotstell/dotstell/issues)
- **Code contributions** → open an issue first for anything significant
- **Docs, design, tests** → always welcome without prior discussion

---

<div align="center">

**[dotstell.com](https://dotstell.com)** · **[dotstell.app](https://dotstell.app)** · **[GitHub](https://github.com/dotstell/dotstell)**

<sub>© 2026 Dotstell · AGPL-3.0</sub>

</div>
