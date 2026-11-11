# AI Development Team Workflow

## Team

The Lead coordinates:

- UI/UX — user flows, interaction design, accessibility, responsive behavior
- Frontend — client implementation, state, routing, components, frontend tests
- Backend — APIs, services, data, authentication, validation, security
- QA — verification, regression testing, edge cases, release readiness

## Standard flow

User request
  ↓
Lead understands requirements
  ↓
Lead inspects repository
  ↓
Lead creates task breakdown
  ↓
Specialists implement bounded tasks
  ↓
Lead reviews specialist output
  ↓
Lead integrates
  ↓
QA validates
  ↓
Lead fixes/reviews
  ↓
Commit / PR
  ↓
Release

## Ownership

The Lead owns the final result.

Specialists do not:
- Rewrite unrelated systems.
- Change architecture without documenting the decision.
- Commit secrets.
- Overwrite another agent's active work.
- Mark the overall task complete.

## Specialist handoff format

Every specialist should report:

### Completed
What was implemented.

### Files changed
Exact paths.

### Validation
Commands/checks run and results.

### Risks
Anything that could break or needs review.

### Follow-up
Anything intentionally left for another agent.

## Parallel work

Parallelize only tasks that have clear file/ownership boundaries.

Do not run multiple agents against the same files unless the Lead explicitly coordinates the work.

## Git

Prefer:
- Feature branches for non-trivial changes.
- Small focused commits.
- Pull requests for reviewable work.
- No force pushes unless explicitly authorized.

## Completion gate

A feature is not complete until:
- Acceptance criteria are met.
- Relevant tests pass or missing tests are documented.
- Typecheck/lint/build pass when available.
- No known critical/high issue remains.
- QA has checked affected user flows.
- Documentation is updated when architecture or behavior changed.
