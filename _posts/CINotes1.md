---
title: 'Causality Inference Notes1: Learning causality and causality-related learning: some recent progress'
date: 2018-01-09
permalink: /2018/CINotes1/
tags:
  - Causality Inference
  - Paper Notes

---
**Identify** causal relation from **observational data**.

Correlation does not directly imply causation. 
However, 
it has been shown that under various sets of assumptions, 
the underlying causal structure over a set of r.vs can be recovered from their observational data,
at least to some extent.

**Conditional independence** has been exploited to discover causal structure since 1990s:
1. PC: asymptotically correct, no confounder assumption.
2. FCI: asymptotically correct, w. confounder assumption.
(How to evaluate the correctness?)
They output equivalent classes (and graphical repr. of them)
i.e. a set of causal structures satisfying the conditional indenpences.
(What is a causal structure?)
So, they do not necessarily provide complete causal info.
(Why?)


