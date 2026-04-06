# CONTROL CENTER

## Purpose
This file acts as the central command layer for the JDUK AI System.

## System Roles
- ChatGPT: strategy, planning, instructions
- Codex: execution, coding, implementation
- GitHub: source of truth
- Notion: dashboard (optional)

## Execution Rule
Codex must always:
1. Read AGENTS.md
2. Read inbox/latest_instruction.md
3. Execute tasks
4. Update docs/status.md and docs/tasks.md

## Priority Order
1. inbox/latest_instruction.md
2. docs/tasks.md
3. docs/roadmap.md

## Notes
Do not rely on chat memory. Always follow repository state.