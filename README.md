# PM Methodology

A portable, markdown-based project management methodology for teams working with human developers and AI coding agents.

## What's in here

- **Standards** (`BACKLOG_STANDARD.md`, `DELIVERY_STANDARD.md`, `RELEASE_STANDARD.md`, `PORTABILITY_STANDARD.md`) — Rules for how work is captured, developed, and shipped
- **`STARTUP.md`** — Entry point for every LLM session
- **`prompts/`** — Role-specific LLM prompts (developer, QA, release planner, etc.)
- **`templates/`** — Markdown templates for backlog items, releases, agent reports
- **`.claude/commands/`** — Claude Code slash commands for common workflows

## How to deploy to a project

From within [Agentic PM Tools](https://github.com/TheEduardoConde/agentic-pm-tools), run:

```
/deploy-methodology <path-to-target-project>
```

This copies the methodology and commands into the target project and scaffolds any missing `docs/project/` structure.

## Version

See `VERSION` file for the current release. Each deployed project gets a `docs/_methodology/VERSION` file so you can track what version is installed.
