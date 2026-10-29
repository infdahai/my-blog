---
citekey: "wangRoboCasaShiftStageAwareRobustnessEvaluationVisionLanguage2026"
title: "RoboCasa-Shift: Stage-Aware Robustness Evaluation of Vision-Language-Action Policies in Long-Horizon Household Manipulation"
authors: ["Haocheng Wang", "Youquan Liu", "Weiyu Guo", "Aokai Zhang", "Donghang Wu", "Hongyu Liu", "Sha Zhang", "Weidong Yang", "Ben Fei"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.27861"
doi: "10.48550/arXiv.2610.27861"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# RoboCasa-Shift: Stage-Aware Robustness Evaluation of Vision-Language-Action Policies in Long-Horizon Household Manipulation

> Haocheng Wang, Youquan Liu, Weiyu Guo, Aokai Zhang, Donghang Wu, Hongyu Liu, Sha Zhang, Weidong Yang, Ben Fei · 2026
> [arXiv](https://arxiv.org/abs/2610.27861) · [PDF](https://arxiv.org/pdf/2610.27861)

## Abstract

Vision-language-action (VLA) robustness is commonly summarized by aggregate task success, which obscures how individual executions change under distribution shifts and where failures emerge in long-horizon tasks. We introduce \textbf{RoboCasa-Shift}, a diagnostic robustness benchmark built on RoboCasa365 that combines controlled single-factor shifts, matched clean-perturbed rollouts in which each pair shares the same underlying settings and differs only in the target shift, and simulator-grounded stage-aware diagnostics. We evaluate GR00T N1.5 on four long-horizon tasks that pass a predefined clean-performance gate under four perturbation factors and three calibrated severity levels, including conditions that drive the evaluated policy to complete task failure, totaling 1,040 formal rollouts. Robustness responses vary substantially across factors and tasks, and increasing severity does not always produce monotonic degradation. For example, one camera condition yields $\Delta\mathrm{SR}=0$ despite 8 of 80 matched episodes changing outcome. Stage-aware analysis further shows that the same end-to-end degradation can correspond to different execution-depth profiles. Camera $L_2$ and Gaussian blur $L_1$ both yield $\Delta\mathrm{SR}=0.188$, yet their first-stage failure rates are 19.0\% and 36.4\%, respectively. Our findings suggest that VLA robustness should be viewed as a multi-dimensional property of execution rather than a single end-to-end performance measure, motivating evaluation protocols that jointly capture outcome degradation, paired outcome sensitivity, and failure progression. The code is publicly available at https://github.com/HaochengWang23/RoboCasa-Shift.

## TL;DR

Vision-language-action (VLA) robustness is commonly summarized by aggregate task success, which obscures how individual executions change under distribution shifts and where failures emerge in long-horizon tasks. We introduce \textbf{RoboCasa-Shift}, a diagnostic robustness benchmark built on RoboCasa365 that combines controlled single-factor shifts, matched clean-perturbed rollouts in which each pair shares the same underlying settings and differs only in the target shift, and simulator-grounded stage-aware diagnostics.

## Related
<!-- [[other-paper-citekey]] -->
