---
citekey: "wangBehaviorWorldGenClosingLoopBetweenActionModelsWorldSimulators2026"
title: "BehaviorWorldGen: Closing the Loop between Action Models and World Simulators via Controllable Behavior-Aware Structured World Generation"
authors: ["Jiaqi Wang", "Zhuo Zhang", "Haining Guan", "Tingguang Zhou", "Haowen Cui", "Zhongyang Zhu", "Yulong Zheng", "ChuanYe Wang", "Xuefeng Chen", "Zhen Yang", "Tianchen Deng", "Feiyang Tan", "Hangning Zhou", "Bo Dai", "Lixia Shen", "Xiwu Chen", "Xiyang Wang", "Jiajun Zhu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.22187"
doi: "10.48550/arXiv.2608.22187"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# BehaviorWorldGen: Closing the Loop between Action Models and World Simulators via Controllable Behavior-Aware Structured World Generation

> Jiaqi Wang, Zhuo Zhang, Haining Guan, Tingguang Zhou, Haowen Cui, Zhongyang Zhu, Yulong Zheng, ChuanYe Wang, Xuefeng Chen, Zhen Yang, Tianchen Deng, Feiyang Tan, Hangning Zhou, Bo Dai, Lixia Shen, Xiwu Chen, Xiyang Wang, Jiajun Zhu · 2026
> [arXiv](https://arxiv.org/abs/2608.22187) · [PDF](https://arxiv.org/pdf/2608.22187)

## Abstract

Modern driving action models are increasingly improved in a self-improvement loop, where a learned world simulator imagines future observations and the resulting data is fed back to refine the action model. However, the bottleneck of this loop lies in the simulators' inability to generate behaviorally plausible responses by surrounding agents, making generated data both unrealistic in interaction and imbalanced in distribution. We introduce BehaviorWorldGen, a framework that closes the loop between action models and world simulators through controllable behavior-aware structured world generation. Its core component is BehaviorFlow, a meta-action-conditioned traffic-flow model that injects interpretable behavior controls and jointly generates multi-agent rollouts. BehaviorFlow realizes the specified agent behaviors while allowing surrounding vehicles to respond to the ego and to one another. The resulting rollouts are rendered by a world simulator into realistic multi-view observations, which are paired with corrected interaction-aware trajectories for action-model refinement. Since BehaviorWorldGen uses structured trajectories as the interface between its modules, it is compatible with diverse action models and world simulators. Experiments on world generation, scene extrapolation, and policy refinement demonstrate consistent improvements, with the largest benefits concentrated on difficult interactive scenarios.

## TL;DR

Modern driving action models are increasingly improved in a self-improvement loop, where a learned world simulator imagines future observations and the resulting data is fed back to refine the action model. However, the bottleneck of this loop lies in the simulators' inability to generate behaviorally plausible responses by surrounding agents, making generated data both unrealistic in interaction and imbalanced in distribution.

## Related
<!-- [[other-paper-citekey]] -->
