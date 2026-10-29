---
citekey: "abdalwhabLearningMultiAgentTaskAssignmentNavigationFactorySimulation2026"
title: "Learning Multi-Agent Task Assignment and Navigation in the Factory: from Simulation to Real Robots"
authors: ["Abdalwhab Bakheet Mohamed Abdalwhab", "Giovanni Beltrame", "David St-Onge"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.14567"
doi: "10.48550/arXiv.2609.14567"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# Learning Multi-Agent Task Assignment and Navigation in the Factory: from Simulation to Real Robots

> Abdalwhab Bakheet Mohamed Abdalwhab, Giovanni Beltrame, David St-Onge · 2026
> [arXiv](https://arxiv.org/abs/2609.14567) · [PDF](https://arxiv.org/pdf/2609.14567)

## Abstract

Reinforcement learning (RL) has shown considerable promise for robotic decision-making, yet deploying multi-agent RL (MARL) on physical multi-robot systems in industrial environments remains challenging. This paper investigates the real-world applicability of decentralized MARL for multi-robot multi-machine tending. We propose Feature-fusion Multi-Agent Proximal Policy Optimization (FMAPPO), which fuses 2D LiDAR measurements with task-specific state information to enable safe decentralized multi-robot task assignment and navigation. A complete simulation-to-reality pipeline was developed using high-fidelity robotic simulation and ROS2 and deployed on physical mobile-manipulator platforms operating under realistic real-world conditions, with the robotic arms disabled during the experiments. We further investigate the sensitivity of the learned policy to command update frequency, an important consideration for real-world deployment. Comparative evaluation in simulation demonstrated that FMAPPO significantly outperformed state-of-the-art baselines with a large effect size, achieving improvements of 106\% and 21\% in parts delivery and 48\% and 11\% in parts collection over MAPPO and SMAPPO, respectively. FMAPPO also increased machine utilization by 31 and 10 percentage points, respectively, while reducing collisions by 18\% and 15\% and increasing the safety score by 14 and 6 percentage points compared with MAPPO and SMAPPO, respectively. Furthermore, real-world experiments demonstrated that the learned decentralized policies can coordinate multiple robots to service multiple machines while maintaining safe operation under real-world sensing and control constraints. Videos of the real-world experiment are available online https://anonymouspapers123.github.io/FMAPPO/.

## TL;DR

Reinforcement learning (RL) has shown considerable promise for robotic decision-making, yet deploying multi-agent RL (MARL) on physical multi-robot systems in industrial environments remains challenging. This paper investigates the real-world applicability of decentralized MARL for multi-robot multi-machine tending.

## Related
<!-- [[other-paper-citekey]] -->
