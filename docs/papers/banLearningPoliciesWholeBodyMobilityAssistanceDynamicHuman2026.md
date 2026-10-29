---
citekey: "banLearningPoliciesWholeBodyMobilityAssistanceDynamicHuman2026"
title: "Learning Robot Policies for Whole-Body Mobility Assistance via Dynamic Human Motion Generation"
authors: ["Shikun Ban", "Shohei Nagai", "Qingyang Song", "Hanxi Wan", "Eric Zhao", "Thomas Wang", "Zackory Erickson"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.17750"
doi: "10.48550/arXiv.2610.17750"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Learning Robot Policies for Whole-Body Mobility Assistance via Dynamic Human Motion Generation

> Shikun Ban, Shohei Nagai, Qingyang Song, Hanxi Wan, Eric Zhao, Thomas Wang, Zackory Erickson · 2026
> [arXiv](https://arxiv.org/abs/2610.17750) · [PDF](https://arxiv.org/pdf/2610.17750)

## Abstract

Robotic assistance for human mobility could benefit care recipients and reduce caregiver burden during physically demanding tasks such as Sit-to-Stand (STS) and Lift-and-Transfer (L&T). Learning robot policies for these whole-body assistive tasks is challenging: real-world data collection for human-robot interaction is costly and safety-critical, making simulation an attractive alternative. Prior work, however, typically treats the human as static or minimally responsive and thus fails to capture the cooperative nature of mobility assistance. We present a simulation-based framework for learning whole-body assistive robot policies. At its core is a human policy trained with an adversarial motion prior that produces realistic care-recipient motion in response to the robot's actions. A human-adaptive scripted controller interacts with this policy to collect diverse robot demonstrations at scale. From these demonstrations, we train 3D diffusion policies that map segmented human point clouds and robot joint positions to whole-body actions for a mobile manipulator, without relying on privileged human state at deployment. The resulting robot policies successfully perform both STS and L&T assistance in simulation. Preliminary experiments further demonstrate sim-to-real transfer for STS after fine-tuning on a small amount of real-world data. Videos are available on our project page: https://rchi-lab.github.io/human-gen-mobility-assistance/

## TL;DR

Robotic assistance for human mobility could benefit care recipients and reduce caregiver burden during physically demanding tasks such as Sit-to-Stand (STS) and Lift-and-Transfer (L&T). Learning robot policies for these whole-body assistive tasks is challenging: real-world data collection for human-robot interaction is costly and safety-critical, making simulation an attractive alternative.

## Related
<!-- [[other-paper-citekey]] -->
