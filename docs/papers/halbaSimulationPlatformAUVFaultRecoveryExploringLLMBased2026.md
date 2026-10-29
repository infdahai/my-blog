---
citekey: "halbaSimulationPlatformAUVFaultRecoveryExploringLLMBased2026"
title: "A Simulation Platform for AUV Fault Recovery: Exploring LLM-Based Diagnostic Strategies"
authors: ["Khalid Halba", "Kylie Cooper", "James G. Bellingham"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.20620"
doi: "10.48550/arXiv.2609.20620"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-19
---

# A Simulation Platform for AUV Fault Recovery: Exploring LLM-Based Diagnostic Strategies

> Khalid Halba, Kylie Cooper, James G. Bellingham · 2026
> [arXiv](https://arxiv.org/abs/2609.20620) · [PDF](https://arxiv.org/pdf/2609.20620)

## Abstract

Autonomous underwater vehicles (AUVs) operating beyond reliable communications must recover from failures without human intervention. We investigate an architecture in which conventional deterministic layered control autonomy manages normal operations, while an invokable large language model (LLM) serves as a diagnostic and recovery planner when onboard anomaly detection identifies performance outside expected limits. Because language models are stochastic, rigorous evaluation requires ensemble testing rather than individual demonstrations. We present a closed-loop simulation architecture that couples real-time C vehicle software with a higher-level orchestration layer for physics-based fault injection, structured prompting, language-model interaction, mission file generation, validation, execution, and LLM-judge scoring. The framework, which we call SPAR (Simulation Platform for AUV Recovery), supports evaluation across fault realizations, prompt structures, reasoning models, and mission conditions. We vary these for a mass-shift fault over 480 SPAR trials, evaluating a frontier model and three off-the-shelf locally deployable LLMs. Model choice dominates diagnosis: the frontier model places the CG-shift mechanism in its top three hypotheses in 85-90% of trials, versus 60-78% for the best local model. Reasoning analysis indicates that local-model success is associated with following the complete diagnostic procedure, whereas weaker models often commit prematurely to elevator failure even though the actuator tracks its command. Diagnosis and operational decision performance do not appear to be coupled in this dataset. The contributions are an architecture extending unanticipated-fault recovery from detection to mitigation and an ensemble methodology for evaluating LLM-assisted mission management on low-power AUVs.

## TL;DR

Autonomous underwater vehicles (AUVs) operating beyond reliable communications must recover from failures without human intervention. We investigate an architecture in which conventional deterministic layered control autonomy manages normal operations, while an invokable large language model (LLM) serves as a diagnostic and recovery planner when onboard anomaly detection identifies performance outside expected limits.

## Related
<!-- [[other-paper-citekey]] -->
