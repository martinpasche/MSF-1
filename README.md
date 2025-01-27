# MSF-1: Financial Stochastic Modeling Assignment

This repository contains the assignment work for the **Financial Stochastic Modelisation 1** course. The project explores various pricing techniques for financial derivatives using stochastic modeling approaches. Each notebook delves into a specific question, covering different techniques, models, and numerical methods used in modern financial engineering.

## Global Idea

The goal of this project is to implement and analyze various techniques for pricing financial derivatives, emphasizing stochastic processes. The repository serves as a comprehensive study of financial models, showcasing both theoretical underpinnings and numerical implementations.

## Libraries Used

The following Python libraries were used throughout the notebooks to implement the models and perform simulations:

- **NumPy**: For numerical operations and matrix manipulations.
- **Pandas**: To handle data structures and manage datasets.
- **Matplotlib**: For visualizing the results of simulations and pricing.
- **SciPy**: To solve equations and handle advanced mathematical computations.
- **SymPy**: For symbolic mathematics and formula derivations.
- **Statsmodels**: To analyze statistical properties of the models.
- **Pytorch**: For deep learning models and neural networks.

## Installation
To install the required libraries, run:
```bash
pip install numpy pandas matplotlib scipy sympy statsmodels torch
```

Ensure you have these libraries installed before running the notebooks.

## Notebooks

The repository contains the following notebooks, each covering a specific topic or question:

1. Question 1: **Black-Scholes Model**

- **Description**: Introduces the foundational problem setup, defining the stochastic processes and initial conditions for pricing financial derivatives. Focuses on understanding the dynamics of asset prices under simplified assumptions.

- **Techniques**: Black-Scholes formula, stochastic differential equations, risk-neutral pricing. Analytical solutions for a simple stochastic differential equation (SDE). Monte Carlo.

2. Question 2: **Asian Options**

- **Description**: Expands the first question, but now using Asian options as the underlying asset and explores some variance reductions techniques.

- **Techniques**: Asian options, Monte Carlo simulations, variance reduction techniques, control variates, antithetic variates.  Analytical solutions for a simple stochastic differential equation (SDE).

3. Question 3: **Barrier Options**

- **Description**: Introduces barrier options and explores the pricing of these derivatives using stochastic models, while also exploring variance reduction techniques.

- **Techniques**: Barrier options, Monte Carlo simulations, variance reduction techniques, Conditional Monte Carlo, control variates, antithetic variates. Analytical solution for barrier options.

4. Question 4: **Deep Galerkin**

- **Description**: This notebook explores the application of Deep Galerkin methods, a machine learning approach for solving partial differential equations (PDEs) related to financial modeling.

- **Techniques**: Deep Galerkin methods, neural networks, PDEs, financial modeling, deep learning, numerical methods.

5. Question 5: **Milstein and Heston Model**

- **Description**: Introduces the Milstein method for solving stochastic differential equations (SDEs) and explores the Heston model for pricing financial derivatives and obtaining implicit volatility.

- **Techniques**: Milstein method, Heston model, stochastic differential equations, numerical methods, financial modeling.

6. Question 6: **Jump models**

- **Description**: Introduces jump models for asset pricing and explores the Merton model for pricing financial derivatives under jump-diffusion processes.

- **Techniques**: Jump-diffusion models, Merton model, stochastic processes, financial modeling, numerical methods.


## Authors and Contributors

This project was developed by:

- [Martín Pasche](https://www.linkedin.com/in/martin-pasche/)
- [Hugo Yeremian](https://www.linkedin.com/in/hugoyeremian/)