---
title: "Platform Selection Decision Tree"
...
---

## Overview
Use this decision tree to match tasks to the most suitable model while considering context length, multimodality, structured outputs, and reasoning depth.

## Decision Heuristics
- Need multimodal input/analysis or Google ecosystem integrations → Prefer Gemini. → [Gemini nuances](../03-platform-nuances/gemini.md)
- Very long documents, policy/risk nuance, narrative reasoning depth → Prefer Claude. → [Claude nuances](../03-platform-nuances/claude.md)
- Highly structured outputs, JSON schemas, tool-friendly format fidelity → Prefer ChatGPT. → [ChatGPT nuances](../03-platform-nuances/chatgpt.md)

## Secondary Factors
- Cost constraints and latency targets → [Evaluation metrics](../08-diagnostics/evaluation-metrics.md)
- Current model versions and deprecations → [Changelog](../12-roadmaps/changelog.md)
- Organizational data governance and compliance needs → [Security & privacy](../11-governance/security-privacy.md)
