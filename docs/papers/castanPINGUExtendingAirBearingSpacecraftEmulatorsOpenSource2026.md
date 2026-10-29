---
citekey: "castanPINGUExtendingAirBearingSpacecraftEmulatorsOpenSource2026"
title: "PINGU: Extending Air-Bearing Spacecraft Emulators with Open-Source Actuators and Learned Control for Contact-Rich Proximity Operations"
authors: ["Ricard Marsal I Castan", "Akiyoshi Uchida", "Aman Arora", "Pedro Lima", "Matteo El-Hariry", "Anrej Orsula", "Francesco Grella", "Antoine Richard", "Cedric Pradalier", "Miguel A. Olivarez-Mendez"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.23554"
doi: "10.48550/arXiv.2609.23554"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# PINGU: Extending Air-Bearing Spacecraft Emulators with Open-Source Actuators and Learned Control for Contact-Rich Proximity Operations

> Ricard Marsal I Castan, Akiyoshi Uchida, Aman Arora, Pedro Lima, Matteo El-Hariry, Anrej Orsula, Francesco Grella, Antoine Richard, Cedric Pradalier, Miguel A. Olivarez-Mendez · 2026
> [arXiv](https://arxiv.org/abs/2609.23554) · [PDF](https://arxiv.org/pdf/2609.23554)

## Abstract

Low-cost planar air-bearing testbeds have matured into a standard proxy for free-flying spacecraft GNC, but they remain largely thruster-only and are rarely equipped for contact-rich, inertia-coupled manipulation. Building on the open-source ATMOS testbed, we contribute a reaction wheel and two force/torque-sensed robotic arms (LEVION) with interchangeable end-effectors, integrated as first-class control actuators through a unified ROS 2 abstraction layer. On top of the software stack we build a reinforcement-learning training environment and digital twin, and a controller that exploits these added degrees of freedom, letting classical optimal controllers and learned policies be swapped on the same hardware without modification. We validate the integrated system, PINGU, across four benchmark tasks: point-to-pose navigation (classical LQR vs. sim-to-real PPO), dynamic disturbance rejection under arm-induced center-of-mass shifts, reaction-wheel momentum stabilization, and force-controlled docking. The results show that these additions extend an ATMOS-class emulator into the contact-rich regime and bridge classical optimal control and reinforcement learning on one reproducible platform.

## TL;DR

Low-cost planar air-bearing testbeds have matured into a standard proxy for free-flying spacecraft GNC, but they remain largely thruster-only and are rarely equipped for contact-rich, inertia-coupled manipulation. Building on the open-source ATMOS testbed, we contribute a reaction wheel and two force/torque-sensed robotic arms (LEVION) with interchangeable end-effectors, integrated as first-class control actuators through a unified ROS 2 abstraction layer.

## Related
<!-- [[other-paper-citekey]] -->
