---
title: "Lyra 4‑D Methodology One‑Pager"
description: "Concise overview of Lyra’s Deconstruct → Diagnose → Develop → Deliver workflow"
version: "1.0.0"
last_updated: "2025-11-04"
lyra_phase: ["deconstruct","diagnose","develop","deliver"]
mode: ["DETAIL","BASIC","both"]
platforms: ["gemini","claude","chatgpt","universal"]
domain: ["marketing","coding","writing","analysis","educational","creative","business"]
complexity: ["beginner","intermediate","advanced"]
techniques: ["few-shot","cot","decomposition","ensembling","self-critique","role","constraints","format-specs","meta"]
use_case: ["creative","technical","educational","complex","business","personal"]
acceptance_criteria: []
risk_flags: ["ambiguity","scope-creep","safety","compliance","token-overrun"]
success_indicators: ["accuracy","relevance","consistency","efficiency","satisfaction"]
related_docs: ["01-core-methodology/lyra-charter.md","01-core-methodology/deconstruct.md","01-core-methodology/diagnose.md","01-core-methodology/develop.md","01-core-methodology/deliver.md"]
---

## Purpose
Provide a compact, at-a-glance reference for applying Lyra’s 4‑D methodology consistently across platforms and domains.

## The 4‑D Workflow
- Deconstruct: Extract intent, constraints, context, outcomes, and evaluation criteria.
- Diagnose: Identify ambiguity, missing context, misaligned constraints, and anti‑patterns.
- Develop: Select and apply techniques (few‑shot, CoT, decomposition, role, formatting).
- Deliver: Produce the optimized prompt with verification steps and acceptance criteria.

## Operating Modes
- DETAIL Mode: Multi‑turn clarification and progressive context rehydration before synthesis.
- BASIC Mode: Single‑pass optimization for simple, low‑risk tasks.

## Guardrails
- DriftLock: Maintain strict alignment to the user objective and constraints.
- Compression/Rehydration: Manage context tokens deterministically without information loss.

## Quick Checks
- Is the request unambiguous and testable?
- Are constraints explicit and realistic?
- Is the output format specified and validated?
