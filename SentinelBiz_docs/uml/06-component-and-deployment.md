# UML — Component and Deployment Models

## Components

```mermaid
flowchart TB
    UI[Angular Frontend] --> API[ASP.NET Core API]
    API --> MOD[SentinelBiz Modules]
    MOD --> PG[(PostgreSQL)]
    MOD --> MG[(MongoDB)]
    MOD --> REDIS[(Redis)]
    MOD --> RABBIT[RabbitMQ]
    MOD --> KAFKA[Kafka]
    MOD --> ML[ML.NET]
    MOD --> AI[LLM + RAG]
    API --> OBS[OpenTelemetry / Serilog]
```

## Deployment concept

```mermaid
flowchart LR
    Client[Browser] --> Web[Angular Application]
    Web --> App[SentinelBiz API / Modular Monolith]
    App --> PG[(PostgreSQL)]
    App --> Mongo[(MongoDB)]
    App --> Redis[(Redis)]
    App --> Rabbit[RabbitMQ]
    App --> Kafka[Kafka]
    App --> AI[LLM / Local Ollama]
    App --> ML[ML.NET]
    App --> Obs[Observability Stack]
```

The deployment model is logical; production topology, replicas, networking, and orchestration are implementation-stage concerns.
