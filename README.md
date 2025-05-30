# rieman-sum
# Numerical Integration using Riemann Sums (with Pthreads)

This program estimates the definite integral of a function using the **Riemann Sum** method and parallelizes the computation using **Pthreads** in C.

---

## 📌 Overview

We approximate the integral of a function `f(x)` over a specified interval `[a, b]` by dividing it into `n` rectangles. The work is split among multiple threads to improve performance on multi-core systems.

---

## 🛠️ How to Compile

Use the following command in the terminal:

```bash
gcc -o riemann riemann_integral.c -lpthread
