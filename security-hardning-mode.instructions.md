---
applyTo: '**'
description: 'Security is critical.'
---
Provide project context and coding guidelines that AI should follow when generating code, answering questions, or reviewing changes.

Always:
- Validate all external input.
- Use parameterized queries only.
- Enforce least privilege.
- Prefer explicit allow-lists over deny-lists.
- Treat identity assertions as untrusted until verified.

Authentication / Identity:
- Never bypass signature validation.
- Never disable certificate checks.
- Do not weaken crypto defaults.
- Preserve AuthnContext / ACR semantics.
- Avoid custom crypto.

Sessions:
- Assume zero trust between services.
- Protect against replay attacks.
- Consider token expiry and rotation.

If a suggestion could weaken security:
→ Warn explicitly.