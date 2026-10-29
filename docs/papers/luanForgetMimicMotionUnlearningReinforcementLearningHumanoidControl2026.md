---
citekey: "luanForgetMimicMotionUnlearningReinforcementLearningHumanoidControl2026"
title: "ForgetMimic: Motion Unlearning for Reinforcement Learning Humanoid Control"
authors: ["Xukun Luan", "Zhongxiang Lei", "Chen Gong", "Shaowei Li", "Yuanguo Bi", "Jinyan Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28378"
doi: "10.48550/arXiv.2609.28378"
tags: [paper, embodied-ai, "cs.CR", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# ForgetMimic: Motion Unlearning for Reinforcement Learning Humanoid Control

> Xukun Luan, Zhongxiang Lei, Chen Gong, Shaowei Li, Yuanguo Bi, Jinyan Liu · 2026
> [arXiv](https://arxiv.org/abs/2609.28378) · [PDF](https://arxiv.org/pdf/2609.28378)

## Abstract

Humanoid control, leveraging human demonstrations, has achieved diverse, agile, and natural locomotion behaviors through reinforcement learning (RL). While this paradigm has yielded remarkable performance in physical humanoid control, how to eliminate specific motions from learned policies remains insufficiently explored. Addressing this issue is motivated by pressing safety and privacy concerns: the removal of malicious, poisoned, or suboptimal motions, as well as copyright-protected motions subject to the right to be forgotten under regulations such as the GDPR, is of critical importance. To this end, we propose {ForgetMimic}, the first motion-level unlearning method designed specifically for physical-world humanoid control. The core idea of ForgetMimic is as follows: given a policy $\pi_\theta$ trained on $N$ motions, our method degrades performance on a target subset of $K$ motions while preserving the effectiveness of the remaining $N-K$ motions. Furthermore, we identify and resolve two key training mechanisms in robot control that lead to unlearning failure. We conduct extensive experiments on the Unitree G1 and H2 humanoid robots across 12 motions, including Dance, Fight, Flip, and others. Experimental results demonstrate that ForgetMimic effectively eliminates memory of designated motions while maintaining the normal operation of all other motions.

## TL;DR

Humanoid control, leveraging human demonstrations, has achieved diverse, agile, and natural locomotion behaviors through reinforcement learning (RL). While this paradigm has yielded remarkable performance in physical humanoid control, how to eliminate specific motions from learned policies remains insufficiently explored.

## Related
<!-- [[other-paper-citekey]] -->
