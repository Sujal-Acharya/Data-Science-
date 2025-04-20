# 🇮🇳📦 A Data-Driven Study of India's Export Dynamics to the Americas

This repository contains the code, data analysis, and machine learning models for a project that explores India's export trends to American countries using statistical and machine learning techniques.

## 📌 Project Overview

In a rapidly evolving global trade environment, understanding export behavior is essential for informed decision-making. This project analyzes export data from India to American countries to:

- Identify top-performing commodities and recipient nations
- Detect patterns and trends over time
- Predict export value using machine learning models
- Cluster trade data to uncover potential opportunities

## 🧠 Key Questions

- What are the key drivers of export value?
- Can we predict export outcomes based on historical data?
- What hidden trade patterns can be discovered via clustering?
- How can insights help guide trade strategy and policy?

## 📊 Dataset

- **Source**: Indian Data Portal (https://indiadataportal.com/)
- **Format**: CSV
- **Data Points**: Top 100 exported commodities, export value in INR and USD, quantity, destination countries, HS codes, etc.
- **No. of Records**: 24,891

## 🧹 Data Preprocessing

- Null value checks (none found)
- Outlier treatment (log transformation, winsorization)
- Encoding categorical variables (LabelEncoder)
- Standardization of numerical features (StandardScaler)

## 🔍 Exploratory Data Analysis (EDA)

- Descriptive statistics & data distributions
- Correlation analysis between features
- Visualizations: boxplots, heatmaps, scatter plots

## 📈 Statistical & Machine Learning Models

### 📌 Regression Models
- **Linear Regression** — R²: 0.999
- **Random Forest Regressor** — R²: 0.998

### 📌 Classification
- **Logistic Regression**
- **Decision Tree Classifier**

### 📌 Clustering
- **K-Means Clustering** based on:
  - Export value, quantity, and INR value
  - Encoded country and commodity features

## 📉 Statistical Testing

- T-Test (e.g., Dominican Republic vs. Mexico)
- One-Way ANOVA across commodities

## 🔮 Predictive Modeling Benefits

- Data-driven decision making
- Early risk detection
- Better trade route prioritization
- Resource allocation and planning

## 📚 Research Reference

- Machine learning-driven forecasting for MSMEs
- Comparative advantage & trade complementarity with the USA
- Exchange rate volatility analysis

## ✅ Conclusion

This project demonstrates the power of data science in trade analytics by:
- Identifying key trade drivers
- Predicting export outcomes
- Revealing untapped trade potential through clustering

## 🛠 Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Statistical Libraries (SciPy)



---

📫 *Feel free to fork this repo, explore, or reach out for collaboration!*
