Assume this commit will be read during a production incident.

Use Conventional Commits.

Format:
<type>(optional-scope): concise summary

Rules:
- Maximum 72 characters for the summary.
- Use present tense ("add", not "added").
- Describe the user or system impact — not the implementation.
- Be concise but specific.
- Avoid filler words.

Types:
feat      → new feature
fix       → bug fix
refactor  → code change with no behavioral change
perf      → performance improvement
test      → tests added/updated
docs      → documentation only
build     → build or dependency changes
ci        → CI/CD changes
chore     → maintenance with no production impact
security  → security improvement or risk reduction

Good examples:
feat(oidc): support ACR → AuthnContext mapping  
fix(session): prevent replay window during token refresh  
refactor(audit): extract formatter to reduce allocations  
security(saml): enforce signature validation on responses

Avoid vague messages:
❌ update code  
❌ fix stuff  
❌ misc changes  
❌ improvements

Body guidelines (include when helpful):
- Why the change was necessary
- Security implications
- Performance impact
- Migration steps
- Breaking changes
- Operational considerations
- Links to relevant documentation, specifications, RFCs, or vendor guides when they influenced the change

Link guidelines:
- Prefer canonical sources (official docs, RFCs, GitHub repos).
- Include direct URLs rather than homepage links.
- Place links at the end of the body under a "References:" section when multiple exist.

Example:

References:
https://datatracker.ietf.org/doc/html/rfc6749  
https://shibboleth.atlassian.net/wiki/

Formatting:
- Separate summary and body with ONE blank line.
- Use bullet points for readability.
- Do NOT rely on "\n" literals — some tools strip them.

Breaking changes:
- Start with: BREAKING CHANGE:
- Clearly describe required action.

AI attribution (required for AI-assisted commits):
Add this trailer at the very bottom:

AI-Generated: GitHub Copilot (JetBrains)

Never place trailers above the body.
