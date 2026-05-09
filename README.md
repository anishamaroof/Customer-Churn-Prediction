Customer Churn Prediction

DevelopersHub Corporation — Data Science & Analytics Internship

📌 Task Objective

Predict whether a customer is likely to leave (churn) or stay with a company using machine learning classification models.

📂 Dataset

Name: Customer Churn Dataset
Source: Loaded directly using pandas
Target: Churn — 1 = Customer Left, 0 = Customer Stayed

Key Features:
Customer Age
Tenure
Monthly Charges
Total Charges
Contract Type
Internet Service
Payment Method
And multiple customer-related features...
🛠️ My Approach
Step 1 — Data Loading & Inspection
Loaded dataset using pandas
Checked shape, columns, and data types
Displayed summary statistics
Step 2 — Data Cleaning
Checked missing values
Removed duplicate records
Converted categorical data using encoding techniques
Step 3 — EDA & Visualizations
Plot	Purpose
Count Plot	Churn vs Non-Churn distribution
Histogram	Monthly charges distribution
Box Plot	Tenure vs churn relationship
Correlation Heatmap	Feature correlations
Pie Chart	Customer contract distribution
Step 4 — Model Training
Logistic Regression
Random Forest Classifier
Decision Tree Classifier
Train/Test Split:
80% Training
20% Testing
Feature Scaling:
StandardScaler
📊 Results & Key Insights
Model	Accuracy
Logistic Regression	~82%
Decision Tree	~78%
Random Forest	~85%

✅ Random Forest performed best among all models

Key Insights:
Customers with higher monthly charges are more likely to churn
Short contract duration increases churn probability
Long-term customers are less likely to leave
Electronic payment users showed slightly higher churn rates
🧰 Libraries Used
pandas
numpy
matplotlib
seaborn
scikit-learn
🚀 How to Run
Open Google Colab or VS Code
Upload CUSTOMER_CHURN_PREDICTION.ipynb
Click Run All
Dataset loads automatically and model training starts ✅
Submitted by : Anisha Maroof
www.linkedin.com/in/anisha-maroof-9a85303a3
