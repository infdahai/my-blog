---
citekey: "pereraReproducibleVisionGuided6DoFManipulatorMixedStepper2026"
title: "Reproducible Vision-Guided 6-DoF Robotic Manipulator with a Mixed Stepper-Driver Architecture and Browser-Native Control"
authors: ["Lasan Perera", "Deneth Priyadarshana", "Dulana Pitiwaduge", "Isitha Dinujaya", "Mokshan Colambage"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.22799"
doi: "10.48550/arXiv.2608.22799"
tags: [paper, embodied-ai, "cs.CV", "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-08-26
---

# Reproducible Vision-Guided 6-DoF Robotic Manipulator with a Mixed Stepper-Driver Architecture and Browser-Native Control

> Lasan Perera, Deneth Priyadarshana, Dulana Pitiwaduge, Isitha Dinujaya, Mokshan Colambage · 2026
> [arXiv](https://arxiv.org/abs/2608.22799) · [PDF](https://arxiv.org/pdf/2608.22799)

## Abstract

We present the NeuralNexus Arm, an open, low-cost 6-DOF robotic manipulator built by an undergraduate engineering team, together with the design decisions and debugging experience needed to reproduce it. The arm is driven by a single STM32H743 microcontroller on a custom printed circuit board (PCB) and combines two stepper-driver strategies on one controller: push-pull 3.3 V step/direction outputs for onboard TMC2209 drivers on the three wrist joints, and open-drain outputs for external CL57T and DM542 drivers on the three high-torque proximal joints. We describe the mechanical design, mixed-driver electronics, interrupt-driven firmware, a MATLAB/Simscape-based inverse-kinematics pipeline, a browser-native control interface using the Web Serial API, and a lightweight vision pipeline for object localisation and autonomous pick-and-place tasks. We also document non-obvious hardware and firmware failure modes encountered during the transition from a development board to the custom PCB as reproducibility guidance. All design files and firmware are released openly. The platform actuates all six axes under coordinated control at a 2 kHz update rate and executes both manual and pre-recorded motions from the browser interface.

## TL;DR

We present the NeuralNexus Arm, an open, low-cost 6-DOF robotic manipulator built by an undergraduate engineering team, together with the design decisions and debugging experience needed to reproduce it. The arm is driven by a single STM32H743 microcontroller on a custom printed circuit board (PCB) and combines two stepper-driver strategies on one controller: push-pull 3.3 V step/direction outputs for onboard TMC2209 drivers on the three wrist joints, and open-drain outputs for external CL57T and DM542 drivers on the three high-torque proximal joints.

## Related
<!-- [[other-paper-citekey]] -->
