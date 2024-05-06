# Bank-Churn-Prediction-Project
![Image-Churn](https://github.com/Gospel-py/Bank-Churn-Prediction-Project/assets/149397162/9fd8e5d0-1263-42aa-8df2-6b94b1ffb391)

## Overview:
Customer churn, the phenomenon where customers cease their relationship with a business, can have significant financial implications for banks. Understanding and predicting churn can help banks retain customers and maintain revenue streams. This project focuses on building predictive models to anticipate churn behavior in a banking context.

Using a dataset containing historical customer information such as transaction history, demographics, account activity, customer interactions, and other relevant features, I aimed to develop machine learning models capable of identifying customers likely to churn in the future. By leveraging this predictive capability, banks can tailor retention strategies and allocate resources more effectively to mitigate customer attrition.

Throughout the project, I explored various machine learning algorithms, evaluated their performance using relevant metrics, and iteratively refined the models to achieve optimal predictive accuracy. Additionally, I conducted feature engineering to extract meaningful insights from the dataset and enhance the predictive power of our models.


## Features:

- **Dataset Exploration**: 
  - Analyzed and visualized the dataset to gain insights into customer behavior and characteristics.
  - Explored distribution of features and correlations to inform preprocessing steps.

- **Preprocessing**:
  - Conducted feature scaling and normalization to ensure uniformity across features.
  - Encoded categorical variables using techniques such as one-hot encoding or label encoding.
  - Applied SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance in the dataset.
  - Splitted the dataset into training and testing sets to evaluate model performance effectively.

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

**Features**:
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


## Getting Started:

As this project was developed on Google Collab, you can easily access and run the code directly in your browser. Follow these steps to get started:

1. **Accessing the Notebook**:
   - Click [here](https://colab.research.google.com/drive/1MFM7t-9BGTflstVqMnih6bWhU8BHbxLn?usp=sharing) to open the project notebook in Google Colab.

2. **Running the Notebook**:
   - Once the notebook is open, you can run each cell sequentially by pressing `Shift + Enter`.

3. **Interacting with the Code**:
   - Feel free to modify the code and experiment with different parameters, algorithms, or preprocessing techniques.

4. **Saving Results**:
   - Any outputs, including plots, tables, or trained models, will be saved automatically within the notebook.
   - You can also download the notebook for future reference or sharing purposes.

That's it! 

## Results:

### Model Performance:

After training and evaluating multiple machine learning algorithms, the Random Forest Classifier emerged as the top-performing model for predicting customer churn. Here are the key performance metrics obtained during evaluation:

- **Area Under the ROC Curve (AUC)**: 86.020448
- **F1-score**: 60.132450
- **Accuracy**: 84.95

### Visualizations:

Below is a screenshot showcasing the performance of the Random Forest Classifier in the notebook:

![Screenshot (307)](https://github.com/Gospel-py/Bank-Churn-Prediction-Project/assets/149397162/7b8fb734-66da-4f1d-8a66-7f7ef9c4eee1)

![Screenshot (308)](https://github.com/Gospel-py/Bank-Churn-Prediction-Project/assets/149397162/5325aa4b-70da-47cc-bfbf-b7f5b47d34ae)

![Screenshot (309)](https://github.com/Gospel-py/Bank-Churn-Prediction-Project/assets/149397162/396af1a2-e8f8-4b11-80f9-5604562039e1)

![Screenshot (311)](https://github.com/Gospel-py/Bank-Churn-Prediction-Project/assets/149397162/2803f433-37f8-429b-af43-060b632b088b)


### Interpretation:

- **Feature Importance**: Analysis of feature importance revealed Age, EstimatedSalary, CreditScore, Balance, NumOfProducts, Tenure as the most influential factors in predicting churn behavior.
 
![Screenshot (305)](https://github.com/Gospel-py/Bank-Churn-Prediction-Project/assets/149397162/cdf79cda-efe9-4b83-baaa-3279c6b5e764)



