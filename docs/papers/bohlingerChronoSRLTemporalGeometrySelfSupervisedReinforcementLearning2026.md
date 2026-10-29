---
citekey: "bohlingerChronoSRLTemporalGeometrySelfSupervisedReinforcementLearning2026"
title: "ChronoSRL: Temporal Geometry for Self-Supervised Reinforcement Learning"
authors: ["Nico Bohlinger", "Jan Peters"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.36238"
doi: "10.48550/arXiv.2609.36238"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# ChronoSRL: Temporal Geometry for Self-Supervised Reinforcement Learning

> Nico Bohlinger, Jan Peters · 2026
> [arXiv](https://arxiv.org/abs/2609.36238) · [PDF](https://arxiv.org/pdf/2609.36238)

## Abstract

A goal that is close in space can be far away in time. Obstacles, terrain, and the agent's own capabilities determine how long it takes to get there. Yet, critics in contrastive and survival reinforcement learning do not measure the distances in their representation space in units of time. We therefore introduce ChronoSRL, which gives the critic's embeddings an explicit temporal geometry. The distance between state-action and goal embeddings is trained to match the time that the agent takes to reach the goal (goal-reaching time), while goals that were not reached, and goals from other trajectories, are pushed at least one discount horizon away. Furthermore, reaching a goal quickly once does not mean that reaching it is reliable in general, so the policy should not follow the temporal distance directly. Instead, we build on survival reinforcement learning and predict from our temporal embeddings not only the full distribution of goal-reaching times but also the time spent near the goal. Thereby, the policy is trained to favor actions that reach the goal sooner and more reliably and that keep the agent near it. ChronoSRL learns faster and reaches higher performance than contrastive, action-chunked contrastive, and survival reinforcement learning baselines on seven standard locomotion and navigation benchmarks, even with much smaller networks. To test the limits of self-supervised reinforcement learning, we introduce velocity tracking, goal-position reaching, and box climbing tasks with a quadruped robot in a realistic sim-to-real locomotion setup, and show how the shaping terms that are typical for robotics can be naturally incorporated into our framework. ChronoSRL is the only one of the tested self-supervised reinforcement learning methods that learns to stay at the commanded velocities and goal positions, and climbs the highest boxes.

## TL;DR

A goal that is close in space can be far away in time. Obstacles, terrain, and the agent's own capabilities determine how long it takes to get there.

## Related
<!-- [[other-paper-citekey]] -->
