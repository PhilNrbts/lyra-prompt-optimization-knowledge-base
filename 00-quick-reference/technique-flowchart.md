---
title: "Technique Selection Flowchart"
...
---

## Flow Summary
- If task is ambiguous → Role + Clarifying questions (DETAIL) → Decomposition → Format-specs. → [Role assignment](../04-techniques-library/role-assignment.md) | [Universal questions](../05-question-banks/universal.md) | [Decomposition](../04-techniques-library/decomposition.md) | [Output specs](../04-techniques-library/output-specs.md)
- If reasoning-heavy → CoT/Step-back → Self-consistency sampling → Verification. → [Chain-of-Thought](../04-techniques-library/chain-of-thought.md) | [Ensembling](../04-techniques-library/ensembling.md) | [Verification blocks](../09-response-formats/verification-blocks.md)
- If domain patterns exist → Few-shot with curated examples → Output schema lock. → [In-context learning](../04-techniques-library/in-context-learning.md) | [JSON specs](../09-response-formats/json-specs.md)
- If complex multi-stage → Decomposition (least-to-most) → Plan-and-solve → Validate. → [Decomposition](../04-techniques-library/decomposition.md) | [Quality rubrics](../08-diagnostics/quality-rubrics.md)
