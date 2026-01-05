**Customer Churn Analysis & Prediction**

*Project Overview*

This project focuses on identifying key indicators of customer turnover (churn) using a dataset of 20 customer profiles. By leveraging Python’s data science ecosystem, the goal was to uncover behavioral patterns that lead to cancellations and build a predictive model to help businesses improve retention strategies.

*Key Insights*

My analysis revealed two significant drivers of churn:

Contract Type: Customers on short-term (Month-to-month) contracts exhibited a significantly higher churn rate compared to those on long-term commitments.

Payment Method: There is a stark contrast in loyalty based on payment habits. Electronic check users had the highest churn rate, while customers using Bank transfers showed a 0% churn rate during the study period.

*Tech Stack*

Language: Python

Libraries: * Pandas: For data manipulation and cleaning.

Matplotlib & Seaborn: For visualizing trends and correlation heatmaps.

Scikit-Learn: For building the regression models and generating performance metrics.

*Methodology & Model Evaluation*

The project involved data cleaning, EDA, and the implementation of a Logistic Regression model. To ensure the model's reliability, I evaluated the results using a comprehensive classification report:

Precision: Accuracy of positive predictions
Recall: Ability to find all positive instances (churned customers)
F1-Score: Harmonic mean of precision and recall
Confusion Matrix: Used to visualise true positives vs false positives 

*Recommendations*

Based on the data, the following strategies are recommended:

Incentivize Long-term Contracts: Offer discounts or loyalty rewards for customers switching from monthly to annual plans.

Payment Method Migration: Encourage the use of automated bank transfers over electronic checks to stabilize the customer base.
