# 📈 Portfolio Optimization & Risk Analysis

## 🔹 Overview
This project applies **Modern Portfolio Theory (Markowitz)** and **risk management techniques** to construct an optimized portfolio that outperforms the benchmark (NIFTY 50).  
The analysis covers **return optimization, risk-adjusted performance, stress testing, and visualization** with a final written report and interactive dashboard.

---

## 📂 Project Structure
- `data/` → Raw and processed datasets  
- `notebooks/` → Jupyter Notebook with step-by-step analysis  
- `scripts/` → Python scripts for portfolio optimization  
- `reports/` → Final report (PDF)  
- `dashboard/` → Power BI / Excel dashboard  
- `images/` → Graphs & visual outputs for quick view  
- `README.md` → Project summary  

---

## 🔧 Methodology
1. Collected historical price data (2020–2024) for selected assets.  
2. Calculated daily returns, covariance matrix, and risk metrics.  
3. Applied **Mean-Variance Optimization** to find efficient portfolio weights.  
4. Simulated 10,000 portfolios (Monte Carlo) for efficient frontier visualization.  
5. Benchmarked against NIFTY 50.  
6. Measured performance using:  
   - Sharpe Ratio  
   - Sortino Ratio  
   - Value at Risk (VaR)  
   - Beta & Drawdowns  
7. Stress-tested portfolio during COVID crash.  

---

## 📊 Results
- **Optimized Portfolio Return (Annualized):** 15.2%  
- **NIFTY 50 Return (Annualized):** 12.1%  
- **Sharpe Ratio:** 0.72 (vs 0.55 for NIFTY)  
- **Max Drawdown:** -18% (vs -28% for NIFTY)  

---

## 🖥️ Dashboard Preview
![Efficient Frontier](images/efficient_frontier.png)
![Portfolio Allocation](images/allocation_pie.png)

---

## 🚀 Tech Stack
- **Python**: pandas, numpy, matplotlib, seaborn, scipy  
- **Optimization**: cvxpy / PyPortfolioOpt  
- **Visualization**: matplotlib, seaborn, Power BI  
- **Data Source**: Yahoo Finance API  

---

## 📄 Report & Dashboard
- [Final Report (PDF)](reports/Portfolio_Optimization_Report.pdf)  
- [Interactive Dashboard](dashboard/portfolio_dashboard.pbix)  

---

## ✨ Key Takeaways
- Built an optimized portfolio with **better risk-adjusted returns** than benchmark.  
- Created an **interactive dashboard** for portfolio insights.  
- Demonstrated **practical application of finance + analytics**.  

---

## 👤 Author
Saksham — Data Analyst | Aspiring Finance Professional  
