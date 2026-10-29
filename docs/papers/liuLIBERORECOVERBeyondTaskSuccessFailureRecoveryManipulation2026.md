---
citekey: "liuLIBERORECOVERBeyondTaskSuccessFailureRecoveryManipulation2026"
title: "LIBERO-RECOVER: Beyond Task Success Towards Failure Recovery in Robotic Manipulation Models"
authors: ["Lin Liu", "Zhicheng Bao", "Lu Zhang", "Ziying Song", "Wu Yang", "Shuai Tao", "Wulong Liu", "Huchuan Lu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.05178"
doi: "10.48550/arXiv.2609.05178"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-08
---

# LIBERO-RECOVER: Beyond Task Success Towards Failure Recovery in Robotic Manipulation Models

> Lin Liu, Zhicheng Bao, Lu Zhang, Ziying Song, Wu Yang, Shuai Tao, Wulong Liu, Huchuan Lu · 2026
> [arXiv](https://arxiv.org/abs/2609.05178) · [PDF](https://arxiv.org/pdf/2609.05178)

## Abstract

Vision-Language-Action (VLA) or World Action (WAM) models have recently demonstrated remarkable performance in robotic manipulation. On LIBERO, SOTA method have achieved nearly 100\% success rates, seemingly suggesting that the models are ready for deployment in real world. However, near perfect performance on existing benchmarks can be misleading: success under ideal conditions does not imply real world robustness. Existing benchmarks primarily evaluate task completion from predefined initial states, while real world interactions inevitably involve failures such as failed grasps, collisions, and unintended object movements. A robot must therefore not only execute tasks successfully, but also recognize and recover from failures to continue the task. Yet this capability remains largely unmeasured, revealing a critical gap between benchmark performance and real world reliability. To address this gap, we introduce LIBERO-Recover Benchmark, a large scale benchmark for failure recovery in robotic manipulation. Built upon LIBERO, we collect real execution failures from SOTA embodied models and construct 1,000+ scenarios across four recovery levels: (1) Action Retry, (2) Action Adaptation, (3) Object State Recovery, and (4) Environmental Recovery. We evaluate four core capabilities: spatial understanding, object structure reasoning, interaction understanding, and topological reasoning. As the first large-scale benchmark for embodied failure recovery, LIBERO-Recover shifts evaluation from \emph{Can the robot succeed?''} to \emph{Can the robot recover after failure?''}, promoting robust and generalizable embodied agents. The project will be avaible in \textcolor{blue}{https://liulin815.github.io/LIBERO-Recovery/}.

## TL;DR

Vision-Language-Action (VLA) or World Action (WAM) models have recently demonstrated remarkable performance in robotic manipulation. On LIBERO, SOTA method have achieved nearly 100\% success rates, seemingly suggesting that the models are ready for deployment in real world.

## Related
<!-- [[other-paper-citekey]] -->
