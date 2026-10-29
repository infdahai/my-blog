---
citekey: "peiFARMReadingFailureSignalsInternalPredictiveStatesFrozen2026"
title: "FARM: Reading Failure Signals from the Internal Predictive States of a Frozen Robotic World Model"
authors: ["Haoran Pei", "Mingrui Luo", "Senbao Wang", "Haoran Lv", "Jie Guo", "Sheng Zhong", "Ruixi Ci"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.11445"
doi: "10.48550/arXiv.2609.11445"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# FARM: Reading Failure Signals from the Internal Predictive States of a Frozen Robotic World Model

> Haoran Pei, Mingrui Luo, Senbao Wang, Haoran Lv, Jie Guo, Sheng Zhong, Ruixi Ci · 2026
> [arXiv](https://arxiv.org/abs/2609.11445) · [PDF](https://arxiv.org/pdf/2609.11445)

## Abstract

Reliable robot deployment requires online failure monitoring, yet existing monitors mainly derive risk from proxy signals or train dedicated monitoring components. We ask whether the internal predictive states of a frozen pretrained robotic world model already contain directly decodable failure information. Failure-Aware Readout from World Models (FARM) trains only a 33,985-parameter supervised readout over frozen VLA-JEPA predictive states, producing step-wise failure scores and causal trajectory risk. Five-fold out-of-fold evaluation across seven source tasks reaches 85.68/88.59 pooled AUROC/AUPRC, and FARM gives the best Seen performance among 15 matched baselines on the 10-task benchmark. Across four real-robot populations on PIPER X, SO-101, and Franka, fixed-readout transfer and readout-only adaptation test deployment shifts without updating the predictive backbone. FARM also discriminates failures from partial causal histories and adds 0.2256 ms mean CUDA latency once the frozen state is available. These results support frozen predictive world-model states as reusable features for causal, transferable, and low-overhead execution monitoring.

## TL;DR

Reliable robot deployment requires online failure monitoring, yet existing monitors mainly derive risk from proxy signals or train dedicated monitoring components. We ask whether the internal predictive states of a frozen pretrained robotic world model already contain directly decodable failure information.

## Related
<!-- [[other-paper-citekey]] -->
