# AI Security

## Requirements
- Never trust user or retrieved content as instructions by default.
- Separate system policy from retrieved/user content.
- Restrict tools/actions through explicit allowlists.
- Apply authorization before retrieval.
- Prevent cross-tenant context leakage.
- Detect sensitive information exposure.
- Log security-relevant AI decisions and tool calls.
- Maintain model/provider abstraction to avoid hard coupling.
