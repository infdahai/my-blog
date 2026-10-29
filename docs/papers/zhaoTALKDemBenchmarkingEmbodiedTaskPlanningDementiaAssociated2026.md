---
citekey: "zhaoTALKDemBenchmarkingEmbodiedTaskPlanningDementiaAssociated2026"
title: "TALK-Dem: Benchmarking Embodied Task Planning under Dementia-Associated Communication Patterns"
authors: ["Guangxin Zhao", "Yiran Hu", "Yuan Cao", "Chenxi Jiang", "Jianfei Yang", "Yegang Du", "Yasuyuki Taki", "Yoshifumi Kitamura", "Lin Gu", "Zhi Zheng"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.38371"
doi: "10.48550/arXiv.2609.38371"
tags: [paper, embodied-ai, "cs.CL", "cs.RO"]
status: unread
rating:
created: 2026-10-04
---

# TALK-Dem: Benchmarking Embodied Task Planning under Dementia-Associated Communication Patterns

> Guangxin Zhao, Yiran Hu, Yuan Cao, Chenxi Jiang, Jianfei Yang, Yegang Du, Yasuyuki Taki, Yoshifumi Kitamura, Lin Gu, Zhi Zheng · 2026
> [arXiv](https://arxiv.org/abs/2609.38371) · [PDF](https://arxiv.org/pdf/2609.38371)

## Abstract

Existing LLM-driven robot task planners rely on a taken-for-granted assumption of an ideal user whose instructions are clear, complete, and task-focused. However, when interacting with real-world users, especially those experiencing cognitive impairments, such as people living with dementia (PLWD), the planners often make mistakes and even pose physical safety risks. We proposed TALK-Dem (Talking Attributes and Linguistic Knowledge in Dementia), the first benchmark for evaluating LLM-driven robot task planning under dementia-associated verbal communication. TALK-Dem contains 4,800 instructions and covers five typical communication patterns, including Referential Imprecision, Object Substitution, Empty Speech, Topic Drift, and Intrusion, at three intensity levels. Experiments across six open-weight LLMs reveal a substantial robustness gap. Across communication patterns, open-weight models exhibited performance drops of up to 22.3 percentage points compared to ideal instructions. This revealed a critical gap and even danger for real-world applications, especially in assistive robotics, where locally deployable models are necessary due to privacy concerns and connectivity constraints. To mitigate this issue, we proposed the Context-Aware Retrieval from Experience (CARE) method, which retrieves relevant previously resolved tasks to provide task-specific interpretation and planning context. CARE generally outperformed standard prompting baselines across the six open-weight models, improving average task success by 18.1 percentage points over the vanilla prompt. These results highlighted the importance of both evaluating communication robustness and developing effective adaptation strategies for locally deployable assistive robots. The TALK-Dem dataset is publicly available at https://anonymous.4open.science/r/TALK-Dem-A6B3/.

## TL;DR

Existing LLM-driven robot task planners rely on a taken-for-granted assumption of an ideal user whose instructions are clear, complete, and task-focused. However, when interacting with real-world users, especially those experiencing cognitive impairments, such as people living with dementia (PLWD), the planners often make mistakes and even pose physical safety risks.

## Related
<!-- [[other-paper-citekey]] -->
