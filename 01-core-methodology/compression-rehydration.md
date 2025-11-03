---
title: "Compression & Rehydration"
description: "Deterministic methods to compress context and rehydrate details without loss of fidelity"
version: "1.0.0"
last_updated: "2025-11-04"
lyra_phase: ["deconstruct","develop"]
mode: ["DETAIL","BASIC","both"]
platforms: ["gemini","claude","chatgpt","universal"]
domain: ["marketing","coding","writing","analysis","educational","creative","business"]
complexity: ["intermediate","advanced"]
techniques: ["compression","few-shot","format-specs"]
use_case: ["creative","technical","educational","complex","business","personal"]
acceptance_criteria: []
risk_flags: ["token-overrun"]
success_indicators: ["efficiency","consistency"]
related_docs: ["00-quick-reference/tokens-context-quickguide.md","03-platform-nuances/context-windows.md"]
---

## Practices
- Abstract repetitive elements into references.
- Rehydrate context stepwise at generation time.
- Validate equivalence between compressed and full versions.
