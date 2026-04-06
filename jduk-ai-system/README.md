# JDUK AI System

JDUK AI System is the working repository for the Japan-to-UK resale automation system.

## Purpose
This repo is the implementation home for the JDUK product pipeline:
- search and collect products
- normalize product data
- apply rule filters
- run AI selection when needed
- calculate pricing
- generate content
- support publishing and future order operations

## Core Principle
- BOT-first where possible
- deterministic pipelines before AI
- GitHub is the source of truth for implementation state
- Notion is the dashboard and management layer
- ChatGPT handles strategy and architecture
- Codex handles implementation and file changes

## Standard Project Files
- `AGENTS.md` — operating rules for Codex and future contributors
- `docs/status.md` — current project state
- `docs/roadmap.md` — direction and milestones
- `docs/tasks.md` — active and backlog tasks
- `docs/decisions.md` — architecture and decision log
- `docs/architecture.md` — system structure
- `src/` — application and module code
- `tests/` — test suite
- `scripts/` — helper scripts
- `data/` — local input/output samples

## Current Goal
Build the MVP foundation for a modular resale automation system that can expand into a broader AI business operating system.

## Initial Modules
- search_runner
- normalize
- rule_filter
- pricing
- content_generator
- publish
- dashboard
- order_ops

## Working Rule
Any meaningful implementation update should also update:
1. `docs/status.md`
2. `docs/tasks.md`
3. `CHANGELOG.md`

## Notes
This scaffold was generated to serve as the final baseline repo structure for JDUK.