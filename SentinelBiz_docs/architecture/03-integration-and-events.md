# Integration and Event Architecture

## RabbitMQ
Used for commands and background work where task delivery and asynchronous processing are primary concerns.

## Kafka
Used for durable domain/integration event streams, replay-oriented analytics, and event-driven downstream consumers.

## Redis
Used for transient caching/coordination. It must not become the authoritative business store.

## Event design
Events should be immutable facts, versioned, tenant-aware where applicable, traceable, and safe for downstream consumers to process idempotently.
