---
citekey: "xinPanelShieldVerifiableClosedLoopSafePlanningIndustrialPanel2026"
title: "PanelShield: Verifiable Closed-Loop Safe Planning for Robotic Industrial Panel Operation"
authors: ["Guipeng Xin", "Jiahe Xu", "Chenhui Wan", "Jie Liu", "Youmin Hu", "Zhongxu Hu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.28305"
doi: "10.48550/arXiv.2608.28305"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-01
---

# PanelShield: Verifiable Closed-Loop Safe Planning for Robotic Industrial Panel Operation

> Guipeng Xin, Jiahe Xu, Chenhui Wan, Jie Liu, Youmin Hu, Zhongxu Hu · 2026
> [arXiv](https://arxiv.org/abs/2608.28305) · [PDF](https://arxiv.org/pdf/2608.28305)

## Abstract

Industrial panel operation is knowledge-intensive and safety-critical. Beyond control recognition and action generation, execution must satisfy constraints in operation manuals and safety regulations. While foundation-model-based planners show strong semantic capability, they typically lack computable, localizable, and reproducible mechanisms for violation detection and repair. To address this, we propose PanelShield, a verifiable closed-loop safety planning framework for manual-guided industrial panel operation. The framework generates parameterized action primitive sequences from task-relevant manual evidence and applies dual formal verification with LTL and a Safety FSM to enforce cross-step temporal correctness and local transition legality. When violations occur, it outputs a structured counterexample with the earliest violating step and cause, enabling targeted repair and re-verification. We build a multi-level long-horizon planning benchmark covering three representative industrial device panels, and evaluate the framework in simulation and real-world robotic experiments. Results show that PanelShield improves complex safety-constrained task performance over foundation-model-only planning baselines while reducing the violation rate to 2.7%, with 4.1 s total latency. Real-world experiments demonstrate end-toend feasibility. Overall, PanelShield offers a verifiable approach to robotic panel operation that balances flexibility, safety, and auditability.

## TL;DR

Industrial panel operation is knowledge-intensive and safety-critical. Beyond control recognition and action generation, execution must satisfy constraints in operation manuals and safety regulations.

## Related
<!-- [[other-paper-citekey]] -->
