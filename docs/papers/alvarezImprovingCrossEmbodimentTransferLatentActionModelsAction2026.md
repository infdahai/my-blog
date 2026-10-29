---
citekey: "alvarezImprovingCrossEmbodimentTransferLatentActionModelsAction2026"
title: "Improving Cross-embodiment Transfer in Latent Action Models with Action-Similarity Supervision"
authors: ["Maxime Alvarez", "Renzo Caballero", "Tatsuya Matsushima", "Yusuke Iwasawa", "Yutaka Matsuo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.19846"
doi: "10.48550/arXiv.2609.19846"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-18
---

# Improving Cross-embodiment Transfer in Latent Action Models with Action-Similarity Supervision

> Maxime Alvarez, Renzo Caballero, Tatsuya Matsushima, Yusuke Iwasawa, Yutaka Matsuo · 2026
> [arXiv](https://arxiv.org/abs/2609.19846) · [PDF](https://arxiv.org/pdf/2609.19846)

## Abstract

As generalist robot policies gain vision and language from web-scale pretraining, demonstrations remain costly to collect and tied to the robot that recorded them. Latent action models (LAMs) address both by learning latent actions from action-free videos that can be shared across embodiments, however, in practice, LAMs are sensitive to background visual noise, and the same motion from two different robots may be encoded with different latents. One solution to the background visual noise is to add an auxiliary loss predicting the robot action from the latent action, further associating the latent action space to the embodiment specific robot action space. We study a different use of the same labels, through action-similarity supervision. The similarity between any two latent actions is trained to match the similarity of the two ground-truth robot action sequences. The ground-truth actions are never predicted by the LAM, so the latent action does not need to encode embodiment specifics. We evaluate cross-embodiment transfer on RoboTwin 2.0 in a controlled setup, two bimanual robots demonstrate disjoint task sets, a policy is trained on all the demonstrations, and each robot is evaluated closed-loop on the tasks only the other demonstrated. With the policy architecture and its hyperparameters, the dataset, and the evaluation protocol fixed, predicting latent actions instead of ground-truth actions more than doubles cross-embodiment success. Given the same ground-truth actions, similarity supervision transfers better than an auxiliary loss that predicts the ground-truth action during the LAM training. Computing the similarities on end-effector motion rather than joint-space motion, and letting the loss compare latent actions across the two robots, gives the best approach of the study.

## TL;DR

As generalist robot policies gain vision and language from web-scale pretraining, demonstrations remain costly to collect and tied to the robot that recorded them. Latent action models (LAMs) address both by learning latent actions from action-free videos that can be shared across embodiments, however, in practice, LAMs are sensitive to background visual noise, and the same motion from two different robots may be encoded with different latents.

## Related
<!-- [[other-paper-citekey]] -->
