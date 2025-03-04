# Economic Recession Analysis and Prediction

## Project Overview

This project explores economic recessions using statistical tools and predictive modeling techniques to analyze their causes, impacts, and potential mitigation strategies. The study leverages economic indicators such as GDP, unemployment rates, inflation, and consumer spending, alongside machine learning methodologies, including time series analysis and the Random Forest algorithm, to predict recession probabilities for 2024, 2025, and 2026.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Literature Review](#literature-review)
- [Methodology](#methodology)
  - [Data Collection and Preprocessing](#data-collection-and-preprocessing)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Analysis](#analysis)
  - [Predictive Modeling](#predictive-modeling)
  - [Evaluation and Validation](#evaluation-and-validation)
  - [Insights and Recommendations](#insights-and-recommendations)
- [Results](#results)
  - [Economic Indicator Analysis](#economic-indicator-analysis)
  - [Predictive Modeling Results](#predictive-modeling-results)
- [Future Scope](#future-scope)
- [References](#references)

## Introduction

Economic recessions are marked by a sharp decline in economic activity and have significant social and financial consequences. This study utilizes statistical and machine learning techniques to analyze recession patterns and predict their occurrence. By examining economic indicators and integrating predictive analytics, the research provides insights that can aid policymakers and businesses in making informed decisions.

## Dataset

The dataset comprises economic indicators sourced from:

- **FRED (Federal Reserve Economic Data)**
- **Yahoo! Finance (S&P 500 index data)**
- **Macroeconomic Indicators (GDP, inflation, unemployment rates, etc.)**

The dataset spans historical data from **1854 to 2023** and includes key variables such as:

- 10-Year Treasury Constant Maturity Rate
- 2-Year Treasury Constant Maturity Rate
- Federal Funds Rate
- Employment Data
- Consumer Price Index (CPI)
- S&P 500 Index Price Changes

## Literature Review

Prior studies have explored machine learning methods in economic forecasting. Key findings include:

- **Supervised Learning Models** such as logistic regression and support vector machines have shown promise in predicting economic downturns.
- **Alternative Data Sources**, including search queries and credit card transactions, enhance prediction accuracy.
- **Random Forest and Decision Trees** outperform traditional models in detecting early recession indicators.
- **COVID-19's Economic Impact** has significantly influenced financial modeling and predictive strategies.

## Methodology

### Data Collection and Preprocessing

- Data gathered from **FRED, Yahoo! Finance, IMF, and other economic databases**.
- Cleaned and formatted data for consistency.
- Removed outliers and handled missing values.
- Standardized features using normalization techniques.

### Exploratory Data Analysis (EDA)

- Generated **correlation heatmaps** to identify key recession indicators.
- Analyzed **economic trends and patterns**.
- Visualized data distributions and relationships using **time series graphs and scatter plots**.

### Analysis

- Examined statistical relationships between economic indicators and recessions.
- Identified **leading indicators** of economic downturns.

### Predictive Modeling

- **Machine Learning Models Used:**
  - Logistic Regression
  - Decision Tree Classifier
  - K-Nearest Neighbors (KNN)
  - Support Vector Machines (SVM)
  - Random Forest Classifier
- **Feature Selection:**
  - Selected features based on correlation analysis.
  - Removed highly correlated variables to prevent redundancy.
- **Training and Testing:**
  - Split dataset into **70% training and 30% testing**.
  - Used **TimeSeriesSplit for cross-validation**.

### Evaluation and Validation

- **Performance Metrics Used:**
  - Precision-Recall AUC
  - ROC AUC Scores
  - Confusion Matrices
- **Findings:**
  - **Random Forest achieved the highest accuracy**, outperforming other models.
  - **Support Vector Classifier was effective** in detecting recessions with a PR AUC of 0.83.

### Insights and Recommendations

- Recession prediction models can help policymakers **anticipate downturns** and implement timely interventions.
- Yield curve inversions and employment trends are **strong indicators** of future recessions.
- Combining traditional economic data with **alternative data sources** improves model robustness.

## Results

### Economic Indicator Analysis

- **Heatmap Analysis:** Identified correlations between CPI, employment rates, and stock market trends.
- **Yield Curve Inversions:** Detected as a leading indicator of recession probability.
- **Employment vs. Inflation Trends:** Showed a strong inverse correlation.

### Predictive Modeling Results

- **Recession Probability for 2023:** Machine learning models flagged September 2019 and March 2022 as warning signals.
- **Recession Prediction for 2024:** No major recession predicted.
- **Recession Prediction for 2025:** Potential economic downturn identified in late 2025.

## Future Scope

- **Incorporate Deep Learning Models** (e.g., LSTM, Transformer models) for improved forecasting.
- **Enhance Sentiment Analysis** using NLP on financial news and economic reports.
- **Integrate Global Economic Indicators** such as geopolitical events, trade policies, and international markets.
- **Improve Model Interpretability** using SHAP and LIME for feature importance analysis.
- **Ethical Considerations and Data Privacy Compliance** to ensure responsible AI use in economic forecasting.

## References

A detailed list of references from academic sources and economic studies supporting this research.
