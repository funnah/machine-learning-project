# 🧠 Multimodal Machine Learning Project: Clustering, Regression & Classification

This project applies unsupervised learning, regression, and classification techniques to real-world datasets to uncover hidden patterns, make accurate predictions, and generate actionable insights across different domains.

---

## 🚀 Project Overview

### 🔹 Unsupervised Learning: Global Well-Being Clustering
Used **PCA**, **K-Means**, and **Hierarchical Clustering** on the World Happiness dataset to identify clusters of countries based on social, economic, and health-related indicators. Key insights include:
- 3 natural clusters representing developed, developing, and underdeveloped nations
- Principal components revealed underlying dimensions such as *quality of life*, *social capital*, and *freedom*

**Dataset**: [World Happiness Report (Kaggle)](https://www.kaggle.com/datasets/unsdsn/world-happiness?select=2019.csv)

---

### 🔹 Regression: Predicting Used Car Prices
Developed predictive models to estimate car resale value using features like power, engine size, transmission type, and mileage. Compared multiple algorithms:
- ✅ **Best Model**: Gradient Boosting (R² ≈ 0.98)
- 🔍 Key predictors: Power, Engine, Transmission

**Dataset**: [Used Car Price Prediction (Kaggle)](https://www.kaggle.com/datasets/sujithmandala/second-hand-car-price-prediction)

---

### 🔹 Classification: Employee Attrition Prediction
Trained classification models to predict whether an employee is likely to leave an organization based on factors like education, salary tier, and experience.
- ✅ **Best Model**: Logistic Regression (F1 score = 1.00)
- 🔍 Top features: Joining year, payment tier, and gender

**Dataset**: [Employee Dataset (Kaggle)](https://www.kaggle.com/datasets/tawfikelmetwally/employee-dataset)

---

## 🧰 Technologies & Tools
- **Python** (Scikit-learn, Pandas, Matplotlib, Seaborn)
- **R** (ggplot2, caret, dplyr)
- **SQL** (data preprocessing and extraction)
- Jupyter Notebooks, RMarkdown

---

## 📈 Key Results Summary

| Task            | Best Model          | R² / Accuracy | Top Features                    |
|-----------------|---------------------|---------------|---------------------------------|
| Clustering      | K-Means (k = 3)     | –             | GDP, life expectancy, freedom   |
| Regression      | Gradient Boosting   | 0.9819        | Power, Engine, Transmission     |
| Classification  | Logistic Regression | 1.000         | Joining year, Payment tier, Gender |

---
