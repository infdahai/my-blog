---
citekey: "scardecchiaVideoWorldModelsNeedPredictableLatents2026"
title: "Video World Models Need Predictable Latents"
authors: ["Mattia Scardecchia", "Sherry Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.34663"
doi: "10.48550/arXiv.2610.34663"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# Video World Models Need Predictable Latents

> Mattia Scardecchia, Sherry Yang · 2026
> [arXiv](https://arxiv.org/abs/2610.34663) · [PDF](https://arxiv.org/pdf/2610.34663)

## Abstract

Video world models trained on large-scale robot data promise a safe and scalable approach for learning and evaluating policies that act in the physical world. However, they still struggle with long-horizon rollouts and out-of-distribution generalization, and they remain computationally demanding at inference time. Typically, video world models make predictions in the latent space of a reconstruction-trained autoencoder, which however is not directly optimized for dynamics modeling. On the other hand, world models designed for latent planning usually optimize latents to be predictable, but they forgo accurate prediction of observations in pixel space. In this paper, we show that it is possible to achieve the best of both worlds: a latent geometry optimized to make future prediction as simple as possible without sacrificing accurate prediction of future observations. More precisely, we find that temporal objectives for representation learning, paired with a past-conditioned decoder architecture, lead to consistent improvements in generative video world models at the same training budget. The gains include up to 5x cheaper inference, over 7x faster training, and 15-24% lower pixel and perceptual errors out of distribution and over long horizons. Our world models also agree more closely with real-world policy evaluation when using a vision-language model to judge task success from their pixel-space predictions. Overall, our study indicates that temporal predictability is an important design criterion for the latent space of video world models, and provides concrete guidance on how to incorporate it into the training of autoencoders.

## TL;DR

Video world models trained on large-scale robot data promise a safe and scalable approach for learning and evaluating policies that act in the physical world. However, they still struggle with long-horizon rollouts and out-of-distribution generalization, and they remain computationally demanding at inference time.

## Related
<!-- [[other-paper-citekey]] -->
