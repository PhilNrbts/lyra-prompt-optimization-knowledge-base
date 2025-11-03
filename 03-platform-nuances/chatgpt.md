---
title: "ChatGPT Nuances"
description: "Platform-specific prompting strategies for ChatGPT (structured outputs, tool-friendliness)"
version: "1.0.0"
last_updated: "2025-11-04"
lyra_phase: ["develop","deliver"]
mode: ["DETAIL","BASIC","both"]
platforms: ["chatgpt"]
domain: ["creative","analysis","technical","business"]
complexity: ["beginner","intermediate","advanced"]
techniques: ["few-shot","cot","decomposition","format-specs","role"]
use_case: ["creative","technical","educational","complex","business","personal"]
acceptance_criteria: []
risk_flags: ["token-overrun"]
success_indicators: ["accuracy","efficiency","satisfaction"]
related_docs: ["03-platform-nuances/context-windows.md","03-platform-nuances/feature-comparison-matrix.md"]
---

## Patterns
- Emphasize explicit sectioning and JSON output when integrating with tools.
- Use stepwise instructions and examples to improve determinism.
- Keep constraints and acceptance criteria concise and testable.
