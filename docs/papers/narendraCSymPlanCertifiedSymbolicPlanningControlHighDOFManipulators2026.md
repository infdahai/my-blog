---
citekey: "narendraCSymPlanCertifiedSymbolicPlanningControlHighDOFManipulators2026"
title: "CSymPlan: Certified Symbolic Planning and Control for High-DOF Manipulators"
authors: ["Aditya Narendra", "Ashok Kumar Saini", "Mahathi Anand", "Mahmoud Khaled", "Fares J. Abu-Dakka", "Abdalla Swikir"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.22983"
doi: "10.48550/arXiv.2608.22983"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-08-26
---

# CSymPlan: Certified Symbolic Planning and Control for High-DOF Manipulators

> Aditya Narendra, Ashok Kumar Saini, Mahathi Anand, Mahmoud Khaled, Fares J. Abu-Dakka, Abdalla Swikir · 2026
> [arXiv](https://arxiv.org/abs/2608.22983) · [PDF](https://arxiv.org/pdf/2608.22983)

## Abstract

Robot manipulators are commonly engineered around a decoupled motion-generation stack: a planner computes a collision-free path and a lower-level controller tracks the resulting reference. This separation is computationally convenient, but it can produce references that are difficult to execute under actuator limits, tracking error, model mismatch, and small obstacle clearances. We present CSymPlan, a certified symbolic planning and control framework for high-DOF manipulators with two complementary implementations: an offline implementation that precomputes certified reach-avoid feedback policies for known workspaces; and an online implementation that synthesizes or updates symbolic policies at runtime from changing task and perception information using parallelization. The offline implementation reduces the manipulator dynamics to a sampled perturbed double-integrator model in operational space through feedback linearization, treats torque-realization errors, modeling inaccuracies, and measurement uncertainty as bounded disturbances, and refines the synthesized symbolic policy to the Franka FR3 through a quantization--lookup--torque realization pipeline. The online implementation uses the same abstraction and refinement interface, but replaces the precomputed policy table with a runtime pFaces request--synthesis--execution loop. In randomized simulated benchmarks and perception-driven Franka FR3 experiments, both implementations complete reach-avoid tasks with zero safety violations; whenever no certified action exists, the robot holds, replans, or stops safely instead of executing an uncertified command.

## TL;DR

Robot manipulators are commonly engineered around a decoupled motion-generation stack: a planner computes a collision-free path and a lower-level controller tracks the resulting reference. This separation is computationally convenient, but it can produce references that are difficult to execute under actuator limits, tracking error, model mismatch, and small obstacle clearances.

## Related
<!-- [[other-paper-citekey]] -->
