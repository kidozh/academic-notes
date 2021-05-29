---
title: Finite element modeling of drilling process
date: "2021-05-24T14:03:00.284Z"
description: "Finite element modelling in drilling process"
categories: [introduction]
comments: true
---

# Typical approaches

There are two main ways of approaching problems that involve the motion of deformable materials - the Lagrangian way and the Eulerian way. These approaches are distinguished by three important aspects: [^2]

1. The mesh description.
2. The stress tensor and momentum equation (kinetics).
3. The strain measure (kinematics).

## Lagrangian approach

It tracks discrete material point and use a use a predetermined line of separation at tool tip, then propagating a fictitious crack ahead of tool. This method precludes the resolution of the cutting edge radius and accurate resolution of the secondary shear zone due to severe mesh distortion.[^1]

## Eulerian approach

It tracks volumes rather than material particles and doesn't not have the burden of remeshing distorted meshes. However, steady state free-surface tracking algorithms were necessary and relied on assumptions such as uniform chip thickness, not allowing the modeling of milling processes or segmented chip formation.

# References

[^1]: Marusich, T. D., Usui, S., Ma, J., Stephenson, D. A., & Shih, A. (2007). Finite element modeling of drilling processes with solid and indexable tooling in metals and stack-ups.
[^2]: https://en.wikiversity.org/wiki/Nonlinear_finite_elements/Lagrangian_and_Eulerian_descriptions



