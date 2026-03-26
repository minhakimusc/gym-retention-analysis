# 🏋️ Gym Membership Retention Analysis

**Analyzing the key drivers of gym membership churn using Excel**

> BUAD 310 — Applied Business Statistics · USC Marshall School of Business
> Authors: Minha Kim, Sangwon Lee · February 2026

---

## 📋 Overview

This project examines what factors influence whether gym members stay or cancel their memberships. Using a dataset of **4,000 active and former gym members**, we analyzed the relationships between customer behaviors, contract structures, and churn rates to deliver actionable retention strategies.

## ❓ Research Question

**How do customer behaviors and contract structures correlate with the likelihood of membership retention?**

## 📊 Key Findings

| Metric | Value |
|--------|-------|
| Churn rate — 1-month contracts | **42.3%** |
| Churn rate — 6-month contracts | **12.5%** |
| Churn rate — 12-month contracts | **2.4%** |
| Median lifetime (retained members) | **4 months** |
| Median lifetime (churned members) | **1 month** |
| Visit frequency vs. tenure correlation | **0.11 (weak)** |

### Insight 1: Contract Length Dramatically Impacts Retention
Members on month-to-month contracts churn at **42.3%** — nearly 18x higher than those on annual contracts (2.4%). Longer financial commitments create a significant barrier to cancellation.

### Insight 2: The First Month Is Critical
75% of all cancellations happen within the first month of membership. Members who survive past their first 1-2 months are exponentially more likely to stay long-term.

### Insight 3: Visit Frequency Is Habit-Based, Not Tenure-Based
A correlation of just 0.11 between tenure and visit frequency suggests that engagement is a personal habit — long-term members don't necessarily visit more often than new ones.

## 🔧 Methods & Tools

- **Tool:** Microsoft Excel
- **Techniques:** Pivot Tables, Histograms, Scatter Plots, Stacked Bar Charts, Box Plots, Descriptive Statistics, Correlation Analysis
- **Dataset:** 4,000 observations with no missing values, covering demographics, financial commitment, and behavioral metrics

## 💡 Business Recommendations

1. **Incentivize long-term contracts** — Offer initiation fee discounts or complimentary services (free personal training, body composition analysis) for 6-month and 12-month sign-ups
2. **Implement first-month onboarding** — Provide structured integration with mandatory training sessions and group classes to help new members build habits before their renewal date

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `BUAD310_Portfolio_Project_1.pdf` | Full written report with analysis and visualizations |
| `README.md` | This file |

## 📊 Visualizations

The full report includes:
- Distribution of Average Class Frequency (Histogram)
- Distribution of Customer Lifetime (Histogram)
- Proportion of Retained vs. Churned Members (Bar Chart)
- Churn Status by Contract Period (Stacked Bar Chart)
- Average Class Frequency vs. Lifetime (Scatter Plot)
- Median Customer Lifetime by Churn Status (Box Plot)

## 📚 Data Source

Vinueza, A. (2024). *Gym Customers Features and Churn* [Data set]. Kaggle.
https://www.kaggle.com/datasets/adrianvinueza/gym-customers-features-and-churn
