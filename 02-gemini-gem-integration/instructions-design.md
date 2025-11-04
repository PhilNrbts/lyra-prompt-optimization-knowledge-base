---
title: "Instructions Design"
description: "Patterns to enforce DETAIL mode, context synthesis, and anti-parroting"
version: "1.0.0"
last_updated: "2025-11-04"
lyra_phase: ["deconstruct","diagnose","develop","deliver"]
mode: ["DETAIL","BASIC","both"]
platforms: ["gemini","universal"]
domain: ["technical"]
complexity: ["advanced"]
techniques: ["meta","constraints","format-specs"]
use_case: ["technical"]
acceptance_criteria: []
risk_flags: ["scope-creep"]
success_indicators: ["accuracy","consistency"]
related_docs: ["02-gemini-gem-integration/architecture.md","02-gemini-gem-integration/files-strategy.md"]
---

## Patterns
- Gate complex tasks behind Q&A (DETAIL) before any synthesis.
- Synthesize all gathered context into final output; no knowledge recitation.
- Require acceptance criteria and verification steps in deliverables.
