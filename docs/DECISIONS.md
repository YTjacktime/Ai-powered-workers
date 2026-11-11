# Architecture Decision Records

Use this file for decisions that materially affect the project.

## ADR-001 — Lead + specialist agent model

**Status:** Accepted

**Decision:** Use one lead/orchestrator agent with bounded UI/UX, frontend, backend, and QA specialists.

**Reason:** This separates responsibilities while keeping one agent accountable for integration and project-wide consistency.

**Consequence:** Specialists must communicate concrete outputs and the lead must review their work before integration.

## ADR-002 — Repository as source of truth

**Status:** Accepted

**Decision:** GitHub is the canonical source of code and project documentation.

**Reason:** It provides version history, review, collaboration, and recovery.

**Consequence:** Agents should keep meaningful project knowledge in versioned files rather than relying on chat history alone.
