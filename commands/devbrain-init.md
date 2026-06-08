# devbrain-init

> **Manual prompt workflow (v0.1).** This is not an executable slash command. Copy the prompt under "How to Run" into Claude Code.

Set up DevBrain in a project for the first time.

## Purpose

Create the `brain/` folder and fill the core context files so Claude Code understands the developer and the project from the start.

## When to Use

- Starting DevBrain in a new project.
- A project has `CLAUDE.md` but no `brain/` files yet.

## What It Does

1. Create the `brain/` folder if it does not exist.
2. Create the core files:
   - `brain/about-me.md`
   - `brain/projects.md`
   - `brain/ai-instructions.md`
   - `brain/coding-style.md`
   - `brain/current-focus.md`
   - `brain/decisions.md`
3. Ask the developer short questions to fill each file:
   - **about-me:** name, role, languages, tools, strengths, preferences.
   - **projects:** what they are building, the problem, tech stack, status.
   - **ai-instructions:** how the AI should respond and what to avoid.
   - **coding-style:** naming, structure, and what to avoid in code.
   - **current-focus:** what they are working on right now.
   - **decisions:** decisions already made, with short reasons.
4. Confirm `CLAUDE.md` points Claude Code at the `brain/` files.

## How to Run (Manual, v0.1)

There is no automation in v0.1. To run this, tell Claude Code:

> Initialize DevBrain. Create any missing files in `brain/`, then interview me one section at a time and fill them in.

## Rules

- Keep each file short and practical.
- Do not invent details. Ask when something is unknown.
- Do not overwrite files that already have content unless asked.
- Stop when the core files are filled. Do not add extra structure.
