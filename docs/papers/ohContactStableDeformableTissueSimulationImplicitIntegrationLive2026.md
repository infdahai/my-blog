---
citekey: "ohContactStableDeformableTissueSimulationImplicitIntegrationLive2026"
title: "Contact-Stable Deformable Tissue Simulation Using Implicit Integration and Live-Pose Grasp Constraints for Laparoscopic Surgery Robot Policy Evaluation"
authors: ["Juahn Oh", "Dongho Yee", "Jinseok Lee", "Jiyul Lee", "Yechan Seo", "Seong Jeong", "Minsung Kim", "Seonho Shim", "Younghoon Noh", "Hyuk Choi", "Youngbin Kong", "Hyoun-Joong Kon"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.25642"
doi: "10.48550/arXiv.2609.25642"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# Contact-Stable Deformable Tissue Simulation Using Implicit Integration and Live-Pose Grasp Constraints for Laparoscopic Surgery Robot Policy Evaluation

> Juahn Oh, Dongho Yee, Jinseok Lee, Jiyul Lee, Yechan Seo, Seong Jeong, Minsung Kim, Seonho Shim, Younghoon Noh, Hyuk Choi, Youngbin Kong, Hyoun-Joong Kon · 2026
> [arXiv](https://arxiv.org/abs/2609.25642) · [PDF](https://arxiv.org/pdf/2609.25642)

## Abstract

Closed-loop evaluation of surgical robots requires tissue that deforms, can be grasped and lifted, and reproduces the anatomy in which the robot will operate. We present a simulator in which this tissue is reconstructed from a fixed-view RGB-D recording of the surgical field, composited to remove the instruments, closed into watertight volumes and tetrahedralised; the pipeline was applied unchanged to three specimens of two species (thirteen organs, 146,061 tetrahedra, no inverted elements). For one specimen, the organs are placed in a bimanual cell in which two Franka FR3 arms operate motorised instruments through 6 mm trocars. The core contribution is the numerical and contact design that keeps this cell stable: implicit integration, simulation meshes separate from collision meshes, numerical guards, and a grasp constraint captured at the live tissue pose. In 45 repeated grasp-lifts, a friction grasp held the tissue in 0 of 15 trials and each constraint grasp in 13 of 15; on displaced tissue, a rest-pose constraint produced one-step snaps of up to 17.8 mm, which live-pose capture eliminates. Against the recording, front-surface depth error is 1.33 to 1.41 mm, organ silhouette IoU is 0.80, and in five grasp-lifts reproduced from video the landmark displacement RMSE is 11.8 mm against 14.2 mm for a static prediction. Biofidelity is not claimed; the environment is intended for closed-loop feasibility, safety, contact and policy screening.

## TL;DR

Closed-loop evaluation of surgical robots requires tissue that deforms, can be grasped and lifted, and reproduces the anatomy in which the robot will operate. We present a simulator in which this tissue is reconstructed from a fixed-view RGB-D recording of the surgical field, composited to remove the instruments, closed into watertight volumes and tetrahedralised; the pipeline was applied unchanged to three specimens of two species (thirteen organs, 146,061 tetrahedra, no inverted elements).

## Related
<!-- [[other-paper-citekey]] -->
