# 🛒 Quantium Retail Analytics & Store Trial Analysis

An end-to-end retail data analytics case study built with **Python**. The project analyzes retail transaction and customer behaviour data to identify high-value customer segments, understand purchasing patterns, evaluate a store trial campaign's performance, and deliver data-driven business recommendations for category growth.

![Python](https://img.shields.io/badge/Python-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-informational)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-lightgrey)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-teal)
![SciPy](https://img.shields.io/badge/SciPy-Statistical%20Analysis-red)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow)

---

## 📌 Project Objective

The objective of this project was to help a Category Manager understand:

- Which customer segments drive sales?
- Which products and brands perform best?
- What purchasing behaviors influence spending?
- Did the store trial campaign generate measurable uplift?
- What strategic actions should be taken over the next six months?

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python** | Core programming language |
| **Pandas** | Data manipulation and cleaning |
| **NumPy** | Numerical computations |
| **Matplotlib / Seaborn** | Data visualization |
| **SciPy** | Statistical testing (T-Test) |
| **Jupyter Notebook** | Interactive development environment |

---

## 📊 Dataset Overview

| Dataset | Description |
|---------|--------------|
| **QVI Transaction Data** | Product purchases, quantities, and sales revenue |
| **QVI Purchase Behaviour** | Customer lifestyle and premium segment data |

---

## 🔄 Project Workflow

**1. Data Cleaning**
- Checked data quality
- Identified missing values
- Removed outlier customer purchases
- Corrected data formats

**2. Feature Engineering**
- Created new features: `Brand Name`, `Pack Size`, `Unit Price`

**3. Exploratory Data Analysis**
- Analyzed sales distribution, customer segments, brand performance, pack size preferences, and revenue contribution.

**4. Statistical Analysis**
- T-Test for customer behaviour comparison
- Spending pattern analysis

**5. Store Trial Analysis**
- Evaluated trial stores: **Store 77, Store 86, Store 88**
- Compared trial stores against control stores using correlation analysis, monthly sales trends, customer counts, and sales uplift measurement.

---

## 💡 Key Findings

### Customer Insights
![Customer Segment Sales](retail%201.png)
*Total sales by customer lifestyle stage and premium segment (Budget · Mainstream · Premium)*

- **Mainstream Young Singles/Couples** represented the largest customer segment.
- **Budget Older Families** generated the highest overall sales.
- Mainstream Young Singles/Couples paid the highest average price per packet.

### Trial Store Insights

| Store 77 vs Control Store 233 | Store 86 vs Control Store 155 |
|:---:|:---:|
| ![Store 77 Chart](retail%203.png) | ![Store 86 Chart](retail%202.png) |

| Store | Sales Uplift | Notes |
|-------|-------------|-------|
| **Store 77** | **+29.1%** | Higher customer traffic, strongest trial performance |
| **Store 86** | **+9.8%** | Positive but moderate impact |

### Brand Insights

🥇 Kettle 🥈 Pringles 🥉 Doritos — these brands contributed significantly to category sales.

---

## ✅ Business Recommendations

1. **Focus future marketing activity on Mainstream Young Singles/Couples** — this segment represents the largest customer base and pays the highest average price per packet.
2. **Expand successful Store 77 trial learnings to similar stores** — a +29.1% sales uplift makes Store 77 the strongest candidate for broader rollout.
3. **Conduct further analysis for Store 88 using a better matched control store** — the current control store match needs improvement before drawing conclusions.

---

## 🎯 Project Outcome

Successfully transformed raw retail transaction data into actionable business insights and strategic recommendations that can support customer targeting, product placement, promotional planning, and store performance improvement.

---

## 👤 Author

**Saimoon Ahmed Adnan**
Computer Science student focused on product analytics, data science, machine learning, and software engineering.

- 📧 Email: adnansaimoon@gmail.com
