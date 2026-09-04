# SentinelBiz AI Specification

## AI responsibilities
- Conversational business support.
- Knowledge-grounded Q&A.
- Business-plan assistance.
- Explanations of assessments and recommendations.
- Contextual guidance.

## Non-responsibilities
The LLM does not own authoritative financial calculations, eligibility rules, workflow state, or security authorization.

## Architecture
User → API → AI Orchestrator → authorization/context → RAG retrieval → prompt construction → LLM → guardrails → response/audit.
