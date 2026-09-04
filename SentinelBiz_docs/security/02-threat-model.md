# Threat Model

## Key threats
- Broken access control.
- Cross-tenant data exposure.
- Token/session compromise.
- Injection attacks.
- Prompt injection.
- Retrieval poisoning.
- Sensitive data leakage through AI.
- Unauthorized model/tool actions.
- Message replay or duplicate processing.
- Secrets exposure.
- Insecure file/document ingestion.
- Abuse and denial-of-service.

## Mitigations
Defense in depth, authorization at boundaries, validation, secure secret management, audit trails, idempotency, rate limits, content controls, and continuous testing.
