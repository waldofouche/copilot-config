---
applyTo: '**'
description: 'description'
---
Production safety matters more than elegance.

Build for failure:
- Timeouts
- Retries with backoff
- Circuit breakers where appropriate

External calls must:
- timeout
- be observable
- degrade gracefully
