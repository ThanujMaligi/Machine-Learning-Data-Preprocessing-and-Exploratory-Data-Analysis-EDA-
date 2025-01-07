# 🩺 Children's Anemia Dataset Analysis

Welcome to the **Children's Anemia Dataset Analysis** repository! This project explores the factors influencing children's anemia through a structured approach that includes **data preprocessing**, **exploratory data analysis (EDA)**, **feature engineering**, and **machine learning model building**.

---

## 📖 Table of Contents

- [📌 Introduction](#introduction)
- [🛠️ Data Preprocessing](#data-preprocessing)
- [🔍 Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [✨ Feature Engineering](#feature-engineering)
- [🤖 Model Building](#model-building)
- [📊 Results](#results)

---

## 📌 Introduction

This project aims to uncover the factors affecting children's anemia and predict key outcomes using machine learning. By analyzing this dataset, we can gain valuable insights and create models to aid in decision-making.

---

## 🛠️ Data Preprocessing

Data preprocessing ensures the dataset is clean and analysis-ready:  

- **Handling Missing Values**: Missing entries were either imputed or removed based on the requirements.  
- **Data Type Conversions**: Categorical variables were encoded for compatibility with machine learning models.  
- **Normalization/Scaling**: Numerical features were normalized or scaled to improve model performance.

---

## 🔍 Exploratory Data Analysis (EDA)

EDA reveals hidden patterns and relationships in the data:

### 📊 Univariate Analysis
- **Age Distribution**: Histograms depict the distribution of age.  
- **Hemoglobin Levels**: Box plots highlight outliers and data spread.  
- **Place of Residence**: Bar charts showcase rural vs. urban distributions.  

### 🔗 Bivariate Analysis
- **Scatter Plots**: Reveal relationships between variables like age and hemoglobin levels.  
- **Correlation Heatmaps**: Highlight relationships between numerical variables visually.

---

## ✨ Feature Engineering

New features were created to enhance predictive power:  

- **AgeCategory**: Numerical midpoints representing age groups.  
- **HemoglobinDifference**: Difference between hemoglobin levels adjusted for altitude and smoking status.  
- **BirthsInterval**: Age gap between respondents and their first childbirth.  
- **WealthEducationInteraction**: An interaction term between wealth index and education level.  
- **SmokingAnemia**: Binary feature indicating smoking habits alongside anemia status.

---

## 🤖 Model Building

Leveraging insights from EDA and feature engineering, machine learning models were built to predict outcomes:  

- **Outlier Handling**: Strategically retained or removed outliers based on analysis.  
- **Feature Selection**: Assessed the relevance of features for modeling.  
- **Model Training**: Trained various machine learning algorithms on the processed dataset.  

---

## 📊 Results

The models' performance was evaluated using metrics like:  
- **Accuracy**  
- **Precision**  
- **Recall**  
- **F1-Score**

Additional visualizations, including **ROC curves** and **confusion matrices**, were generated to better interpret the results.

---

### 🩺 Empowering better health outcomes through data-driven insights! 🌟
