---
citekey: "liuGettingOutGettingBackWorldBehaviorGroundingReal2Sim2Real2026"
title: "Getting Out and Getting Back: World and Behavior Grounding in Real2Sim2Real Co-Training"
authors: ["Samuel Liu", "Youngsun Kim", "Martin Matak", "Gilwoo Lee"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00821"
doi: "10.48550/arXiv.2610.00821"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Getting Out and Getting Back: World and Behavior Grounding in Real2Sim2Real Co-Training

> Samuel Liu, Youngsun Kim, Martin Matak, Gilwoo Lee · 2026
> [arXiv](https://arxiv.org/abs/2610.00821) · [PDF](https://arxiv.org/pdf/2610.00821)

## Abstract

Simulation can expand scarce real demonstrations for co-training, yet how world fidelity and similarity to human behavior affect policy performance remains unclear. We distinguish world grounding, which aligns simulation with the real system, and behavior grounding, which aligns simulated trajectories with human motion. We build a real2sim2real pipeline that varies these axes independently to generate data for co-training. On a dynamic dexterous pick-and-sort task, fully grounded co-training raises success from 52% to 86%; averaged across configurations, world grounding improves success by 18 percentage points and behavior grounding by 10. Deployed policies behave like a mixture of real-derived and simulation-derived policies, imitating real demonstrations in covered states and relying on simulated behavior elsewhere, which we examine through latent-space analysis. Together, these results suggest complementary roles: world grounding lets policies use simulated experience beyond real-data coverage, while behavior grounding matters mainly when world grounding is imperfect. Grounded simulation remains beneficial when co-training foundation models.

## TL;DR

Simulation can expand scarce real demonstrations for co-training, yet how world fidelity and similarity to human behavior affect policy performance remains unclear. We distinguish world grounding, which aligns simulation with the real system, and behavior grounding, which aligns simulated trajectories with human motion.

## Related
<!-- [[other-paper-citekey]] -->
