---
title: "jVMC: Versatile and performant variational Monte Carlo leveraging automated differentiation and GPU acceleration"
date: 2022-10-03T16:20:41+02:00
draft: false
image: 
authors: "Markus Schmitt and Moritz Reh"
preprint: false
journalref: "SciPost Phys. Codebases 2 (2022)"
journalurl: "https://scipost.org/submissions/2108.03409v2/"
year: 2022
arXiv: 2108.03409
highlight: false
tags:
categories:
---

The introduction of Neural Quantum States (NQS) has recently given a new twist to variational Monte Carlo (VMC). The ability to systematically reduce the bias of the wave function ansatz renders the approach widely applicable. However, performant implementations are crucial to reach the numerical state of the art. Here, we present a Python codebase that supports arbitrary NQS architectures and model Hamiltonians. Additionally leveraging automatic differentiation, just-in-time compilation to accelerators, and distributed computing, it is designed to facilitate the composition of efficient NQS algorithms.