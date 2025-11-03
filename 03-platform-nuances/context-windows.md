---
title: "Context Windows"
description: "Practical guidance for context length, token budgeting, and chunking across platforms"
version: "1.0.0"
last_updated: "2025-11-04"
lyra_phase: ["deconstruct","develop"]
mode: ["DETAIL","BASIC","both"]
platforms: ["gemini","claude","chatgpt","universal"]
domain: ["technical","analysis"]
complexity: ["intermediate"]
techniques: ["compression","few-shot","format-specs"]
use_case: ["technical"]
acceptance_criteria: []
risk_flags: ["token-overrun"]
success_indicators: ["efficiency"]
related_docs: ["01-core-methodology/compression-rehydration.md","00-quick-reference/tokens-context-quickguide.md"]
---

## Guidance
- Budget tokens for instructions, knowledge, examples, and outputs.
- Chunk inputs and rehydrate context progressively for long tasks.
