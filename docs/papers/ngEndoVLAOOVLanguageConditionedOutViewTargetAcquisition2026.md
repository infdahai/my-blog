---
citekey: "ngEndoVLAOOVLanguageConditionedOutViewTargetAcquisition2026"
title: "EndoVLA-OOV: Language-Conditioned Out-of-View Target Acquisition in Robotic Endoscopy"
authors: ["Chi Kit Ng", "Yidong Zhang", "Tianchun Wu", "Zhiqing Tang", "Hanlin Zhao", "Siu Hing Lui", "Tao Yang", "Jingsong Lin", "Huxin Gao", "Yeung Trevor", "Raymond Tang", "Hongliang Ren"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.24747"
doi: "10.48550/arXiv.2610.24747"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# EndoVLA-OOV: Language-Conditioned Out-of-View Target Acquisition in Robotic Endoscopy

> Chi Kit Ng, Yidong Zhang, Tianchun Wu, Zhiqing Tang, Hanlin Zhao, Siu Hing Lui, Tao Yang, Jingsong Lin, Huxin Gao, Yeung Trevor, Raymond Tang, Hongliang Ren · 2026
> [arXiv](https://arxiv.org/abs/2610.24747) · [PDF](https://arxiv.org/pdf/2610.24747)

## Abstract

The scan-then-revisit workflow of upper gastrointestinal endoscopy requires bringing a previously observed suspicious region back into view for closer inspection. Acquiring such targets requires translating anatomical and appearance descriptions into camera motions from partial observations of a confined, deformable environment. We present EndoVLA-OOV, a language-conditioned vision-language-action policy for out-of-view target acquisition in robotic endoscopy. The policy adapts a pretrained backbone to continuous two-degree-of-freedom distal bending commands and combines initial, intermediate, and current images to guide search. To support policy learning, we provide an open-source VLA dataset containing 1,050 episodes across six tasks and approximately 262k observation-action pairs. Physical evaluation spans wet-lens and low-light conditions, two unseen stomach phantoms, and cross-embodiment transfer to an unseen ex-vivo environment. In the cross-embodiment evaluation, the full-data policy achieves 93.3% target acquisition success (28/30). In a controlled training-data comparison, expanding the corpus from 312 to 1,050 episodes increases acquisition success from 40.0% to 90.0% under the same model, training, and test configuration. Instruction and observation interventions further support the use of language and temporal context in the evaluated acquisition tasks. These results support language-guided endoscopic revisitation across the evaluated environments and robot embodiments and demonstrate the benefit of expanded task-specific demonstrations.

## TL;DR

The scan-then-revisit workflow of upper gastrointestinal endoscopy requires bringing a previously observed suspicious region back into view for closer inspection. Acquiring such targets requires translating anatomical and appearance descriptions into camera motions from partial observations of a confined, deformable environment.

## Related
<!-- [[other-paper-citekey]] -->
