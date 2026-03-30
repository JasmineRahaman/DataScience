# DataScience

Project 1.Amazon Customer Behavior Analysis

-> Overview
This project analyzes customer behavior on Amazon using survey data. It explores demographics, shopping frequency, product search methods, cart abandonment factors, and satisfaction levels. The goal is to identify customer segments, understand churn risk, and uncover insights that can help improve customer experience.

-> Features
- Data cleaning and preprocessing of survey responses  
- Exploratory Data Analysis (EDA) with visualizations (age, gender, purchase categories, etc.)  
- Customer segmentation using **KMeans clustering**  
- Churn risk prediction using **Random Forest** and **Logistic Regression**  
- Feature importance analysis for churn prediction  
- Insightful visualizations (heatmaps, bar charts, churn distribution, etc.)  

-> Dataset
The dataset used is:  
Amazon Customer Behavior Survey.csv  
It contains survey responses on demographics, shopping frequency, product categories, recommendations, reviews, and satisfaction.

-> Key Insights
- Age group 23–35 dominates the dataset  
- Females shop more frequently than males  
- Beauty & personal care and clothing are top purchase categories  
- Cart abandonment is often due to **better prices elsewhere**  
- Customers with low purchase frequency show higher churn risk  

-> Visualizations
The project generates plots such as:
- Age distribution of customers  
- Gender distribution  
- Purchase category distribution  
- Customer segments (via clustering)  
- Churn risk distribution  
- Feature importance for churn prediction  
- Correlation heatmap

Project 2. Sales Forecasting Analysis

-> Overview
This project focuses on analyzing and forecasting sales using a mock Kaggle dataset. It explores sales trends, seasonality, and predictive modeling to estimate future sales and revenue. The goal is to understand historical sales behavior and build a forecasting model for better business planning.

-> Features
- Data preprocessing and feature engineering (date conversion, lag features, moving averages)  
- Exploratory Data Analysis (EDA) with monthly and weekly sales trends  
- Seasonality detection using moving averages  
- Predictive modeling with **Linear Regression**  
- Forecasting future sales and revenue for the next 60 days  
- Visualizations of historical vs. predicted sales  

-> Dataset
The dataset used is:  
**mock_kaggle.csv**  
It contains sales data with attributes such as date, stock, price, and sales volume.

-> Key Insights
- Monthly and weekly sales trends reveal seasonality patterns  
- Moving averages highlight long-term sales behavior  
- Linear Regression provides reasonable predictions with metrics like MAE, RMSE, and R²  
- Forecasting shows expected sales and revenue for the next 60 days  

-> Visualizations
The project generates plots such as:
- Monthly sales trend  
- Weekly sales trend  
- Sales trend with seasonality (30-day moving average)  
- Actual vs. predicted sales comparison  
- Sales forecast for future dates  


Project 3. Credit Card Fraud Detection

-> Overview
This project analyzes credit card transaction data to detect fraudulent activity. It combines exploratory data analysis, feature engineering, and machine learning models to classify fraud and identify anomalies. The goal is to improve fraud detection accuracy and highlight suspicious transaction patterns.

-> Features
- Data preprocessing and cleaning of transaction records  
- Exploratory Data Analysis (EDA) with fraud vs. non-fraud distributions  
- Feature engineering (high amount flag, night transactions, velocity flag)  
- Fraud classification using **Random Forest**  
- Anomaly detection with **Isolation Forest** and **Autoencoder**  
- Performance evaluation with confusion matrices and classification reports  
- Visualizations of fraud patterns and anomalies  

-> Dataset
The dataset used is:  
**credit_card_fraud_10k.csv**  
It contains transaction details such as transaction ID, amount, merchant category, transaction hour, device trust score, velocity, and fraud labels.

-> Key Insights
- Fraudulent transactions are more frequent during certain hours and merchant categories  
- High transaction amounts and low device trust scores are strong fraud indicators  
- Random Forest provides effective fraud classification with balanced performance  
- Isolation Forest and Autoencoder models highlight anomalies beyond labeled fraud cases  

-> Visualizations
The project generates plots such as:
- Fraud vs. non-fraud transaction distribution  
- Fraud by transaction hour  
- Fraud by merchant category  
- Device trust score vs. fraud  
- Transaction amount vs. fraud  
- Isolation Forest anomalies scatterplot  
- Autoencoder anomalies scatterplot  


Project 4. IBM HR Employee Attrition Analysis

-> Overview
This project analyzes employee attrition using the IBM HR dataset. It explores demographic, job-related, and satisfaction factors that influence attrition. The goal is to identify key drivers of employee turnover and build predictive models to support HR decision-making.

-> Features
- Data preprocessing and cleaning of HR records  
- Exploratory Data Analysis (EDA) on attrition by age, department, job satisfaction, income, overtime, and tenure  
- Feature engineering (Tenure flag, High income flag, Promotion gap flag)  
- Attrition prediction using **Random Forest Classifier**  
- Feature importance analysis to identify key predictors of attrition  
- Visualizations of attrition patterns and feature importance  

-> Dataset
The dataset used is:  
**WA_Fn-UseC_-HR-Employee-Attrition.csv**  
It contains employee details such as age, department, education, income, job role, satisfaction levels, tenure, and attrition status.

-> Key Insights
- Employees with **low tenure (<2 years)** show higher attrition risk  
- **Overtime** is strongly associated with attrition  
- **Monthly income** influences attrition, with lower-income employees more likely to leave  
- **Job satisfaction** and **work-life balance** are critical factors in retention  
- Random Forest highlights tenure, income, and promotion gaps as important predictors  

-> Visualizations
The project generates plots such as:
- Attrition vs. non-attrition distribution  
- Attrition by department  
- Attrition by job satisfaction  
- Attrition by age, income, overtime, and tenure  
- Feature importance for attrition prediction  
