---
applyTo: '**'
description: 'Rails guidelines'
---

Rails guidelines:

Architecture:
- Thin controllers.
- Business logic in services.
- Use POROs when appropriate.
- Prefer composition over inheritance.

Database:
- Prevent N+1 queries (use includes/preload).
- Use DB constraints, not just model validations.
- Index foreign keys and high-cardinality fields.

Performance:
- Avoid loading large ActiveRecord collections.
- Prefer select() when full models are unnecessary.

Background jobs:
- Must be idempotent.

Migrations:
- Must be safe for zero-downtime deploys.
- Avoid long locks.
