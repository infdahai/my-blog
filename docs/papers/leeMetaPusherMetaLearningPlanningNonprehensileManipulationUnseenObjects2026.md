---
citekey: "leeMetaPusherMetaLearningPlanningNonprehensileManipulationUnseenObjects2026"
title: "MetaPusher: Meta Learning and Planning for Nonprehensile Manipulation of Unseen Objects with Rapid Online Adaption"
authors: ["Donghyung Lee", "Seyedali Golestaneh", "Jaskrit Singh", "Zhuoyun Zhong", "Athanasios Kapoutsis", "Constantinos Chamzas"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21122"
doi: "10.48550/arXiv.2609.21122"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-21
---

# MetaPusher: Meta Learning and Planning for Nonprehensile Manipulation of Unseen Objects with Rapid Online Adaption

> Donghyung Lee, Seyedali Golestaneh, Jaskrit Singh, Zhuoyun Zhong, Athanasios Kapoutsis, Constantinos Chamzas · 2026
> [arXiv](https://arxiv.org/abs/2609.21122) · [PDF](https://arxiv.org/pdf/2609.21122)

## Abstract

Manipulating previously unseen objects remains challenging, as their dynamics depend on latent physical properties, such as friction and mass distribution, that cannot be inferred from perception alone. Prior experience across objects can provide an initial estimate of unseen object dynamics, but this estimate remains uncertain and can degrade further during sim-to-real transfer. Adapting the dynamics through interaction can progressively refine the estimation, however, updating the model may invalidate the planned trajectory. Successful and efficient manipulation therefore requires both rapid dynamics adaptation and a planning strategy that can incorporate this evolution. In this work, we introduce MetaPusher, a meta-learning and adaptive planning framework for nonprehensile manipulation of unseen objects without prior object-specific interactions. A meta-learned dynamics model rapidly adapts from interactions during task execution, while an adaptive kinodynamic planner updates long-horizon plans by reusing and refining its existing search tree. This coupling enables manipulation and adaptation without a separate data collection phase. We evaluate MetaPusher on unseen objects in simulation and in sim-to-real scenarios, comparing against fine-tuning and active learning methods, MPPI-based control, and a reinforcement learning policy. It achieves lower prediction error and improves task success rate by up to 20%.

## TL;DR

Manipulating previously unseen objects remains challenging, as their dynamics depend on latent physical properties, such as friction and mass distribution, that cannot be inferred from perception alone. Prior experience across objects can provide an initial estimate of unseen object dynamics, but this estimate remains uncertain and can degrade further during sim-to-real transfer.

## Related
<!-- [[other-paper-citekey]] -->
