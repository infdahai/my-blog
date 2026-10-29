---
citekey: "strongReal2Sem2Real3DSemanticAugmentationsLearningSingleHumanRGB2026"
title: "Real2Sem2Real: 3D Semantic Augmentations for Robot Learning from a Single Human RGB Demonstration"
authors: ["Matthew Strong", "Ankush K. Dhawan", "Julien Poffet", "Giuse Pham", "Jinho So", "Monroe Kennedy III"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.28880"
doi: "10.48550/arXiv.2610.28880"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-23
---

# Real2Sem2Real: 3D Semantic Augmentations for Robot Learning from a Single Human RGB Demonstration

> Matthew Strong, Ankush K. Dhawan, Julien Poffet, Giuse Pham, Jinho So, Monroe Kennedy III · 2026
> [arXiv](https://arxiv.org/abs/2610.28880) · [PDF](https://arxiv.org/pdf/2610.28880)

## Abstract

Human video scales easily and does not need robot hardware, but existing methods require depth sensing, overlay the robot onto 2D video, or generate data only for the demonstrated objects. We present Real2Sem2Real (R2Sem2R), a real-to-semantic-to-real pipeline that turns one monocular RGB video of a human demonstration into thousands of robot demonstrations across the semantic object instances of a category. R2Sem2R tracks the SE(3) pose of each object with DINOv3-distilled Gaussian splats, outperforming existing methods and FoundationPose with estimated metric depth. R2Sem2R then aligns digital cousins, each generated from one or a few photographs, to the demonstrated objects with a semantic alignment. This alignment matches whole objects and the functional regions of target objects, such as a coffee machine's tray. R2Sem2R maps the human hand to a feasible robot grasp that extends to the cousins. Robot demonstrations are generated either in IsaacSim, for photorealistic rendering, or MuJoCo, for contact physics, and R2Sem2R can generate over 2,000 episodes in about two hours. On two real robots and four tasks, we train a vision-language-action policy on data from one human video per task, and policies trained on our data match or exceed policies trained on teleoperation across diverse object instances. The project page is available at https://real2sem2real.github.io/.

## TL;DR

Human video scales easily and does not need robot hardware, but existing methods require depth sensing, overlay the robot onto 2D video, or generate data only for the demonstrated objects. We present Real2Sem2Real (R2Sem2R), a real-to-semantic-to-real pipeline that turns one monocular RGB video of a human demonstration into thousands of robot demonstrations across the semantic object instances of a category.

## Related
<!-- [[other-paper-citekey]] -->
