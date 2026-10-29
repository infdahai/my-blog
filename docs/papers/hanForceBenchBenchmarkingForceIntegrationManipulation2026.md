---
citekey: "hanForceBenchBenchmarkingForceIntegrationManipulation2026"
title: "ForceBench: Benchmarking Force Integration for Robotic Manipulation"
authors: ["Xuan Han", "Zinuo Jin", "Tianlin Li", "Yunfan Lou", "Xin Liu", "Yuchen Xue", "Yuanpeng He", "Boxian Yao", "Shuhan Zhan", "Ruihai Wu", "Zhibo Pang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19604"
doi: "10.48550/arXiv.2610.19604"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# ForceBench: Benchmarking Force Integration for Robotic Manipulation

> Xuan Han, Zinuo Jin, Tianlin Li, Yunfan Lou, Xin Liu, Yuchen Xue, Yuanpeng He, Boxian Yao, Shuhan Zhan, Ruihai Wu, Zhibo Pang · 2026
> [arXiv](https://arxiv.org/abs/2610.19604) · [PDF](https://arxiv.org/pdf/2610.19604)

## Abstract

Force feedback provides vision-language-action (VLA) policies with physical observations that can guide action selection and execution. However, differences in tasks, demonstrations, and control settings across existing systems hinder reliable comparisons of force integration designs. We introduce ForceBench, a simulation benchmark for evaluating six-axis wrist-force integration under a unified protocol. ForceBench combines eight tasks spanning physical-property inference, resistance-dependent interaction, and contact-rich assembly with 1,600 synchronized demonstrations and task-specific success criteria. We compare one no-force baseline and six force integration designs on a shared $\pi_{0.5}$ backbone. Prompt Fusion achieves the highest observed mean simulation success of 35.31%, compared with 23.25% for the baseline, and improves success rates across all three task categories. Predictive and temporal gains in simulation concentrate on physical-property inference, while both temporal designs underperform the baseline on assembly. Real-world evaluation of eight systems across five tasks supports the main qualitative trends: Prompt Fusion and Dual-Path Fusion achieve 63.00% mean success, compared with 40.00% for the baseline, but only Prompt Fusion improves every task. These findings support ForceBench's practical value for identifying the benefits and limitations of force integration across manipulation demands. The project page is available at https://forcebench-platform.github.io/.

## TL;DR

Force feedback provides vision-language-action (VLA) policies with physical observations that can guide action selection and execution. However, differences in tasks, demonstrations, and control settings across existing systems hinder reliable comparisons of force integration designs.

## Related
<!-- [[other-paper-citekey]] -->
