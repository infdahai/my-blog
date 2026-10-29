---
citekey: "changSeeingThroughDisplacedFramePrivilegedNoiseDistillationVision2026"
title: "Seeing Through the Displaced Frame: Privileged Noise Distillation for Vision-Force Precision Assembly"
authors: ["Ching-Hsiang Chang", "Tzu-Yu Chuang", "Yi-Hsiu Lee", "Yi-Ting Chen", "Yuan-Fu Yang", "Min Sun"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07745"
doi: "10.48550/arXiv.2610.07745"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# Seeing Through the Displaced Frame: Privileged Noise Distillation for Vision-Force Precision Assembly

> Ching-Hsiang Chang, Tzu-Yu Chuang, Yi-Hsiu Lee, Yi-Ting Chen, Yuan-Fu Yang, Min Sun · 2026
> [arXiv](https://arxiv.org/abs/2610.07745) · [PDF](https://arxiv.org/pdf/2610.07745)

## Abstract

Pose error in precision assembly can corrupt not only what a robot observes but also the coordinate frame in which it acts. On the FORGE benchmark, the official state-based policy succeeds in 97% to 99% of episodes with the true pose but only 32% to 60% at the benchmark's $\sigma=5$ mm pose-noise setting. The same estimated pose enters the observation and anchors the action frame, making the offset unidentifiable from proprioceptive state alone before contact. We supply this missing information during training in two ways. A privileged teacher observes the offset in simulation, while clean demonstrations can instead be relabelled into the displaced frame in closed form. The deployed student is trained with behaviour cloning followed by one DAgger round and receives only noisy state, a raw wrench window, and two RGB cameras at test time. On the unmodified FORGE tasks, the teacher-route student maintains 92% to 99% success across $\sigma=0$ to 5 mm, while six non-privileged baselines fall to 2% to 80%. A matched behaviour-cloning experiment isolates the source of this robustness. With the same student architecture, data budget, and training procedure, demonstrations generated without offset access yield only 31.5% success at $\sigma=5$ mm, whereas privileged and relabelled demonstrations reach 88.7% and 95.8%. Deployed zero-shot on a Franka, the student reaches 83.3% pooled success at $\sigma=5$ mm against 34.4% for the strongest state-based policy. Deployable sensing alone is insufficient. Robustness requires supervision that encodes compensation for the latent frame offset.Project page: https://drychang.github.io/displaced-frame/

## TL;DR

Pose error in precision assembly can corrupt not only what a robot observes but also the coordinate frame in which it acts. On the FORGE benchmark, the official state-based policy succeeds in 97% to 99% of episodes with the true pose but only 32% to 60% at the benchmark's $\sigma=5$ mm pose-noise setting.

## Related
<!-- [[other-paper-citekey]] -->
