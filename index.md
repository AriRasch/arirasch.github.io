---
layout: single
author_profile: true
---

# About Me

I am a PhD student at the University of Münster in Germany. My research focuses on compiler technologies -- code generation and optimization -- as well as programming language design for multi- and many-core architectures, such as GPU and CPU, based on formal methods. My overall research goal is to provide *Performance*, *Portability*, and *Productivity* for data-parallel computations with particular focus on computations relevant for deep learning platforms (e.g., linear algebra routines and stencil computations).

To achieve my goals, I am one of the main designers of a holistic code *Generation* & *Optimization* & *Execution* approach, consisting of three major sub-projects:

1. [Multi-Dimensional Homomorphisms (MDH)](https://mdh-lang.org) -- a novel algebraic formalism for expressing and reasoning formally about data-parallel computations. In particular, this project includes the design and specification of a Domain-Specific Language (DSL) for expressing MDH functions, as well as the design and implementation of a compiler for this DSL -- the compiler enables automatically generating code for MDHs (e.g., in CUDA, OpenMP, or OpenCL) that can be automatically optimized (auto-tuned) for state-of-the-art GPUs and CPUs;

2. [Auto-Tuning Framework (ATF)](https://atf-tuner.org) -- a general-purpose auto-tuning approach that automatically optimizes parallel programs, based on numerical search techniques and optimized processes of generating, storing, and exploring the optimization spaces of state-of-the-art parallel programs;

3. [Host Code Abstract (HCA)](https://hca-project.org) -- a high-level programming abstraction that simplifies implementing and optimizing so-called *host code* which is required in modern parallel programming approaches (e.g., CUDA and OpenCL) to execute code on the devices of distributed, heterogeneous systems.

You can find my CV [here](assets/files/cv_schulze.pdf).