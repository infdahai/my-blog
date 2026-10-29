---
citekey: "wangAeroHandOpenSimulationReadyTendonDrivenHand2026"
title: "Aero Hand Open: A Simulation-Ready Tendon-Driven Hand for Dexterous Manipulation Learning"
authors: ["Nan Wang", "Mohit Yadav", "Jonathan Wulff", "Aidan Rosenbaum", "Kezhou Chen", "Yuvan Sharma", "Xu Dong", "Yiwei Tao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.28578"
doi: "10.48550/arXiv.2608.28578"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-04
---

# Aero Hand Open: A Simulation-Ready Tendon-Driven Hand for Dexterous Manipulation Learning

> Nan Wang, Mohit Yadav, Jonathan Wulff, Aidan Rosenbaum, Kezhou Chen, Yuvan Sharma, Xu Dong, Yiwei Tao · 2026
> [arXiv](https://arxiv.org/abs/2608.28578) · [PDF](https://arxiv.org/pdf/2608.28578)

## Abstract

Tendon-driven hands are anthropomorphic, and moving the actuators off the joints is what makes a hand of this capability affordable to build. Two effects produce that saving. Routing force through a cable removes the requirement that a motor fit inside the joint it drives, so smaller and cheaper motors suffice, and one motor can drive several joints through a single cable, so fewer motors are needed. They are also harder to learn on than a direct-drive hand. The underactuated transmission that produces the saving is itself difficult to represent in a simulator, and the joints one cable drives are not independently commandable. We present Aero Hand Open, a tendon-driven anthropomorphic hand that is released simulation-ready. Three things ship with it. A simulation model reproduces the cable transmission itself. An identified actuation map connects that model to the motor commands in both directions, including the three-way coupling of the thumb. A reinforcement learning package trains policies for the hand. Together they let a policy be trained entirely in simulation and run on the hand with no fine-tuning and no state estimation. We release the mechanical design, the simulation model, the identified mapping, the training environment and the deployment stack.

## TL;DR

Tendon-driven hands are anthropomorphic, and moving the actuators off the joints is what makes a hand of this capability affordable to build. Two effects produce that saving.

## Related
<!-- [[other-paper-citekey]] -->
