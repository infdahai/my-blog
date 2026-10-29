---
citekey: "singhSeeQTrainingGeneralistValueFunctionsLongHorizonManipulation2026"
title: "SeeQ: Training Generalist Value Functions for Long-Horizon Robotic Manipulation"
authors: ["Saksham Singh", "Zheyuan Hu", "Max Sobol Mark", "Jeffrey Yu", "Zackory Erickson", "Aviral Kumar"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.22085"
doi: "10.48550/arXiv.2609.22085"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# SeeQ: Training Generalist Value Functions for Long-Horizon Robotic Manipulation

> Saksham Singh, Zheyuan Hu, Max Sobol Mark, Jeffrey Yu, Zackory Erickson, Aviral Kumar · 2026
> [arXiv](https://arxiv.org/abs/2609.22085) · [PDF](https://arxiv.org/pdf/2609.22085)

## Abstract

Despite rapid progress, generalist robot policies remain brittle on complex, long-horizon tasks that comprise multiple stages or require repeated attempts and deliberation on the same underlying stage before success. Q-value functions can improve these policies by ranking candidate actions or guiding policy improvement, but learning from sparse task-level rewards entails long credit-assignment horizons, difficult Bellman backups, and broad data-coverage requirements. We introduce SeeQ (Subtask-elicited Q-functions), which instead learns Q-values for the currently active subtask. This shortens the value-prediction horizon and enables effective learning with temporal-difference (TD) objectives. During training, subtask-level annotations present in offline robot data provide the decomposition and enable learning from broad, potentially suboptimal robot datasets. To eliminate the need for human annotations or modular subtask prediction systems at test time, our Q-function architecture is trained to autoregressively predict the active subtask in natural language before estimating its value. We instantiate SeeQ using a base vision-language backbone, pretrain it on diverse open-source robot manipulation data, and finetune it on downstream tasks. Across four real-world manipulation tasks on two bimanual robot platforms, the SeeQ value function substantially improves best-of-N policy steering.

## TL;DR

Despite rapid progress, generalist robot policies remain brittle on complex, long-horizon tasks that comprise multiple stages or require repeated attempts and deliberation on the same underlying stage before success. Q-value functions can improve these policies by ranking candidate actions or guiding policy improvement, but learning from sparse task-level rewards entails long credit-assignment horizons, difficult Bellman backups, and broad data-coverage requirements.

## Related
<!-- [[other-paper-citekey]] -->
