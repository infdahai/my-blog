---
citekey: "liTacOTLearningContactRichDexterousManipulationHumanDemonstrations2026"
title: "TacOT: Learning Contact-Rich Dexterous Manipulation from Human Demonstrations via Tactile-Guided Optimal Transport"
authors: ["Xingting Li", "Yifan Han", "Zijian Lin", "Wei Hou", "Chuqiao Lyu", "Shoujie Li", "Wenbo Ding"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04363"
doi: "10.48550/arXiv.2610.04363"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# TacOT: Learning Contact-Rich Dexterous Manipulation from Human Demonstrations via Tactile-Guided Optimal Transport

> Xingting Li, Yifan Han, Zijian Lin, Wei Hou, Chuqiao Lyu, Shoujie Li, Wenbo Ding · 2026
> [arXiv](https://arxiv.org/abs/2610.04363) · [PDF](https://arxiv.org/pdf/2610.04363)

## Abstract

Learning contact-rich dexterous manipulation from human demonstrations provides a scalable source of interaction data, yet transferring such skills to robots remains challenging due to unreliable human--robot correspondence. Existing human-to-robot transfer methods typically rely on visual appearance or motion similarity, which may associate similar motions with different contact states and force patterns. Tactile dynamics provide interaction-aware cues to distinguish manipulation processes with similar motions but different contact states. We introduce tactile-guided optimal transport (TacOT), a framework for human-to-robot contact-rich manipulation. TacOT leverages action--tactile dynamic time warping to identify human--robot demonstration correspondences with consistent interaction dynamics and uses these correspondences to guide soft optimal transport alignment in a shared policy representation space. This enables human demonstrations to provide contact-rich supervision for robot policy learning without requiring predefined frame-level human--robot pairing. Across four real-world dexterous manipulation tasks, TacOT improves closed-loop success rates over action-guided OT by up to 17 points on in-distribution tasks and 20 points under targeted human-to-robot out-of-distribution transfer. Further analyses show that tactile-guided correspondence selects demonstration pairs with more consistent contact dynamics and produces latent representations that better reflect interaction-state evolution. These results demonstrate that tactile dynamics provide an effective semantic signal for establishing reliable human-to-robot correspondence in contact-rich dexterous manipulation.

## TL;DR

Learning contact-rich dexterous manipulation from human demonstrations provides a scalable source of interaction data, yet transferring such skills to robots remains challenging due to unreliable human--robot correspondence. Existing human-to-robot transfer methods typically rely on visual appearance or motion similarity, which may associate similar motions with different contact states and force patterns.

## Related
<!-- [[other-paper-citekey]] -->
