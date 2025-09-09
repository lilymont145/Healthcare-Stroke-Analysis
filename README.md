# 🧠 **Stroke Prediction Dataset Analysis**
## 📌 **Project Overview**

This project analyzes the Stroke Prediction Dataset (Kaggle) to explore demographic, lifestyle, and health-related factors associated with stroke. The main objective is to uncover meaningful patterns and insights through exploratory data analysis (EDA) and visualization, rather than predictive modeling.

The project focuses on understanding how variables such as age, gender, hypertension, heart disease, BMI, and average glucose level may influence the likelihood of stroke.

## 📂 **Dataset Description**

Source: Kaggle – Stroke Prediction Dataset

Records: ~5,000 individuals (after cleaning)

Features (10 total):

Demographic: gender, age, residence_type, marital_status

Health: hypertension, heart_disease, avg_glucose_level, bmi

Lifestyle: smoking_status, work_type

Target Variable: stroke (1 = stroke occurred, 0 = no stroke)

## 🔍 **Analysis Questions**

1.Which age groups are most represented in the dataset, and how might this affect the observed stroke patterns?

2.How many people have heart disease? 

3.Distribution of average glucose level

4.Does Smoking Behavior Influence Stroke Incidence?

5.How does the risk of stroke change across different age groups?

6.Which attributes show the strongest relationship with stroke?

## 📊 **Key Findings (EDA & Visualization)**

The dataset is highly imbalanced, with the majority of patients not experiencing a stroke.

Age shows the strongest relationship with stroke: older individuals are more likely to suffer from strokes.

Hypertension, heart disease, and high glucose levels show weak but positive correlations with stroke occurrence.

BMI has little correlation with stroke, suggesting it is not a strong standalone indicator in this dataset.

Smoking status shows mixed results, with a non-negligible portion of stroke cases coming from both smokers and non-smokers.

## 🛠️ **Tech Stack**

Python: pandas, numpy, matplotlib, seaborn

Jupyter Notebook for analysis & visualization