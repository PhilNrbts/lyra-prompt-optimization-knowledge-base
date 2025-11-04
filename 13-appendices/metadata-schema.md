---
title: "Metadata Schema"
description: "Complete YAML front-matter specification for all knowledge base documents"
version: "1.0.0"
last_updated: "2025-11-04"
lyra_phase: ["deliver"]
mode: ["DETAIL","BASIC","both"]
platforms: ["universal"]
domain: ["technical"]
complexity: ["intermediate"]
techniques: ["format-specs"]
use_case: ["technical"]
acceptance_criteria: []
risk_flags: []
success_indicators: ["consistency"]
related_docs: ["11-governance/contributing.md"]
---

## Required Fields
```yaml
title: "Document Title"
description: "Brief description of content and purpose"
version: "1.0.0"
last_updated: "YYYY-MM-DD"
```

## Classification Fields
```yaml
lyra_phase: ["deconstruct","diagnose","develop","deliver"]
mode: ["DETAIL","BASIC","both"]
platforms: ["gemini","claude","chatgpt","universal"]
domain: ["marketing","coding","writing","analysis","educational","creative","business"]
complexity: ["beginner","intermediate","advanced","expert"]
```

## Content Fields
```yaml
techniques: ["few-shot","cot","decomposition","ensembling","self-critique"]
use_case: ["creative","technical","educational","complex","business","personal"]
acceptance_criteria: []
risk_flags: ["ambiguity","scope-creep","safety","compliance","token-overrun"]
success_indicators: ["accuracy","relevance","consistency","efficiency","satisfaction"]
related_docs: []
```
