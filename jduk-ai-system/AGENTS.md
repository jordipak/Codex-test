# AGENTS.md

## Mission
Build and maintain the JDUK AI System as a modular, scalable automation pipeline.

## Non-Negotiable Rules
- Follow BOT-first principle
- Do not invent schemas without updating docs/decisions.md
- Always read docs/architecture.md before modifying core pipelines
- Keep modules independent and composable
- Avoid mixing responsibilities across modules

## Workflow Rules
- After any meaningful change:
  - update docs/status.md
  - update docs/tasks.md
  - update CHANGELOG.md
- Prefer deterministic scripts over AI unless necessary

## Code Style
- Keep functions small and composable
- Separate IO from logic
- Use clear naming

## Safety
- Never delete large sections without explanation
- Do not overwrite data files blindly

## Goal
Ensure Codex and future agents operate consistently without drift.