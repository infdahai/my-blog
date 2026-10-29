---
citekey: "bajramiHowLongUntilYourIgnoresYouSafetyBenchmark2026"
title: "How Long Until Your Robot Ignores You? A Safety Benchmark for LLM Orchestrators in Human-Humanoid Collaboration"
authors: ["Aulon Bajrami", "Mohamed Elshamouty", "Werner Kraus"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.07288"
doi: "10.48550/arXiv.2609.07288"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# How Long Until Your Robot Ignores You? A Safety Benchmark for LLM Orchestrators in Human-Humanoid Collaboration

> Aulon Bajrami, Mohamed Elshamouty, Werner Kraus · 2026
> [arXiv](https://arxiv.org/abs/2609.07288) · [PDF](https://arxiv.org/pdf/2609.07288)

## Abstract

Large Language Models (LLMs) are increasingly employed to orchestrate robot behavior through natural-language interfaces, yet no benchmark exists to evaluate their reliability as safety-aware decision makers in human-humanoid collaboration. Unlike deterministic safety systems that enforce binary allow/deny decisions, LLM-based orchestrators exhibit a compliance spectrum ranging from overcompliance (refusing safe actions) to full safety violations. This paper introduces the first safety benchmarking environment for LLM orchestrators in human-humanoid collaboration, built on a Model Context Protocol (MCP)-based architecture with safety invariants grounded in ISO 10218-2:2025 protective measures. The benchmark defines five testable safety invariants, a four-level compliance taxonomy (correct compliance, overcompliance, undercompliance, full violation), and a three-layer evaluation pipeline (text prompting, simulated sensor-actuator loops, and physical validation on a Unitree G1 EDU humanoid). We report Layer-1 results: three cloud backends (Claude Haiku 4.5, GPT-4o-mini, Gemini 2.5 Flash) and a local open-weights baseline (qwen3:8b) across 40 100-turn sessions under full-context and sliding-window budget conditions, while the simulation and physical layers remain ongoing. We find that (1) model family determines the safety floor, as Claude and Gemini remain at or near zero violations while GPT-4o-mini commits up to 13 per session, (2) context management dissociates two failure axes, reducing mean behavioral issues by 42-57% for every cloud backend while nearly doubling GPT-4o-mini's violations (3.8 to 7.2 per session), and (3) proportional compliance, clamping movement speed to the rule-specified maximum rather than refusing, emerges consistently only in Gemini; the preliminary simulation layer reproduces the model ranking and the GPT-4o-mini failure-mode inversion.

## TL;DR

Large Language Models (LLMs) are increasingly employed to orchestrate robot behavior through natural-language interfaces, yet no benchmark exists to evaluate their reliability as safety-aware decision makers in human-humanoid collaboration. Unlike deterministic safety systems that enforce binary allow/deny decisions, LLM-based orchestrators exhibit a compliance spectrum ranging from overcompliance (refusing safe actions) to full safety violations.

## Related
<!-- [[other-paper-citekey]] -->
