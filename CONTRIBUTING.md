# Contributing

## AI-assisted development

This repository is designed for coordinated AI-assisted development.

Before starting:
1. Read CLAUDE.md.
2. Read docs/WORKFLOW.md.
3. Read docs/AGENT_CONTRACT.md.
4. Inspect the existing application.

## Branches

Use focused branch names such as:

- feature/<short-name>
- fix/<short-name>
- refactor/<short-name>
- chore/<short-name>

## Pull requests

A PR should explain:
- What changed.
- Why it changed.
- How it was validated.
- Any risks or follow-up work.

## Secrets

Never commit:
- API keys
- GitHub tokens
- passwords
- private keys
- production .env files
- credentials

Use environment variables and local secret-management mechanisms instead.
