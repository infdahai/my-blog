---
citekey: "marewFastMotionRetargetingPipelineScalableHumanoidLearning2026"
title: "Fast Motion Retargeting Pipeline for Scalable Humanoid Robot Learning"
authors: ["Daniel Marew", "Sangjun Park", "Nisal Perera", "Donghyun Kim"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.28470"
doi: "10.48550/arXiv.2610.28470"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# Fast Motion Retargeting Pipeline for Scalable Humanoid Robot Learning

> Daniel Marew, Sangjun Park, Nisal Perera, Donghyun Kim · 2026
> [arXiv](https://arxiv.org/abs/2610.28470) · [PDF](https://arxiv.org/pdf/2610.28470)

## Abstract

While large-scale human motion capture datasets provide a rich source of demonstrations for humanoid robot learning, retargeting the diverse motions to different humanoid robots remains a nontrivial challenge. Existing kinodynamic trajectory optimization pipelines are computationally expensive and often require manual adjustments per motion. We present FRDV (Fast Retargeting with Dynamics Validation), a scalable framework consisting of rapid constrained kinematic retargeting and an additional dynamics validation pipeline. Its kinematic stage integrates a custom Sequential Quadratic Programming solver, Real-Time Iteration, and parallel chunk-based processing, achieving up to 9,156 frames per second, approximately up to 136 times faster than GMR and ProtoMotions, while robot-specific constraints are incorporated into the optimization to reduce common retargeting artifacts, such as ground penetration and self-collision. For motions requiring additional verification, a contact implicit iLQR controller is utilized to test the retargeted reference under full rigid body dynamics. This dynamics-based validation identifies dynamically infeasible motions and refines contact-related artifacts such as foot floating and foot skating. We evaluate retargeting quality by training motion tracking reinforcement learning policies using several state-of-the-art pipelines and comparing their tracking fidelity and success rates. Furthermore, sim-to-real transfer is demonstrated on a Unitree G1 humanoid. Videos and code are available at: https://daroslab.github.io/frdv/.

## TL;DR

While large-scale human motion capture datasets provide a rich source of demonstrations for humanoid robot learning, retargeting the diverse motions to different humanoid robots remains a nontrivial challenge. Existing kinodynamic trajectory optimization pipelines are computationally expensive and often require manual adjustments per motion.

## Related
<!-- [[other-paper-citekey]] -->
