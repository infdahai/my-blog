---
citekey: "hwangUnifiedKinematicRepresentationEnablesReusableBiologicalJointMoment2026"
title: "A Unified Kinematic Representation Enables Reusable Biological Joint Moment Estimation"
authors: ["Jinwoo Hwang", "Ilseung Park", "Changseob Song", "Vu Phan", "Eni Halilaj", "Inseung Kang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09150"
doi: "10.48550/arXiv.2610.09150"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# A Unified Kinematic Representation Enables Reusable Biological Joint Moment Estimation

> Jinwoo Hwang, Ilseung Park, Changseob Song, Vu Phan, Eni Halilaj, Inseung Kang · 2026
> [arXiv](https://arxiv.org/abs/2610.09150) · [PDF](https://arxiv.org/pdf/2610.09150)

## Abstract

Objective: Data-driven models that estimate physiological states, particularly biological joint moments, are widely used in exoskeleton control. However, these estimators are often coupled to device-specific sensor configurations, limiting controller transfer and the use of open-source biomechanics datasets. Methods: We proposed joint kinematics as an intermediate representation that decouples hardware-specific sensing from downstream biological joint moment estimation. A joint-moment estimator using joint angles and angular velocities was trained exclusively on open-source biomechanics data and evaluated using kinematics from a hip exoskeleton, knee exoskeleton, and inertial measurement unit (IMU) sensor suite during level-ground, ramp-ascent, and ramp-descent walking. Results: The estimator achieved an root mean square error (RMSE) of 0.17 Nm/kg and coefficient of determination (R2) of 0.79 using hip exoskeleton kinematics, 0.19 Nm/kg and 0.62 using knee exoskeleton kinematics, and 0.15 Nm/kg and 0.85 using kinematics derived from IMUs across bilateral hip, knee, and ankle joints. Conclusion: Joint kinematics enabled an estimator trained only on open-source data to operate across distinct wearable platforms. Significance: This framework may reduce target-device data collection and support transferable biological joint moment estimation for exoskeleton control and wearable biomechanics.

## TL;DR

Objective: Data-driven models that estimate physiological states, particularly biological joint moments, are widely used in exoskeleton control. However, these estimators are often coupled to device-specific sensor configurations, limiting controller transfer and the use of open-source biomechanics datasets.

## Related
<!-- [[other-paper-citekey]] -->
