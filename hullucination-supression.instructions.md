---
applyTo: '**'
description: 'Anti-hallucination rules: verify APIs/config exist; never fabricate framework methods, flags, CLI options, or annotations.'
---
Before generating code:

Ask internally:
"Does this API actually exist?"

If unsure:
→ say you are unsure.

Do not fabricate:
- framework methods
- config flags
- CLI options
- annotations