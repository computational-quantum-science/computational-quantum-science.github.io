---
title: "Many-body dynamics with explicitly time-dependent neural quantum states"
date: 2024-12-17T07:45:41+01:00
draft: false
image: 
authors: Anka Van de Walle, Markus Schmitt, Annabelle Bohrdt
preprint: true
journalref:
journalurl:
year: 2024
arXiv: "2412.11830"
highlight: false
tags:
categories:
---

Simulating the dynamics of many-body quantum systems is a significant challenge, especially in higher dimensions where entanglement grows rapidly. Neural quantum states (NQS) offer a promising tool for representing quantum wavefunctions, but their application to time evolution faces scaling challenges. We introduce the time-dependent neural quantum state (t-NQS), a novel approach incorporating explicit time dependence into the neural network ansatz. This framework optimizes a single, time-independent set of parameters to solve the time-dependent Schrödinger equation across an entire time interval. We detail an autoregressive, attention-based transformer architecture and techniques for extending the model's applicability. To benchmark and demonstrate our method, we simulate quench dynamics in the 2D transverse field Ising model and the time-dependent preparation of the 2D antiferromagnetic state in a Heisenberg model, demonstrating state of the art performance, scalability, and extrapolation to unseen intervals. These results establish t-NQS as a powerful framework for exploring quantum dynamics in strongly correlated systems.
