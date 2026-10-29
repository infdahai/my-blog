---
citekey: "aTaskAwareDynamicMovementPrimitivesFailureDetectionRecovery2026"
title: "Task aware Dynamic Movement Primitives for failure detection and recovery in contact rich manipulation"
authors: ["Bhavnashri A", "Sobia Shafi", "Krishnapuram Himavarshini", "Anuj Tiwari"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.23151"
doi: "10.48550/arXiv.2609.23151"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-09-22
---

# Task aware Dynamic Movement Primitives for failure detection and recovery in contact rich manipulation

> Bhavnashri A, Sobia Shafi, Krishnapuram Himavarshini, Anuj Tiwari · 2026
> [arXiv](https://arxiv.org/abs/2609.23151) · [PDF](https://arxiv.org/pdf/2609.23151)

## Abstract

Assembly remains a challenging robotic manipulation task in presence of tight tolerances and complex contact interactions. While Learning from Demonstration (LfD) frameworks like Dynamic Movement Primitives (DMPs) can effectively encode trajectories from a single demonstration, they are highly sensitive to variations in initial grasp configurations and external contact forces. Such variations often lead to task failures during the contact rich phases. This paper presents a task aware failure detection and recovery framework that integrates DMP based trajectory generation with real time stage classification. Utilizing Quadratic Discriminant Analysis (QDA) trained on multimodal sensor data, the framework segments execution into approach, alignment, and insertion stages for a Peg in Hole (PiH) assembly operation. By using goal relative position data as features, this classification generalizes to unseen goal positions without requiring retraining, matching the inherent generalization capability of DMPs. Anomaly detection is performed online using a Mahalanobis distance metric computed over force features, isolating contact induced failures from nominal trajectory execution. Upon failure detection, a spiral search recovery policy is triggered to actively realign the peg under contact before resuming the learned DMP insertion. The proposed approach is evaluated on an experimental setup achieving 95% stage classification accuracy, and demonstrates reliable failure recovery under lateral misalignments of up to 3 mm using only a single demonstration.

## TL;DR

Assembly remains a challenging robotic manipulation task in presence of tight tolerances and complex contact interactions. While Learning from Demonstration (LfD) frameworks like Dynamic Movement Primitives (DMPs) can effectively encode trajectories from a single demonstration, they are highly sensitive to variations in initial grasp configurations and external contact forces.

## Related
<!-- [[other-paper-citekey]] -->
