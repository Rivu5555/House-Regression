# 🏡 House Prices Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.1%2B-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11%2B-purple)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## 📊 Overview

Discover the *hidden patterns* behind what drives house prices!  
This project performs an **in-depth exploratory data analysis (EDA)** on the [Kaggle House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) dataset using Python and popular data science libraries.

---

## 📁 Dataset

- **Rows:** 1,460 &nbsp; | &nbsp; **Columns:** 81  
- **Source:** Kaggle Competition  
- **Target Variable:** `SalePrice`

---

## 🚀 Quick Start
1. git clone https://github.com/Rivu5555/House-Regression.git
  cd house-prices-eda
2. **Install dependencies:**
   pip install -r requirements.txt
3. **Run the Notebook:**
   jupyter notebook house_prices_eda.ipynb

   If the data file is not present, [download it here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) and place it in the `input/` folder.

---

## 🧐 EDA Highlights

- **Target Distribution:**  
![SalePrice Distribution](plots/saleprice_dist.png)

- **Missing Value Analysis:**  
Bar plots to visualize missing data columns.

- **Key Feature Relationships:**  
- `GarageArea` vs `SalePrice`
- `OverallQual` vs `SalePrice`
- `SaleType` impact

- **Visual Insights:**  
- Histograms, KDE plots, Boxplots
- Scatter plots for feature relationships

- **Major Findings:**  
- Higher `OverallQual` and `GarageArea` often predict higher `SalePrice`
- Certain `SaleType`s are linked to price outliers
- Notable missing data in some categorical features

---

## 📦 Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn

- ## 🤝 Contribution

Pull requests are welcome! For major changes, open an issue first to discuss what you would like to change.

---
## 📚 References

- [Kaggle Competition Page](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- [Seaborn EDA Reference](https://seaborn.pydata.org/)

---

*Happy Analyzing! 🏠📈*
   
