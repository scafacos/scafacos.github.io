---
title: Methods
layout: main
---

The following methods are currently included in the ScaFaCoS software library.

## FMM
The corresponding developer of this method is [Ivo Kabadshow](./support.html#fmm).

## MEMD
The corresponding developer of this method is [Florian Fahrenberger](./support.html#memd).

## P<sup>2</sup>NFFT
The particle-particle NFFT (P<sup>2</sup>NFFT) is a general framework for particle mesh
algorithms based on nonequispaced fast Fourier transforms ([NFFT](http://www-user.tu-chemnitz.de/~potts/nfft/)).
By appropriate choice of parameters, this framework includes the Particle-Mesh Ewald methods
for periodic boundary conditions and the fast summation algorithm
for non-periodic boundary conditions.

The corresponding developer of this method is [Michael Pippig](./support.html#p2nfft).

## P<sup>3</sup>M
The corresponding developer of this method is [Olaf Lenz](./support.html#p3m).

## PEPC
The corresponding developer of this method is [Mathias Winkel](./support.html#pepc).

## PP3MG
The corresponding developer of this method is [Matthias Bolten](./support.html#pp3mg).

## VMG
The versatile multi grid (VMG) is a multi-grid based method implemented in C++
with strong emphasis on modularity in terms of employed iterative
solver, domain decomposition, and interpolation schemes. It is a general framework
for solving PDEs on multi-core architectures and offers a range of modules for
plugging together a suitable multi-grid algorithm. For Coulomb interactions so
far only periodic boundary conditions are supported.

The corresponding developer of this method is [Julian Iseringhausen](./support.html#vmg).
