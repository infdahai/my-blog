---
citekey: "dezDualVariationalAutoencodersEfficientSimRealTransferLow2026"
title: "Dual Variational Autoencoders for Efficient Sim-to-Real Transfer in Low-Cost Robotic Navigation"
authors: ["Álvaro Díez", "Fidel Aznar"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.06327"
doi: "10.48550/arXiv.2610.06327"
tags: [paper, embodied-ai, "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# Dual Variational Autoencoders for Efficient Sim-to-Real Transfer in Low-Cost Robotic Navigation

> Álvaro Díez, Fidel Aznar · 2026
> [arXiv](https://arxiv.org/abs/2610.06327) · [PDF](https://arxiv.org/pdf/2610.06327)

## Abstract

Vision-based autonomous navigation for low-cost robots remains a fundamental challenge, primarily due to the significant gap between simulated training environments and real-world operational conditions. Direct policy transfer from simulation is often ineffective, while training exclusively on real data is impractical. We propose a hybrid transfer learning framework that effectively bridges the sim-to-real gap by combining domain randomization with feature-level domain adaptation. Our method employs a dual convolutional variational autoencoder architecture with a shared decoder, trained on an extensive set of 45225 simulated images and a minimal set of only 4556 real-world samples. This architecture learns a compact, common latent representation space that aligns the distributions of both domains. The adaptation process is further enhanced by two complementary data augmentation techniques designed to expand the limited real-world data. Experimental evaluation demonstrates that our method achieves an average success rate of almost 91% on image classification tasks for real-world indoor navigation, significantly outperforming both simulation-only and real-world-only training. We validate these findings through a direct, real-world deployment, where the proposed policy successfully guides a low-cost robot in a reactive exploration task. Furthermore, we validate the model's efficiency through a rigorous computational estimation, confirming its suitability for resource-constrained embedded platforms such as the Raspberry Pi 4 and NVIDIA Jetson Nano. This work presents a practical solution for developing effective and efficient navigation policies for low-cost robotic systems.

## TL;DR

Vision-based autonomous navigation for low-cost robots remains a fundamental challenge, primarily due to the significant gap between simulated training environments and real-world operational conditions. Direct policy transfer from simulation is often ineffective, while training exclusively on real data is impractical.

## Related
<!-- [[other-paper-citekey]] -->
