# Exploratory_Data_Analysis_Project

📊 IBM Watson Employee Dataset – EDA Project (SDG Goal 8)


👩‍💻 Team Members

Hema B (23MIA1101)

Priyanka S (23MIA1032)

Kavya N (23MIA1125)


📌 Project Overview

This project is a comprehensive Exploratory Data Analysis (EDA) conducted on the IBM Watson Employee dataset, aligned with Sustainable Development Goal (SDG) 8 – Decent Work and Economic Growth. It was developed as a part of the CSE3040 – EDA course under the M.Tech Integrated CSE (Business Analytics) curriculum.
The goal was to understand employee behaviors, attrition patterns, compensation distribution, and structural dynamics in the organization using data science techniques.


🧠 Objectives

Analyze how demographic and professional attributes influence employee attrition and income.
Perform data cleaning, preprocessing, and transformation.
Detect outliers and group employees using clustering.
Apply feature selection and dimensionality reduction.
Build a simple linear regression model to explore income prediction.
Use frequent pattern mining to uncover hidden associations.


🗃️ Dataset

Source: IBM Watson HR Dataset
Size: 1676 Rows × 35 Columns
Features: Demographics, job role, salary, satisfaction, experience, etc.
No missing or duplicate values, enabling efficient preprocessing.


🔧 What We Did (Step-by-Step)

✅ Data Cleaning & Preprocessing
    - Label encoding, feature scaling, and imputation techniques (Mean, KNN, MICE).
    - Removal of constant columns like EmployeeCount and StandardHours.

✅ Exploratory Data Analysis
    - Histograms, boxplots, and correlation heatmaps.
    - Insights on salary distribution, job level, attrition rate, etc.

✅ Outlier Detection & Clustering
    - Z-Score & IQR-based methods.
    - KMeans clustering revealed employee groupings based on compensation and experience.

✅ Feature Selection
    - ANOVA, Mutual Information, and Recursive Feature Elimination (RFE).
    - Top features influencing attrition: Age, YearsAtCompany, JobInvolvement, etc.

✅ Dimensionality Reduction
    - PCA and LDA for better class separability and visualization.

✅ Regression Analysis
    - Simple Linear Regression between Age and Monthly Income.
    - Revealed a weak linear relationship (R² ≈ 0.31).

✅ Frequent Pattern Mining
    - Used Apriori algorithm for association rules among departments and roles.
    - Discovered strong interdepartmental patterns.


👥 Teamwork & Collaboration

This project was a collaborative effort that involved:
Dividing tasks like coding, documentation, and visualization.
Brainstorming insights together from plotted graphs and stats.
Peer-reviewing each other’s work to ensure accuracy and consistency.
Presenting findings to faculty in a structured final review.


🔍 Key Insights

Most employees earn lower income and have fewer years at the company.
Attrition is closely tied to Age, Total Working Years, and Job Level.
Certain roles and departments show strong associations, suggesting possible restructuring insights.
A simple regression alone is insufficient; a multivariate model is more effective for income prediction.


🚀 Future Scope

Implement classification models like Decision Trees or Random Forests for attrition prediction.
Add economic and survey data to enrich analysis.
Deploy the model as an HR dashboard using Streamlit or Power BI.
Use time-series models and advanced ML like XGBoost or LSTM for predictive HR analytics.


🙏 Acknowledgment

We sincerely thank Prof. Dr. Asnath Victy Phamila Y (SCOPE) for her continuous support and guidance throughout this project. We also acknowledge the support of our peers and Udemy courses that aided in mastering key concepts.

