---
citekey: "ramdhanSceneGraphBasedDrivingScenarioExtractionAutomotiveEgocentric2026"
title: "Scene Graph-based Driving Scenario Extraction for Automotive Egocentric Datasets"
authors: ["Stefan Ramdhan", "Kyanna Dagenais", "Vera Pantelic", "Victor Bandur", "Mark Lawford"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.00333"
doi: "10.48550/arXiv.2609.00333"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-04
---

# Scene Graph-based Driving Scenario Extraction for Automotive Egocentric Datasets

> Stefan Ramdhan, Kyanna Dagenais, Vera Pantelic, Victor Bandur, Mark Lawford · 2026
> [arXiv](https://arxiv.org/abs/2609.00333) · [PDF](https://arxiv.org/pdf/2609.00333)

## Abstract

Extracting scenarios from unlabelled real-world sensor data streams is a critical but challenging task in the development process of automated driving systems (ADS). Automatically sifting through large datasets to spatially and temporally locate critical scenarios can enable scenario-based coverage analysis of ADS datasets. In this paper, we present a method for extracting scenarios from egocentric datasets using scene graphs and Linear Temporal Logic (LTL). We first process egocentric sensor data and HD maps to generate a sequence of scene graphs representing a driving scenario. Next, we use LTL to formally specify driving scenarios of interest, then extract all instances of the scenarios from the dataset using an off-the-shelf model checker, which evaluates the LTL formula against the sequence of scene graphs. Our approach can be used on both simulated and real world datasets. We evaluate the method on the training and validation datasets from Argoverse 2 consisting of 850 15-second real-world driving logs, and several videos of dashcam footage. We demonstrate the effectiveness of our approach for extracting and querying scenarios by evaluating against a rule-based benchmark based on track annotations and HD maps.

## TL;DR

Extracting scenarios from unlabelled real-world sensor data streams is a critical but challenging task in the development process of automated driving systems (ADS). Automatically sifting through large datasets to spatially and temporally locate critical scenarios can enable scenario-based coverage analysis of ADS datasets.

## Related
<!-- [[other-paper-citekey]] -->
