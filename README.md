# COMP1844 — Summer 2026 — Tutorial 06: Statistical Distributions

### Overview

This laboratory session focuses on **Statistical Distributions**, more specifically **Uniform Distributions** and **Normal Distributions**. Students will solve statistical problems using **NumPy** and **pandas**, which provide the data structures and functionality needed for statistical computation, and **Matplotlib** to visualise the datasets.

---

## Repository structure

```
COMP1844-Su26-Tutorial06/
├── README.md
└── LaboratorySession6.pdf
```

---

## Prerequisites

- Python 3.x
- NumPy, pandas, matplotlib
- Completion of Tutorial 05 (Statistical Analysis — mean, median, range, standard deviation, descriptive statistics)

---

## Tasks

### Task 1: Uniform Distribution

Initialise a one-dimensional NumPy array representing a **uniform distribution** containing **50 values** from the interval `[0 .. 100]`.

Libraries:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
```

### Task 2: Uniform Distribution — Summary Statistics

Find the **minimum value**, the **maximum value**, and the **range** of the dataset from Task 1.

### Task 3: Normal Distribution

Initialise a one-dimensional array representing a **normal distribution** of **1000 data points** with mean value **17** and standard deviation **0.2**.

### Task 4: Normal Distribution — Summary Statistics

Find the **minimum** and **maximum** values of the dataset and calculate the **range**.

### Task 5: Histogram and Probability Density Function

Visualise the dataset from Task 3 using a **histogram with 10 bins**. Visualise the **probability density function (PDF)**.

The probability density function is:

$$
f = \frac{1}{\sigma\sqrt{2\pi}}  e^{-\frac{(X - \mu)^2}{2\sigma^2}}
$$

*(If math does not render: f = 1 / (σ√2π) × e^(−(X − μ)² / (2σ²)).)*

Where **X** represents the data points, **μ** is the mean value, and **σ** is the standard deviation.

---

## Getting Started

1. Create a new Jupyter notebook (Jupyter Notebook, JupyterLab, or VS Code).
2. Import the required libraries (`numpy`, `pandas`, `matplotlib.pyplot`).
3. Work through Tasks 1–5 in order — Tasks 2 and 4 build on the arrays created in Tasks 1 and 3 respectively; Task 5 uses the normal distribution from Task 3.

---

## References

- [NumPy Documentation](https://numpy.org/doc/)
- [NumPy — Random sampling](https://numpy.org/doc/stable/reference/random/index.html)
- [NumPy — Statistics functions](https://numpy.org/doc/stable/reference/routines.statistics.html)
- [pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

---

## License

This lab session is part of the COMP1844 module at the University of Greenwich.

Laboratory Session 6 - Summer 2026