---
applyTo: '**'
description: 'description'
---
Kotlin rules:

- Prefer immutability.
- Use data classes.
- Avoid nullable types unless necessary.
- Model states with sealed classes.

Concurrency:
- Prefer coroutines over blocking.
- Never block request threads.

Spring/Ktor:
- Constructor injection only.
- Keep controllers thin.
- Explicit transaction boundaries.

Serialization:
- Be explicit with field names.
- Avoid reflection-heavy magic.
