---
citekey: "hanEmbodimentClassifierGuidanceTransferringFrozenVLAsDynamicsWithout2026"
title: "Embodiment-Classifier Guidance: Transferring Frozen VLAs Across Robot Dynamics without Demonstrations"
authors: ["Devin Han", "Hershraj Niranjani"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.22576"
doi: "10.48550/arXiv.2610.22576"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-19
---

# Embodiment-Classifier Guidance: Transferring Frozen VLAs Across Robot Dynamics without Demonstrations

> Devin Han, Hershraj Niranjani · 2026
> [arXiv](https://arxiv.org/abs/2610.22576) · [PDF](https://arxiv.org/pdf/2610.22576)

## Abstract

Flow-based policies such as $π_0$ are trained on a fixed set of embodiments, and transferring them to new ones is an open problem. To adapt a frozen $π_0$ to a new embodiment without additional demonstrations or parameter updates, we train a lightweight embodiment classifier to distinguish successful action chunks on the source body from those on the target body, using a few calibration tasks. On transfer tasks that $π_0$ saw on its source body but the classifier was never trained on, we nudge each denoising step of $π_0$ with the classifier's gradient, which estimates the direction from the distribution of successful actions on the source body toward that on the target body. On the LIBERO simulation benchmark with four modified controllers, embodiment-classifier guidance raises $π_0$'s average success on the target bodies from 72% to 80% across 12 suite-controller pairs, with a 31% relative reduction in failures (11 of 12 gain; 5 significant after Holm correction). In simulation, guidance is data-efficient, needing few target-body rollouts per task, which makes it promising for sim-to-real transfer, where rollouts are costly. Guidance is mixed on weak wrists and harmful on a locked wrist, when the classifier lacks data or favors infeasible motions. Collecting more target-body data with guided $π_0$ can fill such gaps: on one weak-wrist arm, guided $π_0$ solved a task on which unguided $π_0$ had zero successes in the original data, and retraining the classifier on the guided successes raised success from 52.5% to 70.7%.

## TL;DR

Flow-based policies such as $π_0$ are trained on a fixed set of embodiments, and transferring them to new ones is an open problem. To adapt a frozen $π_0$ to a new embodiment without additional demonstrations or parameter updates, we train a lightweight embodiment classifier to distinguish successful action chunks on the source body from those on the target body, using a few calibration tasks.

## Related
<!-- [[other-paper-citekey]] -->
