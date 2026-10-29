---
citekey: "ioannidisPriMoRetargetHumanoidMotionTransferThroughPrioritizedMotionRetargeting2026"
title: "PriMoRetarget: Humanoid Motion Transfer Through Prioritized Motion Retargeting"
authors: ["Nicholas Ioannidis", "Dun Yang", "Max Smith", "Tue Vu", "Ziyu Zhang", "Shayegan Omidshafiei", "Xue Bin Peng"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12642"
doi: "10.48550/arXiv.2610.12642"
tags: [paper, embodied-ai, "cs.GR", "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# PriMoRetarget: Humanoid Motion Transfer Through Prioritized Motion Retargeting

> Nicholas Ioannidis, Dun Yang, Max Smith, Tue Vu, Ziyu Zhang, Shayegan Omidshafiei, Xue Bin Peng · 2026
> [arXiv](https://arxiv.org/abs/2610.12642) · [PDF](https://arxiv.org/pdf/2610.12642)

## Abstract

Motion retargeting is a critical preprocessing step for transferring human motion data to humanoid robots. While existing methods are effective for single-character motions, interactions involving multiple characters and objects introduce additional contacts and spatial relationships that must be preserved. Retargeting is commonly formulated as a weighted multi-objective optimization problem, where conflicting objectives can require careful tuning of relative weights and can still compromise important motion characteristics. We introduce PriMoRetarget, a prioritized motion-retargeting framework that replaces relative objective weighting with an explicit priority hierarchy. Lower-priority updates are constrained to preserve higher-priority objectives, allowing critical characteristics such as foot placement and interaction contacts to take precedence over lower-priority pose objectives. The method is evaluated on four datasets spanning single-character motion, character-object manipulation, and character-character interactions. The resulting motions better preserve task-relevant interactions and provide reference trajectories that can be tracked more reliably than those produced by widely used retargeting methods.

## TL;DR

Motion retargeting is a critical preprocessing step for transferring human motion data to humanoid robots. While existing methods are effective for single-character motions, interactions involving multiple characters and objects introduce additional contacts and spatial relationships that must be preserved.

## Related
<!-- [[other-paper-citekey]] -->
