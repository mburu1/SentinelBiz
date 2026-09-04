# SentinelBiz OOAD — System Overview

## Purpose
SentinelBiz is an AI-powered entrepreneur training, business support, learning analytics, and decision-support platform.

## Primary business journey
Registration → Business Ideation → Investment Readiness → Business Planning → Market Entry → Ongoing Support.

## Design principles
- Domain-driven modular monolith.
- Explicit bounded contexts and module ownership.
- Deterministic business rules are authoritative.
- ML.NET provides predictions and recommendations.
- LLM + RAG provides contextual language assistance.
- Human escalation is available for complex or sensitive cases.
- Tenant isolation, auditability, and security are first-class concerns.

## Primary actors
- Entrepreneur
- Advisor/Support Officer
- Program/Operations Manager
- Platform Administrator
- System/Integration
- AI Assistant
- ML Prediction Services

## Quality attributes
Security, reliability, maintainability, observability, explainability, testability, scalability, and tenant isolation.
