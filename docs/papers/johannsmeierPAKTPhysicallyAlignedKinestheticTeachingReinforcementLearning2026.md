---
citekey: "johannsmeierPAKTPhysicallyAlignedKinestheticTeachingReinforcementLearning2026"
title: "PAKT: Physically-Aligned Kinesthetic Teaching for Reinforcement Learning"
authors: ["Lars Johannsmeier", "Yashraj Narang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.25630"
doi: "10.48550/arXiv.2609.25630"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# PAKT: Physically-Aligned Kinesthetic Teaching for Reinforcement Learning

> Lars Johannsmeier, Yashraj Narang · 2026
> [arXiv](https://arxiv.org/abs/2609.25630) · [PDF](https://arxiv.org/pdf/2609.25630)

## Abstract

Real-world reinforcement learning (RL) systems still struggle with the demands of contact-rich industrial manipulation, including micrometer-level precision, success rates above 99%, and human-level cycle times. Although off-policy algorithms can improve performance by leveraging demonstrations and interventions, a key bottleneck is the lack of an intuitive interface for collecting such guidance while complying with constraints of the physical system and the policy. We propose PAKT, a framework for kinesthetic teaching in RL. As opposed to teleoperation approaches, PAKT relies on kinesthetic guidance, which is widely used in industry. However, a critical weakness of kinesthetic guidance is the possibility for the operator to move the robot along trajectories (e.g., velocities, accelerations, jerk) that the robot and/or policy cannot physically reproduce. Using PAKT, operators guide the robot through admittance control, which maps human-applied forces to motion. The downstream reference generator applies the same kinematic limits used during policy execution, keeping the collected trajectories within these limits. To support this teaching interface with an appropriate execution layer, PAKT adds a high-performance control stack that maps low-frequency RL actions to high-frequency torque commands. It consists of a reference generator and subsequent impedance controller, where the reference generator preserves the tracking performance of the impedance controller while improving contact handling and producing smoother policy actions. Across the reported runs on four insertion and industrial assembly benchmarks, including a data center compute tray, the end-to-end system reduces cycle time by 23%-48% and cumulative intervention count by 62%-86% relative to the HIL-SERL baseline. Project website: https://pakt-website.github.io/pakt-website}{https://pakt-website.github.io/pakt-website

## TL;DR

Real-world reinforcement learning (RL) systems still struggle with the demands of contact-rich industrial manipulation, including micrometer-level precision, success rates above 99%, and human-level cycle times. Although off-policy algorithms can improve performance by leveraging demonstrations and interventions, a key bottleneck is the lack of an intuitive interface for collecting such guidance while complying with constraints of the physical system and the policy.

## Related
<!-- [[other-paper-citekey]] -->
