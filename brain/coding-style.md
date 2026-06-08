# Coding Style

Template. This file describes how you prefer code to be written. The defaults below are sensible starting points — keep, edit, or replace them to match your own style.

## General Principles

- Keep code simple and readable.
- Prefer small, safe, reviewable changes.
- Do not rewrite large files without a clear reason.
- Preserve the existing project structure unless a refactor is requested.
- Avoid unnecessary dependencies.
- When something is unclear, make a reasonable assumption and mention it.

## Naming

- Use clear, descriptive names over short clever ones.
- Functions describe an action.
- Variables describe the value they hold.
- Be consistent with the naming already used in a file.

## Structure

- Keep functions short and focused on one job.
- Group related logic together.
- Avoid deep nesting; return early when it helps.
- Keep files focused. Split only when a file is clearly doing too much.

## Comments

- Comment the "why", not the obvious "what".
- Keep comments short and accurate.
- Remove comments that no longer match the code.

## Languages I Use Most

- <primary language and its main framework>
- <secondary language / framework>

Match the idioms of whichever language a file is written in.

## Errors and Edge Cases

- Handle the common failure cases explicitly.
- Fail clearly with a useful message instead of failing silently.
- Do not add heavy error frameworks for small scripts.

## What to Avoid

- Over-engineering simple tasks.
- Premature abstraction.
- Large rewrites when a small edit works.
- Changing behavior that was not requested.

## When Editing

- Explain what changed and why.
- Include file paths and commands when they help.
- Keep the diff small enough to review easily.
