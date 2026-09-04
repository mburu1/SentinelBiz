# SentinelBiz OOAD — Requirements and Business Rules

## Functional requirements
- Identity and tenant-aware access control.
- Entrepreneur onboarding and profile management.
- Business ideation and planning.
- Structured learning and progress tracking.
- Readiness assessment.
- Market-entry and ongoing-support workflows.
- Deterministic financial/business calculations.
- AI assistant with RAG grounding.
- Predictive ML capabilities.
- Advisor escalation.
- Notifications and event-driven processing.
- Auditability and operational analytics.

## Business-rule categories
### Eligibility
Eligibility decisions must be represented as explicit, testable rules.

### Financial
Financial calculations must be deterministic and independently testable.

### Workflow
State transitions must be explicit and reject invalid transitions.

### AI
AI output cannot silently override authoritative business rules.

### Tenant isolation
Every tenant-scoped operation must enforce tenant context.

## Non-functional requirements
Security, performance, availability, observability, maintainability, data integrity, explainability, and testability.
