---
citekey: "lanTRACEEfficientTransferLearningNeuralWholeBodyControl2026"
title: "TRACE: Efficient Transfer Learning for Neural Whole-Body Control Across Humanoid Embodiments"
authors: ["Qingyu Lan", "Zhihao Tian", "Zifan Wang", "Junwei Liang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.17999"
doi: "10.48550/arXiv.2610.17999"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# TRACE: Efficient Transfer Learning for Neural Whole-Body Control Across Humanoid Embodiments

> Qingyu Lan, Zhihao Tian, Zifan Wang, Junwei Liang · 2026
> [arXiv](https://arxiv.org/abs/2610.17999) · [PDF](https://arxiv.org/pdf/2610.17999)

## Abstract

Humanoid behavior foundation models (BFMs) enable diverse whole-body control, but adapting a pretrained controller to a new embodiment remains challenging because of kinematic and dynamic mismatch. We present TRACE, a framework for efficient cross-embodiment adaptation that preserves pretrained motion representations while specializing feedback control to the target robot.TRACE first injects kinematic priors into input and output projection layers and aligns nominal joint dynamics to reduce embodiment mismatch and support stable fine-tuning. It then combines encoder distillation with low-rank reinforcement learning on a compact, quality-screened motion set, using a two-phase curriculum to establish stable tracking before refining difficult motions. We apply TRACE to transfer SONIC from Unitree G1 to Unitree H2 using 10 million motion frames and approximately eight hours of training on a single RTX PRO 6000 GPU, at less than 0.1% of the GPU-hour cost of training SONIC from scratch. The adapted controller achieves 96.08\% success on 67,953 evaluation motions under a height-scaled tracking criterion. Real-robot demonstrations span dynamic motion tracking and whole-body teleoperation, with collected demonstrations supporting downstream vision-language-action policy post-training. These results demonstrate practical reuse of a pretrained humanoid controller across robots with different body scales and dynamics.

## TL;DR

Humanoid behavior foundation models (BFMs) enable diverse whole-body control, but adapting a pretrained controller to a new embodiment remains challenging because of kinematic and dynamic mismatch. We present TRACE, a framework for efficient cross-embodiment adaptation that preserves pretrained motion representations while specializing feedback control to the target robot.TRACE first injects kinematic priors into input and output projection layers and aligns nominal joint dynamics to reduce embodiment mismatch and support stable fine-tuning.

## Related
<!-- [[other-paper-citekey]] -->
