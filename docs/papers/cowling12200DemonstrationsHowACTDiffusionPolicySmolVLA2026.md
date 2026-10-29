---
citekey: "cowling12200DemonstrationsHowACTDiffusionPolicySmolVLA2026"
title: "From 12 to 200 Demonstrations: How ACT, Diffusion Policy, SmolVLA and $\pi_{0.5}$ Scale on a Low-Cost Arm"
authors: ["Simon Cowling"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.37170"
doi: "10.48550/arXiv.2610.37170"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# From 12 to 200 Demonstrations: How ACT, Diffusion Policy, SmolVLA and $\pi_{0.5}$ Scale on a Low-Cost Arm

> Simon Cowling · 2026
> [arXiv](https://arxiv.org/abs/2610.37170) · [PDF](https://arxiv.org/pdf/2610.37170)

## Abstract

We trained four widely used imitation-learning policies, ACT, Diffusion Policy, SmolVLA and $\pi_{0.5}$, on nested subsets of 12, 25, 50, 100 and 200 teleoperated demonstrations of one pick-and-place task with distractor objects, using one fixed training recipe per policy. Every trained model was then run on a physical SO-101 arm on a fixed set of object placements: 1,340 scored episodes in 126 blocks. ACT, trained from scratch, rose from 1 success in 40 episodes at 12 demonstrations to 37 in 40 at 100. $\pi_{0.5}$ with its action expert fine-tuned was the best policy when data was scarce (16 of 40 at 12 demonstrations, 28 of 40 at 25) and then stayed near 70%; from 100 demonstrations ACT was ahead, by a margin this study does not fully resolve. SmolVLA and Diffusion Policy peaked near 50%, and both were affected by a failure to start: SmolVLA's arm never started moving in 47% of episodes, and Diffusion Policy hardly ever started until an idle lead-in was trimmed from the demonstrations. For $\pi_{0.5}$ the fine-tuning recipe mattered more than the amount of data: low-rank adaptation succeeded in 4 of 110 episodes, against 130 of 200 for action-expert fine-tuning. From the joint and camera recordings we place every episode on a four-stage ladder (started, reached the ball, carried it, delivered it) and show that for ACT more data moves failures from reaching, to grasping, to none, while the failures $\pi_{0.5}$ retains are in grasping. We also measure how weak a ten-episode block is as a measurement (the same checkpoint tested twice differs by 2 successes in 10 on average), separate seed-to-seed variation from that noise, and audit the human scoring against the recordings. Training length was fixed within each recipe, so the amount of data and the number of times it was seen change together; we state which conclusions survive that confound and which do not.

## TL;DR

We trained four widely used imitation-learning policies, ACT, Diffusion Policy, SmolVLA and $\pi_{0.5}$, on nested subsets of 12, 25, 50, 100 and 200 teleoperated demonstrations of one pick-and-place task with distractor objects, using one fixed training recipe per policy. Every trained model was then run on a physical SO-101 arm on a fixed set of object placements: 1,340 scored episodes in 126 blocks.

## Related
<!-- [[other-paper-citekey]] -->
