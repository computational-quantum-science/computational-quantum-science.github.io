---
title: "Neural Quantum States and Peaked Molecular Wave Functions: Curse or Blessing?"
date: 2024-08-15T18:50:55+01:00
draft: false
image: 
authors: A. Malyshev, M. Schmitt, A. I. Lvovsky
preprint: true
journalref:
journalurl:
year: 2024
arXiv: 2408.07625
highlight: false
tags:
categories: NQS
---

The field of neural quantum states has recently experienced a tremendous progress, making them a competitive tool of computational quantum many-body physics. However, their largest achievements to date mostly concern interacting spin systems, while their utility for quantum chemistry remains yet to be demonstrated. Two main complications are the peaked structure of the molecular wave functions, which impedes sampling, and large number of terms in second quantised Hamiltonians, which hinders scaling to larger molecule sizes. In this paper we address these issues jointly and argue that the peaked structure might actually be key to drastically more efficient calculations. Specifically, we introduce a novel algorithm for autoregressive sampling without replacement and a procedure to calculate a computationally cheaper surrogate for the local energy. We complement them with a custom modification of the stochastic reconfiguration optimisation technique and a highly optimised GPU implementation. As a result, our calculations require substantially less resources and exhibit more than order of magnitude speedup compared to the previous works. On a single GPU we study molecules comprising up to 118 qubits and outperform the ``golden standard'' CCSD(T) benchmark in Hilbert spaces of about 10^15 Slater determinants, which is orders of magnitude larger than what was previously achieved. We believe that our work underscores the prospect of NQS for challenging quantum chemistry calculations and serves as a favourable ground for the future method development.
