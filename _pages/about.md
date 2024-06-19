---
permalink: /
title: "Welcome, and..."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

```cpp
std::cout << "Hello World!\n"; 
```
---

Hi! I'm a Python/C++ quantitative developer with interests spanning across software engineering, mathematics and finance. I hold a bachelors degree in Mathematics from the University of Warwick and a masters degree in Mathematical and Computational Finance from Oxford University.

---

Stay tuned to hear occasional rants about how Python is so much easier to develop in compared to C++, or how much faster C++ is compared to Python (looking at you, GIL!). I'll probably sporadically (or rather, stochastically) throw in a volatility related topic as well.

A short Python puzzle to get us acquainted:
```python
f = lambda i: i
g = f
g = lambda x: g(x) + 1
print(g(1))
```
What goes wrong, why does it go wrong and how would you fix it without changing the (non-default) function signature of `g`? 


