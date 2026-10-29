---
citekey: "wangCounterfactualVideoGenerationEnablesScalableHumanoidLocoManipulation2026"
title: "Counterfactual Video Generation Enables Scalable Humanoid Loco-Manipulation"
authors: ["Zihan Wang", "Zhen Wu", "Pieter Abbeel", "Rocky Duan", "Jitendra Malik", "Carmelo Sferrazza", "C. Karen Liu", "Guanya Shi", "Angjoo Kanazawa"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.38172"
doi: "10.48550/arXiv.2609.38172"
tags: [paper, embodied-ai, "cs.CV", "cs.GR", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Counterfactual Video Generation Enables Scalable Humanoid Loco-Manipulation

> Zihan Wang, Zhen Wu, Pieter Abbeel, Rocky Duan, Jitendra Malik, Carmelo Sferrazza, C. Karen Liu, Guanya Shi, Angjoo Kanazawa · 2026
> [arXiv](https://arxiv.org/abs/2609.38172) · [PDF](https://arxiv.org/pdf/2609.38172)

## Abstract

Teaching humanoids loco-manipulation skills, such as carrying diverse objects, via visual imitation is a promising path toward generalist robots. However, collecting diverse, high-quality interaction videos, such as clips that clearly show a person's full body and unoccluded interactions with objects, poses a practical barrier to scaling this approach. We propose PRISM, a real-to-sim-to-real framework that overcomes this limitation by amplifying a handful of real videos into a large, diverse training set. PRISM first generates hundreds of diverse "counterfactual" human-object interaction videos via video-to-video (V2V) generation from a few exemplar real videos. Our contact-anchored real-to-sim pipeline then reconstructs both human and object motions, retargeting this imperfect video data into physically plausible trajectories. The intra-class variability across these counterfactual videos lets us train a single policy that generalizes to unseen objects within each category. We demonstrate the full pipeline by deploying this policy on a real robot without any real-world fine-tuning. Using only onboard depth observations, our humanoid picks up, carries, and drops objects, including boxes, barrels, bins, and balls, across novel instances, sizes, and initial configurations.

## TL;DR

Teaching humanoids loco-manipulation skills, such as carrying diverse objects, via visual imitation is a promising path toward generalist robots. However, collecting diverse, high-quality interaction videos, such as clips that clearly show a person's full body and unoccluded interactions with objects, poses a practical barrier to scaling this approach.

## Related
<!-- [[other-paper-citekey]] -->
