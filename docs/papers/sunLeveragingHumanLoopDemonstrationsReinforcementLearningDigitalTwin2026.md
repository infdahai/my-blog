---
citekey: "sunLeveragingHumanLoopDemonstrationsReinforcementLearningDigitalTwin2026"
title: "Leveraging Human-In-The-Loop Demonstrations in Reinforcement Learning for Digital Twin-Driven Robot Flexibility"
authors: ["Yuzhu Sun", "Mien Van", "Nguyen Minh Nhat", "Stephen McIlvanna", "Sean McLoone"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12140"
doi: "10.48550/arXiv.2610.12140"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-10-10
---

# Leveraging Human-In-The-Loop Demonstrations in Reinforcement Learning for Digital Twin-Driven Robot Flexibility

> Yuzhu Sun, Mien Van, Nguyen Minh Nhat, Stephen McIlvanna, Sean McLoone · 2026
> [arXiv](https://arxiv.org/abs/2610.12140) · [PDF](https://arxiv.org/pdf/2610.12140)

## Abstract

Growing automation makes collaborative robots work in more variable environments, increasing the need for adaptation. We propose a human-in-the-loop online training framework combining a digital twin (DT), reinforcement learning (RL), and human demonstrations. Unlike DTs used mainly to generate synthetic data before task execution, our DT is synchronized with the physical system in real time through camera feeds, allowing the virtual robot to update its observations and policy from real-world feedback. A dual actor framework integrates imitation learning (IL) without adding a direct imitation loss to the RL actor, so demonstrations can guide adaptation instead of manual reprogramming. The proposed framework is demonstrated on the Ufactory Xarm5 collaborative robot, where the robot's end-effector aims to reach the target position while avoiding obstacles. The experiments show that the framework can resume training after a change in the physical workspace and that, with a fixed set of non-optimal demonstrations, the dual actor framework achieves a much higher final success rate than two methods that add an imitation loss to the actor. The same pattern holds with real human demonstrations collected in virtual reality (VR): with demonstrations that never reach the goal, the dual actor framework reached 83-100% mean deterministic evaluation success, against 0-17% for the two imitation-loss methods.

## TL;DR

Growing automation makes collaborative robots work in more variable environments, increasing the need for adaptation. We propose a human-in-the-loop online training framework combining a digital twin (DT), reinforcement learning (RL), and human demonstrations.

## Related
<!-- [[other-paper-citekey]] -->
