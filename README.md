# CAC 40 Equity Analysis: Multi-Factor Risk Decomposition and Portfolio Optimization

## Project Overview

This project provides an end-to-end quantitative analysis of CAC 40 equities, combining market risk analysis, correlation structure, multi-factor modeling, and portfolio optimization.

The objective is to demonstrate how classical financial models and modern statistical techniques can be used together to:
- understand equity risk drivers,
- analyze dependence structures,
- decompose portfolio risk,
- and construct optimized portfolios.

The project is designed as a professional financial analysis case study, suitable for data analyst, business analyst, or finance-oriented roles.

---

## Scope of the Analysis

The analysis covers the period 2015–2025 and includes the following components:

### 1. Market & Return Analysis
- Daily return computation for the CAC 40 index and constituent stocks
- Volatility analysis (daily and annualized)
- Drawdown analysis and tail risk assessment
- Distributional analysis (skewness, kurtosis, normality tests)

### 2. Correlation Structure
- Full correlation matrix of CAC 40 stocks
- Visualization of correlation patterns
- Identification of highly correlated clusters

### 3. Factor Modeling
- CAPM regression for each stock:
  - Alpha
  - Beta
  - R²
- Extension to a multi-factor framework using PCA:
  - Market factor
  - Principal Components (PC1, PC2)
- Analysis of factor loadings and residual (specific) risk

### 4. Portfolio Optimization
- Minimum Variance Portfolio (MVP)
- Efficient Frontier (daily scale)
- Tangency (maximum Sharpe) portfolio
- Comparison of portfolio weights
- Identification of dominant contributors

### 5. Risk Decomposition
- Decomposition of MVP risk into:
  - Market risk
  - PCA factor risk
  - Specific (idiosyncratic) risk
- Interpretation of diversification effects

### 6. Dimensionality Reduction & Clustering
- PCA visualization of stocks
- Sector-based coloring
- Hierarchical clustering in PCA space

---

## Tools & Technologies

- Python: pandas, numpy, scipy, statsmodels, scikit-learn, matplotlib, seaborn
- Power BI:
  - Interactive dashboards
  - Portfolio metrics visualization
  - Risk decomposition views
- Statistical Methods:
  - CAPM
  - PCA
  - Correlation analysis
  - Mean-variance optimization

---

## Repository Structure

CAC40_MultiFactor_Portfolio/
│
├── data/
│ ├── cac40_stocks/ # Raw stock and index data
│ └── clean_stocks/ # Cleaned and aligned datasets
│
├── notebooks/
│ ├── data_cleaning.ipynb
│ ├── cac40_index_analysis.ipynb
│ ├── cac40_stocks_analysis.ipynb
│ ├── factor_model_and_portfolio.ipynb
│ 
│
├── outputs/
│ ├── figures/ # All plots and charts
│ └── tables/ # CSV outputs (weights, loadings, metrics)
│
├── powerbi/
│ └── CAC40 Multifactor Risk Analysis & Portfolio Optimization.pbix
│
├── report/
│ └──CAC 40 Equity Analysis Multi-Factor Risk Decomposition and Portfolio Optimization.pdf
│
└── README.md



---

## Key Results (High-Level)

- The CAC 40 exhibits moderate long-term volatility with pronounced spikes during systemic crises.
- Stock returns are non-normal, with heavy tails and negative skewness.
- Correlations are significant but heterogeneous, enabling diversification.
- PCA factors capture common risk dimensions beyond the market factor.
- The Minimum Variance Portfolio is dominated by specific risk, highlighting diversification benefits.
- Tangency portfolio weights show strong concentration, illustrating the trade-off between risk minimization and return maximization.

---

## Purpose of the Project

This project was developed to:
- demonstrate applied financial analytics skills,
- bridge statistical modeling and business-oriented insights,
- showcase end-to-end analysis from raw data to executive-level dashboards.

This project is for educational and analytical purposes only and does not constitute investment advice.

