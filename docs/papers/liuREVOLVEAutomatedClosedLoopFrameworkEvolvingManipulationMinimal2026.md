---
citekey: "liuREVOLVEAutomatedClosedLoopFrameworkEvolvingManipulationMinimal2026"
title: "REVOLVE: An Automated Closed-Loop Framework for Evolving Robot Manipulation with Minimal Human Intervention"
authors: ["Hanyu Liu", "Qian Li", "Yizhu Ding", "Jiayi Wen", "Keqiang Ren", "Yunsheng Ma", "Tao Jian", "Zhihua Wang", "Zhuofan Yu", "Xinran Li", "Zhigong Song"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.14633"
doi: "10.48550/arXiv.2609.14633"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# REVOLVE: An Automated Closed-Loop Framework for Evolving Robot Manipulation with Minimal Human Intervention

> Hanyu Liu, Qian Li, Yizhu Ding, Jiayi Wen, Keqiang Ren, Yunsheng Ma, Tao Jian, Zhihua Wang, Zhuofan Yu, Xinran Li, Zhigong Song · 2026
> [arXiv](https://arxiv.org/abs/2609.14633) · [PDF](https://arxiv.org/pdf/2609.14633)

## Abstract

Recent advances in data-driven robot manipulation policies have substantially improved task execution and generalization. However, real-world deployment still relies heavily on humans for failure assessment, correction, and environment reset, while models often fail to continually learn from failures and corrective experience. We present REVOLVE (Robot Evolving via Orchestrated Loops, Verification, and Experience), an automated closed-loop framework for evolving robot manipulation with minimal human intervention. Built on a unified software platform, REVOLVE integrates data collection, policy training and deployment, failure recovery, and continual learning into a single closed-loop workflow. Its Automated Reset and Collection (ARC) architecture automatically resets the environment and intervenes to correct policy failures. Dual-Loop Evolution (DLE) continually improves the manipulation policy and agent by feeding real-world interaction and failure--correction data back into policy learning and using an external mismatch memory to refine agent judgments. Experiments across four real-world manipulation tasks show that, after five iterations, REVOLVE improves average policy success rate by 18.5% and agent judgment accuracy by 8.5%, while reducing human effort in data collection and deployment testing by 94.4% and 95.1%, respectively. These results demonstrate that REVOLVE transforms real-world deployment into a closed-loop learning process that continually accumulates and uses execution experience, enabling continual evolution of both the policy and supervisory model with substantially less human intervention.

## TL;DR

Recent advances in data-driven robot manipulation policies have substantially improved task execution and generalization. However, real-world deployment still relies heavily on humans for failure assessment, correction, and environment reset, while models often fail to continually learn from failures and corrective experience.

## Related
<!-- [[other-paper-citekey]] -->
