---
citekey: "bargelliniEnhancingSim2RealTransferTorqueControlledThroughReal2SimDynamics2026"
title: "Enhancing Sim2Real Transfer for Torque-Controlled Robots through Real2Sim Dynamics Estimation and Reinforcement Learning"
authors: ["Davide Bargellini", "Alex Pasquali", "Andrea Govoni", "Riccardo Zanella", "Gianluca Palli"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.22629"
doi: "10.48550/arXiv.2608.22629"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-08-27
---

# Enhancing Sim2Real Transfer for Torque-Controlled Robots through Real2Sim Dynamics Estimation and Reinforcement Learning

> Davide Bargellini, Alex Pasquali, Andrea Govoni, Riccardo Zanella, Gianluca Palli · 2026
> [arXiv](https://arxiv.org/abs/2608.22629) · [PDF](https://arxiv.org/pdf/2608.22629)

## Abstract

Transferring reinforcement learning policies from simulation to Real-World robots remains a major challenge, particularly when dealing with low-level torque control, where even small modelling inaccuracies can lead to unstable or unsafe behaviours. In this work, we propose a Real2Sim2Real pipeline that improves Sim2Real transfer for torque-controlled robotic arms by combining trajectory matching, parameter optimization via genetic algorithms, and domain randomization. Using the 7-DOF Franka Emika Panda robot, we first identify friction, inertia, and gravity compensation parameters by minimizing the error between real and simulated joint trajectories. These calibrated dynamics are then used to train a TQC-based reinforcement learning agent in simulation. The trained policy is evaluated in both Gazebo and MuJoCo environments, and finally deployed on the real robot. Our results demonstrate a significant improvement in tracking accuracy and policy robustness after parameter tuning, with smooth policy transfer from simulation to the Real-World across multiple target-reaching tasks. This work highlights the effectiveness of accurate physical modelling in enabling stable and generalizable torque-based reinforcement learning policies.

## TL;DR

Transferring reinforcement learning policies from simulation to Real-World robots remains a major challenge, particularly when dealing with low-level torque control, where even small modelling inaccuracies can lead to unstable or unsafe behaviours. In this work, we propose a Real2Sim2Real pipeline that improves Sim2Real transfer for torque-controlled robotic arms by combining trajectory matching, parameter optimization via genetic algorithms, and domain randomization.

## Related
<!-- [[other-paper-citekey]] -->
