---
citekey: "zhangBananaKickResponseInformedSkillEvolutionHumanoidSoccer2026"
title: "Banana Kick: Response-Informed Skill Evolution for Humanoid Soccer"
authors: ["Hao E. Zhang", "Ruize Geng", "Raihan Haque", "Khalil Zbiss", "Guanyang Luo", "Hui-ping Wang", "H. Eric Tseng", "Ding Zhao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.27269"
doi: "10.48550/arXiv.2609.27269"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# Banana Kick: Response-Informed Skill Evolution for Humanoid Soccer

> Hao E. Zhang, Ruize Geng, Raihan Haque, Khalil Zbiss, Guanyang Luo, Hui-ping Wang, H. Eric Tseng, Ding Zhao · 2026
> [arXiv](https://arxiv.org/abs/2609.27269) · [PDF](https://arxiv.org/pdf/2609.27269)

## Abstract

Humanoid kicking requires coordinated whole-body motion and precise contact, while a banana kick demands contact mechanics that generate ball spin and aerodynamic curvature. Motion imitation provides a reliable ordinary-kick prior, but reinforcement learning may improve shot speed and placement accuracy without changing the underlying kicking technique. Adapting this prior to a qualitatively different contact-rich skill can fail even when the reward is dense and optimization remains stable. The failure occurs when the task objective is locally flat over the current policy's responses. We term this condition first-order learning starvation. To address it, we propose response-informed skill evolution (RISE), a closed-loop objective-continuation method for policy adaptation. RISE ranks bounded objective changes using response sensitivity estimated from cached rollouts and accepts updates only when they produce verified response progress while preserving kicking reliability. Our analysis shows that rescaling a saturated spin reward cannot recover first-order sensitivity at zero spin, whereas adapting coupled contact responses can provide a learnable path to spin generation. We integrate RISE into a humanoid kicking pipeline under calibrated contact and Magnus-force aerodynamics, and sim-to-real transfer. Experiments show that RISE evolves the ordinary kick into a high-spin curved kick with 11.55 rad/s mean ball spin, improves the mean evaluation score by 19.8% over a learning-progress curriculum, and raises joint target attainment from 15.2% to 50.9%. Ablations and response diagnostics support the mechanism, while 30 motion-capture-recorded physical trials demonstrate consistent hardware transfer of the learned curved kick. Project website: https://haozhang-thu.github.io/bananakick/

## TL;DR

Humanoid kicking requires coordinated whole-body motion and precise contact, while a banana kick demands contact mechanics that generate ball spin and aerodynamic curvature. Motion imitation provides a reliable ordinary-kick prior, but reinforcement learning may improve shot speed and placement accuracy without changing the underlying kicking technique.

## Related
<!-- [[other-paper-citekey]] -->
