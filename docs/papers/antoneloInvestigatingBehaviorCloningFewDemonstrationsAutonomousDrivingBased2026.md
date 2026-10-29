---
citekey: "antoneloInvestigatingBehaviorCloningFewDemonstrationsAutonomousDrivingBased2026"
title: "Investigating Behavior Cloning from Few Demonstrations for Autonomous Driving based on Bird's-Eye View in Simulated Cities"
authors: ["Eric Aislan Antonelo", "Gustavo Claudio Karl Couto", "Christian Möller", "Pedro Henrique Fernandes"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.20203"
doi: "10.48550/arXiv.2610.20203"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# Investigating Behavior Cloning from Few Demonstrations for Autonomous Driving based on Bird's-Eye View in Simulated Cities

> Eric Aislan Antonelo, Gustavo Claudio Karl Couto, Christian Möller, Pedro Henrique Fernandes · 2026
> [arXiv](https://arxiv.org/abs/2610.20203) · [PDF](https://arxiv.org/pdf/2610.20203)

## Abstract

This paper investigates the use of Behavior Cloning (BC) for autonomous driving from a bird's-eye view (BEV) perspective in simulated urban environments. BC uses supervised learning to mimic expert driving behaviors. Previous works have applied BC in the CARLA simulator but did not fully address the challenges of traffic light compliance. Our approach enhances BC by integrating a kernel density estimator to adjust training sample weights based on action density, thereby improving the learning of rare but critical actions such as stopping at red lights and accelerating at green lights, specially in scenarios of scarce number of expert demonstrations. Using BEV inputs, which provide an abstract top-down view of the driving environment, our method simplifies the policy learning process. The trained convolutional neural network (CNN) outputs steering and acceleration actions based on these BEV inputs and additional state variables. Experimental results in the CARLA simulator demonstrate that our weighted BC method significantly improves driving performance, achieving higher route completion compared to standard BC. This weighted approach proved to be crucial in learning correct driving behaviors, particularly in test environments not encountered during training, highlighting its potential for enhancing autonomous vehicle navigation.

## TL;DR

This paper investigates the use of Behavior Cloning (BC) for autonomous driving from a bird's-eye view (BEV) perspective in simulated urban environments. BC uses supervised learning to mimic expert driving behaviors.

## Related
<!-- [[other-paper-citekey]] -->
