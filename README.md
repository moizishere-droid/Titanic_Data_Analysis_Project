# 🚢 Titanic Data Analysis Project

## 📌 Overview

This project performs an in-depth **exploratory data analysis (EDA)** on the **Titanic Dataset**.
The goal is to analyze key factors affecting survival.

We also include an **automated profiling report** (`result.html`) generated using **ydata-profiling**, providing detailed dataset insights.

---

## 📂 Files in This Repository

* **`Titanic_Data_Analysis_Project.ipynb`** → Jupyter Notebook containing step-by-step analysis, visualizations, and model building.
* **`result.html`** → Data profiling report with dataset summary, distributions, correlations, and missing value analysis.

---

## 📊 Dataset

* **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/vinicius150987/titanic3/code)
* **Features**:

  * PassengerId, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked
* **Target**:

  * `Survived` (0 = Did not survive, 1 = Survived)

---

## 🔎 Steps Covered in Notebook

1. **Data Loading & Cleaning**

   * Handling missing values (Age, Cabin, Embarked).
   * Encoding categorical variables.
   * Feature engineering (family size, title extraction from names).

2. **Exploratory Data Analysis (EDA)**

   * Survival rates by **gender, age, class, family size, embarkation point**.
   * Correlation heatmaps.
   * Visualizations with Matplotlib & Seaborn.

3. **Automated Data Profiling**

   * Generated via `ydata-profiling`.
   * Full HTML report (`result.html`) showing:

     * Missing values
     * Feature distributions
     * Correlation analysis


---

## 📈 Results

* **Key insights**:

  * Women had a much higher survival rate.
  * Higher-class passengers (1st class) survived more often.
  * Children had better survival chances compared to older passengers.

---



