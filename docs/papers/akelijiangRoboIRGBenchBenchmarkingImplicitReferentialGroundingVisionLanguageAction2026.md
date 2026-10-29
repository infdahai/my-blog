---
citekey: "akelijiangRoboIRGBenchBenchmarkingImplicitReferentialGroundingVisionLanguageAction2026"
title: "RoboIRGBench: Benchmarking Implicit Referential Grounding in Vision-Language-Action Models"
authors: ["Aernaer Akelijiang", "Jiannan Li", "Zhineng Chen", "Jingjing Chen", "Bin Zhu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.34384"
doi: "10.48550/arXiv.2609.34384"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# RoboIRGBench: Benchmarking Implicit Referential Grounding in Vision-Language-Action Models

> Aernaer Akelijiang, Jiannan Li, Zhineng Chen, Jingjing Chen, Bin Zhu · 2026
> [arXiv](https://arxiv.org/abs/2609.34384) · [PDF](https://arxiv.org/pdf/2609.34384)

## Abstract

Vision-Language-Action (VLA) models have shown strong capabilities in robotic manipulation, yet existing benchmarks typically assume that task-relevant information is explicitly specified in the instruction. In practice, however, humans frequently refer to objects, quantities, and relations implicitly, requiring robots to recover the intended target from linguistic and perceptual context. We study this capability as Implicit Referential Grounding (IRG) and introduce RoboIRG-Bench, a manipulation benchmark designed to systematically evaluate it. Built upon RoboMME, RoboIRG-Bench contains 40 variants derived from 11 tasks and covers four challenges, including direct, reasoning-mediated, spatial, and contextual referential grounding. As IRG often requires retaining and retrieving previously established context, we evaluate representative VLAs spanning different memory mechanisms. Our evaluation reveals a noticeable referential robustness gap. Models that perform well under explicit instructions can degrade sharply when the same task-relevant information must be recovered from context. Reasoning-mediated and spatial references are particularly challenging, while models using external VLMs show greater robustness but still exhibit significant failures. Moreover, replacing the external VLM with a stronger model does not eliminate these gaps. We further validate these findings on a Franka Research 3 robot arm, where the gap persists under real-world manipulation and manifests as both incorrect referent grounding and downstream execution failures. These results establish IRG as a distinct and underexplored capability for reliable robotic instruction following and highlight the need for VLAs that can robustly integrate language, perception, reasoning, and action.

## TL;DR

Vision-Language-Action (VLA) models have shown strong capabilities in robotic manipulation, yet existing benchmarks typically assume that task-relevant information is explicitly specified in the instruction. In practice, however, humans frequently refer to objects, quantities, and relations implicitly, requiring robots to recover the intended target from linguistic and perceptual context.

## Related
<!-- [[other-paper-citekey]] -->
