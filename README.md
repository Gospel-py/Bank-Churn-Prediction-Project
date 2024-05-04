# Bank-Churn-Prediction-Project
![Image-Churn](https://github.com/Gospel-py/Bank-Churn-Prediction-Project/assets/149397162/9fd8e5d0-1263-42aa-8df2-6b94b1ffb391)

## Overview:
Customer churn, the phenomenon where customers cease their relationship with a business, can have significant financial implications for banks. Understanding and predicting churn can help banks retain customers and maintain revenue streams. This project focuses on building predictive models to anticipate churn behavior in a banking context.

Using a dataset containing historical customer information such as demographics, transaction history, and interactions with the bank, I aimed to develop machine learning models capable of identifying customers likely to churn in the future. By leveraging this predictive capability, banks can tailor retention strategies and allocate resources more effectively to mitigate customer attrition.

Throughout the project, I explored various machine learning algorithms, evaluated their performance using relevant metrics, and iteratively refined the models to achieve optimal predictive accuracy. Additionally, I conducted feature engineering to extract meaningful insights from the dataset and enhance the predictive power of our models.

The ultimate goal of this project is to provide banks with a toolset to proactively identify at-risk customers and implement targeted retention efforts, thereby fostering long-term customer relationships and maximizing profitability.


## Features:

- **Dataset Exploration**: 
  - Analyzed and visualized the dataset to gain insights into customer behavior and characteristics.
  - Explored distribution of features, missing values, and correlations to inform preprocessing steps.

- **Preprocessing**:
  - Conducted feature scaling and normalization to ensure uniformity across features.
  - Encoded categorical variables using techniques such as one-hot encoding or label encoding.
  - Applied SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance in the dataset.
  - Split the dataset into training and testing sets to evaluate model performance effectively.

- **Model Building**:
  - Implemented various machine learning algorithms such as Logistic Regression, Decision Trees, Random Forest, Gradient Boosting.
  - Fine-tuned hyperparameters using techniques like grid search to optimize model performance.
  - Used hyperparameter tuning technique to find the best hyperparameters for each model.

- **Evaluation**:
  - Assessed model performance using metrics such as accuracy, precision, recall, F1-score, and ROC AUC.
  - Employed techniques like cross-validation to ensure robustness of model evaluation.
  - Conducted thorough analysis of model errors to identify areas for improvement.
 
## Data:

The dataset used in this project consists of historical customer information obtained from [https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers]. The dataset contains a comprehensive set of features that capture various aspects of customer interactions with the bank. Here's an overview of the dataset:

- **Features**:
- **Credit Score (creditscore)**: The credit score of the customer.
- **Geography (geography)**: The country where the customer resides.
- **Gender (gender)**: The gender of the customer.
- **Age (age)**: The age of the customer.
- **Tenure (tenure)**: The number of years the customer has been with the bank.
- **Balance (balance)**: The account balance of the customer.
- **Number of Products (NumOfProducts)**: The number of bank products the customer has.
- **Has Credit Card (HasCrCcard)**: Indicates whether the customer has a credit card (1 if yes, 0 if no).
- **Is Active Member (IsActiveMember)**: Indicates whether the customer is an active member (1 if yes, 0 if no).
- **Estimated Salary (EstimatedSalary)**: The estimated salary of the customer.
- **Exited (Exited)**: The target variable indicating whether the customer has churned (1 if yes, 0 if no).

These features provide valuable insights into various aspects of customer behavior and demographics, which are instrumental in predicting customer churn.

