# Architecture Decision Records

## ADR-001 — Modular monolith
**Decision:** Begin with a modular monolith.

**Rationale:** Strong domain boundaries and independent modules provide maintainability without premature distributed-system complexity.

## ADR-002 — PostgreSQL as transactional authority
**Decision:** Use PostgreSQL for primary transactional business state.

## ADR-003 — Separate ML and LLM responsibilities
**Decision:** ML.NET handles predictive models; LLM + RAG handles contextual language tasks.

## ADR-004 — Deterministic rules remain authoritative
**Decision:** AI and ML cannot silently override deterministic business rules.

## ADR-005 — Dual messaging strategy
**Decision:** RabbitMQ handles task-oriented asynchronous work; Kafka handles durable event streams.
