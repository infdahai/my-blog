---
citekey: "plepiSlotDiTObjectCentricRepresentationsDiffusionTransformers2026"
title: "SlotDiT: Object-Centric Representations for Diffusion Transformers"
authors: ["Gjergj Plepi", "Sven Behnke"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.17414"
doi: "10.48550/arXiv.2609.17414"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# SlotDiT: Object-Centric Representations for Diffusion Transformers

> Gjergj Plepi, Sven Behnke · 2026
> [arXiv](https://arxiv.org/abs/2609.17414) · [PDF](https://arxiv.org/pdf/2609.17414)

## Abstract

Text-conditioned latent diffusion models perform strongly in video generation and are promising backbones for robotic applications. However, existing approaches rely on pixel-level or VAE-based latent representations that lack explicit semantic structure, leaving the impact of the representation space largely unexplored. Slot-based object-centric representations offer a structured alternative by decomposing scenes into object-level latents, or slots. While they have shown success in dynamics modeling and planning, they have not yet been explored for diffusion-based generative modeling. We introduce SlotDiT, a text-guided Diffusion Transformer (DiT) that operates in a slot-based latent space. Given a reference image and a language instruction, SlotDiT decomposes the scene into object-centric slots representing individual entities. Conditioned on the instruction and observed scene context, the model autoregressively denoises future slot trajectories to predict scene dynamics. To systematically investigate latent-space design for diffusion transformers, we compare slot-based representations against VAE-based and semantics-aligned alternatives within a unified DiT framework. Our experiments show that using slots as DiT latents yields competitive video generation quality while consistently improving task-completion rates across four robotic datasets. Furthermore, their compact representation provides a computationally efficient alternative to VAE-based and semantics-aligned latent spaces. Overall, our results demonstrate that object-centric structure is a powerful inductive bias for diffusion-based generative modeling in robotic environments. The project page is available at https://slot-dit.github.io/.

## TL;DR

Text-conditioned latent diffusion models perform strongly in video generation and are promising backbones for robotic applications. However, existing approaches rely on pixel-level or VAE-based latent representations that lack explicit semantic structure, leaving the impact of the representation space largely unexplored.

## Related
<!-- [[other-paper-citekey]] -->
