---
title: "Time-dependent variational Monte Carlo without bias"
date: 2026-05-06T09:58:16+02:00
draft: false
image: 
authors: W. Krinitsin and M. Schmitt
preprint: true
journalref:
journalurl:
year: 2026
arXiv: 2605.03930
highlight: false
tags:
categories:
---

When combined with highly expressive ansatz functions such as neural quantum states, variational Monte Carlo (VMC) constitutes a versatile numerical approach to tackle the quantum many-body problem in and out of equilibrium. However, its traditional formulation exhibits a subtle estimation bias leading to inaccuracies, which can be particularly detrimental when addressing real time dynamics. In this work, we investigate two avenues to circumvent said estimation bias. First, we propose an unbiased variant of time-dependent VMC using self-normalized importance sampling with respect to a cutoff-based deformation of the Born distribution. We demonstrate the feasibility and accuracy of the approach in pathological and generic cases of quench dynamics. Furthermore, we explore an alternative sampling strategy based on active learning via the tensor cross interpolation (TCI). While we find that our choice of tensor network architecture lacks the required low rank property, the proposed TCI-based algorithm complements the conventional importance sampling paradigm, providing an alternative perspective that may be further explored in future work.
