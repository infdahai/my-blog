---
citekey: "pengRoboCodeLearningReusableActionPrimitivesManipulation2026"
title: "RoboCode: Learning Reusable Action Primitives for Robot Manipulation"
authors: ["Xianyue Peng", "Devi Amarsaikhan", "Iman Soltani"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.32225"
doi: "10.48550/arXiv.2610.32225"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# RoboCode: Learning Reusable Action Primitives for Robot Manipulation

> Xianyue Peng, Devi Amarsaikhan, Iman Soltani · 2026
> [arXiv](https://arxiv.org/abs/2610.32225) · [PDF](https://arxiv.org/pdf/2610.32225)

## Abstract

Recent robot manipulation policies commonly predict continuous action chunks directly from observations, without explicitly modeling reusable structure in the action space. However, manipulation demonstrations often contain recurring short-horizon motion patterns that are shared across tasks. We introduce \textsc{RoboCode}, which learns these patterns through a shared soft-gated primitive action interface. Rather than assigning each action chunk to a single discrete code, \textsc{RoboCode} represents it as a soft composition of multiple learned primitives, providing a flexible intermediate representation of short-horizon actions. The primitive interface is learned from action chunks pooled across multiple tasks and then frozen while task-specific state encoders are trained to map current state inputs into the shared latent space. Experiments on five ManiSkill manipulation tasks address three questions. First, the learned primitive interface reconstructs action chunks with an average reconstruction MSE of 0.0187. Second, analysis of code activations reveals structured code reuse across tasks. Third, \textsc{RoboCode} achieves the highest or tied closed-loop success rate on all evaluated tasks, with an average success rate of 75.6%, compared with 68.8% for ACT and 41.6% for the larger Diffusion Policy baseline. These results suggest that soft-gated primitive codebooks provide an effective and interpretable intermediate action representation for robot manipulation.

## TL;DR

Recent robot manipulation policies commonly predict continuous action chunks directly from observations, without explicitly modeling reusable structure in the action space. However, manipulation demonstrations often contain recurring short-horizon motion patterns that are shared across tasks.

## Related
<!-- [[other-paper-citekey]] -->
