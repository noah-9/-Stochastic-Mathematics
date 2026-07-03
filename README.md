# 📈 Stochastic Mathematics for Finance

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
[![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)]()
[![Institution](https://img.shields.io/badge/IIT_Kanpur-Stamatics_Club-purple?style=for-the-badge)]()
[![Timeline](https://img.shields.io/badge/Timeline-May_'26_--_Jul_'26-2ea44f?style=for-the-badge)]()

Welcome to the **Stochastic Mathematics for Finance** project repository, developed in association with the **Stamatics Club at IIT Kanpur**. 

This project is a high-performance quantitative finance engine designed to model financial derivatives using advanced stochastic processes. By bridging continuous mathematical theory with discrete market reality, this repository provides tools for accurate derivative pricing, risk management, and computational optimization.

---

## 🎯 Objective

To engineer a robust framework that models financial derivatives using stochastic processes, successfully connecting continuous mathematical theory with the realities of discrete financial markets.

---

## 🧠 Core Methodology & Features

### 🧮 Stochastic Modeling & Derivative Pricing
* **Geometric Brownian Motion (GBM):** Derived GBM analytically to accurately simulate asset price trajectories.
* **Advanced Calculus Engine:** Solved complex stochastic differentials utilizing **Itô’s Calculus** and **Euler-Maruyama methods**.
* **Pricing Models:** Implemented derivative pricing via the foundational **Black-Scholes PDE** and highly optimized, variance-reduced **Monte Carlo simulations**.

### 📉 Algorithmic Backtesting & Hedging
* **Delta-Hedging:** Built a dynamic Delta-hedging historical backtester to meticulously quantify Profit and Loss (PnL) bleed in simulated portfolios.
* **Real-World Data Integration:** Fed the backtester with historical market data using `yfinance`, specifically targeting the **NIFTY 50** index.

### ⚡ C++ Computational Optimization
* **Language Translation:** Translated the original Python-based pricing engine into **C++**.
* **Latency Reduction:** Significantly optimized computational complexity to handle massive simulations with minimal execution time.

---

## 🚀 Results & Benchmarks

* **High-Fidelity Accuracy:** Matched theoretical pricing bounds with **>99% accuracy** utilizing variance-reduced Monte Carlo simulations across **100,000 individual paths**.
* **Performance Reporting:** Delivered a comprehensive benchmark report directly comparing Python and C++ execution times for generating a massive scale of **1,000,000 simulated price paths**.
