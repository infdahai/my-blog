---
citekey: "yanOmniIGNOnboardImageGoalNavigationDronesOmnidirectional2026"
title: "Omni-IGN: Onboard Image-Goal Navigation for Drones with Omnidirectional Vision"
authors: ["Zichen Yan", "Rui Huang", "Shenao Wang", "Yucong Wang", "Nuthasith Gerdpratoom", "Lin Zhao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.36968"
doi: "10.48550/arXiv.2610.36968"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# Omni-IGN: Onboard Image-Goal Navigation for Drones with Omnidirectional Vision

> Zichen Yan, Rui Huang, Shenao Wang, Yucong Wang, Nuthasith Gerdpratoom, Lin Zhao · 2026
> [arXiv](https://arxiv.org/abs/2610.36968) · [PDF](https://arxiv.org/pdf/2610.36968)

## Abstract

Image-goal navigation (ImageNav) requires an agent to reach a location specified by a goal image in an unknown environment. For drones, this task demands exploration, goal- directed navigation, and collision avoidance under limited onboard computing resources. Existing aerial ImageNav methods are built on single-view observations, requiring additional rotation and exploration to search for goal-relevant cues outside the field of view. In this paper, we present Omni-IGN, a fully onboard ImageNav system that integrates quad-fisheye perception, an attention-based reinforcement learning (RL) policy, and a collision-aware safety layer. The policy adaptively fuses goal-relevant features across multiple views to provide directional guidance for continuous navigation. The quad-fisheye RGB images support both ImageNav and obstacle avoidance without a dedicated depth sensor. On Habitat benchmarks, Omni-IGN achieves the best performance among continuous-action baselines. Moreover, flight tests in IsaacSim validate the effectiveness of integrating learning-based depth estimation with the action safety layer for collision avoidance. Finally, real-world experiments demonstrate zero-shot sim-to-real transfer without any fine-tuning or external localization. The code and model checkpoints will be released upon acceptance.

## TL;DR

Image-goal navigation (ImageNav) requires an agent to reach a location specified by a goal image in an unknown environment. For drones, this task demands exploration, goal- directed navigation, and collision avoidance under limited onboard computing resources.

## Related
<!-- [[other-paper-citekey]] -->
