---
title: "Reinforcement learning pulses for transmon qubit entangling gates"
date: 2023-11-09T09:40:55+01:00
draft: false
image: 
authors: H.N. Nguyen, F. Motzoi, M. Metcalf, K.B. Whaley, M. Bukov, M. Schmitt
preprint: false
journalref: "Machine Learning: Science and Technology 5, 025066 (2024)"
journalurl: "https://doi.org/10.1088/2632-2153/ad4f4d"
year: 2024
arXiv: 2311.03684
highlight: false
tags:
categories:
---

The utility of a quantum computer depends heavily on the ability to reliably perform accurate quantum logic operations. 
For finding optimal control solutions, it is of particular interest to explore model-free approaches, since their quality 
is not constrained by the limited accuracy of theoretical models for the quantum processor - in contrast to many 
established gate implementation strategies. In this work, we utilize a continuous-control reinforcement learning algorithm 
to design entangling two-qubit gates for superconducting qubits; specifically, our agent constructs cross-resonance and CNOT 
gates without any prior information about the physical system. Using a simulated environment of fixed-frequency, 
fixed-coupling transmon qubits, we demonstrate the capability to generate novel pulse sequences that outperform the 
standard cross-resonance gates in both fidelity and gate duration, while maintaining a comparable susceptibility to 
stochastic unitary noise. We further showcase an augmentation in training and input information that allows our agent to 
adapt its pulse design abilities to drifting hardware characteristics, importantly with little to no additional optimization. 
Our results exhibit clearly the advantages of unbiased adaptive-feedback learning-based optimization methods for transmon 
gate design.
