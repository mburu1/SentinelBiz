# SentinelBiz OOAD — Domain Model

## Core concepts
- Tenant
- User
- Entrepreneur Profile
- Business
- Business Idea
- Learning Program
- Learning Module
- Learning Progress
- Assessment
- Readiness Assessment
- Business Plan
- Market Plan
- Financial Plan
- Support Case
- Advisor Interaction
- Recommendation
- Prediction
- Knowledge Document
- AI Conversation
- Audit Record

## Aggregate guidance
Likely aggregate roots include Business, Business Plan, Learning Program, Assessment, Support Case, and AI Conversation. Exact aggregate boundaries must be confirmed during detailed design.

## Invariants
- Tenant-owned records cannot cross tenant boundaries.
- Authoritative financial calculations are deterministic.
- Prediction output is not treated as deterministic fact.
- AI responses must respect authorization, grounding, and safety policies.
- Sensitive cases may require human escalation.
- Audit records are append-oriented and traceable.

## Domain events
Examples include BusinessCreated, LearningProgressRecorded, AssessmentCompleted, ReadinessEvaluated, BusinessPlanUpdated, SupportCaseEscalated, PredictionGenerated, and AIInteractionCompleted.
