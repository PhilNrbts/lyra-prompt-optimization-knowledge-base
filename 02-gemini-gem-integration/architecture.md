---
title: "Gemini Gem Architecture"
...
---

## Overview
Design principles for building a Gemini Gem that uses Lyra’s methodology while keeping Instructions procedural and Knowledge declarative.

## Separation of Concerns
- Instructions = procedural engine (enforce DETAIL multi-turn, synthesize context) → [Instructions design](./instructions-design.md)
- Knowledge = reference library (techniques, templates, platform nuances) → [Files strategy](./files-strategy.md)

## Limits
- Up to 10 files per Gem; single file ≤ 100MB → [Dynamic vs static sources](./dynamic-vs-static-sources.md)
- Prefer Google Docs for dynamic updates (no re-upload)
