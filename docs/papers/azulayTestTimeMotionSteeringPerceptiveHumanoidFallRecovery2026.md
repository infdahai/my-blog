---
citekey: "azulayTestTimeMotionSteeringPerceptiveHumanoidFallRecovery2026"
title: "Test-Time Motion Steering for Perceptive Humanoid Fall Recovery"
authors: ["Osher Azulay", "Cheng-Lin Hsieh", "Stella X. Yu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.30061"
doi: "10.48550/arXiv.2610.30061"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-23
---

# Test-Time Motion Steering for Perceptive Humanoid Fall Recovery

> Osher Azulay, Cheng-Lin Hsieh, Stella X. Yu · 2026
> [arXiv](https://arxiv.org/abs/2610.30061) · [PDF](https://arxiv.org/pdf/2610.30061)

## Abstract

Humanoid fall recovery requires selecting a motion that suits both the surrounding scene and the task. The same fallen pose can admit several ways to stand, with different routes, support transitions, and final headings. Yet reliable recovery alone does not provide control over which of these alternatives the robot executes. Steering this choice requires anticipating the physical consequences of a requested movement. We present RISE, an approach to perceptive humanoid recovery that lets task objectives steer how the robot returns to standing at inference time. It builds on two insights: diverse recoveries can be composed from shared movements, and anticipating how these movements unfold allows recovery to be steered toward a task objective. We learn a recovery vocabulary that connects intended movements to motor actions through sensory feedback. A visual diffusion planner learns from executions of this vocabulary to predict motion intent as future body states. Task costs guide this prediction toward a desired heading, rise speed, or path. The planner then generates motion latents conditioned on the steered intent, allowing the requested movement to shape its execution. Simulation experiments demonstrate diverse recoveries, terrain adaptation, and test-time steering without retraining, complemented by real-world demonstrations on a Unitree G1. Project page: https://osheraz.github.io/RISE/

## TL;DR

Humanoid fall recovery requires selecting a motion that suits both the surrounding scene and the task. The same fallen pose can admit several ways to stand, with different routes, support transitions, and final headings.

## Related
<!-- [[other-paper-citekey]] -->
