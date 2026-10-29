---
citekey: "kalariaVICARVideoImitationContactAwareRetargetingHumanoidInteractive2026"
title: "VICAR: Video Imitation with Contact-Aware Retargeting for Humanoid Interactive Skills"
authors: ["Dvij Kalaria", "Bike Zhang", "S. Shankar Sastry"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.13079"
doi: "10.48550/arXiv.2610.13079"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# VICAR: Video Imitation with Contact-Aware Retargeting for Humanoid Interactive Skills

> Dvij Kalaria, Bike Zhang, S. Shankar Sastry · 2026
> [arXiv](https://arxiv.org/abs/2610.13079) · [PDF](https://arxiv.org/pdf/2610.13079)

## Abstract

Third-person human videos offer a scalable alternative to task-specific reward engineering, teleoperation, and manually scripted demonstrations for humanoid loco-manipulation. Recent video-to-humanoid systems have shown that noisy human motion, object trajectories, and contacts can be extracted from unstructured videos and refined into deployable skills. However, a key gap remains for contact-rich imitation: the task is often defined by world-frame contacts whose poses, timing, and speed must survive embodiment mismatch and runtime scene changes. Towards this, we present VICAR (Video Imitation with Contact-Aware Retargeting), a pipeline for learning humanoid interactive skills from third-person human videos. The system first recovers human motion, reconstructs task-relevant obstacles from monocular video, and then retargets the motion to a humanoid while preserving global contact poses, motion speed, and collision clearance. Unlike retargeting methods that only remove penetration or preserve local interaction geometry, our formulation represents user-specified contact poses and collision clearance as high-priority Lagrangian penalty terms and optimizes the full motion to remain smooth through contact-rich transitions. The resulting motions are used to train a contact-conditioned motion generator whose inputs include movable contact points enabling runtime adaptation to new contact positions. We demonstrate the framework on ten diverse third-person video skills, including six table-tennis serves, three object-pickup tasks, and ladder climbing, and deploy the learned skills on hardware. These results suggest that contact-preserving retargeting is a practical step toward humanoids that learn useful interactive behavior by watching humans.

## TL;DR

Third-person human videos offer a scalable alternative to task-specific reward engineering, teleoperation, and manually scripted demonstrations for humanoid loco-manipulation. Recent video-to-humanoid systems have shown that noisy human motion, object trajectories, and contacts can be extracted from unstructured videos and refined into deployable skills.

## Related
<!-- [[other-paper-citekey]] -->
