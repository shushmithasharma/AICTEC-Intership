# 📊 Week 2 – Data Preprocessing & Exploratory Analysis

This week focused on **understanding the dataset**, **cleaning inconsistencies**, and preparing the features for modeling. The raw Excel data was examined in-depth, categorical values were encoded, and exploratory visualizations were created to uncover patterns in greenhouse gas emissions.

---

## 🔍 Objectives

- Clean the raw dataset and remove irrelevant/unusable columns.
- Handle missing values and check data types.
- Convert categorical variables (`Substance`, `Unit`, `Source`) into numerical form.
- Visualize the distribution of the target variable.
- Understand the frequency and spread of key features.

---

## 🧹 Key Preprocessing Steps

- **Dropped `Unnamed: 7` column** which contained only NaN values.
- Checked data types and null values using `.info()` and `.isnull().sum()`.
- Encoded categorical columns:
  - `Substance` → carbon dioxide, methane, nitrous oxide, other GHGs → 0,1,2,3
  - `Unit` → kg/2018 USD and kg CO2e/2018 USD → 0,1
- Investigated unique values in `Source`, `Unit`, and `Substance` columns.
- Used `.describe()` to examine feature distributions and outliers.

---

## 📊 Exploratory Visualizations

- **Histogram** of the target variable `Supply Chain Emission Factors with Margins` to understand its distribution.
- Frequency plots for:
  - `Substance` values
  - `Unit` values
  - `Source` values

These plots revealed:
- Skewness in the emission factor distribution.
- Dominant units used in the dataset.
- Frequency of different GHG types reported.

---

## 📁 Files Included

- `week2_updation.ipynb` – Contains all the preprocessing and EDA steps.
- `README.md` – This file.

---

## ✍️ Author Notes

This week was all about **laying the foundation for machine learning modeling**.  
I paid special attention to making sure the data was:
- Clean,
- Interpretable,
- And ready for training algorithms in the upcoming weeks.

---

## 🚀 Next Steps (Week 3 Preview)

- Train baseline ML models using the cleaned dataset.
- Evaluate performance and check which features influence predictions most.

---

## 🙋‍♀️ About Me

Hi, I'm Shushmitha — a BTech AIML student passionate about using data for solving real-world challenges. This project is part of my internship and learning journey in climate-related analytics.

