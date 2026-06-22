---
type: harness
status: active
updated: "2026-06-23"
---

# profile-readme Harness

## Purpose

Make this repository legible, executable, verifiable, and easy for future agent runs to resume.

## Routing

| Work type | Read first | Output |
| --- | --- | --- |
| Code change | `AGENTS.md`, `docs/agent-harness.md`, package scripts | code diff + verification result |
| Test or build failure | package scripts, failing file, logs | fix or failure report |
| Follow-up planning | `next-actions.md`, `docs/agent-logs/` | updated task or log |

## Verification

Current detected scripts:

- (none detected)

If no script is listed, inspect the repo and add the smallest reliable verification path before shipping changes.

## Logging

- Durable run logs: `docs/agent-logs/`
- Backlog/follow-ups: `next-actions.md` if present
- Decisions: `decision-log.md` if present

## Safety

- Preserve unrelated dirty files.
- Do not commit, push, open PRs, deploy, or call external write APIs unless explicitly requested.
- Generated test artifacts such as `test-results/` should stay uncommitted.
