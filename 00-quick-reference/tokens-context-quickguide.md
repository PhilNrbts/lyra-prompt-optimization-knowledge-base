---
title: "Tokens & Context Quick Guide"
description: "Practical limits and patterns for efficient context window usage"
version: "1.0.0"
last_updated: "2025-11-04"
lyra_phase: ["deconstruct","develop"]
mode: ["DETAIL","BASIC","both"]
platforms: ["gemini","claude","chatgpt","universal"]
domain: ["marketing","coding","writing","analysis","educational","creative","business"]
complexity: ["beginner","intermediate","advanced"]
techniques: ["compression","few-shot","format-specs"]
use_case: ["creative","technical","educational","complex","business","personal"]
acceptance_criteria: []
risk_flags: ["token-overrun"]
success_indicators: ["efficiency","consistency"]
related_docs: ["01-core-methodology/compression-rehydration.md","03-platform-nuances/context-windows.md"]
---

## Practices
- Compress early, rehydrate just-in-time.
- Trim examples to highest-signal demonstrations.
- Prefer references/IDs over full inlined content when possible.
