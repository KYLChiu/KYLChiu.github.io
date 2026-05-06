---
layout: archive
permalink: /
title: "Kelvin Chiu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Software engineer with a strong interest in **high-performance computing**, **quantitative finance**, and **applied mathematics**. I build systems where correctness, performance, and elegance all matter.

---

## What I Work On

I spend most of my time at the intersection of low-latency systems and numerical methods — the kind of problems that demand both rigorous algorithmic thinking and careful implementation.

**Languages:** C++20, Python, CUDA  
**Interests:** Concurrent programming, Monte Carlo methods, game-tree search, derivative pricing

---

## Projects

A few things I've built:

- **[Sporkfish](https://github.com/KYLChiu/sporkfish)** — A Python chess engine using recursive minimax with alpha-beta pruning, accelerated with Numba JIT.
- **[EMCE](https://github.com/KYLChiu/ExoticMonteCarloEngine)** — A CUDA/C++ Monte Carlo framework for pricing exotic derivatives, with seamless GPU/CPU switching.
- **[Kutils](https://github.com/KYLChiu/Kutils)** — A C++20 library with lock-free queues, thread pooling, and future chaining primitives.

See the full [Portfolio](/portfolio/) for more.

---

## A Python Puzzle

```python
f = lambda i: i
g = f
print(g(1))        # what does this print?
g = lambda x: g(x) + 1
print(g(1))        # and this?
```

Think carefully before you run it.

---

Feel free to reach out at [kchiu1997@gmail.com](mailto:kchiu1997@gmail.com) or connect on [LinkedIn](https://linkedin.com/in/kelvin-chiu) / [GitHub](https://github.com/kylchiu).
