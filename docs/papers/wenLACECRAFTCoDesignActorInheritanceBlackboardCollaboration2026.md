---
citekey: "wenLACECRAFTCoDesignActorInheritanceBlackboardCollaboration2026"
title: "LACE-CRAFT: Robot Co-Design with Actor Inheritance and Blackboard Collaboration"
authors: ["Yuhan Wen", "Jiawei Wang", "Qixuan Zhang", "Yusen Qin", "Lan Xu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09283"
doi: "10.48550/arXiv.2610.09283"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# LACE-CRAFT: Robot Co-Design with Actor Inheritance and Blackboard Collaboration

> Yuhan Wen, Jiawei Wang, Qixuan Zhang, Yusen Qin, Lan Xu · 2026
> [arXiv](https://arxiv.org/abs/2610.09283) · [PDF](https://arxiv.org/pdf/2610.09283)

## Abstract

Robot co-design couples morphology search with policy learning, yet training every new design from scratch discards acquired control experience. We present LACE-CRAFT, which compares continued learning on the current robot with policy adaptation to new morphology-reward pairs. LACE resumes the incumbent's full learning state and initializes compatible challengers with its actor parameters and observation statistics. A fixed task metric selects among both branches and the frozen incumbent. CRAFT coordinates Feedback, Morphology, Reward, and Integration roles through shared experimental records and behavioral replays to generate and cross-review paired proposals. A generative extension converts generated meshes into editable articulated models with configured joints, actuator interfaces, and consistently updated simulation assets. Across five locomotion benchmarks, mean scores over three evaluation seeds are 6.4-91.9% higher than D2C. Both methods train 30 new morphology-reward pairs over five rounds; LACE additionally uses four continuation training units. Five-task ablations examine policy inheritance and replay-derived feedback. A fabricated prototype demonstrates indoor walking and illustrates the geometry-to-hardware workflow.

## TL;DR

Robot co-design couples morphology search with policy learning, yet training every new design from scratch discards acquired control experience. We present LACE-CRAFT, which compares continued learning on the current robot with policy adaptation to new morphology-reward pairs.

## Related
<!-- [[other-paper-citekey]] -->
