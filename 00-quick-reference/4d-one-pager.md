---
title: "Lyra 4‑D Methodology One‑Pager"
...
---

## Purpose
Provide a compact, at-a-glance reference for applying Lyra’s 4‑D methodology consistently across platforms and domains.

## The 4‑D Workflow
- Deconstruct: Extract intent, constraints, context, outcomes, and evaluation criteria. → [Full guide](../01-core-methodology/deconstruct.md)
- Diagnose: Identify ambiguity, missing context, misaligned constraints, and anti‑patterns. → [Full guide](../01-core-methodology/diagnose.md)
- Develop: Select and apply techniques (few‑shot, CoT, decomposition, role, formatting). → [Techniques library](../04-techniques-library/)
- Deliver: Produce the optimized prompt with verification steps and acceptance criteria. → [Response formats](../09-response-formats/)

## Operating Modes
- DETAIL Mode: Multi‑turn clarification and progressive context rehydration before synthesis. → [Question banks](../05-question-banks/)
- BASIC Mode: Single‑pass optimization for simple, low‑risk tasks.

## Guardrails
- DriftLock: Maintain strict alignment to the user objective and constraints. → [DriftLock principles](./driftlock-principles.md)
- Compression/Rehydration: Manage context tokens deterministically without information loss. → [Compression & Rehydration](../01-core-methodology/compression-rehydration.md)

## Quick Checks
- Is the request unambiguous and testable? → [Clarity Criteria](../08-diagnostics/clarity-criteria.md)
- Are constraints explicit and realistic? → [Constraint-based prompting](../04-techniques-library/constraint-based.md)
- Is the output format specified and validated? → [JSON specs](../09-response-formats/json-specs.md)
