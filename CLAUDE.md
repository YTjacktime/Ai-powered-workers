# AI-Powered Workers — Claude Code Rules

This repository is the source of truth for the AI-powered development team.

## Core rules
- Inspect the repository before changing code.
- Detect the actual stack before making architectural assumptions.
- Preserve working functionality; prefer targeted changes over rewrites.
- Never invent APIs, environment variables, files, or services.
- Never commit secrets, tokens, private keys, or real production environment files.
- Keep work modular and testable.
- Validate changes before declaring them complete.
- Do not overwrite another agent's active work.

## Git workflow
- Use descriptive feature branches for non-trivial work.
- Keep commits focused.
- Do not force-push unless explicitly authorized.
- The lead agent owns integration and final review.

## Agent workflow
The lead agent plans, delegates, reviews, integrates, validates, and reports. Specialist agents have bounded responsibilities and must return changed files, validation results, and blockers.

## Definition of done
- Relevant tests pass, or missing tests are documented.
- Build/typecheck/lint pass when available.
- No new runtime errors are introduced.
- User flows affected by the change are checked.
- Security-sensitive changes receive explicit review.

## Project knowledge
- Architecture: docs/ARCHITECTURE.md
- Work queue: docs/TASKS.md
- Decisions: docs/DECISIONS.md
- Specialist agents: .claude/agents/
