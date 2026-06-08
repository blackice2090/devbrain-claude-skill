# devbrain-update

> **Manual prompt workflow (v0.1).** This is not an executable slash command. Copy the prompt under "How to Run" into Claude Code.

Keep the brain files current as the project changes.

## Purpose

Update the `brain/` files so Claude Code always works from accurate context. This is the command used most often.

## When to Use

- The current focus has changed.
- A new decision was made.
- A project's status, stack, or next steps changed.
- Coding-style preferences changed.

## What It Does

1. Ask what changed since the last update.
2. Update only the files that need it. Common targets:
   - `brain/current-focus.md` — new priorities and in-progress work.
   - `brain/decisions.md` — add new decisions with a short reason.
   - `brain/projects.md` — status, challenges, next steps.
   - `brain/coding-style.md` — changed preferences.
3. Keep edits small. Remove anything that is now outdated.
4. Summarize what changed, file by file.

## How to Run (Manual, v0.1)

Tell Claude Code:

> Update DevBrain. Ask me what changed, then edit only the relevant `brain/` files and show me a per-file summary.

## Rules

- Make small, targeted edits. Do not rewrite whole files.
- When a decision is reversed, fix or remove the old entry so it does not contradict the new one.
- Keep files concise. Trim stale content.
- Do not add new files or structure in v0.1.
