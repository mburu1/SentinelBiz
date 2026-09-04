# Data Governance

## Classification
Data should be classified according to business sensitivity before implementation.

## Principles
- Minimize collection.
- Enforce tenant boundaries.
- Encrypt data in transit and at rest where applicable.
- Define retention periods.
- Audit privileged access.
- Maintain provenance for AI/RAG content.
- Separate operational, analytical, document, cache, and event data responsibilities.

## Consistency
PostgreSQL is authoritative for transactional business state. Kafka provides durable event streams; RabbitMQ handles asynchronous work; Redis is not an authoritative system of record.
