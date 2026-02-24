# Pandas Profiling

Pandas Profiling is a Python library that generates a comprehensive Exploratory Data Analysis (EDA) report from a pandas DataFrame in just a few lines of code. Instead of manually writing dozens of lines to understand your data, it automatically produces an interactive HTML report with statistics, distributions, correlations, missing values, and more.

It saves hours of manual EDA work and gives you a bird's-eye view of your dataset instantly.

The library has been rebranded as **ydata-profiling** (formerly pandas-profiling), but the functionality remains the same.

---

## What It Covers Automatically

- **Dataset overview** — shape, size, missing values, duplicate rows  
- **Variable analysis** — type, unique values, min/max, mean, median, std  
- **Distributions** — histograms for numerical, bar charts for categorical  
- **Correlations** — Pearson, Spearman, Cramér's V  
- **Missing value analysis** — heatmaps and counts  
- **Interactions** — scatter plots between numerical variables  
- **Duplicate rows** — detected and flagged  

---

## When to Use It

Pandas profiling is best used at the very beginning of a data science project, right after loading your dataset. It helps you quickly understand what you're working with before diving into cleaning, feature engineering, or modeling. It's especially useful when you receive an unfamiliar dataset and need to get up to speed fast.
