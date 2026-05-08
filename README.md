# SteelAdvisory 🏗️

> **Purchasing green steel has never been easier.**

*MIT Energy & Climate Hackathon 2025 | Array Project Challenge Track*

---

## 🎯 Overview

[SteelAdvisory](steeladvisory.vercel.app) empowers [Array](https://arraytechinc.com/), a Phoenix-based solar company, to optimize steel procurement through predictive analytics and multi-objective optimization—reducing costs while advancing sustainability goals.

## 💡 The Problem

Steel procurement involves volatile pricing, uncertain market conditions, and the challenge of balancing cost efficiency with carbon reduction targets. Traditional approaches leave money on the table and miss critical decarbonization opportunities.

## 🚀 Our Solution

An all-in-one platform delivering:

- **📈 Price Forecasting**: ARIMAX time-series models trained on Federal Reserve data predict steel prices under varying market scenarios (recessions, tariffs, incentives)
  - **8.06% MAPE** for 6-month forecasts | **14.78% MAPE** for 12-month forecasts
  - Validated using walk-forward analysis across 7+ years of out-of-sample data
- **🎲 Procurement Strategy Optimization**: Monte Carlo simulations across 1,000+ trials evaluate spot-market, long-term contracts, hedging, and options strategies
- **🌱 Supplier Selection**: Pareto optimization co-optimizes cost and sustainability metrics to identify suppliers on the efficiency frontier
- **🔮 Scenario Modeling**: Interactive event simulation to stress-test procurement strategies against market shocks

## 💰 Impact

**Projected savings**: $200K–$1.7M annually for companies with significant steel expenditures

## 🛠️ Tech Stack

**Backend**: FastAPI, Python (statsmodels, NumPy, SciPy)  
**Frontend**: Next.js, React  
**Modeling**: ARIMAX, Monte Carlo Simulation, Pareto Optimization

## 👥 Team

**Manush Gopal** • **Devin Guevara** • **Camille Tauro** • **Nikhita Bhatt**

---

*Built with ❤️ at MIT Energy & Climate Hackathon 2025*
