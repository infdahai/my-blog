---
citekey: "tangAWLSAdvantageWeightedLatentSteeringOneStepGenerative2026"
title: "AWLS: Advantage-Weighted Latent Steering for One-Step Generative Robotic Manipulation Policies"
authors: ["Jiahong Tang", "Jiaju He", "Zhiyuan Yang", "Ruyang Han", "Haiyue Zhu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.27736"
doi: "10.48550/arXiv.2610.27736"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# AWLS: Advantage-Weighted Latent Steering for One-Step Generative Robotic Manipulation Policies

> Jiahong Tang, Jiaju He, Zhiyuan Yang, Ruyang Han, Haiyue Zhu · 2026
> [arXiv](https://arxiv.org/abs/2610.27736) · [PDF](https://arxiv.org/pdf/2610.27736)

## Abstract

Human-collected real-world robotic manipulation demonstrations often contain mixed-quality trajectories, including hesitant, indirect, or inefficient action segments. While diffusion- and flow-based policies can model such multimodal data, standard behavior cloning (BC) assigns equal likelihood to all demonstrated actions and may therefore reproduce suboptimal modes. Offline RL value estimates offer a natural signal for biasing policies toward higher-value behavioral modes, but directly fine-tuning the generative policy or using critic gradients for policy steering can amplify critic errors and induce prior drift. We propose Advantage-Weighted Latent Steering (AWLS), an offline post-training method for improving frozen one-step generative manipulation policies without updating their decoders. AWLS learns a residual noise shaper, an observation-conditioned residual correction to the policy's latent noise, and trains it with an advantage-weighted action reconstruction objective. The advantages are detached, scale-normalized, and used only as supervised weights on demonstrated actions, avoiding critic-gradient policy updates while preserving fast single-step inference. We further introduce a rollout-free decoder-sensitivity criterion for selecting pretrained checkpoints that remain responsive to latent-noise perturbations. Experiments on simulated and real-world robotic manipulation tasks with clean and mixed-quality demonstrations show that AWLS improves over the frozen base policy while limiting drift from the pretrained behavior prior. Project page: https://awls-corl2026.github.io/

## TL;DR

Human-collected real-world robotic manipulation demonstrations often contain mixed-quality trajectories, including hesitant, indirect, or inefficient action segments. While diffusion- and flow-based policies can model such multimodal data, standard behavior cloning (BC) assigns equal likelihood to all demonstrated actions and may therefore reproduce suboptimal modes.

## Related
<!-- [[other-paper-citekey]] -->
