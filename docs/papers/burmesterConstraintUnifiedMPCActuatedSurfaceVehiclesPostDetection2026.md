---
citekey: "burmesterConstraintUnifiedMPCActuatedSurfaceVehiclesPostDetection2026"
title: "Constraint-Unified MPC for Over-Actuated Surface Vehicles with Post-Detection Fault Reconfiguration"
authors: ["Sebastian Burmester", "Ruiheng Jiang", "Noa Sendlhofer", "Raffaello D'Andrea", "Aswin Ramachandran"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21046"
doi: "10.48550/arXiv.2609.21046"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-09-22
---

# Constraint-Unified MPC for Over-Actuated Surface Vehicles with Post-Detection Fault Reconfiguration

> Sebastian Burmester, Ruiheng Jiang, Noa Sendlhofer, Raffaello D'Andrea, Aswin Ramachandran · 2026
> [arXiv](https://arxiv.org/abs/2609.21046) · [PDF](https://arxiv.org/pdf/2609.21046)

## Abstract

Choreographed aquatic performances require small autonomous surface vehicles to track precise paths under per-thruster force and rate limits, including after thruster failures. We report a deployed system in which trajectory tracking, thrust allocation, and the per-thruster force and rate limits are resolved in a single quadratic program over the per-thruster commands, with fault reconfiguration entering through one binary flag per thruster from an external detector. The system has driven a fleet in live performances on Lake Zürich and at the Time Space Existence 2025 exhibition in Venice. The field campaign measures 1.6 cm root mean square position error in a 10-minute hold and 4.3 cm over a 10 m square at 0.6 m/s. At 0.5 m/s, losing the front thruster increases the error to 11.6 cm, while losing the starboard-side thruster increases it to 11.5 cm. Losing two thrusters simultaneously leaves the craft tracking a 0.4 m/s square with a root mean square position error of 1.25 m. Compared to our own cascaded baseline, the unified formulation tracks the nominal square to the same few centimeters and holds station more tightly with roughly half the thruster force. The architectures separate after a thruster failure, where the unified controller stays within 24 cm of the reference path while the cascade leaves it.

## TL;DR

Choreographed aquatic performances require small autonomous surface vehicles to track precise paths under per-thruster force and rate limits, including after thruster failures. We report a deployed system in which trajectory tracking, thrust allocation, and the per-thruster force and rate limits are resolved in a single quadratic program over the per-thruster commands, with fault reconfiguration entering through one binary flag per thruster from an external detector.

## Related
<!-- [[other-paper-citekey]] -->
