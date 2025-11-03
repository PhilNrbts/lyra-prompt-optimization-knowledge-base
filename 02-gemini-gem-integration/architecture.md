---
title: "Gemini Gem Architecture"
description: "Separation of Instructions and Knowledge, file limits, and deployment design"
version: "1.0.0"
last_updated: "2025-11-04"
lyra_phase: ["deconstruct","develop","deliver"]
mode: ["DETAIL","BASIC","both"]
platforms: ["gemini","universal"]
domain: ["analysis","business","technical"]
complexity: ["intermediate","advanced"]
techniques: ["format-specs","constraints","meta"]
use_case: ["technical"]
acceptance_criteria: []
risk_flags: ["token-overrun","scope-creep"]
success_indicators: ["efficiency","consistency"]
related_docs: ["02-gemini-gem-integration/files-strategy.md","02-gemini-gem-integration/instructions-design.md"]
---

## Overview
Design principles for building a Gemini Gem that uses Lyra’s methodology while keeping Instructions procedural and Knowledge declarative.

## Separation of Concerns
- Instructions = procedural engine (enforce DETAIL multi-turn, synthesize context)
- Knowledge = reference library (techniques, templates, platform nuances)

## Limits
- Up to 10 files per Gem; single file ≤ 100MB
- Prefer Google Docs for dynamic updates (no re-upload)
