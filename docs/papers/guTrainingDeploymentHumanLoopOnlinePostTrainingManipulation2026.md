---
citekey: "guTrainingDeploymentHumanLoopOnlinePostTrainingManipulation2026"
title: "Training in Deployment: Human-in-the-loop Online Post-Training for Robot Manipulation"
authors: ["Chun Gu", "Xiaofei Wei", "Yiming Chen", "Bozhou Zhang", "Juntong Zhang", "Xiatian Zhu", "Li Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.29264"
doi: "10.48550/arXiv.2610.29264"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# Training in Deployment: Human-in-the-loop Online Post-Training for Robot Manipulation

> Chun Gu, Xiaofei Wei, Yiming Chen, Bozhou Zhang, Juntong Zhang, Xiatian Zhu, Li Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.29264) · [PDF](https://arxiv.org/pdf/2610.29264)

## Abstract

Large pretrained robot foundation models provide strong priors for manipulation, yet adapting them to target tasks with offline teleoperated demonstrations often fails to cover the contact-rich, recovery, and precision-critical states encountered during deployment. Existing methods mitigate this issue by augmenting offline demonstrations with human-in-the-loop data or online reinforcement learning. Despite this, offline post-training adapts slowly because it cannot immediately absorb deployment experience, while online RL typically relies on value functions or auxiliary actor-critic models, increasing both training complexity and instability. We present TIDE (Training In DEployment), a human-in-the-loop online post-training system. TIDE introduces a provenance-conditioned supervised learning framework that updates the policy online from human interventions and policy-generated rollouts collected during deployment, without a learned critic, reward model, or action scorer. Across four real-world bimanual manipulation tasks, TIDE improves milestone-normalized task progress and binary full-task completion over the warm-start policy and matched additional offline demonstrations, and performs comparably to the fixed-policy collection baseline while making updated checkpoints available during deployment. Each task-specific online post-training session, from the start of deployment rollouts until the final checkpoint is available, completes in less than one hour while learning and checkpoint handling run asynchronously.

## TL;DR

Large pretrained robot foundation models provide strong priors for manipulation, yet adapting them to target tasks with offline teleoperated demonstrations often fails to cover the contact-rich, recovery, and precision-critical states encountered during deployment. Existing methods mitigate this issue by augmenting offline demonstrations with human-in-the-loop data or online reinforcement learning.

## Related
<!-- [[other-paper-citekey]] -->
