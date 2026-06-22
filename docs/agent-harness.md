---
title: "Agent Harness"
date: "2026-06-23"
tags: [agent, harness]
status: active
type: note
---

# Agent Harness

## Current Capability

Audit status: `missing-map, missing-dev-local, missing-verification, missing-log-layer`

Package manager: `unknown`

## Scripts

- (none detected)

## Required Gates

- For code changes, run the narrowest relevant script from the list above.
- For UI or workflow changes, add or run an e2e/manual verification path and record evidence in the final report.
- If no runnable verification exists, record the gap in `next-actions.md` before claiming completion.

## Shared Knowledge Layer

- What is true now belongs in repo docs.
- What happened in a run belongs in `docs/agent-logs/`.
- Follow-up work belongs in `next-actions.md` or the parent project tracker.

## Timeline

- 2026-06-23 | harness applied - portable Codex codebase harness initialized.
