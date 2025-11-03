---
title: "Pitfalls & Mitigations"
description: "Common failure modes in Gem setups and how to prevent them"
version: "1.0.0"
last_updated: "2025-11-04"
lyra_phase: ["diagnose","deliver"]
mode: ["DETAIL","BASIC","both"]
platforms: ["gemini","universal"]
domain: ["technical"]
complexity: ["intermediate","advanced"]
techniques: ["constraints","format-specs","self-critique"]
use_case: ["technical"]
acceptance_criteria: []
risk_flags: ["scope-creep","token-overrun"]
success_indicators: ["consistency","accuracy"]
related_docs: ["02-gemini-gem-integration/instructions-design.md"]
---

## Pitfalls
- Parroting knowledge instead of applying it → Enforce application rules.
- Premature optimization without Q&A → Gate behind DETAIL questioning.
- Loss of context across turns → Explicit synthesis step.
