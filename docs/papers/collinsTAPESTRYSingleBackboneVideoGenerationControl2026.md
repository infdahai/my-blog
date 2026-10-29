---
citekey: "collinsTAPESTRYSingleBackboneVideoGenerationControl2026"
title: "TAPESTRY: A Single Backbone for Video Generation and Robot Control"
authors: ["Jeremy A. Collins", "Seungjae Lee", "Rachanon Wachakorn", "Krishnan Srinivasan", "Animesh Garg", "Vitor Campagnolo Guizilini", "Paarth Shah"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.36823"
doi: "10.48550/arXiv.2610.36823"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# TAPESTRY: A Single Backbone for Video Generation and Robot Control

> Jeremy A. Collins, Seungjae Lee, Rachanon Wachakorn, Krishnan Srinivasan, Animesh Garg, Vitor Campagnolo Guizilini, Paarth Shah · 2026
> [arXiv](https://arxiv.org/abs/2610.36823) · [PDF](https://arxiv.org/pdf/2610.36823)

## Abstract

Pretrained video generation models encode rich priors about physical interactions, but leveraging them for robot control typically requires either resource-intensive video generation at test time or action heads trained from scratch that do not fully utilize the pretrained backbone. We introduce Tokenizing Actions as Video Patches in a Shared Transformer Policy (TAPESTRY), a world action model that repurposes a pretrained video diffusion transformer into a robotic policy without requiring video generation at inference. Our key idea is to treat robot actions as single-patch tokens in the video model's latent space. A lightweight linear projection maps each action timestep to the patch dimensions of the pretrained VAE, and the resulting tokens are processed by the same patchifying layers and transformer backbone used for video. The shared backbone is optimized through three diffusion objectives sampled per minibatch element: Video diffusion uses VAE latents from robot and human videos to establish dynamics priors. Joint video+action diffusion trains on robot demonstrations using a coupled diffusion timestep and an asymmetric attention mask. Action-only diffusion denoises actions conditioned on clean image latents. At test time, the model generates a compact action token sequence in a single DDIM step from pure noise, producing smooth action chunks at 84 ms per action chunk on consumer hardware and avoiding the cost of full video generation. Across simulation benchmarks and real-robot experiments, TAPESTRY achieves strong performance with substantially lower inference cost than comparable joint video--action policies. More information can be found at https://tapestry-wam.github.io.

## TL;DR

Pretrained video generation models encode rich priors about physical interactions, but leveraging them for robot control typically requires either resource-intensive video generation at test time or action heads trained from scratch that do not fully utilize the pretrained backbone. We introduce Tokenizing Actions as Video Patches in a Shared Transformer Policy (TAPESTRY), a world action model that repurposes a pretrained video diffusion transformer into a robotic policy without requiring video generation at inference.

## Related
<!-- [[other-paper-citekey]] -->
