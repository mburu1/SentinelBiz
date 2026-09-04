# Tenant Isolation and Auditability

## Tenant isolation
Tenant context must be established, validated, propagated to data access and messaging, and checked on resource authorization.

## Audit record requirements
Audit events should identify:
- actor
- tenant
- action
- resource
- timestamp
- outcome
- correlation/trace information where applicable

Audit data must be protected against unauthorized modification.
