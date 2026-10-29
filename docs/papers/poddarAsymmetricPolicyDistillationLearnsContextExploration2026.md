---
citekey: "poddarAsymmetricPolicyDistillationLearnsContextExploration2026"
title: "Asymmetric On-Policy Distillation Learns In-Context Exploration"
authors: ["Sriyash Poddar", "Yanda Bao", "Jacob Krantz", "Matthew Chang", "Xavier Puig", "Roozbeh Mottaghi", "Natasha Jaques", "Abhishek Gupta"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.30105"
doi: "10.48550/arXiv.2610.30105"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-23
---

# Asymmetric On-Policy Distillation Learns In-Context Exploration

> Sriyash Poddar, Yanda Bao, Jacob Krantz, Matthew Chang, Xavier Puig, Roozbeh Mottaghi, Natasha Jaques, Abhishek Gupta · 2026
> [arXiv](https://arxiv.org/abs/2610.30105) · [PDF](https://arxiv.org/pdf/2610.30105)

## Abstract

Sequential decision-making under partial observability is difficult because agents must explore to infer hidden, task-relevant information before acting effectively. Learning such information-gathering behaviors tabula rasa via online reinforcement learning is sample-inefficient, whereas offline imitation averages expert actions across hidden states and fails to learn exploration. In this work, we propose ASTEROID, a simple and effective student--teacher supervised learning framework that can learn test-time exploration. Although a privileged expert never needs to explore, we demonstrate that a history-conditioned student can learn to do so when trained with on-policy contexts: the student first collects on-policy context under partial observability, and the privileged expert provides action labels conditioned on that context. By distilling expert actions directly conditioned on the student's on-policy history, the student learns to systematically resolve partial observability, i.e., search while uncertain and exploit once the hidden state is revealed. This enables efficient test-time exploration (similar to Bayesian posterior sampling) without incurring the impractical training-data costs of reinforcement learning. Across a diverse range of eleven different environments, including discrete exploration benchmarks, robotic manipulation, navigation, and Procgen environments, ASTEROID achieves ~2x higher returns under fixed exploration budgets, uses ~100x fewer interactions than RL baselines, and outperforms frontier models at exploration. Finally, our method transfers policies trained in simulation to vision-denied real-world robot manipulation, exhibiting efficient exploration and increasing success by +40% over standard distillation. Overall, it provides a simple yet surprisingly effective framework to learn efficient test-time exploration.

## TL;DR

Sequential decision-making under partial observability is difficult because agents must explore to infer hidden, task-relevant information before acting effectively. Learning such information-gathering behaviors tabula rasa via online reinforcement learning is sample-inefficient, whereas offline imitation averages expert actions across hidden states and fails to learn exploration.

## Related
<!-- [[other-paper-citekey]] -->
