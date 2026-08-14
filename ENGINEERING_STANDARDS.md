# OAE™ Engineering Standards

This repository is maintained under the **Open Autonomous Engineer (OAE™)** engineering standard.

## Required practices

- Security first; never commit credentials, tokens, private keys, or production secrets.
- Validate untrusted input at system boundaries.
- Keep configuration explicit and reviewable.
- Prefer small, cohesive modules and avoid duplicated domain logic.
- Every substantive capability must have automated tests.
- Cover normal, edge, and failure cases where applicable.
- Do not rely on hidden network state in unit tests.
- Verify changes before acceptance.
- Make one coherent change at a time.
- Preserve existing behaviour unless a contract change is intentional.
- Record consequential architectural decisions.

## Production readiness

Production readiness must be demonstrated, not assumed. The repository must have a verified runtime, configuration contract, automated tests, deployment path, and operational documentation before it is described as production-ready.

## OAE™ improvement loop

```text
Observe → Understand → Plan → Approve → Implement → Test → Verify → Measure
```
