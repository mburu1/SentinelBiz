# SentinelBiz Database Specification

## Data stores

| Store | Purpose |
|---|---|
| PostgreSQL | Primary transactional relational data |
| MongoDB | Documents, AI/RAG-related data, flexible knowledge content |
| Redis | Caching, transient coordination, and short-lived state |
| Kafka | Durable event streams |
| RabbitMQ | Commands/background work and asynchronous task delivery |

## Ownership
Each bounded context owns its transactional data and exposes data through application contracts rather than unrestricted cross-module table access.

## Tenancy
Tenant identity is a mandatory data-access concern for tenant-owned records.
