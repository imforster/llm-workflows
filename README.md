# llm-workflows

A collection of prompts, workflows, and agent configurations for AI-assisted development.

## Contents

### useful-prompts.md

Reusable prompt templates:
- Tutor prompt (personalized learning with quizzes)
- Generic agent prompt structure template

### kiro/

- **Kiro-coding-pr-workflow.md** — Best practices for Kiro's spec-driven development workflow, from feature planning through PR creation. (Kiro IDE-specific; for CLI, use Kiro skills directly.)

### ai-dev-tasks/ (submodule)

[snarktank/ai-dev-tasks](https://github.com/snarktank/ai-dev-tasks) — Structured markdown prompts for AI-powered feature development:
1. `create-prd.md` — Generate a Product Requirement Document
2. `generate-tasks.md` — Break a PRD into granular task lists
3. `process-task-list.md` — Execute tasks one at a time with review checkpoints

> **Note:** This is a generic, tool-agnostic workflow. If you use Kiro CLI, the `to-prd`, `to-issues`, and `triage` skills provide an integrated alternative with tool access and context awareness.

### map-notes.md

Notes on MCP (Model Context Protocol) tool integrations — Context7, Sequential, Magic, Playwright.

### archive/

Superseded configurations kept for reference:
- **amazon-q/cli-agents/** — Amazon Q Developer CLI agents, now replaced by Kiro CLI agent roles.
