# Option Pricing Models – Monte Carlo, Black–Scholes, and Binomial Tree

## Overview
This repository contains **Python** and **Excel** implementations of multiple option pricing models — **Monte Carlo Simulations**, **Black–Scholes**, and **Binomial Tree** — applied to **European**, **Asian**, and **Barrier** options. It also includes a comparative analysis of computational efficiency, convergence, and accuracy across these methods.

## Monte Carlo Simulations
- Developed simulation models for European, Asian, and Barrier options using **Geometric Brownian Motion (GBM)** under the risk-neutral measure.
- Implemented advanced **variance reduction techniques**:
  - **Antithetic Variates**
  - **Control Variates**
- Built both **Python** scripts and an **Excel-based Monte Carlo framework** integrating:
  - Random number generation
  - Path-dependent simulations
  - Statistical analysis and sensitivity testing

## Black–Scholes Model
- Implemented closed-form pricing for European options in **Python** and **Excel**.
- Analyzed key assumptions, including:
  - Constant volatility
  - Lognormal price distribution
  - No arbitrage
  - Continuous trading
- Examined the impact of relaxing these assumptions compared to Monte Carlo and Binomial Tree methods.

## Binomial Tree Model
- Implemented a recombining binomial tree for European and American-style options in **Python** and **Excel**.
- Captured **early exercise flexibility** for American options.

## Comparative Analysis
- **Monte Carlo**: Handles complex, path-dependent payoffs; slower convergence.
- **Binomial Tree**: Flexible for early exercise; intuitive discrete-time approach.
- **Black–Scholes**: Fast, closed-form solution under idealized assumptions.
- Compared models on:
  - Computational complexity
  - Convergence speed
  - Accuracy
