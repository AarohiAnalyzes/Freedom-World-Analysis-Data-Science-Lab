# 🌍 Freedom in the World  
## An Empirical Data Science Study on Digital Access, Gender Inclusion & Academic Freedom

---

## 📌 Project Overview

This project investigates how socio-economic factors influence democratic freedoms across countries using panel data from **2013–2023**.

By integrating governance indicators with development metrics, the study examines how **digital access, gender participation, and higher education** relate to civil liberties, women’s rights, and academic freedom.

The objective is to combine rigorous statistical modeling and machine learning techniques to uncover measurable global patterns behind democratic outcomes.

---

## 🎯 Research Questions

1. Does Internet penetration improve Freedom of Expression?
2. Is Female Labor Force Participation associated with stronger Women’s Rights?
3. Do higher Tertiary Education levels predict Academic Freedom?

---

## 📊 Dataset

- Panel dataset covering **196+ countries**
- Time range: **2013–2023**
- Country-year observations across multiple global regions

### Core Freedom Indicators
- Political Rights (PR)
- Civil Liberties (CL)
- Category Scores (A–G)
- Academic Freedom (D3)
- Freedom Status (Free, Partly Free, Not Free)

### Enriched Socio-Economic Indicators
- Internet Penetration Rate (% of population using the Internet)
- Female Labor Force Participation Rate (% of female population 15+)
- Tertiary Education Enrollment Rate (% gross enrollment ratio)

---

## 📚 Data Sources

### 🏛 Freedom House – *Freedom in the World*
The core governance dataset is derived from the annual **Freedom in the World** report published by Freedom House.

It provides standardized country-level indicators of political rights and civil liberties.

Source:  
https://freedomhouse.org/report/freedom-world

### 🌍 World Bank – World Development Indicators (WDI)
Socio-economic indicators were obtained from the World Bank’s **World Development Indicators** database.

Source:  
https://data.worldbank.org/

---

## 🧪 Methodology

### 📈 Statistical Analysis
- Descriptive Statistics  
- Pearson Correlation  
- Partial Correlation  
- OLS Regression (Robust Standard Errors – HC3)  
- Bootstrapped Confidence Intervals  
- Mixed-Effects (Multilevel) Modeling  
- Interaction Effects  
- Model Diagnostics (RMSE, MAE, VIF, Residual Analysis)

### 🤖 Machine Learning
- Random Forest Regression  
- Permutation Feature Importance  
- Partial Dependence Plots (PDP)  
- Train/Test Validation (75/25 split)

---

## 🔍 Key Insights

- Higher Internet penetration shows a statistically significant association with improved civil liberties outcomes.
- Female labor force participation correlates positively with stronger protections for women’s rights, particularly in politically freer systems.
- Tertiary education enrollment is associated with higher academic freedom, though effects vary across political status categories.
- Machine learning models confirm non-linear dynamics that complement regression findings.

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Statsmodels  
- Scikit-learn  
- Pingouin  

---

## 📂 Repository Structure

Freedom-World-Analysis-Data-Science-Lab/

- `Freedom_World.ipynb` → Full reproducible analysis (Python notebook)
- `Freedom_World_Report.pdf` → Final academic report & synthesis
- `README.md` → Project documentation & overview

---

## 📈 Skills Demonstrated

- Panel Data Analysis  
- Multilevel / Mixed-Effects Modeling  
- Statistical Inference & Hypothesis Testing  
- Feature Importance Interpretation  
- Data Cleaning & Cross-Dataset Integration  
- Bootstrapping & Robust Estimation  
- Applied Machine Learning  
- Reproducible Analytical Workflow  

---

## 🌍 Why This Project Matters

Understanding the structural drivers of democratic freedoms is critical in a world facing:

- Digital censorship  
- Gender inequality  
- Institutional restrictions  
- Declining global civil liberties  

This project demonstrates how data science can provide empirical, policy-relevant insight into global governance and democratic development.

---

## 🚀 Project Status

Completed research study with reproducible analysis pipeline.  
