---
title: "An Order-Optimal Square-Root Bound for Online Maximin Share Allocation with Known Types"
collection: publications
category: working
permalink: /publication/online-mms-known-types
date: 2026-11-24
status: "arXiv preprint arXiv:2611.31732, 2026"
link: "https://arxiv.org/abs/2611.31732"
paperurl: "https://arxiv.org/pdf/2611.31732"
codeurl: "https://github.com/EsperZhou/online-mms-lean/tree/lean-v1.0.1"
excerpt: "Deterministic online maximin share (MMS) allocation of indivisible goods when the k possible additive valuations are known in advance: the optimal guarantee is of order Θ(1/√k). [[arXiv](https://arxiv.org/abs/2611.31732)] [[Lean 4 formalization](https://github.com/EsperZhou/online-mms-lean/tree/lean-v1.0.1)]"
---

**Abstract.** An allocator knows the indivisible goods, the number n of agents, and the k possible additive valuations. Each agent reveals their type on arrival and must immediately receive an irrevocable bundle. Kulkarni, Mehta, and Shahkar established a deterministic guarantee of 1/k of maximin share (MMS) and an upper bound of 2/(√k − 2) for k > 4. We determine the optimal order Θ(k<sup>−1/2</sup>) by constructing a deterministic polynomial-time algorithm, Single-or-Select. On every arrival sequence, it gives each agent a fraction (1/√2 − o(1))/√k of their truncated proportional share. This share dominates MMS and is the largest target y for which the item values capped at y sum to at least ny. By specializing the construction of Kulkarni et al. to two arrivals and counting its types exactly, we sharpen the upper bound to (√2 + o(1))/√k even for binary valuations. For two arrivals with binary valuations and every k ≥ 2, the optimal fraction is 1/p, where p is the largest integer with 1 + C(2p, 2) ≤ k. In particular, up to six binary types permit full maximin share. For two arbitrary additive types, a different polynomial-time algorithm guarantees 4/7 of maximin share for any number of agents. This ratio is tight for the algorithm. With three arrivals and two types, the optimal deterministic fraction is exactly 9/10. For randomized policies with k known additive types, the optimal MMS fraction guaranteed to all agents with probability at least 1 − δ on every fixed arrival sequence is Θ(max{k<sup>−1/2</sup>, √δ}) for 0 ≤ δ < 1.

**Links:** [arXiv:2611.31732](https://arxiv.org/abs/2611.31732) · [PDF](https://arxiv.org/pdf/2611.31732) · [Lean 4 formalization](https://github.com/EsperZhou/online-mms-lean/tree/lean-v1.0.1)
