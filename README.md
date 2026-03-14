# Pi-approximations
Here are some python scripts that I've created which approximate the constant Pi, some are famous pi formulas and others I have derived myself!
This repository contains a collection of Python implementations exploring different mathematical methods for approximating **π**. The goal of this project is to experiment with classical and modern formulas for π, understand how they arise mathematically, and compare their convergence and efficiency.

Many of the formulas implemented here were recreated through personal experimentation and numerical exploration, while others are well-known results from mathematicians such as Euler, Ramanujan, and the Chudnovsky brothers.

The scripts focus on series expansions, infinite products, numerical methods, and convergence acceleration techniques.

---

## Contents

### Basic Series Approximations
- **`approximating pi.py`**  
  A basic implementation of a simple π approximation method for comparison.

- **`approximating pi leibniz.py`**  
  Implements the classic **Leibniz series**  
  \[
  \frac{\pi}{4} = 1 - \frac{1}{3} + \frac{1}{5} - \frac{1}{7} + \dots
  \]  
  A historically important but very slowly converging series.

- **`approximating pi nilakantha.py`**  
  Uses the **Nilakantha series**, which converges significantly faster than the Leibniz series.

---

### Series Derived from Trigonometric Expansions
- **`arcsine maclaurin series.py`**  
  Uses the Maclaurin expansion of the arcsine function to derive an approximation for π.

- **`cosine infinite product pi approximation.py`**  
  Investigates infinite product identities involving cosine that lead to π.

---

### Advanced Series and Number Theory
- **`ramanujan sata type pi sum.py`**  
  Implements a Ramanujan-style rapidly converging series for π.

- **`best pi approximation ever (chudnovsky).py`**  
  Implements the **Chudnovsky algorithm**, one of the fastest known series for computing digits of π.

- **`pi series with dirichlet beta function ...`**  
  Explores π-related identities involving the **Dirichlet beta function**.

- **`sigma pi finn combinatoric euler formula.py`**  
  Experiments with a combinatorial or summation-based expression related to Euler-style π identities.

---

### Numerical Methods
- **`newtons method solving for pi.py`**  
  Uses **Newton’s method** to numerically solve an equation whose root corresponds to π.

---

### Convergence Acceleration
- **`accelerating my pi series using the nth forward ...`**  
  Investigates accelerating slow series using forward difference or convergence acceleration techniques.

- **`euler transform pi algorithm.py`**  
  Applies the **Euler transformation** to improve the convergence of alternating π series.

---

### Other Experiments
- **`pi formula euler number 12.py`**  
  An experimental formula relating π to Euler-style constants or identities.

---

## Purpose of the Project

This repository was created to:

- Explore how different mathematical areas produce formulas for π  
- Compare the **speed of convergence** between series  
- Experiment with **numerical methods and transformations**  
- Recreate and test famous formulas computationally

It serves as both a programming exercise and a mathematical investigation.

---

## Requirements

Python 3.x

Some scripts may optionally use:

- `math`
- `decimal`
- `numpy` (if higher precision or performance is required)

---

## Future Additions

Possible future expansions include:

- Visualising convergence rates
- Implementing the **Gauss–Legendre algorithm**
- Arbitrary precision calculations
- Benchmarking accuracy vs computation time
- More Ramanujan-type series

---

## Notes

This project is intended primarily as a **mathematical exploration** rather than an optimized π calculator. Many of the scripts are written to demonstrate the underlying ideas behind the formulas rather than maximize performance.
