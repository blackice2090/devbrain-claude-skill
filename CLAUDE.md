# DevBrain Claude Code Instructions

This project uses DevBrain, a structured developer context system for AI coding agents.

Before answering, editing, generating code, or suggesting changes, read and respect the files inside the `brain/` folder.

## Core Context Files

- `brain/about-me.md`
- `brain/projects.md`
- `brain/ai-instructions.md`
- `brain/coding-style.md`
- `brain/current-focus.md`
- `brain/decisions.md`

## Main Rules

1. Use the brain files as the primary developer context.
2. Preserve the existing project structure unless the user asks for refactoring.
3. Prefer small, safe, reviewable changes.
4. Do not rewrite large files without a clear reason.
5. Explain what changed and why.
6. When context is missing, make a reasonable assumption and mention it.
7. Avoid generic AI writing.
8. Keep responses practical and implementation-focused.
9. When helping with code, include file paths and commands when useful.
10. When updating the brain, keep the files concise and easy to maintain.

## DevBrain Purpose

DevBrain does not try to clone a person’s entire mind.

It gives Claude Code structured context about:

- who the developer is
- what projects they are building
- how they prefer to code
- how they prefer AI to respond
- what decisions have already been made
- what the current focus is

The goal is better continuity, better technical decisions, and less repeated explanation.