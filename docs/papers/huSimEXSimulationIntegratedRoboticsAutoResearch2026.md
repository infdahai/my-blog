---
citekey: "huSimEXSimulationIntegratedRoboticsAutoResearch2026"
title: "SimEX: Simulation-Integrated Robotics AutoResearch"
authors: ["Jiaheng Hu", "Roberto Martin-Martin", "Peter Stone", "Rocky Duan", "Zhenyu Jiang", "Guanya Shi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.38982"
doi: "10.48550/arXiv.2609.38982"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-04
---

# SimEX: Simulation-Integrated Robotics AutoResearch

> Jiaheng Hu, Roberto Martin-Martin, Peter Stone, Rocky Duan, Zhenyu Jiang, Guanya Shi · 2026
> [arXiv](https://arxiv.org/abs/2609.38982) · [PDF](https://arxiv.org/pdf/2609.38982)

## Abstract

Coding agents powered by large language models (LLMs) have shown remarkable abilities to autonomously reason about and achieve goals in the digital world. However, bringing this success to the physical world remains challenging. On the one hand, direct generation methods (e.g., Code as Policies) often suffer from the LLMs' insufficient understanding of robots and physical environments. On the other hand, iterative trial-and-error tuning in the physical world (e.g., physical autoresearch) induces significant experimental cost and safety concerns. We introduce SimEX: Simulation-Integrated Robotics AutoResearch, an autoresearch framework that tightly integrates simulated experimentation, enabling coding agents to efficiently acquire physical capabilities for controlling real robots. SimEX operates in two stages. First, the agent conducts open-ended probe-and-optimize iterations in simulation, developing a robot toolbox with robust and generalizable capabilities. Second, the agent adapts the toolbox and the simulator together through only a few physical trials: each trial corrects the simulator, and the corrected simulator is used to diagnose failures and screen candidate repairs. We evaluate SimEX extensively in sim-to-sim settings and on physical robots. On challenging real-world manipulation tasks including towel folding, barcode scanning, and plate manipulation, SimEX enables coding agents to efficiently acquire robot skills without any demonstration and with only 10 minutes of real-robot interaction. These results suggest that simulation can be a critical component in achieving physical intelligence, not only as a source of training data that must closely replicate the real world, but also as a roughly correct laboratory where a coding agent develops the knowledge and procedures needed to act on the robot. More details and robot videos at https://robo-simex.github.io/

## TL;DR

Coding agents powered by large language models (LLMs) have shown remarkable abilities to autonomously reason about and achieve goals in the digital world. However, bringing this success to the physical world remains challenging.

## Related
<!-- [[other-paper-citekey]] -->
