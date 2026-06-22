# AGENTS.md

This repository is prepared for agent-assisted development.

## Read First

1. `HARNESS.md`
2. `docs/agent-harness.md`
3. `project.md` or `README.md` if present
4. `next-actions.md` if present

## Operating Rules

- Keep the harness thin: route detailed procedures to docs, scripts, and skills.
- Before edits, check `git status --short` and preserve unrelated user changes.
- Prefer existing package scripts and local conventions over new tooling.
- Run the narrowest relevant verification before reporting success.
- Record durable follow-ups in `next-actions.md` or `docs/agent-logs/`.
- Do not commit, push, deploy, send, or write to external services without explicit approval or a repo-local rule that allows it.
