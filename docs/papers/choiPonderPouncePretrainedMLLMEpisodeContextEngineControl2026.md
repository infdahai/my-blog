---
citekey: "choiPonderPouncePretrainedMLLMEpisodeContextEngineControl2026"
title: "PonderPounce: A Pretrained MLLM as an Episode Context Engine for Robot Control"
authors: ["Suhwan Choi", "Jaeyoon Jung", "Sungkyung Kim", "Yunsung Lee", "Youngjae Yu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.24115"
doi: "10.48550/arXiv.2608.24115"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-08-26
---

# PonderPounce: A Pretrained MLLM as an Episode Context Engine for Robot Control

> Suhwan Choi, Jaeyoon Jung, Sungkyung Kim, Yunsung Lee, Youngjae Yu · 2026
> [arXiv](https://arxiv.org/abs/2608.24115) · [PDF](https://arxiv.org/pdf/2608.24115)

## Abstract

Multimodal large language models (MLLMs) can integrate long visual histories, reason under partial observability, and infer behavior from a few examples. Yet vision-language-action (VLA) models generally inherit pretrained representations without using this contextual capacity as episode memory. Memory-dependent policies address this gap through purpose-built history mechanisms. PonderPounce instead reuses an MLLM's native causal context as robot memory. Ponder, a System2 MLLM, accumulates episode observations, demonstrations, and prior cognition in its native causal context and can generate subgoal text and demonstration reasoning for internal use. Pounce, a System1 VLA, receives the current observation, instruction, and proprioception directly; through the Ponder--Pounce interface, it asynchronously receives only the newest continuous cognition token and its age. Both are jointly trained end to end without a purpose-built memory module or separate bridge pretraining. Optimized serving achieves p50 latencies of 78ms for cognition refresh and 25ms for action-model invocation, supporting 20Hz action playback. On RoboMME with base-scale training data, PonderPounce reaches 60.83% with 9B and 50.04% with 0.8B under the same Pounce architecture and interface, versus 44.51% for FrameSamp+Modul and 17.93% for the current-observation π_{0.5}. With 9x data, it reaches 75.54% versus 57.88% for FrameSamp+Modul. On RoboCasa-DC, the same interface learns from action supervision alone and reaches 12.5% versus 11.6% for the strongest published demonstration-conditioned baseline, falling to 8.6% when cognition is replaced by a learned null state.

## TL;DR

Multimodal large language models (MLLMs) can integrate long visual histories, reason under partial observability, and infer behavior from a few examples. Yet vision-language-action (VLA) models generally inherit pretrained representations without using this contextual capacity as episode memory.

## Related
<!-- [[other-paper-citekey]] -->
