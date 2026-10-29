---
citekey: "liTacGooseBumpsTacGBRetrofittingNormalOnlyTactileSensorsShear2026"
title: "TacGooseBumps (TacGB): Retrofitting Normal-Only Tactile Sensors with Shear Encoding for Learning Contact-Rich Manipulation"
authors: ["Wenjie Li", "Binyu Yang", "Yuxin Chen", "Ambrose Wang", "Masayoshi Tomizuka"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.34006"
doi: "10.48550/arXiv.2609.34006"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# TacGooseBumps (TacGB): Retrofitting Normal-Only Tactile Sensors with Shear Encoding for Learning Contact-Rich Manipulation

> Wenjie Li, Binyu Yang, Yuxin Chen, Ambrose Wang, Masayoshi Tomizuka · 2026
> [arXiv](https://arxiv.org/abs/2609.34006) · [PDF](https://arxiv.org/pdf/2609.34006)

## Abstract

Contact-rich policies often fail because distinct physical states look alike yet require different actions. Cameras may not reveal whether a connector is aligned or fully seated, while many normal-only tactile sensors can miss the tangential interactions perpendicular to the grasping direction that distinguish these states. We ask whether a learning policy needs calibrated shear measurements, or only a repeatable observation that separates shear-dependent contact states. We introduce TacGooseBumps (TacGB), a passive domed film that mechanically encodes tangential loading as pattern changes in an existing sensor's pressure map. Tangential loading tilts each dome and redistributes pressure across its footprint; an end-to-end policy consumes the resulting maps without added electronics, force reconstruction, or taxel-level dome alignment. Across four imitation-learning tasks and two data-collection pipelines, TacGB improves goal attainment, efficiency, and contact quality: insertion success increases by up to 36 percentage points, and successful insertions are completed faster, while fragile-object placement becomes gentler and drawing becomes more continuous and straight. Signal, stage-wise, failure-mode, and trajectory analyses link these gains to contact regimes in which task-relevant tangential interactions are poorly resolved by vision and normal pressure alone. Together, these results show that shear need not be measured metrically to benefit robot learning; it can instead be mechanically encoded without changing the underlying tactile sensor or the policy's pressure-map input format.

## TL;DR

Contact-rich policies often fail because distinct physical states look alike yet require different actions. Cameras may not reveal whether a connector is aligned or fully seated, while many normal-only tactile sensors can miss the tangential interactions perpendicular to the grasping direction that distinguish these states.

## Related
<!-- [[other-paper-citekey]] -->
