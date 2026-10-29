---
citekey: "yuPHIRLAligningLearnedRewardsTaskProgressInverseReinforcement2026"
title: "PHIRL: Aligning Learned Rewards with Task Progress for Inverse Reinforcement Learning"
authors: ["Hang Yu", "James Staley", "Cheng Xi Tsou", "Xiujin Liu", "Wenchang Gao", "Jindan Huang", "Shijie Fang", "Zhegong Shangguan", "Angelo Cangelosi", "Reuben Aronson", "Elaine Short"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.31855"
doi: "10.48550/arXiv.2609.31855"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# PHIRL: Aligning Learned Rewards with Task Progress for Inverse Reinforcement Learning

> Hang Yu, James Staley, Cheng Xi Tsou, Xiujin Liu, Wenchang Gao, Jindan Huang, Shijie Fang, Zhegong Shangguan, Angelo Cangelosi, Reuben Aronson, Elaine Short · 2026
> [arXiv](https://arxiv.org/abs/2609.31855) · [PDF](https://arxiv.org/pdf/2609.31855)

## Abstract

Human demonstrations provide dense policy-level information but sometimes lack local precision. Human feedback presents accurate local critiques, but offers sparse evaluations rather than direct policy guidance. We propose Progress-Heuristicized Inverse Reinforcement Learning (PHIRL), a data-efficient framework that learns robust reward functions by jointly leveraging demonstrations and feedback. Specifically, we use progress, a feedback modality that describes cumulative task completion. PHIRL iteratively infers a reward function from demonstrations via inverse reinforcement learning, calculates the learned rewards over the progress-annotated demonstrations, and aligns the rewards with progress annotations over four dimensions. We evaluate PHIRL on real and simulated robot tasks, with additional exploration using a fine-tuned vision-language model to provide progress feedback. Results demonstrate that PHIRL significantly outperforms the baselines, achieving substantially higher environmental return rewards and task success with only twenty percent of demonstrations annotated. Analysis of reward-hacking scenarios demonstrates that PHIRL learned reward functions are reliable against exploitation.

## TL;DR

Human demonstrations provide dense policy-level information but sometimes lack local precision. Human feedback presents accurate local critiques, but offers sparse evaluations rather than direct policy guidance.

## Related
<!-- [[other-paper-citekey]] -->
