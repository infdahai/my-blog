---
citekey: "qianEIDAExecutionInterfaceDynamicsAdaptationRealSimReal2026"
title: "EIDA: Execution-Interface Dynamics Adaptation for Real-to-Sim-to-Real Robot Navigation"
authors: ["Yiwei Qian", "Shanze Wang", "Qingyuan Hu", "Xinming Zhang", "Wei Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01219"
doi: "10.48550/arXiv.2610.01219"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# EIDA: Execution-Interface Dynamics Adaptation for Real-to-Sim-to-Real Robot Navigation

> Yiwei Qian, Shanze Wang, Qingyuan Hu, Xinming Zhang, Wei Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.01219) · [PDF](https://arxiv.org/pdf/2610.01219)

## Abstract

Simulation-to-robot transfer can fail when velocity commands produce motion and feedback that differ from those modeled during policy training. We present execution-interface dynamics adaptation (EIDA), which fits these responses from target-platform execution data without reconstructing actuator dynamics. A model of body-frame pose increments updates simulator geometry, while a separate model predicts the velocity feedback observed by the policy; a short history of velocity feedback is included in the policy input. The fitted models are used within a lightweight GPU-parallel simulator. On the full Jackal and Go2 validation sets, the fitted models reduced position and yaw prediction errors relative to the simulator's predefined motion model. Across 100 benchmark navigation environments evaluated in a separate physics-based simulator, EIDA achieved the highest success rate and navigation score among the compared learned policies, both with and without global guidance. Feedback ablations further supported the need to match policy-facing velocity estimates. On a physical Unitree Go2, EIDA reached the goal without collision in all 20 static-scene trials, compared with 4 of 20 for the baseline. These results show that execution-interface adaptation can improve navigation transfer without detailed actuator simulation.

## TL;DR

Simulation-to-robot transfer can fail when velocity commands produce motion and feedback that differ from those modeled during policy training. We present execution-interface dynamics adaptation (EIDA), which fits these responses from target-platform execution data without reconstructing actuator dynamics.

## Related
<!-- [[other-paper-citekey]] -->
