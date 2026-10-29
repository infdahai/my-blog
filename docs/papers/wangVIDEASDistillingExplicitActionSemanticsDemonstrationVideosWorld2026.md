---
citekey: "wangVIDEASDistillingExplicitActionSemanticsDemonstrationVideosWorld2026"
title: "VIDEAS: Distilling Explicit Action Semantics from Demonstration Videos for World Models via Prior-Guided Simulation"
authors: ["Jianan Wang", "Haoquan Zhai", "Siyang Zhang", "Bin Li", "Juan Chen", "Jingtao Qi", "Zhuo Zhang", "Enze Wang", "Haoxiang Jin", "Chen Qian"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.33464"
doi: "10.48550/arXiv.2609.33464"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# VIDEAS: Distilling Explicit Action Semantics from Demonstration Videos for World Models via Prior-Guided Simulation

> Jianan Wang, Haoquan Zhai, Siyang Zhang, Bin Li, Juan Chen, Jingtao Qi, Zhuo Zhang, Enze Wang, Haoxiang Jin, Chen Qian · 2026
> [arXiv](https://arxiv.org/abs/2609.33464) · [PDF](https://arxiv.org/pdf/2609.33464)

## Abstract

World models learn internal representations of environment dynamics to predict future states, enabling agents to optimize action plans without physical interactions. However, developing world models that genuinely internalize underlying causal physical laws to explicitly reason about action preconditions and subsequent state transitions remains an open challenge. In this paper, we propose VIDEAS, a data distillation framework that transforms continuous physical dynamics from operational videos into explicit action semantics for foundation models. Specifically, it deconstructs visual demonstrations into discrete action trajectories and utilizes advanced vision-language models (VLMs) to extract structured knowledge encapsulating action preconditions and effects. To ensure physical consistency, we introduce a prior-guided trajectory simulation mechanism grounded within a text-based environment to rigorously validate the extracted knowledge. Notably, we incorporate negative trajectories to enrich knowledge completeness and enhance data diversity to mitigate cognitive bias. Furthermore, we present VIDEAS-WM, an 8B/9B-parameter suite of language-based world models trained on 34K high-quality samples derived from AgiBot-World dataset. Extensive experiments demonstrate that VIDEAS-WM establishes state-of-the-art performance in high-level embodied action semantic reasoning, exhibiting profound physical understanding and robust generalization across unseen scenarios.

## TL;DR

World models learn internal representations of environment dynamics to predict future states, enabling agents to optimize action plans without physical interactions. However, developing world models that genuinely internalize underlying causal physical laws to explicitly reason about action preconditions and subsequent state transitions remains an open challenge.

## Related
<!-- [[other-paper-citekey]] -->
