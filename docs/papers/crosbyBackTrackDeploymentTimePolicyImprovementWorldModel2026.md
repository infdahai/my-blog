---
citekey: "crosbyBackTrackDeploymentTimePolicyImprovementWorldModel2026"
title: "Back on Track: Deployment-time Policy Improvement via World Model Planning"
authors: ["Colton Crosby", "Hao Wang", "Mac Schwager", "Somil Bansal"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19579"
doi: "10.48550/arXiv.2610.19579"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Back on Track: Deployment-time Policy Improvement via World Model Planning

> Colton Crosby, Hao Wang, Mac Schwager, Somil Bansal · 2026
> [arXiv](https://arxiv.org/abs/2610.19579) · [PDF](https://arxiv.org/pdf/2610.19579)

## Abstract

State-of-the-art visuomotor policies are increasingly capable of executing complex tasks, yet can fail during deployment in ways they cannot predict or recover from on their own. Improving their performance and robustness typically requires collecting more data, retraining, or modifying the policy architecture, all of which are time- and resource-intensive in practice. We instead propose an offline-trained monitoring-and-intervention framework that improves a policy during deployment using only black-box query access. From a limited set of labeled on-policy rollouts, we learn a policy-conditioned liveness value that measures the nominal policy's progress toward task completion; we additionally train a compact latent world model using these rollouts together with play data. At deployment, the liveness value continuously monitors execution. When it detects a loss of progress, a short-horizon planner searches the world model for corrective actions using the same value as its planning objective, after which control returns to the nominal policy. We evaluate our method on the LIBERO-Goal task suite and on a Franka Panda manipulator, using the vision-language-action model $\pi_{0.5}$ and a diffusion policy as nominal policies, and demonstrate significant improvements in task success rates, while supporting real-time control. Additional results and videos are available on the project website (https://policy-improvement-wm.pages.dev/).

## TL;DR

State-of-the-art visuomotor policies are increasingly capable of executing complex tasks, yet can fail during deployment in ways they cannot predict or recover from on their own. Improving their performance and robustness typically requires collecting more data, retraining, or modifying the policy architecture, all of which are time- and resource-intensive in practice.

## Related
<!-- [[other-paper-citekey]] -->
