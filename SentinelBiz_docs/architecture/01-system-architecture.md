# SentinelBiz Architecture Specification

## Architectural style
SentinelBiz is a **modular monolith** with explicit bounded contexts and event-driven boundaries.

## Logical layers
- Presentation/API
- Application
- Domain
- Infrastructure
- AI/ML capabilities
- Cross-cutting observability and security

## Core infrastructure
ASP.NET Core REST API, PostgreSQL, MongoDB, Redis, RabbitMQ, Kafka, ML.NET, LLM abstraction, RAG/vector search, Serilog, OpenTelemetry, Prometheus, Grafana, and Docker Compose.

## Guiding rule
Modularity comes before distribution. Microservices are not introduced merely because messaging infrastructure exists.
