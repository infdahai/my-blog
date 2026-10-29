---
citekey: "parkDELTADeformableElevationBasedLocalTerrainAttentionEncoder2026"
title: "DELTA: Deformable Elevation-Based Local Terrain Attention Encoder for Sparse-Terrain Quadrupedal Locomotion"
authors: ["Sanghyun Park", "Moonkyu Jung", "Jemin Hwangbo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.22033"
doi: "10.48550/arXiv.2608.22033"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# DELTA: Deformable Elevation-Based Local Terrain Attention Encoder for Sparse-Terrain Quadrupedal Locomotion

> Sanghyun Park, Moonkyu Jung, Jemin Hwangbo · 2026
> [arXiv](https://arxiv.org/abs/2608.22033) · [PDF](https://arxiv.org/pdf/2608.22033)

## Abstract

Stable quadrupedal locomotion on sparse terrain requires selecting state-relevant terrain evidence for precise foot placement. Model-based foothold planners provide precise foothold selection but rely heavily on explicit model assumptions. Recent attention-based map encoding (AME) studies show that end-to-end reinforcement learning (RL) can learn implicit foothold guidance. However, the computational cost of dense AME encoding grows with map resolution, limiting its scalability to fine-grained sparse terrain. We propose DELTA, a Deformable Elevation-Based Local Terrain Attention encoder. DELTA predicts state-conditioned sampling locations, forms terrain evidence tokens from adaptive local elevation patches, and attends only to a fixed-size token set. With fixed sampling and patch settings, DELTA's encoder cost is independent of map resolution. Experiments show that DELTA achieves final traversal performance comparable to AME at the standard resolution while improving learning efficiency. This fixed encoder cost enables the use of higher-resolution terrain maps, improving traversal on fine-grained sparse terrain. DELTA also demonstrates strong generalization to unseen mixed evaluation courses composed of continuous and discrete terrain elements. Beyond simulation, DELTA demonstrates successful sim-to-real transfer on RAIBO2. Analysis of the learned sampling offsets and attention weights shows that DELTA samples steppable regions and attends to terrain evidence relevant to future touchdowns without foothold labels or attention supervision.

## TL;DR

Stable quadrupedal locomotion on sparse terrain requires selecting state-relevant terrain evidence for precise foot placement. Model-based foothold planners provide precise foothold selection but rely heavily on explicit model assumptions.

## Related
<!-- [[other-paper-citekey]] -->
