---
citekey: "sohalDIADenoisingIntermediateAdvantageDiffusionPolicyOptimization2026"
title: "DIA: Denoising Intermediate Advantage for Diffusion Policy Optimization"
authors: ["Arjun Sohal", "Yuchi Zhao", "Miroslav Bogdanovic", "Alan Aspuru-Guzik"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.12245"
doi: "10.48550/arXiv.2609.12245"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# DIA: Denoising Intermediate Advantage for Diffusion Policy Optimization

> Arjun Sohal, Yuchi Zhao, Miroslav Bogdanovic, Alan Aspuru-Guzik · 2026
> [arXiv](https://arxiv.org/abs/2609.12245) · [PDF](https://arxiv.org/pdf/2609.12245)

## Abstract

Diffusion-based robot policies have become widely used in robotic manipulation, where they are typically trained with behavior cloning. However, policies trained purely from demonstrations are limited by the quality and coverage of the available data. Reinforcement learning can further improve the performance of these pretrained policies through interaction. A common approach is to use policy-gradient methods that formulate diffusion-policy fine-tuning as an outer environment MDP together with an inner denoising MDP. However, existing methods typically assign the same environment-level credit to all denoising steps used to construct an action chunk, without distinguishing which intermediate decisions contributed most to the final return. We introduce Denoising Intermediate Advantage (DIA), a policy-gradient method that learns a value function over partially denoised actions and uses it to construct a denoising- level advantage for each step of the generative process. DIA com- bines this inner credit signal with the standard environment-level PPO advantage, providing state-dependent credit throughout the denoising chain. Across Robomimic, FurnitureBench, Franka Kitchen, and D3IL, DIA consistently improves final performance over existing diffusion-policy fine-tuning methods. Beyond final reward, DIA reaches successful states more efficiently and can shift farther from the pretrained behavior distribution, enabling it to discover more effective and efficient task-level strategies and subtask sequences that baseline methods fail to reach.

## TL;DR

Diffusion-based robot policies have become widely used in robotic manipulation, where they are typically trained with behavior cloning. However, policies trained purely from demonstrations are limited by the quality and coverage of the available data.

## Related
<!-- [[other-paper-citekey]] -->
