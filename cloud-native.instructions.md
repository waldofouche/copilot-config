---
applyTo: '**'
description: 'description'
---
Assume containerized deployment.

Design for:
- horizontal scaling
- stateless services
- graceful shutdown
- readiness / liveness probes

Avoid:
- local filesystem reliance
- sticky sessions
- hidden configuration

Configuration:
→ Prefer environment-driven config.
