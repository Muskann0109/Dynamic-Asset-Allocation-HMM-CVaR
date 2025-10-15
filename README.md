# Dynamic Asset Allocation using HMM and CVaR Optimization

This project implements a **dynamic portfolio optimization strategy** that combines **Hidden Markov Models (HMM)** for market regime detection and **Conditional Value at Risk (CVaR)** for risk-aware portfolio allocation.

---

## 📌 Project Overview

- **Objective:** Adjust portfolio weights dynamically based on market conditions (Bear, Neutral, Bull) to maximize risk-adjusted returns.
- **Assets Used:** 
  - SPY (S&P 500 ETF) – Equity
  - QQQ – Technology ETF
  - TLT – Long-term Treasury Bonds
  - GLD – Gold ETF
- **Techniques:** 
  - HMM for regime detection using returns and volatility
  - CVaR optimization to minimize expected tail losses
  - Dynamic backtesting with monthly rebalancing
- **Performance Metrics:** Sharpe Ratio, Annualized Return, Annualized Volatility, Maximum Drawdown

---

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/<your-username>/Dynamic-Asset-Allocation-HMM-CVaR.git
