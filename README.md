# 🛳️ Survival Insights: Exploratory Data Analysis on Titanic Passengers

**Author:** Ezra Satria Bagas Airlangga  
**Project Type:** Mini Data Science Project  
**Model Used:** Random Forest Classifier  
**Dataset:** [titanic.xlsx](https://github.com/papapipopepo/Survival-Insights-Exploratory-Data-Analysis-on-Titanic-Passengers/blob/main/titanic.xlsx)  

---

## 📌 Project Overview

This project explores the Titanic dataset to understand the factors influencing passenger survival and builds a predictive model using Random Forest. By conducting a comprehensive Exploratory Data Analysis (EDA), the project highlights patterns and visual insights—particularly focusing on age and gender.

---

## 🎯 Objectives

- Understand the structure and key features of the Titanic dataset.
- Handle missing values and outliers effectively.
- Explore survival relationships based on age and gender.
- Build and evaluate a Random Forest model for survival prediction.
- Visualize key findings and feature importance.

---

## 🧮 Dataset Details

- **Rows:** 500 passengers  
- **Key features:**  
  - `survived` (0 = not survived, 1 = survived)  
  - `sex`  
  - `age`  
  - `name`

---

## 🔧 Data Preprocessing

- **Duplicate Handling:** 1 duplicate removed (final count: 499)
- **Missing Values:**  
  - Categorical: Imputed with mode  
  - Numeric: Imputed with median  
- **Outlier Treatment:**  
  - Age values clipped to a realistic boundary (ages < 3 or > 80)

---

## 📊 Exploratory Analysis & Visualization

- Histograms and visual comparisons show that:
  - **Females** had a significantly higher survival rate.
  - **Younger passengers** were more likely to survive.
- Feature importance plot supports these findings:
  - **Sex** is the most influential feature.
  - **Age** follows as the second most important.

---

## 🤖 Modeling

- **Algorithm:** Random Forest Classifier
- **Accuracy:** 82%
- **Metrics:**
  - Precision (survived): 0.89
  - F1-score (survived): 0.84
  - Recall (not survived): 0.85

- **Confusion Matrix:**
  - True Negatives: 33
  - True Positives: 49
  - False Positives: 6
  - False Negatives: 12

---

## ✅ Conclusion

- The model effectively identifies survival patterns using minimal features.
- Preprocessing steps like imputation and outlier handling improved model performance.
- The analysis confirms historical insights: **"Women and children first"** played a significant role in survival.

---

## 🧠 Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (RandomForestClassifier, evaluation metrics)
- Google Collab

---

## 📧 Contact & Collaboration
If you have any suggestions or feedback, feel free to reach out:

📧 ezra.satria16@gmail.com

🔗 [LinkedIn – Ezra Satria](https://www.linkedin.com/in/ezra-satria-70baa7334/)

#Python #BeginnerProject #PythonProgramming #LearningPython  #DataScience #Titanic #MachineLearning #EDA #DataExploration #RandomForest #ExploratoryDataAnalyst
