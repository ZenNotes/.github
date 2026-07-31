<div align="center">
  <img src="zennotes.png" alt="ZenNotes" width="140">
  <h1>ZenNotes</h1>
  <p><strong>Keyboard-first local Markdown notes with Vim motions, diagrams, databases, workflows, and first-party MCP integration.</strong></p>
  <p>Plain files. Fast editing. One shared core across desktop, self-hosted web, and a planned hosted mode.</p>
  <p>
    <a href="https://zennotes.org">zennotes.org</a>
    ·
    <a href="https://github.com/ZenNotes/zennotes/releases/latest">Download Latest Release</a>
    ·
    <a href="https://github.com/ZenNotes/zennotes">Main Repository</a>
    ·
    <a href="https://discord.gg/W4fWzapKS6">Join Discord</a>
    ·
    <a href="https://github.com/ZenNotes/zennotes/issues">Report an Issue</a>
  </p>
</div>

---

<div align="center">
  ZenNotes keeps your notes as ordinary local Markdown files and layers on real Vim motions, live-preview editing,
  math and diagram rendering, databases, drawings, tasks, workflows, search, backlinks, and a bundled MCP server
  for Claude Code, Claude Desktop, and Codex.
</div>

## What Ships Today

- Plain-file vaults: notes are normal `.md` files on disk, no hidden database, and an Obsidian-shaped vault works as-is, since the system folders (Inbox, Quick Notes, Archive, Trash) can map to any directories you already have
- Keyboard-first editing with first-class Vim mode, leader flows, a command palette, and pane/tab motion; every feature ships with a key
- Live-preview editor (CodeMirror 6): GFM tables as an editable grid, callouts as cards, wiki links, transclusion with `![[Note]]`, footnotes, and heading folding, with the cursor line always showing its raw source
- Rendering both ways: KaTeX or Typst for math (Typst definitions can follow a note's tags), Mermaid, TikZ, JSXGraph, and function-plot for diagrams, plus bring-your-own code languages via TextMate grammars
- Databases: any `.csv` opens as a Notion-style table or board with typed columns, AND/OR filtering, and rows that open as real notes
- Excalidraw drawings as first-class items, embeddable inline in notes
- Tasks everywhere: inline checkboxes, whole-note task files, Kanban with custom statuses, bullet-journal forwarding, and daily, weekly, and monthly notes
- Workflows: repeatable pipelines over the vault written as plain `.md` and drawn on a canvas; the engine only plans, every change is counted before you approve, and Undo restores byte for byte (opt-in)
- Vault-wide search (built-in, `ripgrep`, or `fzf`), backlinks for wiki and plain Markdown links, tags, quick capture, and URL embeds with bookmark cards
- Make it yours: Obsidian-style CSS themes and snippets, no-code quick tweaks, fonts, and rebindable keymaps that travel in `config.toml`
- Real exits: Word export built from Word's own Heading styles, copy-for-email HTML, and PDFs that state their title
- The `zn` CLI for scripting and capture, against a local vault or your self-hosted server
- First-party MCP server with desktop install flows for Claude Code, Claude Desktop, and Codex; every note result is a clickable `zennotes://` link
- Self-hosted Docker deployment with secure-by-default auth, a server-backed vault picker, and LAN/home-server access

## Runtimes

ZenNotes ships from one monorepo with one shared app core:

- **Desktop**: Electron shell with native menus, app updater, floating note windows, signed macOS builds, and Windows / Linux installers
- **Self-hosted**: Vite web client plus a Go server, deployable via Docker on your own machine or home server
- **Hosted**: planned, built on the same web/server stack

## Get ZenNotes

- [Latest desktop release downloads](https://github.com/ZenNotes/zennotes/releases/latest) (macOS, Windows, Linux x64 + arm64)
- Package managers: `brew install --cask zennotes/tap/zennotes`, `yay -S zennotes-bin` (AUR), Nix flake in-repo, `docker pull adibhanna/zennotes`
- [Source code](https://github.com/ZenNotes/zennotes)
- [Docs](https://zennotes.org/docs) · [Releases and demos](https://zennotes.org/releases)
- [Community Discord](https://discord.gg/W4fWzapKS6)
