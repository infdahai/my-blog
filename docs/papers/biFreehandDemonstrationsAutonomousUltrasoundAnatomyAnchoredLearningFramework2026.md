---
citekey: "biFreehandDemonstrationsAutonomousUltrasoundAnatomyAnchoredLearningFramework2026"
title: "From Freehand Demonstrations to Autonomous Robotic Ultrasound: An Anatomy-Anchored Learning Framework"
authors: ["Yuan Bi", "Fangxu Han", "Ye Su", "Yiping Zhou", "Zhongliang Jiang", "Nassir Navab"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.32525"
doi: "10.48550/arXiv.2610.32525"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# From Freehand Demonstrations to Autonomous Robotic Ultrasound: An Anatomy-Anchored Learning Framework

> Yuan Bi, Fangxu Han, Ye Su, Yiping Zhou, Zhongliang Jiang, Nassir Navab · 2026
> [arXiv](https://arxiv.org/abs/2610.32525) · [PDF](https://arxiv.org/pdf/2610.32525)

## Abstract

Ultrasound imaging is highly operator-dependent, motivating robotic systems that reproduce expert scanning skills consistently. These skills involve coordinated interpretation of anatomical landmarks, ultrasound images, and probe-tissue interactions that are difficult to encode in hand-designed control strategies. Imitation learning offers an alternative, but its observation and action representations should reflect the anatomically structured nature of scanning. We propose an anatomy-anchored imitation-learning framework that combines anatomy-guided probe placement with learned ultrasound navigation. The placement module identifies a task-specific anatomical starting point from external visual observations and establishes the initial probe pose as the reference frame for scanning. A flow-based policy then generates scanning motions from anchor-relative probe poses, ultrasound images, probe-mounted camera views, and contact forces, while a termination head predicts task completion. This avoids continuous reliance on third-person vision and reduces dependence on the robot-patient configuration. A handheld acquisition platform enables multimodal demonstrations to be collected during natural freehand scanning without a robot. On 16 unseen participants, task success reaches 96%, 94%, 88%, and 94% for kidney, gallbladder, and liver standard-plane acquisition and radial artery sweeping, respectively. Compared with a fine-tuned pi_0 model, success on the abdominal tasks improves by 10-42 percentage points, with lower time-to-target, peak contact force, and trajectory jerk. Ablations support the complementary roles of anatomical anchoring, egocentric vision, and force feedback. End-to-end trials with automatic placement achieve 90-100% success, and the policies transfer without retraining to a second robot with 83-100% success.

## TL;DR

Ultrasound imaging is highly operator-dependent, motivating robotic systems that reproduce expert scanning skills consistently. These skills involve coordinated interpretation of anatomical landmarks, ultrasound images, and probe-tissue interactions that are difficult to encode in hand-designed control strategies.

## Related
<!-- [[other-paper-citekey]] -->
