# DevBrain Claude Skill

DevBrain gives AI coding agents structured developer context using simple Markdown files, so sessions don't start from zero.

DevBrain v0.1 is **manual Markdown only** — no CLI, no MCP, no database, no automation. You edit plain files by hand and Claude Code reads them.

---

## What It Provides

A `brain/` folder of context files, plus a `CLAUDE.md` that tells Claude Code to read them first.

```text
brain/
├── about-me.md         # who you are
├── projects.md         # what you are building
├── ai-instructions.md  # how the AI should respond
├── coding-style.md     # how you want code written
├── current-focus.md    # what you are working on now
└── decisions.md        # decisions already made
```

---

## How to Use It

1. Copy `CLAUDE.md` and `brain/` into your project root.
2. Fill the `brain/` files with your own context (they ship as templates with placeholders).
3. Work in Claude Code — it reads `CLAUDE.md`, which points at the brain files.

---

## Manual Commands

The `commands/` folder holds **manual prompt workflows** for init, update, and review.

These are copy/paste prompts, not executable slash commands. See each file for the full prompt text.

---

See [README.md](README.md) for full setup, usage examples, and roadmap.
