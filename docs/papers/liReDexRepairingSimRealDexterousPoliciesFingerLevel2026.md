---
citekey: "liReDexRepairingSimRealDexterousPoliciesFingerLevel2026"
title: "ReDex: Repairing Sim-to-Real Dexterous Policies by Finger-Level Compliant Interaction"
authors: ["Jinzhou Li", "Hadi Tabatabaee", "Kelin Yu", "Yuyin Sun", "Cheng-Hao Kuo", "Roberto Martín-Martín", "Nima Fazeli", "X. Alice Wu", "Xianyi Cheng"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07525"
doi: "10.48550/arXiv.2610.07525"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# ReDex: Repairing Sim-to-Real Dexterous Policies by Finger-Level Compliant Interaction

> Jinzhou Li, Hadi Tabatabaee, Kelin Yu, Yuyin Sun, Cheng-Hao Kuo, Roberto Martín-Martín, Nima Fazeli, X. Alice Wu, Xianyi Cheng · 2026
> [arXiv](https://arxiv.org/abs/2610.07525) · [PDF](https://arxiv.org/pdf/2610.07525)

## Abstract

Dexterous manipulation policies trained in simulation often fail to transfer to the real world because of errors in contact timing and force regulation. Yet these policies can retain useful multi-finger coordination for task progression. We propose ReDex, a framework for adapting a simulation-trained base policy to the real world by correcting local contact failures and incorporating tactile feedback. Starting from a proprioception-only base policy, ReDex allows a human operator to physically correct contact failures at selected fingers under compliant control during real-world rollouts, while the frozen base policy continues to control the remaining fingers. These rollouts combine base policy execution, human-corrected finger motion, and fingertip force observations. We reconstruct force-informed targets from these rollouts to train a standalone force-conditioned policy via behavior cloning. This design reduces human correction effort, enables learning of contact regulation from real-world interaction, and introduces force feedback into a proprioception-only policy without tactile simulation or complex full-hand teleoperation. We evaluate ReDex on two challenging, contact-rich dexterous manipulation tasks on real hardware. Compared with sim-to-real transferred base policies, ReDex increases Object Flipping success rate from 14\% to 86\% across two objects and average Screwdriver Rotation progress from 26.0% to 95.3% across three objects.

## TL;DR

Dexterous manipulation policies trained in simulation often fail to transfer to the real world because of errors in contact timing and force regulation. Yet these policies can retain useful multi-finger coordination for task progression.

## Related
<!-- [[other-paper-citekey]] -->
