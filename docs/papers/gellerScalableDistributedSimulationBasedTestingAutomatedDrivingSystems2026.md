---
citekey: "gellerScalableDistributedSimulationBasedTestingAutomatedDrivingSystems2026"
title: "Scalable Distributed Simulation-Based Testing for Automated Driving Systems"
authors: ["Christian Geller", "Benedikt Haas", "Lutz Eckstein"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.20904"
doi: "10.48550/arXiv.2608.20904"
tags: [paper, embodied-ai, "cs.DB", "cs.RO", "cs.SE"]
status: unread
rating:
created: 2026-08-27
---

# Scalable Distributed Simulation-Based Testing for Automated Driving Systems

> Christian Geller, Benedikt Haas, Lutz Eckstein · 2026
> [arXiv](https://arxiv.org/abs/2608.20904) · [PDF](https://arxiv.org/pdf/2608.20904)

## Abstract

Virtual scenario-based testing is a key enabler for validating automated driving systems (ADS) and intelligent transport systems (ITS). However, executing large-scale test suites involving possibly thousands of scenarios remains labor-intensive and difficult to scale. This paper presents an end-to-end, DevOps-driven framework that automates build, deployment, and distributed execution of CARLA-based scenario tests of an ADS on a lightweight Kubernetes cluster. ROS 2 applications are packaged as standardized Kubernetes Helm charts generated from repository specifications, while entire simulation environments are composed declaratively via dynamic Helmfile manifests. The paper describes how a distributed testing workflow can be implemented in Argo Workflows to provision environments, aggregate and batch OpenSCENARIO test cases from configurable sources, execute scenarios in parallel across cluster nodes, and collect logs and resource metrics. In an evaluation on a multi-node K3s cluster running 200 scenarios, the best configuration speeds up end-to-end workflow time by more than a factor of eight compared to a sequential baseline. The results demonstrate significant gains in end-to-end execution time and quantify trade-offs between parallelism, orchestration overhead, and cluster stability. The framework is further demonstrated in a real-world ADS test application with connections to scenario sources and downstream evaluation modules. This demonstrates that the approach provides a strong foundation not only for scalable simulation testing, but also for generating traceable evidence that can support safety arguments.

## TL;DR

Virtual scenario-based testing is a key enabler for validating automated driving systems (ADS) and intelligent transport systems (ITS). However, executing large-scale test suites involving possibly thousands of scenarios remains labor-intensive and difficult to scale.

## Related
<!-- [[other-paper-citekey]] -->
