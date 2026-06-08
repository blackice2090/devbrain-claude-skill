# DevBrain Roadmap

This roadmap describes where DevBrain is going. v0.1 is intentionally small. Later versions are listed only so the direction is clear, not because they are being built yet.

## v0.1 (Current)

Goal: make DevBrain usable manually inside Claude Code, with no extra tooling.

- [x] Define the `brain/` folder structure
- [x] Write `about-me.md`, `projects.md`, `ai-instructions.md`
- [ ] Fill `coding-style.md`, `current-focus.md`, `decisions.md`
- [ ] Write the three command guides in `commands/`
- [ ] Keep `CLAUDE.md` pointing Claude Code at the brain files
- [ ] Test the full setup inside a real Claude Code session
- [ ] Publish to GitHub with a clear README

What v0.1 is **not**:

- No CLI
- No MCP server
- No database
- No memory or RAG engine
- No automation

Everything in v0.1 is plain Markdown that a developer edits by hand.

## v0.2 (Planned)

- Example brain files for different developer types
- A short setup guide with screenshots
- Optional prompt files for guided interviews and updates

## v0.3 (Ideas)

- A small Node.js CLI to scaffold the `brain/` folder
- A helper to summarize and compress long brain files

## Later (Not Committed)

- MCP integration
- A memory/RAG layer for large project histories
- Sync across machines

## Principle

Add complexity only when the manual version is clearly not enough. Every new feature must keep DevBrain simple to read and easy to maintain.
