---
citekey: "thomasFailureDriftEvaluatingMonocularSLAMSyntheticRealWorld2026"
title: "Failure or Drift? Evaluating Monocular SLAM under Synthetic and Real-World Corruptions"
authors: ["Abhay Skaria Thomas", "Shashank Agnihotri", "Margret Keuper"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.30690"
doi: "10.48550/arXiv.2608.30690"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-04
---

# Failure or Drift? Evaluating Monocular SLAM under Synthetic and Real-World Corruptions

> Abhay Skaria Thomas, Shashank Agnihotri, Margret Keuper · 2026
> [arXiv](https://arxiv.org/abs/2608.30690) · [PDF](https://arxiv.org/pdf/2608.30690)

## Abstract

Visual SLAM is commonly evaluated on clean trajectories, although deployment failures are often caused by adverse weather, illumination, blur, and sensor artifacts. Controlled corruptions are attractive because they isolate such factors, but a synthetic stress test is useful only when it leads to the same engineering conclusion as the condition it is intended to approximate. This work examines that question for monocular SLAM. We evaluate a classical feature-based system and two learned trackers under image-space, geometry-aware, and compound corruptions, and compare their behavior with adverse conditions from 4Seasons. Rather than reducing robustness to a single trajectory error, the evaluation separates explicit tracking failure from drift accumulated by methods that remain active. The results show that learned trackers largely replace catastrophic loss with sustained, and sometimes severe, drift. More importantly, the apparent ordering of the learned systems changes with the physical fidelity of the corruption: structured rain and fog proxies preserve the real-world ordering, whereas a simple illumination proxy does not. Code is available at: https://github.com/abhaythomas/master_thesis_vslamlab_robustness.

## TL;DR

Visual SLAM is commonly evaluated on clean trajectories, although deployment failures are often caused by adverse weather, illumination, blur, and sensor artifacts. Controlled corruptions are attractive because they isolate such factors, but a synthetic stress test is useful only when it leads to the same engineering conclusion as the condition it is intended to approximate.

## Related
<!-- [[other-paper-citekey]] -->
