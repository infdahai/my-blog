---
citekey: "safaeiCDFFConceptLevelDiagnosticsMechanismParitySimulation2026"
title: "C-DFF: Concept-Level Diagnostics for Mechanism Parity in Simulation-Based Validation of Autonomous Driving Perception"
authors: ["Danial Safaei", "Siddartha Khastgir", "Matthew Higgins", "Jeroen Ploeg", "Mohsen Alirezaei", "Son Tong", "Ludo Gielen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.33760"
doi: "10.48550/arXiv.2610.33760"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# C-DFF: Concept-Level Diagnostics for Mechanism Parity in Simulation-Based Validation of Autonomous Driving Perception

> Danial Safaei, Siddartha Khastgir, Matthew Higgins, Jeroen Ploeg, Mohsen Alirezaei, Son Tong, Ludo Gielen · 2026
> [arXiv](https://arxiv.org/abs/2610.33760) · [PDF](https://arxiv.org/pdf/2610.33760)

## Abstract

Simulation is widely used in autonomous-driving validation, but matching task outputs between real and synthetic images does not guarantee that a system relies on the same visual evidence. This creates a validation gap for transfer, especially in safety-critical perception functions. We present Concept-Decisive Feature Fidelity (C-DFF), a concept-level mechanism-parity diagnostic for paired real-synthetic evaluation. Starting from decisive evidence extracted from a frozen system-under-test (SUT), C-DFF projects that evidence into a shared semantic concept space using off-the-shelf segmentation and compares real and synthetic concept-importance vectors. The result is not only a scalar mechanism-parity score, but also a concept-shift diagnostic that identifies which scene concepts become more or less decisive in simulation. We evaluate C-DFF on KITTI $\leftrightarrow$ Virtual KITTI 2 with 2126 matched pairs across three frozen SUTs (steering regression, YOLOP drivable-area, YOLOP lane-line). Across these tasks, C-DFF is SUT-discriminative and yields interpretable concept-level summaries that support validation triage and simulator debugging. When reported alongside task-specific output-value context metrics, C-DFF shows that output agreement does not by itself establish mechanism parity. These results position C-DFF as a practical semantic diagnostic layer for validation and verification workflows in simulation-based AV testing.

## TL;DR

Simulation is widely used in autonomous-driving validation, but matching task outputs between real and synthetic images does not guarantee that a system relies on the same visual evidence. This creates a validation gap for transfer, especially in safety-critical perception functions.

## Related
<!-- [[other-paper-citekey]] -->
