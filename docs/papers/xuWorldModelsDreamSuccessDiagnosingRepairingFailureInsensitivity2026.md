---
citekey: "xuWorldModelsDreamSuccessDiagnosingRepairingFailureInsensitivity2026"
title: "World Models Dream of Success: Diagnosing and Repairing Failure Insensitivity in Robot World Models"
authors: ["Jiuyi Xu", "Xiao Hu", "Meida Chen", "Peng Gao", "Yang Ye", "Yangming Shi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09134"
doi: "10.48550/arXiv.2610.09134"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# World Models Dream of Success: Diagnosing and Repairing Failure Insensitivity in Robot World Models

> Jiuyi Xu, Xiao Hu, Meida Chen, Peng Gao, Yang Ye, Yangming Shi · 2026
> [arXiv](https://arxiv.org/abs/2610.09134) · [PDF](https://arxiv.org/pdf/2610.09134)

## Abstract

Robot world models support policy evaluation, planning, and synthetic data generation, but these applications require predictions that distinguish successful actions from failures. Across four released checkpoints from two architecture families, we observe weak sensitivity to action changes and success-like predictions on verified failures. Although recent work incorporates failures into model training, which data can repair released checkpoints without changing their architecture or training objective still remains underexplored. To this end, we introduce CureWM, which constructs alternative actions from successful demonstrations across a severity grid, verifies their outcomes through execution in simulation or on hardware, and fine-tunes released models on the resulting failures and surviving successes alongside nominal demonstrations. This construction provides controlled action contrasts from shared starting contexts. On 484 held-out LIBERO failure counterfactuals, optimism falls from 80\% after fine-tuning on the official data to 30--43\% across four independently fine-tuned CureWM models (38\% mean). In two separate evaluations on a physical robot arm, failure predictions scored as success-like by a latent-distance diagnostic decrease from 90\% after fine-tuning on successful demonstrations alone to 33\% with CureWM. With failure counts per task, successful replay data, and training budget matched, counterfactual failures yield a success--failure value gap of 0.124, compared with 0.014 for freshly collected on-policy failures. These findings support execution-verified counterfactual replay for post-hoc repair and show why reduced optimism must be evaluated alongside success--failure discrimination. Code is available at https://github.com/jiuyixu25/CureWM.

## TL;DR

Robot world models support policy evaluation, planning, and synthetic data generation, but these applications require predictions that distinguish successful actions from failures. Across four released checkpoints from two architecture families, we observe weak sensitivity to action changes and success-like predictions on verified failures.

## Related
<!-- [[other-paper-citekey]] -->
