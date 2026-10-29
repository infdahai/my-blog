---
citekey: "liRoboRecoverBenchmarkingPolicyRecoveryExecutionDeviations2026"
title: "RoboRecover: Benchmarking Robot Policy Recovery under Execution Deviations"
authors: ["Yang Li", "Chen Zhao", "Zhuoran Wang", "Jiankang Wang", "Chao Shao", "Yihan Lin", "Haitao Shen", "Jing Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28952"
doi: "10.48550/arXiv.2609.28952"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# RoboRecover: Benchmarking Robot Policy Recovery under Execution Deviations

> Yang Li, Chen Zhao, Zhuoran Wang, Jiankang Wang, Chao Shao, Yihan Lin, Haitao Shen, Jing Zhang · 2026
> [arXiv](https://arxiv.org/abs/2609.28952) · [PDF](https://arxiv.org/pdf/2609.28952)

## Abstract

Robot-policy benchmarks increasingly cover diverse tasks and preset out-of-distribution conditions, but typically evaluate complete trajectories from predefined initial states. These evaluations often focus on the initialized scene and the final outcome, while paying less attention to the dynamic interaction process. During closed-loop execution, actions and contacts can alter object relations and task progress, producing off-nominal intermediate states that need recovery. Recovery requires a policy to infer how task progress has changed, correct the relevant relations, and continue the original goal. We introduce RoboRecover, a benchmark for robot policy recovery under execution deviations. RoboRecover selects deviation states from trajectories, reconstructs them by replaying action prefixes, and evaluates policies on the original task. RoboRecover contains 2,000 scenarios across RoboTwin and LIBERO, with 1,000 scenarios and a fixed 800/200 train/test split on each platform. Results show that initial-state performance does not determine recovery performance and policies exhibit different recovery strengths across scenarios. Using its training split, RoboRecover further supports study on recovery interventions. RoboRecover establishes recovery from execution-induced intermediate states as a distinct dimension of robot policy evaluation.

## TL;DR

Robot-policy benchmarks increasingly cover diverse tasks and preset out-of-distribution conditions, but typically evaluate complete trajectories from predefined initial states. These evaluations often focus on the initialized scene and the final outcome, while paying less attention to the dynamic interaction process.

## Related
<!-- [[other-paper-citekey]] -->
