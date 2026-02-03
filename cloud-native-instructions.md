---
applyTo: '**'
description: 'Cloud-native deployment guidelines: stateless, horizontally scalable, health-checked services with env-driven config.'
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
