---
citekey: "baoNavSafeInftyBenchmarkingClosedLoopDrivingSafetyPhotorealistic2026"
title: "NavSafe-$\infty$: Benchmarking Closed-Loop Driving Safety in Photorealistic Environments"
authors: ["Yuxin Bao", "Hongwei Ruan", "Luobin Wang", "Seth Z. Zhao", "Ziyang Leng", "Zihan Zhang", "Yu Zeng", "Rowan McAllister", "Henrik Christensen", "Bolei Zhou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.26618"
doi: "10.48550/arXiv.2609.26618"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-24
---

# NavSafe-$\infty$: Benchmarking Closed-Loop Driving Safety in Photorealistic Environments

> Yuxin Bao, Hongwei Ruan, Luobin Wang, Seth Z. Zhao, Ziyang Leng, Zihan Zhang, Yu Zeng, Rowan McAllister, Henrik Christensen, Bolei Zhou · 2026
> [arXiv](https://arxiv.org/abs/2609.26618) · [PDF](https://arxiv.org/pdf/2609.26618)

## Abstract

End-to-end (E2E) driving policies have progressed rapidly on open-loop (OL) benchmarks, yet OL evaluation cannot reveal whether a policy withstands compounding errors, recovers from failures, or interacts safely with surrounding actors. We introduce NavSafe-$\infty$, a photorealistic closed-loop (CL) benchmark of 280 scenarios spanning 28 event types, each with success and failure criteria defined within a structured traffic-safety taxonomy, which yields category-level capability scores for Traffic Crashes, Vulnerable Road User Crashes, Traffic Violations, and Traffic Incidents. Evaluating 20 E2E policies, we find that OL gains do not reliably transfer to CL safety. Analyzing two common remedies further shows that passive demonstration perturbation helps mainly when CL rollouts stay near its perturbed training states, and that OL reinforcement-learning fine-tuning exhibits reward hacking by trading safety margin for ego progress, which CL feedback amplifies into compounding safety-critical errors. Together, these results demonstrate the blind spot of OL benchmarks indicating CL safety success. The benchmark and an extensible toolbox for customizable event curation and policy diagnosis will be open-sourced and maintained to facilitate future research.

## TL;DR

End-to-end (E2E) driving policies have progressed rapidly on open-loop (OL) benchmarks, yet OL evaluation cannot reveal whether a policy withstands compounding errors, recovers from failures, or interacts safely with surrounding actors. We introduce NavSafe-$\infty$, a photorealistic closed-loop (CL) benchmark of 280 scenarios spanning 28 event types, each with success and failure criteria defined within a structured traffic-safety taxonomy, which yields category-level capability scores for Traffic Crashes, Vulnerable Road User Crashes, Traffic Violations, and Traffic Incidents.

## Related
<!-- [[other-paper-citekey]] -->
