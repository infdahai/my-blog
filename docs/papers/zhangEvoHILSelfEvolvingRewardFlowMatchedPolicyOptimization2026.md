---
citekey: "zhangEvoHILSelfEvolvingRewardFlowMatchedPolicyOptimization2026"
title: "EvoHIL: Self-Evolving Reward and Flow-Matched Policy Optimization for Robust Human-in-the-Loop Reinforcement Learning"
authors: ["Shuoqin Zhang", "Tongtong Cheng", "Xiru Gao", "Jinzhuo Peng", "Bin Zheng", "Jiahao Tu", "Ke Wang", "Jia Pan", "Zhe Hu", "Kai Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.03872"
doi: "10.48550/arXiv.2608.03872"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# EvoHIL: Self-Evolving Reward and Flow-Matched Policy Optimization for Robust Human-in-the-Loop Reinforcement Learning

> Shuoqin Zhang, Tongtong Cheng, Xiru Gao, Jinzhuo Peng, Bin Zheng, Jiahao Tu, Ke Wang, Jia Pan, Zhe Hu, Kai Liu · 2026
> [arXiv](https://arxiv.org/abs/2608.03872) · [PDF](https://arxiv.org/pdf/2608.03872)

## Abstract

Human-in-the-loop reinforcement learning (HIL-RL) enables robots to learn contact-rich manipulation from limited real-world interaction, but deployment exposes three coupled limitations: static visual reward models fail under scene changes; independently sampled actions cause temporally inconsistent motion; and vision-based policies remain sensitive to appearance shifts. We present EvoHIL, a unified framework that adapts the reward model, action generator, and visual do main within a staged human-in-the-loop learning process. First, self-evolving reward (SER) adapts the success classifier from human-confirmed positives and provisional weak negatives. Second, Action Flow Stabilization (AFS) generates temporally coherent action chunks through flow matching, grounding policy updates in executed action prefixes and demonstrated behavior. Third, retention-aware offline fine-tuning replays relit interaction data while anchoring the AFS actor-critic to prior behavior, adapting the visual domain without additional robot interaction. Across six manipulation tasks on Franka FR3 and SO-101 arms under a controlled lighting shift, EvoHIL improves task success, agreement with human-confirmation labels, motion smoothness, and completion time relative to human-in-the-loop and imitation baselines.Project page: https://anonymous4366.github.io/EvoHIL/

## TL;DR

Human-in-the-loop reinforcement learning (HIL-RL) enables robots to learn contact-rich manipulation from limited real-world interaction, but deployment exposes three coupled limitations: static visual reward models fail under scene changes; independently sampled actions cause temporally inconsistent motion; and vision-based policies remain sensitive to appearance shifts. We present EvoHIL, a unified framework that adapts the reward model, action generator, and visual do main within a staged human-in-the-loop learning process.

## Related
<!-- [[other-paper-citekey]] -->
