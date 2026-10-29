---
citekey: "liReactHumanPhysicsGroundedBenchmarkHumanLikeReactiveDecision2026"
title: "ReactHuman: A Physics-Grounded Benchmark for Human-Like Reactive Decision-Making in Embodied Multimodal LLMs"
authors: ["Yizhan Li", "Jianxin You", "Mengyang Xiong", "Yinhuan Chen", "Zicheng Zhao", "Dekun Wu", "Dongqing Zhang", "Bang Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.10895"
doi: "10.48550/arXiv.2609.10895"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# ReactHuman: A Physics-Grounded Benchmark for Human-Like Reactive Decision-Making in Embodied Multimodal LLMs

> Yizhan Li, Jianxin You, Mengyang Xiong, Yinhuan Chen, Zicheng Zhao, Dekun Wu, Dongqing Zhang, Bang Liu · 2026
> [arXiv](https://arxiv.org/abs/2609.10895) · [PDF](https://arxiv.org/pdf/2609.10895)

## Abstract

Reacting to sudden physical hazards (catching a slipping plate, dodging a falling knife) is both a meaningful test of embodied intelligence and a hard requirement for deploying multimodal large language models (MLLMs) as the decision coreof household robots. Existing evaluations, however, probe intuitive physics passively through question answering over videos, or target deliberate, long-horizon tasks such as navigation and rearrangement; none measure whether a model can turn physical understanding into immediate, safety-critical action. We introduce ReactHuman, the first physics-grounded benchmark for human-like reactive decision-making, in which the evaluated MLLM acts as the brain of a simulated humanoid facing sudden household hazards; it spans 17 event families and over 1,000 bit-for-bit reproducible scenes with exact, annotation-free ground truth derived from 240 Hz rigid-body simulation, including adversarial objects whose appearance contradicts their physics (a foam anvil, a steel apple). We further design a five-metric suite that scores each reaction along three axes: reasonable, safe, and physically grounded. We physically execute every committed plan so that decisions have observable consequences. With this harness we evaluate seven representative MLLMs. Results show that reactive safety is far from solved: models mishandle roughly one hazard in three, act from fixed dispositions rather than the observed scene, trust appearance over motion, and miss interception points at meter scale even when the chosen action is correct; none of these failures shrink with model scale. ReactHuman thus offers both a fine-grained diagnosis and a scalable training signal toward physically grounded, safety-aware embodied agents. The benchmark can be found here: https://huggingface.co/datasets/Alan123/reacthuman-benchmark-scaled

## TL;DR

Reacting to sudden physical hazards (catching a slipping plate, dodging a falling knife) is both a meaningful test of embodied intelligence and a hard requirement for deploying multimodal large language models (MLLMs) as the decision coreof household robots. Existing evaluations, however, probe intuitive physics passively through question answering over videos, or target deliberate, long-horizon tasks such as navigation and rearrangement; none measure whether a model can turn physical understanding into immediate, safety-critical action.

## Related
<!-- [[other-paper-citekey]] -->
