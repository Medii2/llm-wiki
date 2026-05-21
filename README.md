# LLM Wiki + clo-author

A Claude Code research system combining a persistent knowledge wiki with a structured paper-writing pipeline.

**Start here: open [Research Wiki Guide.html](Research%20Wiki%20Guide.html) in your browser.** It walks you through every setup step interactively, with macOS/Windows toggle and copy buttons.

---

## What's in this repo

| Folder | Purpose |
|--------|---------|
| `LLM-Wiki/` | Empty vault scaffold — your knowledge base lives here |
| `Claude-Skills/` | Four slash commands: `/wiki-pull`, `/wiki-push`, `/wiki-ingest`, `/wiki-maintain` |
| `Claude-Agents/` | `wiki-librarian` agent used by the wiki skills |
| `clo-author-template/` | Full research pipeline template (Discovery → Writing → Review) |
| `VAULT_PATH.example` | Template for the local vault path config file |

## Quick setup

1. Clone: `git clone https://github.com/svwangenheim/llm-wiki ~/LLM-Wiki`
2. Open `Research Wiki Guide.html` and follow the path that fits your needs:
   - **Wiki only** — persistent knowledge base across all your projects
   - **clo-author only** — structured pipeline for a single paper
   - **Full system** — both, integrated

## How the wiki works

The wiki is a folder of plain markdown files in a fixed directory structure (`00_inbox/` through `90_synthesis/`). Claude reads and writes it via four skills. You point Claude at the folder by creating `~/.claude/VAULT_PATH` with the path — see the guide for details.

## clo-author

A worker/critic agent pipeline for research papers. Copy `clo-author-template/` into your project folder, fill in three lines at the top of `CLAUDE.md`, and start with `/wiki-pull [your topic]`. See `clo-author-template/README.md` for the full workflow.
