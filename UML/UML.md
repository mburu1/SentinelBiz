# UML

## Purpose

Maintain UML views that communicate the structure and behavior of SentinelBiz.

## Use-case view

```mermaid
flowchart LR
    User[Primary user] --> System[SentinelBiz]
    Admin[Administrator] --> System
    Support[Support team] --> System
```

## Component view

```mermaid
flowchart TB
    Client[User interface] --> Application[Application boundary]
    Application --> Domain[Domain model]
    Application --> Infrastructure[Infrastructure boundary]
```

These are placeholders and must be refined after the requirements and domain
vocabulary are approved.

## Modeling conventions

- Use nouns for domain concepts.
- Use verbs for behaviors and interactions.
- Show ownership and cardinality where they matter.
- Keep diagrams focused on one question.
