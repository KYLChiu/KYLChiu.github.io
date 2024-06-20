---
layout: archive
permalink: /
title: "Hello World"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
---

Hi! I'm a Python/C++ quantitative developer with interests spanning across software engineering, mathematics and finance. I completed a bachelors degree in Mathematics at Warwick University and a masters degree in Mathematical and Computational Finance at Oxford University.

Stay tuned for the occasional discussion about the joys and frustrations of using Python and C++. You'll hear about how Python makes development a breeze, or how C++ usually runs circles around Python in terms of speed (thanks, GIL!). And don't be surprised if I occasionally (or stochastically) dive into a topic related to volatility.

A short Python puzzle to get us acquainted:
```python
f = lambda i: i
g = f
print(g(1))
g = lambda x: g(x) + 1
print(g(1))
```
What should we expect the output of this code to be? 
