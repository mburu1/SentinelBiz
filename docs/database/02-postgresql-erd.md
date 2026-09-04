# PostgreSQL — Conceptual ERD

```mermaid
erDiagram
    TENANT ||--o{ USER : contains
    TENANT ||--o{ BUSINESS : owns
    USER ||--o| ENTREPRENEUR_PROFILE : has
    ENTREPRENEUR_PROFILE ||--o{ BUSINESS : operates
    BUSINESS ||--o| BUSINESS_PLAN : has
    BUSINESS ||--o{ LEARNING_PROGRESS : records
    BUSINESS ||--o{ ASSESSMENT : completes
    BUSINESS ||--o{ SUPPORT_CASE : creates
    BUSINESS ||--o{ PREDICTION : receives
    BUSINESS ||--o{ RECOMMENDATION : receives
    SUPPORT_CASE }o--o| USER : assigned_to
```

This is a conceptual ERD, not an implementation schema. Keys, normalization, indexes, constraints, retention, and migration strategy are to be finalized before implementation.
