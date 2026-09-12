# Security Model

## Purpose

Define how SentinelBiz protects identities, data, operations, and integrations.

## Security objectives

- Preserve confidentiality, integrity, and availability.
- Apply least privilege and separation of duties.
- Protect secrets and sensitive data throughout their lifecycle.
- Make security-relevant actions auditable.

## Threat model scope

```mermaid
flowchart LR
    User[Users] --> Identity[Identity boundary]
    Identity --> Application[SentinelBiz]
    Application --> Data[Business data]
    Application --> Integration[External integrations]
    Attacker[Potential attacker] -. threatens .-> Identity
    Attacker -. threatens .-> Application
    Attacker -. threatens .-> Data
```

## Controls to define

- Authentication and session management
- Authorization model
- Input validation and abuse prevention
- Encryption in transit and at rest
- Logging, monitoring, and incident response
- Data retention and privacy handling
