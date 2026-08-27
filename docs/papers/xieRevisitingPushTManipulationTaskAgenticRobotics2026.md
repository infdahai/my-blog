---
citekey: "xieRevisitingPushTManipulationTaskAgenticRobotics2026"
title: "Revisiting the \"Push-T\" Robot Manipulation Task with Agentic Robotics"
authors: ["Shuangyu Xie", "Kaiyuan Chen", "Ken Goldberg"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.18227"
doi: "10.48550/arXiv.2608.18227"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Revisiting the "Push-T" Robot Manipulation Task with Agentic Robotics

> Shuangyu Xie, Kaiyuan Chen, Ken Goldberg · 2026
> [arXiv](https://arxiv.org/abs/2608.18227) · [PDF](https://arxiv.org/pdf/2608.18227)

## Abstract

Push-T is an iconic benchmark for learning manipulation policies from human demonstrations. The robot must use a single point of contact to push a T-shaped block into a target pose. In this short paper, we revisit the Push-T task in the context of emerging advances in Agentic Robotics where an LLM coding agent -- Claude Code with Fable 5 -- is prompted to create an algorithmic solution that does not require any demonstration data. We study how effective the agentic coding loop can solve the Push-T task, and compare the resulting code as policy with the visuomotor imitation learning policy. Results suggest that the agent found the 2D gym simulation online, and used sim experiments to learn push mechanics, iteratively optimizing to achieve 100% success rate using 46% fewer steps than the best diffusion policy trained with 200 human demonstrations. The coding agent also solve extensions from T to the full alphabet (Push-A to Push-Z) using a self generated curriculum and generated simulation code for the Franka and UR5 robot arms in 3D cross-embodiment simulations with visual feedback. Videos, policies and details will be posted online.

## TL;DR

Push-T is an iconic benchmark for learning manipulation policies from human demonstrations. The robot must use a single point of contact to push a T-shaped block into a target pose.

## Related
<!-- [[other-paper-citekey]] -->
