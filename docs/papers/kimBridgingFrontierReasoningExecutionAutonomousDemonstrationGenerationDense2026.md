---
citekey: "kimBridgingFrontierReasoningExecutionAutonomousDemonstrationGenerationDense2026"
title: "Bridging Frontier Reasoning and Robot Execution: From Autonomous Demonstration Generation to Dense Language Supervision"
authors: ["Bosung Kim", "Alexander Trevithick", "Ruiyi Wang", "Prithviraj Ammanabrolu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.03615"
doi: "10.48550/arXiv.2610.03615"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-06
---

# Bridging Frontier Reasoning and Robot Execution: From Autonomous Demonstration Generation to Dense Language Supervision

> Bosung Kim, Alexander Trevithick, Ruiyi Wang, Prithviraj Ammanabrolu · 2026
> [arXiv](https://arxiv.org/abs/2610.03615) · [PDF](https://arxiv.org/pdf/2610.03615)

## Abstract

Recent advances in frontier models enable robot manipulation from only a few demonstrations, but high inference latency limits their use for real-time robot control. To bridge this gap, we study two complementary approaches that connect frontier reasoning with low-latency local execution. First, we use a frontier model to autonomously generate demonstrations that supplement human demonstrations for training a fast local policy. We augment its in-context examples with corrective demonstration segments that show how to recover from physical errors, improving generation reliability. Generation time and cost decrease as successful examples accumulate in context, suggesting a path toward more efficient data collection. At deployment, a harness combines frontier-generated instructions with a fast local policy, enabling efficient execution while preserving the frontier model's ability to guide and correct actions. With low-latency execution delegated to the local policy, the bottleneck shifts to its capacity to reliably follow the frontier model's diverse instructions. Our second bridge introduces dense language supervision across three nested granularities---primitive, atomic, and composite---with multi-aspect descriptions at each level. Across long-horizon tasks in RoboCasa 365 and BEHAVIOR-1K, where instructions change as execution progresses, the combined supervision achieves the highest performance under both oracle and frontier-model instructors, demonstrating more reliable instruction following through the policy's language interface. Finally, we evaluate both bridges together on a crossword task that combines semantic planning and manipulation within a fixed time budget. These results support autonomous demonstration generation and dense language supervision as complementary components for connecting frontier reasoning to low-latency local execution.

## TL;DR

Recent advances in frontier models enable robot manipulation from only a few demonstrations, but high inference latency limits their use for real-time robot control. To bridge this gap, we study two complementary approaches that connect frontier reasoning with low-latency local execution.

## Related
<!-- [[other-paper-citekey]] -->
