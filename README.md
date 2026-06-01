# project_unemployement_analysis_in-_india


# 📊 Unemployment Analysis in India

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat&logo=python)
![NumPy](https://img.shields.io/badge/NumPy-1.24%2B-013243?style=flat&logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-150458?style=flat&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7%2B-orange?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12%2B-4c72b0?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

A complete **Data Science project** analyzing unemployment trends across Indian states from **May 2019 to June 2020**, with a focus on the impact of the **COVID-19 pandemic and national lockdown** on employment.

This project was built as part of a **Data Science Internship** to demonstrate real-world data analysis using Python, NumPy, and Pandas.

---

## 📁 Project Structure

```
unemployment-india-analysis/
│
├── Unemployment_India_Analysis.ipynb   # Main Jupyter Notebook (full analysis)
├── unemployeementinindia.csv           # Dataset (source: Kaggle)
├── README.md                           # Project documentation
```

---

## 📌 Objective

> Unemployment is measured as the percentage of unemployed people out of the total labour force. This project analyzes how unemployment varied across Indian states and regions — and how sharply it spiked during the COVID-19 lockdown of 2020.

**Goals:**
- Understand unemployment distribution across Indian states
- Compare **Rural vs Urban** unemployment patterns
- Quantify the **COVID-19 impact** on unemployment
- Derive actionable insights using NumPy and Pandas

---

## 📂 Dataset

| Field | Details |
|-------|---------|
| **Source** | [Kaggle — Unemployment in India](https://www.kaggle.com/datasets/gokulrajkmv/unemployment-in-india) |
| **File** | `unemployeementinindia.csv` |
| **Period** | May 2019 – June 2020 |
| **Records** | ~768 rows |
| **Coverage** | 28 States / UTs |

**Columns:**

| Column | Description |
|--------|-------------|
| `Region` | Indian State / Union Territory |
| `Date` | Monthly observation date |
| `Frequency` | Frequency of measurement (Monthly) |
| `Estimated Unemployment Rate (%)` | % of unemployed people in the labour force |
| `Estimated Employed` | Number of employed people |
| `Estimated Labour Participation Rate (%)` | % of working-age people actively in the labour force |
| `Area` | Rural or Urban |

---

## 🔧 Libraries Used

```python
import numpy as np        # Statistical computations
import pandas as pd       # Data manipulation & EDA
import matplotlib.pyplot as plt   # Plotting
import seaborn as sns     # Advanced visualizations
```

---

## 📓 Notebook Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | Import Libraries | Setup all dependencies |
| 2 | Load Dataset | Read CSV, inspect shape and columns |
| 3 | Data Cleaning | Parse dates, fix dtypes, handle nulls, feature engineering |
| 4 | EDA with Pandas | `.describe()`, `.groupby()`, `.crosstab()`, pivot tables |
| 5 | NumPy Statistical Analysis | Mean, median, std, IQR, Z-scores, percentiles, moving average |
| 6 | Region-wise Analysis | State-level full summary table |
| 7 | Rural vs Urban Analysis | Comparison with NumPy arrays + trend line chart |
| 8 | COVID-19 Impact Analysis | Pre vs during lockdown, April 2020 spike |
| 9 | Correlation Analysis | NumPy `corrcoef`, heatmap, scatter plots |
| 10 | Visualizations | 6 publication-quality charts |
| 11 | Key Insights & Conclusions | Summary of findings |

---

## 📊 Visualizations Included

- 📈 National unemployment trend over time (with COVID-19 lockdown band)
- 🌾 Rural vs Urban unemployment trend comparison
- 🏆 Top 10 highest & lowest unemployment states
- 🗓️ State × Month heatmap
- 📉 Frequency distribution with NumPy histogram
- 📦 Box plot + Violin plot by area type
- 🦠 Pre-COVID vs During-COVID grouped bar chart (state-wise)
- 🔴 April 2020 COVID peak — top 15 states
- 🔗 Correlation heatmap & scatter plots

---

## 🔍 Key Findings

| Insight | Value |
|---------|-------|
| Overall average unemployment | ~9.7% |
| Pre-COVID average | ~9.6% |
| During-COVID average | ~20.2% |
| COVID impact (% increase) | **+110%** |
| Highest unemployment state | **Tripura / Haryana** |
| Lowest unemployment state | **Gujarat / Meghalaya** |
| Urban vs Rural difference | Urban ~3% higher |
