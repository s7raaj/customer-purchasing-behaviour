**Supermarket Sales Analysis and Customer Segmentation**
**1. Introduction**
This report analyzes customer purchasing behavior in a supermarket setting. The primary goal is to predict whether a customer will spend above or below the average transaction value using machine learning techniques.

**2. Data Overview**
The dataset contains the following columns:

Invoice ID
Branch
City
Customer type
Gender
Product line
Unit price
Quantity
Tax 5%
Total
Date
Time
Payment
Cogs
Gross margin percentage
Gross income
Rating
Average Transaction Value
The average transaction value calculated from the dataset is 322.97.

**3. Model Evaluation**
Logistic Regression Classification Report
markdown
Copy code
              precision    recall  f1-score   support

           0       0.96      1.00      0.98       113
           1       1.00      0.94      0.97        87

    accuracy                           0.97       200
   macro avg       0.98      0.97      0.97       200
weighted avg       0.98      0.97      0.97       200

**Logistic Regression Metrics**
Accuracy: 0.975
Precision: 1.0
Recall: 0.9425
F1 Score: 0.9704
**
Decision Tree Classifier**
Accuracy: 1.0
Feature Importance from Decision Tree
Feature	Importance
Tax 5%	1.0
Unit price	0.0
Quantity	0.0
Cogs	0.0
Gross margin percentage	0.0
Gross income	0.0
Rating	0.0
Branch_B	0.0
Branch_C	0.0
City_Naypyitaw	0.0
City_Yangon	0.0
Customer type_Normal	0.0
Gender_Male	0.0
Product line_Fashion accessories	0.0
Product line_Food and beverages	0.0
Product line_Health and beauty	0.0
Product line_Home and lifestyle	0.0
Product line_Sports and travel	0.0
Payment_Credit card	0.0
Payment_Ewallet	0.0

**Cross-Validation Results**
Logistic Regression Cross-Validation Accuracy Scores: [0.98, 0.975, 0.99, 0.99, 0.97]
Mean Accuracy: 0.981
Decision Tree Cross-Validation Accuracy Scores: [1.0, 0.99, 1.0, 1.0, 1.0]
Mean Accuracy: 0.998

**Feature Importance After Pruning**
Feature	Importance
Tax 5%	1.0
Unit price	0.0
Quantity	0.0
Cogs	0.0
Gross margin percentage	0.0
Gross income	0.0
Rating	0.0
Branch_B	0.0
Branch_C	0.0
City_Naypyitaw	0.0
City_Yangon	0.0
Customer type_Normal	0.0
Gender_Male	0.0
Product line_Fashion accessories	0.0
Product line_Food and beverages	0.0
Product line_Health and beauty	0.0
Product line_Home and lifestyle	0.0
Product line_Sports and travel	0.0
Payment_Credit card	0.0
Payment_Ewallet	0.0

**4. Marketing Strategies**
Based on the analysis, here are some personalized marketing strategies:

Develop Personalized Marketing Strategies: Focus on product categories that lead to higher spend to target customers effectively.

Promote Additional Services or Products: For customers purchasing in lower-transaction-value categories, suggest complementary services or products.

Utilize Loyalty Programs or Discounts: Encourage larger transactions, particularly in branches performing below average, through loyalty programs and targeted discounts.
