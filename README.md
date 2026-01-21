# GARCH-Based-Portfolio-Risk-and-Conditional-VaR-Analysis
Portfolio Risk - Portfolio Risk & Volatility Analysis & Time-Varying Risk Modeling using VaR and Stress Testing

---

Project Overview

Financial markets are dynamic, and portfolio risk fluctuates over time rather than remaining fixed. During periods of market uncertainty or economic shocks, risk can rise sharply, making simple static risk measures insufficient.

This project analyzes a multi-asset investment portfolio to understand how risk evolves over time and how potential losses can be quantified using industry-relevant risk metrics.
The focus is on combining quantitative modeling with clear business interpretation to support informed investment and risk management decisions.

---

## Business Objectives

- Measure portfolio risk under changing market conditions

- Identify periods of elevated volatility and uncertainty

- Estimate potential losses during normal and adverse scenarios

- Support portfolio monitoring and risk-aware decision making

---

## Data Description

- Market: Equity Market

- Frequency: Daily data

- Price Type: Adjusted closing prices

- Input: Historical asset prices used to compute returns

Adjusted prices are used to ensure returns reflect the true investor experience, including corporate actions.

# Stock Include In The Portfolio.
 1. YESBANK,
 2. EICHERMOT,
 3. HAVELLS,
 4. DRREDDY,
 5. BHEL
Using adjusted prices ensures that returns reflect the true investor experience.

---

## Portfolio Construction

An equal-weighted portfolio is created by assigning identical weights to all assets.

# Why equal weighting?

- Prevents concentration in a single asset

- Clearly demonstrates diversification effects

- Keeps the analysis transparent and unbiased

---

## Key Concepts and Methodology
# Log Returns

Instead of using raw price levels, the analysis is performed on log returns.

# Why log returns?

- Risk is measured in percentage terms, not prices

- Log returns handle compounding naturally

- They are well-suited for volatility and risk modeling

---

## Volatility Analysis

Portfolio returns are analyzed over time to observe changing risk patterns.

# Business relevance:

- Highlights calm versus turbulent market phases

- Shows how volatility clusters during stress periods

- Helps risk teams anticipate unstable conditions

---

## Value at Risk (VaR)

Value at Risk estimates the maximum expected portfolio loss at a given confidence level.

# Interpretation example:

A 95% VaR of −2% implies the portfolio is unlikely to lose more than 2% on most days

# Why VaR is used:

- Simple and intuitive risk metric

- Commonly used for risk limits and reporting

- Answers the question: “How much can we lose?”

---

## Stress Testing

Stress testing evaluates portfolio losses under extreme but plausible market conditions.

# Why stress testing matters:

- VaR assumes normal conditions

- Stress tests reveal downside exposure during crises

- Supports contingency planning and capital allocation

---

## Key Insights

- Portfolio risk varies significantly over time

- Volatility tends to spike during periods of market stress

- Static risk measures underestimate downside risk

- Stress-based analysis provides better visibility into extreme losses

---

## Tools and Technologies

- Python

- pandas, numpy

- matplotlib

- scikit-learn / statistical libraries

- Jupyter Notebook

---

## Business Applications

- Portfolio risk monitoring

- Investment risk assessment

- Stress testing and scenario analysis

- Supporting risk-aware portfolio decisions

# Conclusion

This project demonstrates how quantitative risk techniques can be applied to real-world portfolios to capture time-varying risk and downside exposure.
By combining statistical analysis with business-oriented interpretation, the approach mirrors how risk is analyzed and communicated in professional investment and risk management environments.

