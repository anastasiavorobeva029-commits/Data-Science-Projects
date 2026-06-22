# Exploratory Data Analysis (EDA) Projects

This repository contains my training projects focused on Exploratory Data Analysis (EDA). The objective of these projects is to practice formulating and testing hypotheses, uncovering hidden patterns in data, handling anomalies, and creating clear, informative visualizations.

All projects were conducted using non-commercial datasets from the Kaggle platform.

---

## Project List

### 1. Titanic Passenger Survival Analysis (Titanic EDA)
A classic dataset used to explore the factors that influenced passenger survival rates during the Titanic shipwreck.

* **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn.
* **Key Steps Performed:**
    * Conducted a detailed missing value analysis (specifically focusing on age and cabin features) and applied appropriate imputation strategies.
    * Investigated the impact of socio-demographic factors (sex, age, passenger class) on survival probability.
    * Performed Feature Engineering: engineered new features, such as `FamilySize` (derived from the number of relatives) and passenger titles extracted from names.
* **Key Insight:** The analysis clearly confirmed the "women and children first" rule and revealed a strong dependency of survival rates on ticket class, showing that 1st class passengers held a significant advantage.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1BxOvpKI1rxXb5YdcXvKtuOCnpWK2cCBh)

---

### 2. Pokemon Characteristics Study (Pokemon EDA)
A multidimensional dataset containing base combat statistics, types, and generations of Pokemon. This dataset serves as an excellent foundation for grouping operations and correlation analysis.

* **Tools:** Python, Pandas, Seaborn, Matplotlib.
* **Key Steps Performed:**
    * Examined the distributions of combat metrics (HP, Attack, Defense, Speed) and identified outlier Pokemon with extreme stats.
    * Analyzed the relationship between Pokemon types (primary and secondary) and their total combat power.
    * Constructed a correlation matrix to identify dependencies between physical parameters and battle strengths.
* **Key Insight:** Visualizations demonstrated that Legendary Pokemon possess distinctly unbalanced stats. Furthermore, contrary to common gaming stereotypes, there is no rigid negative correlation between attack and defense attributes for most types.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1u5itggG7Of_ZjwrW0nMeWZ6jM6Zewp4m)

---

## Skills Acquired
Through completing these projects, I have reinforced the following skills:
* Cleaning data by removing noise/duplicates and handling NaN values.
* Grouping, aggregating, and filtering complex tabular data.
* Constructing data visualizations (Boxplots, Pairplots, Heatmaps, density plots).
* Interpreting statistical indicators to prepare data for downstream machine learning tasks.
