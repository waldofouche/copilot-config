Use Conventional Commits.

<type>(scope): summary

Rules:
- ≤ 72 chars
- Present tense
- Describe impact, not mechanics.
- concise yet descriptive

Good:
feat(oidc): support ACR → AuthnContext mapping
fix(session): prevent replay window during token refresh
refactor(audit): extract formatter to reduce allocation

Avoid:
❌ "update code"
❌ "fix stuff"
❌ "changes"


Include when helpful:
- why the change exists
- security implications
- migration notes
- breaking changes
