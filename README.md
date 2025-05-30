# Sales Data Analysis and Business Strategy

**Author:** Abdullah Sharaf  
**Start Date:** [10 Dec 2024]  
**End Date:** [20 Dec 2024]

---

## 📌 Project Overview

This project analyzes customer sales data to uncover patterns, evaluate the effectiveness of different sales methods, and provide actionable strategies for revenue growth. The goal is to support data-driven business decisions by identifying which methods convert best and where efforts should be concentrated to maximize efficiency.

---

## 🎯 Objectives

- Analyze sales data to identify behavioral and revenue trends.
- Evaluate the conversion effectiveness of different sales methods: **Email**, **Call**, and **Email + Call**.
- Provide strategic recommendations to improve sales performance and marketing allocation.

---

## 🏆 Business Goals

- **Increase Sales Efficiency**: Determine which sales approach yields the highest conversion.
- **Optimize Strategies**: Use insights to fine-tune and adapt future campaigns.
- **Identify Weak Links**: Detect underperforming sales methods or regions.

---

## ⚙️ Work Undertaken

### 🔧 Data Cleaning

- Standardized inconsistent labels in the `sales_method` column (e.g., `'email'` → `'Email'`, `'em + call'` → `'Email + Call'`).
- Removed rows with missing revenue values to preserve data integrity.
- Dropped outliers in `years_as_customer` where values exceeded 40 (company founded in 1984).

### 📊 Exploratory Data Analysis (EDA)

- Histograms and bar plots to understand:
  - Revenue distribution.
  - Customer concentration by state.
  - Performance by sales method.

---

## 💡 Key Findings

- **Revenue Distribution**: Right-skewed with a concentration around \$50.
- **Outliers**: Present, suggesting a need for robust modeling in future phases.
- **Top Performing State**: **California** – highest customer activity.
- **Lowest Performing State**: **Wyoming** – potential for strategic outreach.
- **Most Effective Sales Method**: **Email + Call**.
- **Least Effective Method**: **Call only**.


