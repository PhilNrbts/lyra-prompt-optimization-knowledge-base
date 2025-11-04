---
title: "Files Strategy"
description: "Dynamic (Docs) vs static (PDF/DOCX) files, namespacing, and update cadence"
version: "1.0.0"
last_updated: "2025-11-04"
lyra_phase: ["develop","deliver"]
mode: ["DETAIL","BASIC","both"]
platforms: ["gemini","universal"]
domain: ["technical","business"]
complexity: ["intermediate"]
techniques: ["format-specs","constraints"]
use_case: ["technical"]
acceptance_criteria: []
risk_flags: ["token-overrun"]
success_indicators: ["efficiency","consistency"]
related_docs: ["02-gemini-gem-integration/architecture.md","02-gemini-gem-integration/instructions-design.md"]
---

## Strategy
- Dynamic: Google Docs for living knowledge; version stamp in header.
- Static: PDFs/DOCX for frozen snapshots; mirror to repo with changelog.
- Namespacing: 01_core, 02_questions, 03_techniques, 04_platforms, 05_formats.
