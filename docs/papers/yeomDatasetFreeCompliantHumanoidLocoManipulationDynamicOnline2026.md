---
citekey: "yeomDatasetFreeCompliantHumanoidLocoManipulationDynamicOnline2026"
title: "Dataset-Free Compliant Humanoid Loco-Manipulation with Dynamic Online Posture"
authors: ["Seungho Yeom", "Zhenyu Wu", "Jaeyoung Huh", "Diego Williams", "Yuheng Zhi", "Soofiyan Atar", "Michael Yip"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.05678"
doi: "10.48550/arXiv.2610.05678"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Dataset-Free Compliant Humanoid Loco-Manipulation with Dynamic Online Posture

> Seungho Yeom, Zhenyu Wu, Jaeyoung Huh, Diego Williams, Yuheng Zhi, Soofiyan Atar, Michael Yip · 2026
> [arXiv](https://arxiv.org/abs/2610.05678) · [PDF](https://arxiv.org/pdf/2610.05678)

## Abstract

Most humanoid loco-manipulation controllers require human motion data to learn whole-body coordination and posture, leaving policies reliant on external sources to provide this data. We present OCLO (Online-posture Compliant LOco-manipulation), a humanoid loco-manipulation system trained without human motion data and commanded only through two end-effector targets. Because these targets do not uniquely determine whole-body posture, OCLO generates pelvis height and torso orientation online using an analytic reachability prior, further refined through policy-in-the-loop sampling with a task-agnostic cost. OCLO also learns whole-body compliance by displacing end-effector references according to measured forces through a spring-damper model, encouraging the legs, waist, and pelvis to yield to external loads. In simulation, using the reachability prior leads to a 77.8% success rate in acquiring the commanded reference, a vast improvement over the 37.8% success rate accomplished without the prior. Further, refinement reduces end-effector orientation error across all evaluated tasks. The same posture module improves a pretrained SONIC controller on four of five tasks. Without compliance training, policies tend to lose balance under disturbances rather than sacrifice tracking. On a Unitree G1, OCLO maintains balance under end-effector disturbances that cause its ablations to fail and performs seven loco-manipulation tasks, including crouched walking and picking up a box from a low surface. Project website: https://oclo-humanoid.github.io/

## TL;DR

Most humanoid loco-manipulation controllers require human motion data to learn whole-body coordination and posture, leaving policies reliant on external sources to provide this data. We present OCLO (Online-posture Compliant LOco-manipulation), a humanoid loco-manipulation system trained without human motion data and commanded only through two end-effector targets.

## Related
<!-- [[other-paper-citekey]] -->
