---
citekey: "leeAdaptingVisionLanguageActionModelsUnknownVisualDisruptions2026"
title: "Adapting Vision-Language-Action Models to Unknown Visual Disruptions During Execution"
authors: ["Ahin Lee", "Jinwoo Seo", "Youngsoo Jang", "Taesik Gong"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07946"
doi: "10.48550/arXiv.2610.07946"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# Adapting Vision-Language-Action Models to Unknown Visual Disruptions During Execution

> Ahin Lee, Jinwoo Seo, Youngsoo Jang, Taesik Gong · 2026
> [arXiv](https://arxiv.org/abs/2610.07946) · [PDF](https://arxiv.org/pdf/2610.07946)

## Abstract

Visual disruptions can arise while a robot is executing a task, leaving a vision-language-action (VLA) policy to respond without knowing the disruption type or timing. We introduce Self-supervised Adaptation from Leftover Trajectories (SALT), which uses the leftover trajectory, the unexecuted part of the previous action chunk, as self-supervision for test-time adaptation. Because consecutive chunks overlap in time, the leftover provides a temporally aligned target for the current prediction over the same future control interval. At the onset of a visual shift, the leftover can retain a plan formed before the corruption, so updating the policy toward it anchors the adaptation across the shift (Transition Anchoring). SALT keeps the adapted policy and regenerates the current chunk, whose leftover becomes the target at the next replan, carrying the correction forward along the execution trajectory (Sequential Correction Propagation). Supervision comes entirely from the policy's own predictions, requiring no disruption annotations, expert actions, or target-domain demonstrations, and a lightweight adaptation gate calibrated only on nominal trajectories decides when updates begin. On LIBERO-10, SALT increases average success across five persistent visual corruptions from 43.9% to 53.2% with SmolVLA and from 58.7% to 66.0% with GR00T N1.7, while largely preserving nominal performance. On a real robot, it raises task progress averaged over digital and physical disruptions from 0.49 to 0.61.

## TL;DR

Visual disruptions can arise while a robot is executing a task, leaving a vision-language-action (VLA) policy to respond without knowing the disruption type or timing. We introduce Self-supervised Adaptation from Leftover Trajectories (SALT), which uses the leftover trajectory, the unexecuted part of the previous action chunk, as self-supervision for test-time adaptation.

## Related
<!-- [[other-paper-citekey]] -->
