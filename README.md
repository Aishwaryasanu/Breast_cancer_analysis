# Breast_cancer_analysis
# Breast-Cancer-Logistic-Regression
Project Overview
This project explores the Breast Cancer Wisconsin Diagnostic Dataset to analyze tumor characteristics and predict whether tumors are benign (0) or malignant (1).
The analysis includes data preprocessing, exploratory data analysis (EDA), visualization, feature importance analysis, and machine learning classification using Logistic Regression.

Dataset Information
* Source: [Breast Cancer Wisconsin (Diagnostic) Dataset – UCI/Kaggle]
* Description: Contains data of 569 patients with 30 features derived from digitized images of fine needle aspirate (FNA) of breast mass.
  * Features: mean, standard error, and worst values of characteristics like radius, texture, perimeter, area, smoothness, concavity, etc.
  * Target:
    * 0 → Benign
    * 1 → Malignant

Objectives
* Clean and preprocess the dataset
* Handle categorical encoding and feature scaling
* Perform Exploratory Data Analysis (EDA)
* Visualize trends and correlations in tumor features
* Build and evaluate Logistic Regression model
* Interpret model coefficients and tune classification threshold

Technologies & Libraries Used
* Language:Python 3
* Libraries:
  * Data Handling → pandas, numpy
  * Visualization → matplotlib, seaborn
  * Machine Learning → scikit-learn

Key Highlights

1. Exploratory Data Analysis (EDA)
* Identified correlations between tumor features and diagnosis.
* Used heatmaps, pair plots, and histograms to visualize patterns.
* Discovered strong correlations (e.g., *radius, area, perimeter*) with malignant diagnosis.

2. Data Cleaning and Preprocessing
* Removed irrelevant columns (`id`, empty columns).
* Encoded diagnosis (`M` → 1, `B` → 0).
* Standardized features using `StandardScaler` for ML models.

3. Feature Engineering
* Explored feature importance using Logistic Regression coefficients.
* Considered dimensionality reduction (e.g., Recursive Feature Elimination).
* Highlighted top predictive features: concavity, area, radius, and perimeter.

4. Machine Learning Model
* Logistic Regression:
  * Achieved high accuracy with standardized features.
  * Evaluated using confusion matrix, precision, recall, F1-score, ROC-AUC.
  * Tuned decision threshold to balance precision and recall.

5. Visualization and Insights
* Heatmaps for correlation analysis.
* ROC curve to evaluate classifier performance.
* Sigmoid function plot to explain probability outputs.
* Coefficient bar charts to show most influential tumor features.

Results & Insights
* Logistic Regression provided a simple yet interpretable model with strong predictive performance.
* Features like **concavity, radius, perimeter, and area** were the most important indicators of malignancy.
* ROC-AUC score demonstrated excellent model separability between benign and malignant cases.
* Threshold tuning allowed trade-off control between precision and recall for different clinical needs.




