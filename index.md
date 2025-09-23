---
layout: single
author_profile: true
---

# About Me

I am a postdoctoral researcher at the [University of Münster](https://www.uni-muenster.de/en/) in Germany. My work focuses on compiler technologies---code generation and optimization---as well as programming language design for parallel architectures, including GPUs and CPUs, based on formal methods. My central research goal is to advance *Performance*, *Portability*, and *Productivity* for data-parallel computations, with a particular emphasis on computations relevant to deep learning (e.g., linear algebra routines and stencil computations).

To pursue this goal, I am the principal designer of a holistic code *Generation* & *Optimization* & *Execution* approach, structured into three major sub-projects:

1. [Multi-Dimensional Homomorphisms (MDH)](https://mdh-lang.org) (*Code Generation*)---a novel algebraic formalism for expressing and reasoning formally about optimizations for data-parallel computations. This project includes the design and specification of a Domain-Specific Language (DSL) for expressing data-parallel computations, as well as the development of a compiler for this DSL. Our compiler generates code (e.g., in CUDA, OpenMP, and OpenCL) that can be automatically optimized (auto-tuned) for contemporary parallel architectures.

2. [Auto-Tuning Framework (ATF)](https://atf-tuner.org) (*Code Optimization*)---a general-purpose auto-tuning approach that automatically optimizes parallel programs with constrained optimization parameters. For this, ATF introduces novel processes for generating, storing, and exploring the search spaces of constrained optimization parameters.

3. [Host Code Abstraction (HCA)](https://hca-project.org) (*Code Execution*)---a high-level programming abstraction that simplifies implementing and optimizing so-called host code which is required in modern parallel programming approaches (e.g., CUDA and OpenCL) to execute code on the devices of (potentially distributed) multi-device systems.

You can find my CV [here](assets/files/cv_rasch.pdf).

PhD Thesis is available [here](assets/files/phd_rasch.pdf); Diploma Thesis [here](assets/files/diploma_rasch.pdf) (German).
