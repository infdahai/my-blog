---
citekey: "jajooRegularizedLatentDynamicsPredictionIsStrongBaselineBehavioral2026"
title: "Regularized Latent Dynamics Prediction is a Strong Baseline For Behavioral Foundation Models"
authors: ["Pranaya Jajoo", "Harshit Sikchi", "Siddhant Agarwal", "Amy Zhang", "Scott Niekum", "Martha White"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2603.15857"
doi: "10.48550/arXiv.2603.15857"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Regularized Latent Dynamics Prediction is a Strong Baseline For Behavioral Foundation Models

> Pranaya Jajoo, Harshit Sikchi, Siddhant Agarwal, Amy Zhang, Scott Niekum, Martha White · 2026
> [arXiv](https://arxiv.org/abs/2603.15857) · [PDF](https://arxiv.org/pdf/2603.15857)

## Abstract

Behavioral Foundation Models (BFMs) produce agents with the capability to adapt to any unknown reward or task. These methods, however, are only able to produce near-optimal policies for the reward functions that are in the span of some pre-existing state features, making the choice of state features crucial to the expressivity of the BFM. As a result, BFMs are trained using a variety of complex objectives and require sufficient dataset coverage, to train task-useful spanning features. In this work, we examine the question: are these complex representation learning objectives necessary for zero-shot RL? Specifically, we revisit the objective of self-supervised next-state prediction in latent space for state feature learning, but observe that such an objective alone is prone to increasing state-feature similarity, and subsequently reducing span. We propose an approach, Regularized Latent Dynamics Prediction (RLDP), that adds a simple orthogonality regularization to maintain feature diversity and can match or surpass state-of-the-art complex representation learning methods for zero-shot RL. Furthermore, we empirically show that prior approaches perform poorly in low-coverage scenarios where RLDP still succeeds.

## TL;DR

Behavioral Foundation Models (BFMs) produce agents with the capability to adapt to any unknown reward or task. These methods, however, are only able to produce near-optimal policies for the reward functions that are in the span of some pre-existing state features, making the choice of state features crucial to the expressivity of the BFM.

## Related
<!-- [[other-paper-citekey]] -->
