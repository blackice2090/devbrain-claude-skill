# devbrain-review

> **Manual prompt workflow (v0.1).** This is not an executable slash command. Copy the prompt under "How to Run" into Claude Code.

Check that the brain files are accurate, consistent, and still useful.

## Purpose

Read the whole `brain/` folder and report problems: outdated info, contradictions, gaps, or files that have grown too long.

## When to Use

- Before sharing or publishing the project.
- After a busy period of changes.
- When Claude Code's answers feel out of sync with the project.

## What It Does

1. Read every file in `brain/`.
2. Check for:
   - **Outdated content** — focus, status, or decisions no longer true.
   - **Contradictions** — files that disagree with each other.
   - **Gaps** — missing context the AI clearly needs.
   - **Bloat** — files that have grown long and should be trimmed.
3. Report findings as a short list, grouped by file.
4. Suggest specific edits, but do not apply them automatically.

## How to Run (Manual, v0.1)

Tell Claude Code:

> Review DevBrain. Read all `brain/` files and list anything outdated, contradictory, missing, or too long, grouped by file.

## Rules

- Review only. Do not change files unless asked.
- Be specific. Point to the file and the exact issue.
- Prefer trimming over adding. Keep the brain small and accurate.
- If everything looks good, say so plainly.
