# AI-Powered Workers

A structured AI development team for building software with Claude Code and specialist agents.

## Team model

                    LEAD / ORCHESTRATOR
                           |
          +----------------+----------------+
          |                |                |
        UI/UX           FRONTEND         BACKEND
          |                |                |
          +----------------+----------------+
                           |
                         QA
                           |
                    REVIEW + INTEGRATE
                           |
                         GIT

## Repository structure

- `CLAUDE.md` — project-wide Claude Code rules
- `.claude/agents/` — specialist subagent definitions
- `docs/ARCHITECTURE.md` — system architecture
- `docs/TASKS.md` — current work queue
- `docs/DECISIONS.md` — important technical decisions
- `.github/` — collaboration and pull-request standards

## How the team should work

The lead agent owns planning, delegation, integration, and final validation. Specialist agents work within bounded responsibilities and return concrete implementation notes, changed files, validation results, and blockers.

Do not assume the application's technology stack until the repository has been inspected.

## Status

Initial AI-team foundation.
