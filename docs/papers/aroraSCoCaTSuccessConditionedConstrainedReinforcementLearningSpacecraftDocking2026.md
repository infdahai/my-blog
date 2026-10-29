---
citekey: "aroraSCoCaTSuccessConditionedConstrainedReinforcementLearningSpacecraftDocking2026"
title: "SCoCaT: Success Conditioned Constrained Reinforcement Learning for Spacecraft Docking"
authors: ["Aman Arora", "Ricard Marsal I Castan", "Matteo El-Hariry", "Miguel Olivares-Mendez"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.06061"
doi: "10.48550/arXiv.2609.06061"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# SCoCaT: Success Conditioned Constrained Reinforcement Learning for Spacecraft Docking

> Aman Arora, Ricard Marsal I Castan, Matteo El-Hariry, Miguel Olivares-Mendez · 2026
> [arXiv](https://arxiv.org/abs/2609.06061) · [PDF](https://arxiv.org/pdf/2609.06061)

## Abstract

Termination-based constrained reinforcement learning is attractive for safety-critical robotic deployments: it avoids online optimization at inference, scales easily to many constraints via a single scalar per constraint, and is simpler to implement than commonly used Lagrangian methods. Instead of pricing violations through summed cost penalties, this approach makes violations structurally unprofitable by shortening the effective horizon for each violation. We identify a structural failure mode of this method class on terminal-navigation tasks: reaching a precise goal configuration while satisfying safety constraints that tighten along the final approach. When the goal sits inside the region close to where the constraints become active, the survival-weighted objective makes dwelling outside the goal region strictly preferable to entering, producing high constraint compliance with low task completion. We formalize this pathology and show that a minimal augmentation to off-the-shelf RL algorithms like PPO resolves this ``feasibility collapse''. We empirically demonstrate that adding a dense per-step success signal via an auxiliary value critic improves the task completion rate while maintaining safety-critical constraint compliance. Validation across two representative spacecraft platforms: a 6U-CubeSat spanning the mass and degree-of-freedom envelope of operational proximity operations, and a floating platform testbed for zero-shot sim-to-real transfer in our laboratory, supports the generality of these findings.

## TL;DR

Termination-based constrained reinforcement learning is attractive for safety-critical robotic deployments: it avoids online optimization at inference, scales easily to many constraints via a single scalar per constraint, and is simpler to implement than commonly used Lagrangian methods. Instead of pricing violations through summed cost penalties, this approach makes violations structurally unprofitable by shortening the effective horizon for each violation.

## Related
<!-- [[other-paper-citekey]] -->
