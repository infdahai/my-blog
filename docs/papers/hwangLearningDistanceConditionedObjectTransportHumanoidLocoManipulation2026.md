---
citekey: "hwangLearningDistanceConditionedObjectTransportHumanoidLocoManipulation2026"
title: "Learning Distance-Conditioned Object Transport for Humanoid Loco-Manipulation from a Single Motion Clip"
authors: ["Yuhyeon Hwang", "Daniel Sungho Jung", "YongHyeok Seo", "Mingi Jung", "Chang Nho Cho", "Jung-Hoon Hwang", "Dongin Shin"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21467"
doi: "10.48550/arXiv.2609.21467"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-21
---

# Learning Distance-Conditioned Object Transport for Humanoid Loco-Manipulation from a Single Motion Clip

> Yuhyeon Hwang, Daniel Sungho Jung, YongHyeok Seo, Mingi Jung, Chang Nho Cho, Jung-Hoon Hwang, Dongin Shin · 2026
> [arXiv](https://arxiv.org/abs/2609.21467) · [PDF](https://arxiv.org/pdf/2609.21467)

## Abstract

Motion tracking can reproduce humanoid loco-manipulation from a single retargeted motion clip, but a policy trained on a fixed reference primarily reproduces its demonstrated transport outcome. Although the source trajectory visits intermediate object displacements, transport termination is demonstrated only at its endpoint. We identify this mismatch as the termination-versus-passage gap: intermediate displacements are observed as passage states rather than termination-complete outcomes. We introduce Distance-Conditioned Reference Recomposition (DCRR), which relocates the demonstrated termination segment to intermediate transport states. A frozen tracking teacher replays the recomposed references under closed-loop dynamics, and the retained trajectories are relabeled by their achieved object placements and distilled into a reference-free policy. This procedure constructs distance-conditioned supervision from the interaction behavior encoded in the source motion. Across Carry, Kick-Push, Crouch-Push, and Drag, DCRR-BC produces command-dependent transport with an overall normalized distance mean absolute error (MAE) of 0.15, compared with 0.28 for source-only behavior cloning. RL fine-tuning further improves the command response and execution robustness in the training simulator and under sim-to-sim transfer. Finally, hardware experiments demonstrate transport-distance modulation across all four interaction modes.

## TL;DR

Motion tracking can reproduce humanoid loco-manipulation from a single retargeted motion clip, but a policy trained on a fixed reference primarily reproduces its demonstrated transport outcome. Although the source trajectory visits intermediate object displacements, transport termination is demonstrated only at its endpoint.

## Related
<!-- [[other-paper-citekey]] -->
