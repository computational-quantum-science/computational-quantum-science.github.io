---
title: "Reinforcement learning for quantum control"
date: 2022-09-26T20:40:06+02:00
draft: false
tags: 
image: 
icon: "/images/research/icons/rlqc.svg"
categories: 
summary: RL is cool
---

The ability to precisely manipulate a quantum system is fundamental for the successful realization of quantum computing. In the case of superconducting qubits, for example, the implementation of an arbitrary quantum algorithm boils down to applying a specific sequence of electromagnetic pulses corresponding to the desired circuit of unitary gates. Generally, finding optimal control protocols is often a challenging en- deavor due to the exponential size of spaces of possible protocols. The quantum world poses additional obstacles, because quantum states cannot be directly observed and – in the context of NISQ technology – we are often lacking accurate models for the physical systems, which account for the current imperfections of the devices.

In optimal control theory a cost functional asserts the quality of control protocols and the variational minimization of the cost yields optimal strategies. On this basis, various algorithms have been developed to achieve quantum optimal control, which can be largely separated into two classes – gradient-based algorithms and gradient-free algorithms. Gradient-based methods require the ability to evaluate the cost function as well as the variational derivatives. Exploiting knowledge about the gradients typically enables fast convergence, but a microscopic model for the dynamics of the physical system is required. Gradient-free algorithms, on the other hand, rely solely on evaluations of the cost function, enabling optimization of non-differentiable cost or in the absence of microscopic models.

Reinforcement learning (RL) falls into the category of gradient-free approaches. In the RL framework an artificial intelligence (AI) called the agent is trained to solve a given task by interacting with an environment. The agent can take actions and observe their effect on the state of the environment. Additionally, the agent is given a reward for each action taken, which indicates its usefulness for the given task and thereby enables the agent to improve the policy followed when proposing actions. As such, the RL framework matches the control problem at the core of quantum computation, namely to manipulate the available control knobs such that the resulting evolution corresponds to the desired quantum operation. And, in fact, first studies show that quantum control benefits from specific features of RL algorithms, namely robustness in the presence of noise and in complex control landscapes, non-local exploration, and reacting to feedback as a part of the strategy.

In our research we aim to tap the full potential of RL to facilitate high-precision control of NISQ devices. Thereby, RL-enhanced NISQ devices will provide a further boost towards relevant applications. Further interesting aspects are the tradeoff between accuracy and incomplete information within the RL framework and the possible identification of previously unknown characteristics of the quantum devices from the control strategies developed by the AI.