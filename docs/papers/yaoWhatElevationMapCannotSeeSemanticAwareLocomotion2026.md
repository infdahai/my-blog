---
citekey: "yaoWhatElevationMapCannotSeeSemanticAwareLocomotion2026"
title: "What the Elevation Map Cannot See: Semantic-Aware Locomotion and Execution-Aware Navigation for Humanoid Robot"
authors: ["Shunyu Yao", "Songyang Liu", "Dinghao Chen", "Yuanyuan Lei", "Shuai Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07396"
doi: "10.48550/arXiv.2610.07396"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# What the Elevation Map Cannot See: Semantic-Aware Locomotion and Execution-Aware Navigation for Humanoid Robot

> Shunyu Yao, Songyang Liu, Dinghao Chen, Yuanyuan Lei, Shuai Li · 2026
> [arXiv](https://arxiv.org/abs/2610.07396) · [PDF](https://arxiv.org/pdf/2610.07396)

## Abstract

Navigation for humanoid robots is critical, yet large-scale evaluation on physical hardware is often impractical due to cost and safety concerns, making simulation benchmarks essential. Existing VLN benchmarks achieve physically executable navigation, but still assume (1) all hazards are observable from elevation maps; (2) realized motions closely match desired motions. In real environments, however, fallen bottles may be ambiguous in elevation maps, while phones and water spills may be difficult to differentiate; hazard avoidance by the locomotion policy can cause the robot's actual trajectory to deviate from the path intended by the VLN policy. Such command-execution mismatch can accumulate and lead the robot toward unintended locations. To expose these failure modes, we introduce a benchmark that models both elevation-subtle hazards and execution deviations, together with a closed-loop VLN + locomotion control framework that continuously realigns high-level navigation with the robot's actual state. We evaluate navigation in simulation and further validate the locomotion policy on a physical Unitree G1 humanoid robot. Results show that semantic input reduces contact with hazards poorly represented in elevation maps, while anti-deviation improves navigation success. These findings highlight the need to evaluate humanoid navigation jointly in terms of route completion and hazard avoidance.

## TL;DR

Navigation for humanoid robots is critical, yet large-scale evaluation on physical hardware is often impractical due to cost and safety concerns, making simulation benchmarks essential. Existing VLN benchmarks achieve physically executable navigation, but still assume (1) all hazards are observable from elevation maps; (2) realized motions closely match desired motions.

## Related
<!-- [[other-paper-citekey]] -->
