---
citekey: "zhangLearningUnknownConstraintsWithoutUnsafeDataOptimalityCounterfactual2026"
title: "Learning Unknown Constraints without Unsafe Data via Optimality and Counterfactual Regularization"
authors: ["Zhouyu Zhang", "Chih-Yuan Chiu", "Glen Chou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09350"
doi: "10.48550/arXiv.2610.09350"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# Learning Unknown Constraints without Unsafe Data via Optimality and Counterfactual Regularization

> Zhouyu Zhang, Chih-Yuan Chiu, Glen Chou · 2026
> [arXiv](https://arxiv.org/abs/2610.09350) · [PDF](https://arxiv.org/pdf/2610.09350)

## Abstract

Learning from demonstrations (LfD) provides a framework for inferring unknown constraints from locally optimal, constraint-satisfying expert behavior. Existing approaches largely fall into two paradigms, constrained inverse optimal control (CIOC) and inverse constrained reinforcement learning (ICRL). CIOC exploits optimality conditions such as the Karush--Kuhn--Tucker (KKT) conditions but typically assumes known dynamics and structured constraint representations. Meanwhile, ICRL accommodates complex unknown constraints and unknown transition dynamics but often requires extensive online exploration, during which unsafe constraint violations may occur. In this work, we introduce Counterfactual KKT (CF-KKT), a constraint learning framework that leverages learned dynamics and locally optimal demonstrations to recover unknown constraints without requiring known dynamics or additional risky exploration, thereby combining the data efficiency and safety advantages of CIOC with the flexibility of ICRL. First, we use a locally learned differentiable dynamics model to impose KKT-inspired optimality conditions directly on the demonstrations. Second, we use the learned dynamics to generate reward-improving counterfactual behaviors near the demonstrations, revealing behaviors that would be preferable in the absence of the unknown constraint and thus providing synthetic infeasible data. When the constraint parameterization is known, the same learned-dynamics framework enables direct CIOC-based parameter recovery, and we characterize its sensitivity to dynamics misspecification. Across high-dimensional robotic control tasks, our approach learns neural constraint representations with improved safety and data efficiency relative to state-of-the-art offline ICRL baselines.

## TL;DR

Learning from demonstrations (LfD) provides a framework for inferring unknown constraints from locally optimal, constraint-satisfying expert behavior. Existing approaches largely fall into two paradigms, constrained inverse optimal control (CIOC) and inverse constrained reinforcement learning (ICRL).

## Related
<!-- [[other-paper-citekey]] -->
