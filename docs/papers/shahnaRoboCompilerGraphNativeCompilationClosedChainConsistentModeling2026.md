---
citekey: "shahnaRoboCompilerGraphNativeCompilationClosedChainConsistentModeling2026"
title: "RoboCompiler: Graph-Native Compilation of Closed-Chain Robots for Consistent Modeling, Control, and Simulation"
authors: ["Mehdi Heydari Shahna", "Joongheon Kim", "Jouni Mattila"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.35717"
doi: "10.48550/arXiv.2609.35717"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# RoboCompiler: Graph-Native Compilation of Closed-Chain Robots for Consistent Modeling, Control, and Simulation

> Mehdi Heydari Shahna, Joongheon Kim, Jouni Mattila · 2026
> [arXiv](https://arxiv.org/abs/2609.35717) · [PDF](https://arxiv.org/pdf/2609.35717)

## Abstract

Robots with kinematic loops, coupled actuators, and changing contacts require consistent models of configuration, motion, force, and dynamics. Yet these interfaces are often reconstructed separately for control and simulation, making closure and actuation consistency difficult to maintain. This paper presents RoboCompiler, a graph-native framework that compiles a canonical mechanism graph into a shared mechanical interface. From bodies, joints, frames, inertias, and actuator ports, it constructs closure paths and analytic residual Jacobians, then assembles feasible configurations through rank-checked continuation and correction. A tangent lift maps independent velocities to full robot and task motion, while paired actuator-port maps preserve virtual work. A constraint-curvature correction extends the reduction to accelerations and projected rigid-body dynamics, including floating-base and support modes. Cycle-local evaluation, generated Jacobians, and dependency-aware reuse enable localized updates when closure inputs change. We evaluate physical loops and task-induced constraints on a Komatsu excavator, Unitree Go2, Franka Panda, Kangaroo, and a six-UPS Stewart platform. High-precision constrained-dynamics and independent Pinocchio checks confirm mechanical consistency; MuJoCo and Isaac Sim/PhysX executions demonstrate task performance and model reuse under native contact. For Kangaroo, compilation reduces residual-and-Jacobian evaluation time by 96.7% and closed-loop rollout wall time by 66.8%, with dynamics and control held fixed.

## TL;DR

Robots with kinematic loops, coupled actuators, and changing contacts require consistent models of configuration, motion, force, and dynamics. Yet these interfaces are often reconstructed separately for control and simulation, making closure and actuation consistency difficult to maintain.

## Related
<!-- [[other-paper-citekey]] -->
