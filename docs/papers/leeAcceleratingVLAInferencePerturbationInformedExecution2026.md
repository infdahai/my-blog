---
citekey: "leeAcceleratingVLAInferencePerturbationInformedExecution2026"
title: "Accelerating VLA Inference with Perturbation Informed Execution"
authors: ["Jehun Lee", "Hajun Lee", "Jimin Ryu", "Youhan Lee", "Beomseok Kang", "Jonghyun Choi", "Jae-Joon Kim"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19656"
doi: "10.48550/arXiv.2610.19656"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Accelerating VLA Inference with Perturbation Informed Execution

> Jehun Lee, Hajun Lee, Jimin Ryu, Youhan Lee, Beomseok Kang, Jonghyun Choi, Jae-Joon Kim · 2026
> [arXiv](https://arxiv.org/abs/2610.19656) · [PDF](https://arxiv.org/pdf/2610.19656)

## Abstract

Action-chunking vision-language-action (VLA) models predict sequences of future robot actions. Under fixed-horizon execution, the robot executes a fixedlength prefix of each predicted chunk before invoking the policy again, leaving the remaining predictions unused. For a given number of executed actions, short execution horizons require more policy calls. Extending the execution horizon amortizes policy inference cost over more actions. However, uniformly applying long horizons across episodes can limit opportunities for precise corrections. To address this limitation, we propose PICES (Perturbation-Informed Chunk and Execution Horizon Selection), a training-free method that jointly selects an action chunk and the number of actions executed before the next policy call. Within a single policy call, the action expert generates a batch of action chunks from multiple initial noise samples and their locally perturbed counterparts, using the same conditioning features across all samples. PICES exploits differences between corresponding actions in each nominal chunk and its counterpart to determine candidate-specific execution horizons and select a nominal chunk for execution. Experiments on simulation benchmarks and real-world manipulation tasks demonstrate that PICES achieves speedup by up to 2.3x in wall-clock policy inference time on Jetson Orin and Thor relative to fixed horizon baselines while improving the success rate.

## TL;DR

Action-chunking vision-language-action (VLA) models predict sequences of future robot actions. Under fixed-horizon execution, the robot executes a fixedlength prefix of each predicted chunk before invoking the policy again, leaving the remaining predictions unused.

## Related
<!-- [[other-paper-citekey]] -->
