# MachineLearningProject_Connecttel
ConnectTel enlisted our data science team to develop a machine learning-based customer churn prediction system. By analyzing customer data, we provided accurate churn forecasts, enabling targeted retention strategies. This proactive approach helps ConnectTel reduce churn, boost loyalty, and stay competitive in the telecom industry.
![image](https://github.com/user-attachments/assets/c1a64e0d-f439-42b3-8393-96884f06eaf6)

## Table Of Content
1.  Introduction
2. Problem Statement
3. Data Overview
4. Exploratory Data Analysis (EDA)
6. Model Development
7. Model TRAINNING & Evaluation
8. Recommendations
9. Conclusion

## Introduction:
ConnectTel is a telecommunications company focused on maintaining business sustainability and growth. However, the company is currently facing challenges in customer retention, which is crucial for its success in the competitive telecom industry. To stay competitive, ConnectTel aims to adopt proactive strategies that enhance customer loyalty and reduce churn.

## Current Challenges
ConnectTel’s existing customer retention strategies are ineffective, leading to the loss of valuable customers to competitors. To address this, the company seeks to develop a robust customer churn prediction system, leveraging advanced analytics and machine learning. This initiative aims to forecast churn accurately and implement targeted retention measures to minimize customer attrition.

## Project Aim
Development of a predictive model to forecast churn and enable targeted retention initiatives.

## Data sources:
The dataset used for the customer churn prediction project at ConnectTel  includes several key types of data about customers. That provide valuable insights into customer behavior, demographics, and interaction with services. Four of the most important features for connectel are monthly charges, payment method, tenure & contract

## Data Cleaning:
DATA WAS MAJORLY CLEAN, WITH NO MISSING VALUES

## Model development, training and selection.
The customer churn prediction analysis was built using supervised machine learning approach. Training and test data was split 80:20. Several classification algorithms were experimented with, including but not limited to:
Logistic Regression, Random Forest, K-Nearest Neighbour, Decision Tree

## Key Insights
After extensive experimentation and hyperparameter tunning, the final ML model was selected based on the objective of the project, which is Recall (Recall= TP/(TP+FN): from all the positive classes, how many we predicted correctly. Recall should be high as possible.)
•	The main purpose of this project is to help with customer churn prediction for connecttel
•	Based on the problem, ConnectTel aims to develop a robust customer churn prediction system . The company seeks to accurately forecast customer churn and implement targeted retention initiatives; By this , it means that the company favors CLASS1 (CHURN)
•	The plot of churn vs non-churn shows that approximately 26% of the customers will churn ; as there is a serious class imbalance. This has to be taken care of in the model, as connecttel seems to want to prevent customer churn. What is important to the company is RECALL
•	The best model to chose from will be the one with lowest FN from the confusion matrix, emphasizing on RECALL , and the LogisticRegression model came up tops

## Conclusion
With the successful development of our customer churn prediction model, we achieved a high Recall of 92% using the Logistic Regression approach, demonstrating the model's strong ability to identify potential churners accurately (After a comprehensive evaluation of various models). Though the overall accuracy stands at 68%, this high Recall ensures we can proactively target at-risk customers, enhancing retention efforts and enabling ConnectTel to prioritize loyalty-focused strategies effectively. This model serves as a critical tool for minimizing customer loss and driving long-term growth in our competitive market.


