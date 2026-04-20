# 📊 SaaS Sales Dashboard Analysis

> Turning Revenue Growth into Sustainable Profit Growth Through Data-Driven Pricing Strategy

---

## 📌 Project Overview

This project analyzes transactional sales data from a **Software as a Service (SaaS)** company to evaluate business growth, regional performance, customer contribution, product profitability, and the impact of discounting on profit.

The objective is to uncover why a growing company with strong sales performance still faces profitability pressure — and how profit can be improved **without increasing sales volume**.

This end-to-end project combines:

- **Python** for data cleaning, EDA, statistical analysis, and simulations  
- **Tableau** for interactive dashboard visualization  
- **Business Analytics** for strategic recommendations  

---

## 🎯 Business Problem

Although the company has demonstrated strong sales growth, profitability has not increased proportionally.

Management needs to understand:

- Which regions perform best?
- Which products and customers create the most value?
- Is discounting helping growth or destroying margins?
- How can profit be improved efficiently?

---

# 📈 Executive Summary

The company shows positive commercial momentum with strong demand and growing order volume.

| KPI | Value |
|-----|------:|
| Total Sales | **2.29 Million** |
| Total Profit | **286 Thousand** |
| Total Orders | **5,009** |

This confirms that the business has a healthy market position.

However:

> The core issue is **not weak sales** — it is **suboptimal discount and pricing strategy**.

---

# 🛠️ Tools & Technologies

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Statsmodels
- **Jupyter Notebook**
- **Tableau**
- **GitHub**

---

# 📂 Dataset Information

Source dataset contains SaaS transaction-level sales data including:

- Order Date  
- Customer  
- Region / Country / City  
- Industry / Segment  
- Product  
- Sales  
- Profit  
- Quantity  
- Discount  

Each row represents one completed sales transaction.

---

# 🔍 Analytical Workflow

## 1️⃣ Data Preparation

- Checked missing values  
- Checked duplicates  
- Converted date columns  
- Created new features:
  - Year
  - Quarter
  - Profit Margin
  - Loss Indicator
  - Discount Category

## 2️⃣ Exploratory Data Analysis

- Sales trend over time  
- Profit trend  
- Regional comparison  
- Product analysis  
- Customer concentration  
- Discount impact

## 3️⃣ Statistical Modeling

Multiple Linear Regression used to identify profit drivers.

## 4️⃣ Business Simulations

Three pricing policy scenarios tested to improve profitability.

---

# 📌 Key Findings

---

## 1️⃣ Strong Business Growth

From **2022 to 2023**, both sales and profit increased consistently.

This indicates:

- Successful market expansion  
- Growing customer base  
- Strong product demand  

However, revenue growth has not been fully converted into optimal profit growth.

---

## 2️⃣ Regional Performance Differences

Significant performance gaps exist across regions.

| Region | Insight |
|--------|---------|
| EMEA | Strong sales and profit contribution |
| AMER | Strong overall commercial performance |
| APJ | Lower profitability |

### Business Meaning:

A single global pricing strategy may be inefficient.

---

## 3️⃣ Product Profitability Gap

Several products generate high revenue, but not all products deliver healthy margins.

Some products produce:

- Low profit  
- Thin margins  
- Negative returns  

### Opportunity:

- Repricing  
- Bundling strategy  
- Product portfolio optimization

---

## 4️⃣ Customer Contribution Imbalance

A relatively small group of customers contributes a large portion of total revenue.

However:

- High sales customers are not always profitable  
- Some large accounts receive excessive discounts

### Opportunity:

Shift focus from revenue-based ranking to **profit-based account management**.

---

# 💸 Critical Insight: Discount is the Main Profit Killer

The most important finding in this project:

> **Discounting is the primary factor pressuring profitability.**

A strong negative relationship exists between **Discount** and **Profit**.

### Threshold Insights

| Discount Level | Impact |
|---------------|--------|
| ≤20% | Generally healthy |
| >20% | Profit starts declining |
| >50% | Nearly all transactions generate losses |

### Business Meaning:

The company is sacrificing margin to chase revenue.

---

# 📉 Regression Analysis Results

Multiple Linear Regression confirms:

- **Sales** has a statistically significant positive impact on Profit  
- **Discount** has a statistically significant negative impact on Profit  

The model explains approximately **31%** of profit variation.

### Interpretation:

The company has strong selling capability, but current discount strategy is limiting profit potential.

---

# 🧪 Profit Improvement Simulations

Three pricing strategies were tested.

| Scenario | Estimated Profit Increase |
|---------|--------------------------:|
| Max Discount Cap at 20% | **+30.57%** |
| Remove Extreme Discounts (>50%) | **+26.73%** |
| Adaptive Regional Discount Strategy | **+36.61%** ⭐ |

## Best Scenario

> **Adaptive discount strategy by region** produces the highest projected profit increase.

---

# 📊 Dashboard Features

Interactive Tableau dashboard includes:

- Executive KPI Overview  
- Sales & Profit Trend  
- Regional Performance Breakdown  
- Product Profitability Review  
- Customer Value Analysis  
- Discount vs Profit Visualization  
- Simulation Scenario Summary  

*(Insert dashboard screenshot here)*

---

# 🎯 Strategic Recommendations

## 1. Implement Adaptive Discount Strategy by Region

Different regions require different pricing approaches.

## 2. Apply Maximum Discount Cap of 20%

Protect margins while remaining competitive.

## 3. Eliminate Extreme Discount Transactions (>50%)

These transactions destroy profitability.

## 4. Reevaluate Low-Margin Products

Review price structure and bundling potential.

## 5. Use Profit-Based Sales KPI

Focus on sustainable profit growth, not revenue alone.

---

# 🧠 Final Conclusion

The company’s main challenge is **not sales performance**.

The real issue lies in:

- Weak discount governance  
- Margin leakage  
- Inefficient pricing execution  

With smarter pricing controls, the company can significantly improve profit **without increasing sales volume**.

---

# 🚀 Closing Statement

The business already has strong demand.

Now the next stage is clear:

> **Transform Sales Growth into Sustainable Profit Growth**

---

# 📁 Repository Structure

```bash id="j6x77f"
saas-sales-dashboard-analysis/
│── README.md
│── SaaS_Sales_Dea_Capstone_Project_2.ipynb
│── dashboard/
│── dataset/
│── images/
