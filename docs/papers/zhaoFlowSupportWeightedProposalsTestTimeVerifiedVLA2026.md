---
citekey: "zhaoFlowSupportWeightedProposalsTestTimeVerifiedVLA2026"
title: "Flow-Support-Weighted Proposals for Test-Time Verified VLA Policies"
authors: ["Chen Zhao", "Zipeng Ye", "Haitao Shen", "Guanlin Li", "Yuchen Xie", "Jing Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14588"
doi: "10.48550/arXiv.2610.14588"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# Flow-Support-Weighted Proposals for Test-Time Verified VLA Policies

> Chen Zhao, Zipeng Ye, Haitao Shen, Guanlin Li, Yuchen Xie, Jing Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.14588) · [PDF](https://arxiv.org/pdf/2610.14588)

## Abstract

Test-time sampling promises to turn one action prediction into a set of distinct executable candidates that a verifier can choose among. Downstream fine-tuning works against that promise. A vision-language-action model trained to solve one task distribution concentrates its flow-matching decoder around the dominant demonstrated action, so repeated samples differ only marginally and the verifier receives many copies of one decision. We call this proposal contraction and identify it as a key constraint on test-time scaling: repeated samples can remain highly redundant as the candidate budget grows. Action Dynamic Sampling (ADS) alleviates the constraint on the proposal side, during training. At each training step, ADS integrates $K$ additional trajectories from the current policy under fresh base noise, scores each by the flow support along its path with a Hutchinson trace estimator, and corrects the policy's local action distribution toward this weighted set through a detached finite-set KL term. Training cost rises; deployment cost is unchanged. Across simulation and four physical-robot tasks, ADS raises proposal spread without the success penalty that Gaussian perturbation incurs, lifts oracle best-of-8 success on RoboCasa from 57.6% to 63.0%, improves fixed verifiers by 2.4 to 4.9 points in simulation, and raises TokenPB by up to 13.0 points on real-world manipulation.

## TL;DR

Test-time sampling promises to turn one action prediction into a set of distinct executable candidates that a verifier can choose among. Downstream fine-tuning works against that promise.

## Related
<!-- [[other-paper-citekey]] -->
