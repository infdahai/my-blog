---
citekey: "wuGatedResidualBodyHandCoordinationWholeBodyHumanoid2026"
title: "Gated Residual Body-Hand Coordination for Whole-Body Humanoid Teleoperation"
authors: ["Ruiming Wu", "Shuang Li", "Liding Zhang", "Alois Knoll", "Zhaopeng Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.18763"
doi: "10.48550/arXiv.2609.18763"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-18
---

# Gated Residual Body-Hand Coordination for Whole-Body Humanoid Teleoperation

> Ruiming Wu, Shuang Li, Liding Zhang, Alois Knoll, Zhaopeng Chen · 2026
> [arXiv](https://arxiv.org/abs/2609.18763) · [PDF](https://arxiv.org/pdf/2609.18763)

## Abstract

Whole-body humanoid teleoperation commonly combines a motion-tracking policy with a separate dexterous-hand retargeter. However, independently generated commands do not explicitly preserve body-hand geometric relations, leading to mismatches in relative wrist poses and fingertip positions during bimanual interaction. We present a gated residual coordination framework that keeps both modules frozen and applies bounded corrections to their outputs. A motion-conditioned action gate allocates correction authority across joint groups, while reference-geometry-dependent reward gates emphasize relevant interaction objectives during training. To establish the nominal body controller on Agile One, we introduce multi-pose morphology calibration that jointly estimates triaxial scales and effector-local offsets, together with staged motion dataset curation for training a SONIC-based tracker. The residual policy uses human motion references, initial commands, and robot proprioception without explicit object or contact observations. In simulation, it reduces wrist and fingertip geometry errors by 39.2-56.3% over direct composition on held-out GRAB motions, while preserving whole-body tracking on AMASS, with success rates of 89.03% without residual coordination and 89.29% with it. Ablations characterize the contributions of reward gating, adaptive correction authority, and separate body and hand correction heads.

## TL;DR

Whole-body humanoid teleoperation commonly combines a motion-tracking policy with a separate dexterous-hand retargeter. However, independently generated commands do not explicitly preserve body-hand geometric relations, leading to mismatches in relative wrist poses and fingertip positions during bimanual interaction.

## Related
<!-- [[other-paper-citekey]] -->
