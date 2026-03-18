# Advanced Statistics — Ganesh Lakshmana

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

A comprehensive Jupyter Notebook exploring advanced probability and statistical methods through theory, computation, and visualisation. Each task covers a distinct statistical concept — from discrete distributions and survival analysis to Bayesian inference and regression modelling.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Tasks & Topics Covered](#tasks--topics-covered)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Author](#author)

---

## Project Overview

This notebook is a structured collection of statistical analyses implemented in Python. It spans seven distinct tasks, each addressing a real-world statistical problem using rigorous mathematical methods and rich visualisations. The work covers:

- Probability distributions (discrete and continuous)
- Survival analysis
- Maximum Likelihood Estimation (MLE)
- Hypothesis testing
- Regression modelling
- Bayesian inference

---

## Tasks & Topics Covered

### Task 0 — Discrete Probability Distributions

A unified framework for computing and visualising four discrete distributions based on configurable parameters (ξ₁, ξ₂, ξ₃):

| Distribution | Parameters |
|---|---|
| **Bernoulli** | Probability of success p |
| **Poisson** | Rate parameter λ |
| **Negative Binomial** | Number of successes k, probability p |
| **Geometric** | Probability of success p |

**Outputs:** PMF/CDF table, stem plots, expectation, median, and mode.

---

### Task 1 — Negative Binomial: Meteorite Count Modelling

Models the distribution of meteorite counts using a Negative Binomial distribution with r = 30 successes and p = 0.31.

**Outputs:** Bar chart of PMF with annotated mean and median; variance and cutoff analysis.

---

### Task 2 — Continuous Survival / Waiting Time Analysis

Analyses a custom mixed survival function defined as:

```
S(y) = 0.54 · exp(−5√y) + 0.45 · exp(−9√(y³))
```

**Outputs:** PDF plot, survival function curve, probability in interval [2, 4], mean, variance, standard deviation, Q1, median, and Q3.

---

### Task 3 — Gamma Distribution & Maximum Likelihood Estimation

Models network router bandwidth throughput using a Gamma distribution. Compares the PDF of a single-router (α = 7) and a dual-router system (α = 14), and derives the MLE estimate of the scale parameter θ.

**Outputs:** Side-by-side PDF plots, MLE estimate, expected bandwidth for dual-router system.

---

### Task 4 — One-Sample Hypothesis Test (t-Test)

Performs a left-tailed one-sample t-test on a weight dataset to determine whether a new system produces statistically lower weights than the historical mean (μ₀ = 805 g, α = 0.05).

**Outputs:** Test statistic, critical value, p-value, decision, box plot, and distribution comparison.

---

### Task 5 — Polynomial Regression & Ridge Regularisation

Fits polynomial and Ridge regression models to a dataset of (x, y) pairs, selecting the optimal degree via cross-validation. Addresses overfitting through regularisation.

**Outputs:** Scatter plot with fitted curve, cross-validation scores, optimal degree and regularisation strength.

---

### Task 6 — Bayesian Estimation with Conjugate Prior

Performs Bayesian inference on a Gamma-distributed likelihood using a conjugate Gamma prior (α = 77, β = 42). Derives posterior parameters and computes Bayes estimators under two loss functions:

- **Square-error loss** → posterior mean
- **Absolute-error loss** → posterior median

**Outputs:** Prior vs posterior distribution plot, posterior parameters, Bayesian estimates, and update factor.

---

## Tech Stack

| Library | Purpose |
|---|---|
| [`NumPy`](https://numpy.org/) | Numerical computations |
| [`SciPy`](https://scipy.org/) | Statistical distributions, integration, optimisation |
| [`Matplotlib`](https://matplotlib.org/) | Visualisation |
| [`Pandas`](https://pandas.pydata.org/) | Data tables |
| [`scikit-learn`](https://scikit-learn.org/) | Regression modelling and cross-validation |

---

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Ganeshlakshmana/Advance-stats.git
   cd Advance-stats
   ```

2. **Install dependencies:**

   ```bash
   pip install numpy scipy matplotlib pandas scikit-learn jupyter
   ```

3. **Launch the notebook:**

   ```bash
   jupyter notebook Advanced_statistics_Ganesh_Lakshmana.ipynb
   ```

---

## Repository Structure

```
Advance-stats/
│
├── Advanced_statistics_Ganesh_Lakshmana.ipynb   # Main notebook (all 7 tasks)
└── README.md                                    # Project documentation
```

---

## Author

**Ganesh Lakshmana**  
[GitHub Profile →](https://github.com/Ganeshlakshmana)
