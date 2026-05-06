---
layout: page
title: EMCE
description: A fast CUDA/C++ Monte Carlo options pricing framework.
img:
importance: 2
redirect: https://github.com/KYLChiu/ExoticMonteCarloEngine
---

A Monte Carlo framework for pricing exotic derivatives in C++, designed to switch seamlessly between CUDA (GPU) and multithreaded CPU environments.

**Key features:**
- CUDA acceleration for high-throughput simulation
- CPU fallback with multithreading via standard C++ primitives
- Flexible payoff definitions for exotic instruments
- Designed for correctness and performance parity across backends
