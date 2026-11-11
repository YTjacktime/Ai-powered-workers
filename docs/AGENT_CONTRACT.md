# Agent Contract

All agents follow this contract.

## Before work

1. Read CLAUDE.md.
2. Read the relevant architecture/task documentation.
3. Inspect the current implementation.
4. Identify existing patterns and dependencies.
5. State the scope before making changes.

## During work

- Make the smallest coherent change.
- Reuse existing abstractions.
- Keep security boundaries explicit.
- Do not invent missing requirements.
- Do not add dependencies without justification.
- Do not touch unrelated files.
- Keep changes easy to review.

## After work

Return:
- Summary
- Files changed
- Validation
- Risks
- Follow-up

## Escalate when

Ask the Lead for a decision when:
- Requirements conflict.
- A breaking API/schema change is required.
- A new external service is required.
- Security implications are unclear.
- The existing architecture cannot safely support the requested feature.
