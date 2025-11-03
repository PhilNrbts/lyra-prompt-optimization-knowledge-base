---
title: "Technique Selection Flowchart"
description: "Flowchart to select prompt optimization techniques by task profile"
version: "1.0.0"
last_updated: "2025-11-04"
lyra_phase: ["develop"]
mode: ["DETAIL","BASIC","both"]
platforms: ["gemini","claude","chatgpt","universal"]
domain: ["marketing","coding","writing","analysis","educational","creative","business"]
complexity: ["beginner","intermediate","advanced"]
techniques: ["few-shot","cot","decomposition","ensembling","self-critique","role","constraints","format-specs","meta"]
use_case: ["creative","technical","educational","complex","business","personal"]
acceptance_criteria: []
risk_flags: ["ambiguity","scope-creep","token-overrun"]
success_indicators: ["accuracy","relevance","consistency","efficiency"]
related_docs: ["04-techniques-library/in-context-learning.md","04-techniques-library/chain-of-thought.md","04-techniques-library/decomposition.md","04-techniques-library/ensembling.md","04-techniques-library/self-critique.md"]
---

## Flow Summary
- If task is ambiguous → Role + Clarifying questions (DETAIL) → Decomposition → Format-specs.
- If reasoning-heavy → CoT/Step-back → Self-consistency sampling → Verification.
- If domain patterns exist → Few-shot with curated examples → Output schema lock.
- If complex multi-stage → Decomposition (least-to-most) → Plan-and-solve → Validate.
