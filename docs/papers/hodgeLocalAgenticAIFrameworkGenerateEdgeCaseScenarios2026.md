---
citekey: "hodgeLocalAgenticAIFrameworkGenerateEdgeCaseScenarios2026"
title: "A Local Agentic AI Framework to Generate Edge Case Scenarios for Safety Assurance"
authors: ["Victoria J. Hodge", "Colin Paterson", "Rob Alexander"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.13479"
doi: "10.48550/arXiv.2610.13479"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-14
---

# A Local Agentic AI Framework to Generate Edge Case Scenarios for Safety Assurance

> Victoria J. Hodge, Colin Paterson, Rob Alexander · 2026
> [arXiv](https://arxiv.org/abs/2610.13479) · [PDF](https://arxiv.org/pdf/2610.13479)

## Abstract

Generating edge case scenarios is crucial for training, testing and safety assuring autonomous systems. This identifies hazardous failures to increase system reliability and robustness, ensures the system can still function safely on the boundaries of its operational design domain and learns the expected system behaviour for these edge cases. The rapid advancement in the generation and analysis capabilities of language models (LMs) has expanded their applicability and recent work has investigated LM scenario generation. However, many recent approaches rely on human-in-the-loop or rule-based strategies. This restricts the LM's ability to generate diverse and edge case scenarios; the long tail of the distribution. Our work uses local LMs in a laptop-based agentic AI framework for adaptive scenario generation. This is cheap, fully-controlled, ensures data privacy and security. It uses think, act, observe, update, and continue loops with lightweight JSON encoding to generate scenarios. We use the system requirements, system description and environment description as knowledge bases in contextual prompts for an LM to ensure scenario realism. A second, independent LM critiques each scenario using domain specific criteria so it can be refined. The refined scenarios are run in simulation and evaluation metrics collected. These metric scores are analysed and similar scenarios are created for edge cases (exploitation) or novel scenarios are generated to explore the scenario space. Post-hoc clustering using metric scores and thematic-type analysis of the rich-text scenario descriptions produced by the LM pinpoints functional gaps and their triggering conditions. This creates traceable evidence for the safety assurance case. Our work highlights the potential of a flexible and adaptive local agentic AI framework for automating edge case generation and producing traceable safety assurance evidence.

## TL;DR

Generating edge case scenarios is crucial for training, testing and safety assuring autonomous systems. This identifies hazardous failures to increase system reliability and robustness, ensures the system can still function safely on the boundaries of its operational design domain and learns the expected system behaviour for these edge cases.

## Related
<!-- [[other-paper-citekey]] -->
