# Customer-Churn-Analysis

This project analyzes customer churn in a telecom dataset to identify key factors contributing to customer attrition. The insights derived can help telecom companies implement targeted strategies to retain customers and improve satisfaction.

Overview
Customer churn is a critical issue for telecom companies, as retaining existing customers is often more cost-effective than acquiring new ones. This project explores a telecom dataset, performs data preprocessing and visualization, and applies statistical analysis to uncover patterns and trends related to customer churn.

Dataset Description
The dataset used in this analysis contains 7,043 rows and 31 columns. It includes customer demographics, account details, service usage, and churn status.

Key features include:

Demographics: Gender, Senior Citizen, Partner, Dependents.
Service Details: Internet service type, online security, online backup, device protection, tech support, streaming TV, streaming movies.
Account Information: Contract type, paperless billing, payment method, monthly charges, total charges.
Target Variable: Churn (Yes/No).

Analysis Performed
1. Data Cleaning and Preparation
Handled missing values.
Encoded categorical variables.
Standardized numerical columns for consistency.
2. Exploratory Data Analysis (EDA)
Visualized customer demographics and service preferences.
Investigated relationships between features and churn rates.
Created correlation heatmaps to identify significant features.
3. Key Insights
High churn among customers using fiber optic services without tech support.
Many customers who churned did not sign up for online backup.
Monthly contracts had the highest churn rate.
Electronic check payments were linked to higher churn rates.
A significant portion of customers churned within the first 12 months.
4. Data Visualization
Used Seaborn and Matplotlib to create:
Bar plots.
Histograms.
Heatmaps.
Box plots for feature comparison.
Technologies Used
Python: Pandas, NumPy, Seaborn, Matplotlib.
Jupyter Notebook: For coding and visualization.
Scikit-learn: For preprocessing and analysis.
Results and Recommendations
Offer discounts or incentives to customers on monthly contracts to encourage long-term subscriptions.
Promote online backup and tech support to reduce churn.
Reassess billing systems to reduce the reliance on electronic check payments.
Focus retention strategies on new customers during the first 12 months.
