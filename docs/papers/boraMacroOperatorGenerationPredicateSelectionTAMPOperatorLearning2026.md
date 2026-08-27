---
citekey: "boraMacroOperatorGenerationPredicateSelectionTAMPOperatorLearning2026"
title: "Macro-Operator Generation and Predicate Selection for TAMP Operator Learning"
authors: ["Can Emir Bora", "Emre Ugur"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.23629"
doi: "10.48550/arXiv.2608.23629"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Macro-Operator Generation and Predicate Selection for TAMP Operator Learning

> Can Emir Bora, Emre Ugur · 2026
> [arXiv](https://arxiv.org/abs/2608.23629) · [PDF](https://arxiv.org/pdf/2608.23629)

## Abstract

Creating symbolic operators by hand is one of the main bottlenecks in deploying Task and Motion Planning systems (TAMP). Recent works show that these operators can instead be learned directly from demonstration data. Existing methods, however, typically learn each action in isolation and cannot capture the recurring multi-step structure of manipulation tasks, so the search becomes intractable on long sequential tasks. A further inefficiency arises in the symbolic state: every provided predicate is evaluated at every search node, even when it never appears in any learned operator. We present a system that addresses both problems together. Its central component is the automatic generation of macro-operators, composite actions that compress a recurring sequence of individual actions into a single planning step. Our system discovers causally linked action pairs directly from the training data, where one action produces exactly the condition that the next one requires, and turns each pair into a new operator. Alongside this, our system prunes every predicate that no learned operator references, which shrinks the symbolic state evaluated at each search node. Together, these changes shorten the effective planning horizon, and the benefit they bring grows with the length of the task. Across four TAMP domains, our method reaches up to a 4.6x planning speedup compared to the baseline method, namely Learning Operators for TAMP. More importantly, it solves a long sequential task that the baseline cannot solve. Macro-operator discovery thus not only accelerates planning but, in certain domains, determines solvability in practice.

## TL;DR

Creating symbolic operators by hand is one of the main bottlenecks in deploying Task and Motion Planning systems (TAMP). Recent works show that these operators can instead be learned directly from demonstration data.

## Related
<!-- [[other-paper-citekey]] -->
