---
citekey: "renTokensMotionPrimitiveMotionLearningHumanHumanoidSkill2026"
title: "Tokens of Motion: Primitive Motion Learning for Human-Humanoid Skill Transfer"
authors: ["Hanwen Ren", "Meng Zheng", "Wenzhe Cui", "Benjamin Planche", "Zhongpai Gao", "Anwesa Choudhuri", "Terrence Chen", "Ziyan Wu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.37330"
doi: "10.48550/arXiv.2610.37330"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# Tokens of Motion: Primitive Motion Learning for Human-Humanoid Skill Transfer

> Hanwen Ren, Meng Zheng, Wenzhe Cui, Benjamin Planche, Zhongpai Gao, Anwesa Choudhuri, Terrence Chen, Ziyan Wu · 2026
> [arXiv](https://arxiv.org/abs/2610.37330) · [PDF](https://arxiv.org/pdf/2610.37330)

## Abstract

Vision-language-action (VLA) models provide a promising paradigm for scalable robotic manipulation, yet their reliance on success-only behavioral cloning leaves them brittle; lacking corrective training signals, minor execution errors rapidly compound into unrecoverable, out-of-distribution failures. To address this limitation, we propose Adaptive Failure-Informed Learning (AFIL), an end-to-end framework that leverages failure trajectories as adaptive negative guidance for diffusion- and flow-based VLA policies. AFIL uses a pretrained VLA to generate failure rollouts online, avoiding the need for handcrafted failure-mode design or human-in-the-loop recovery. It then jointly trains Dual Action Generators (DAGs) for successful and failed behaviors while sharing a common vision-language backbone, enabling efficient failure-aware policy learning with limited parameter overhead. During sampling, the failure generator adaptively steers action generation away from failure-prone regions and toward more reliable success modes, with guidance strength determined by the per-diffusion-step distance between success and failure distributions. Experiments across in-domain and out-of-domain robotic manipulation tasks, covering both short- and long-horizon settings, show that AFIL consistently improves task success rates and robustness over existing VLA baselines, demonstrating its effectiveness, efficiency, and generality.

## TL;DR

Vision-language-action (VLA) models provide a promising paradigm for scalable robotic manipulation, yet their reliance on success-only behavioral cloning leaves them brittle; lacking corrective training signals, minor execution errors rapidly compound into unrecoverable, out-of-distribution failures. To address this limitation, we propose Adaptive Failure-Informed Learning (AFIL), an end-to-end framework that leverages failure trajectories as adaptive negative guidance for diffusion- and flow-based VLA policies.

## Related
<!-- [[other-paper-citekey]] -->
