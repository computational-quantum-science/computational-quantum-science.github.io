---
title: "Neural quantum states"
date: 2022-09-26T20:40:06+02:00
draft: false
tags: 
image: "/images/research/nqs_image.png"
icon: "/images/research/icons/nqs.svg"
categories: 
summary: NQS is cool
---

Devising efficient and broadly applicable schemes for the simulation of correlated quantum matter is a paramount challenge in computational physics and different regimes of physical interest are still beyond the scope of the established techniques. New numerical methods based on the recently introduced neural quantum states (NQS) can potentially allow us to overcome some of the existing limitations, e.g., to simulate non-equilibrium dynamics of two-dimensional systems.

The underlying idea is that the proven capabilities of neural networks in pattern recognition and generalization make them well-suited for the representation of many-body wave functions. Since neural networks are universal function approximators in the limit of large network sizes, arbitrary quantum states can be represented as NQS in principle. This means that NQS can render variational Monte Carlo techniques numerically exact, which were previously limited by the inductive bias of the chosen ansatz wave functions. The utility of NQS has been outlined in a number of fundamental works gauging their potential to overcome current limitations of other methods for both low-energy physics and non-equilibrium dynamics. In addition to expressiveness, NQS inherit the neural network’s amenability to leverage large-scale supercomputing resources. Therefore, NQS- based methods can allow us to push the boundaries of classical computing for quantum many-body simulations.

## Directions

At this point, a central obstacle to the further development is our limited understanding of what are good NQS architectures, how (quantum) information is encoded, and what generally defines their scope. Better illuminating these issues could have conceptual implications far beyond methodological progress – similar to tensor networks, which fundamentally shaped our current understanding of quantum information and condensed matter.