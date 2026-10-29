---
citekey: "wangWhoTrustMultiSystemsJointObjectHypothesisTrust2026"
title: "Who to Trust in Multi-Robot Systems: Joint Robot and Object Hypothesis Trust Inference via Neural-Symbolic Cross-Validation"
authors: ["Ruiyang Wang", "Hao-Lun Hsu", "Haocheng Meng", "Songqiao Xie", "Miroslav Pajic"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14530"
doi: "10.48550/arXiv.2610.14530"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# Who to Trust in Multi-Robot Systems: Joint Robot and Object Hypothesis Trust Inference via Neural-Symbolic Cross-Validation

> Ruiyang Wang, Hao-Lun Hsu, Haocheng Meng, Songqiao Xie, Miroslav Pajic · 2026
> [arXiv](https://arxiv.org/abs/2610.14530) · [PDF](https://arxiv.org/pdf/2610.14530)

## Abstract

Multi-robot systems (MRS) offer significant advantages over single-robot platforms by enabling information sharing and coordination for different tasks in complex environments. However, reliable cooperation critically depends on inferring trust over both information sources and their reported hypotheses, particularly under partial observability and potential adversarial interference. Existing approaches frequently depend on pre-established trust relationships or side-channel information, which may not be available or reliable in realistic MRS deployments. This work introduces NeST-Bayes, a neural-symbolic framework that jointly infers robot and hypothesis trust using only inter-robot observation consistency, without requiring preassigned robot trust, reputation information, or side-channel identity signals. NeST-Bayes infers instantaneous trust evidence scores for robots and object hypotheses by reasoning over ego-centric relational graphs constructed from cross-robot observation consistency. These evidence scores are accumulated over time through Bayesian updates of Beta-distributed trust beliefs to maintain temporally consistent trust estimates. Extensive evaluations show that NeST-Bayes achieves the highest mean object precision and robot recall across all benchmark settings, and the highest robot precision and object recall in most settings, compared to trust-based methods. Under aggressive optimized attacks, it achieves 98.8\% robot precision with 93.8\% recall and 98.3\% object precision with 95.4\% recall. In an occlusion-rich Webots warehouse, it maintains 92.5\% robot precision with 92.0\% recall and 97.3\% object precision with 85.0\% recall. These results demonstrate joint improvements in the reliability and coverage of retained information.

## TL;DR

Multi-robot systems (MRS) offer significant advantages over single-robot platforms by enabling information sharing and coordination for different tasks in complex environments. However, reliable cooperation critically depends on inferring trust over both information sources and their reported hypotheses, particularly under partial observability and potential adversarial interference.

## Related
<!-- [[other-paper-citekey]] -->
