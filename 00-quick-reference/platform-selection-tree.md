---
title: "Platform Selection Decision Tree"
description: "Heuristics to choose between Gemini, Claude, and ChatGPT based on task requirements"
version: "1.0.0"
last_updated: "2025-11-04"
lyra_phase: ["deconstruct","diagnose"]
mode: ["DETAIL","BASIC","both"]
platforms: ["gemini","claude","chatgpt","universal"]
domain: ["marketing","coding","writing","analysis","educational","creative","business"]
complexity: ["beginner","intermediate","advanced"]
techniques: ["constraints","format-specs","role"]
use_case: ["creative","technical","educational","complex","business","personal"]
acceptance_criteria: []
risk_flags: ["ambiguity","token-overrun"]
success_indicators: ["accuracy","efficiency","satisfaction"]
related_docs: ["03-platform-nuances/gemini.md","03-platform-nuances/claude.md","03-platform-nuances/chatgpt.md","03-platform-nuances/feature-comparison-matrix.md"]
---

## Overview
Use this decision tree to match tasks to the most suitable model while considering context length, multimodality, structured outputs, and reasoning depth.

## Decision Heuristics
- Need multimodal input/analysis or Google ecosystem integrations → Prefer Gemini.
- Very long documents, policy/risk nuance, narrative reasoning depth → Prefer Claude.
- Highly structured outputs, JSON schemas, tool-friendly format fidelity → Prefer ChatGPT.

## Secondary Factors
- Cost constraints and latency targets
- Current model versions and deprecations
- Organizational data governance and compliance needs
