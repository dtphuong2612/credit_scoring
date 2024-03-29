
# Revolutionizing Credit Scoring in Myanmar: Machine Learning Approaches for Risk Management

This project aims to revolutionize credit scoring in Myanmar, by using machine learning approaches to improve the accuracy and efficiency of risk management.




## Backgound

Credit scoring plays a crucial role in the lending industry, enabling financial institutions to evaluate the creditworthiness of individuals or businesses seeking loans. Traditionally, credit scoring has relied on manual processes and subjective assessments, leading to inefficiencies and potential biases. By leveraging machine learning algorithms and techniques, this project seeks to enhance the credit scoring process in Myanmar, resulting in more accurate and objective risk assessments.
## Goals

The goal of this project is to build a credit scoring machine learning model for risk management:

- Understand the data of loan history and customer data to build the model

- Develop and deploy a robust credit scoring model using machine learning techniques.

- Improve the accuracy and efficiency of credit risk assessment.

- Reduce the risk of defaults and improve the overall loan portfolio

## Reseach methods

Some research methods that have been used in the project to improve the machine
learning model for credit scoring in the risk management strategy in Myanmar:
- **Data collection**: Data in the project include the borrower’s payment history, the amount of debt they have, the length of their credit history, employment history, and income.

- **Data Cleaning**: Data has been cleaned after collection to remove any errors or inconsistencies. This will ensure that the model is trained on the correct data.

- **Feature Engineering**: After the data is clean, we need to design the features from the data. Features are the variables used to train the model. Features can be created by combining existing variables or by creating new ones from scratch.

- **Model selection**: Once the features have been designed, a model needs to be selected for training. There are many different machine learning models we can choose from. The best model will depend on the data collected and the features designed.

- **Model training**: Once a model has been selected, it needs to be trained on the data. This process involves providing data to the model and allowing the model to learn the relationships between the features and the target variable.

- **Model evaluation**: After the model is trained, it needs to be evaluated for its performance. This involves testing the model on a culling dataset not used to train the model. The evaluation results will show how well the model can predict the target variable.

- **Model tuning**: If the model’s performance is unsatisfactory, the model’s hyperparameters can be adjusted. Model parameters known as hyperparameters cannot be learned from the data. By tuning the hyperparameter, it is possible to improve the model’s performance.

## Data

This project was built upon a dataset from the Bank of Myanmar, in 2021. The dataset comprises three distinct data frames:

* The first data frame (named "Customer-info.csv") presents the demographic information of 115,848 customers. It encompasses various attributes such as ID, Name, date of birth, marital status, account status, onboarding branch ID, onboarding time, etc. 
* The second data frame (named "Loan-infomation.csv") describes the loan information of 15005 customers including debit/credit accounts, credit purposes, disbursement amount,  interest, date of the end of the tenor, etc.
* The third data frame (named Customer-account-transaction-history.csv) provides insight into the transaction history of 30091 customers. This data frame consists of 323717 records and 7 features that describe various aspects such as customer ID, debit/credit account ID, transaction amount, transaction content, etc. 

## Notebook Structure

The Jupyter Notebook structure includes:
- **EDA_creditCard**: the process of cleaning and preparing data for analysis. This may involve removing missing values, dealing with outliers, transforming data into a format that is suitable for analysis, feature engineering, feature selecting, and so on. The process of exploring data to gain insights into its distribution, patterns, and relationships using statistical methods, visualization techniques, and hypothesis testing.

- **Model_V1**: includes model training notebook and result set of trained models

- **Model_V2**: includes analysis of results and selection of important features for each model. And that includes the process of retraining models with important features.

- **loan_fn.csv**: Data set after preprocessing data to put into training model.
## Results

This project trained and evaluated many models including Logistic Regression, SVM, Random Forest, XGBoost, Gradient Boosting, and CATBoost. Models are trained on a dataset that includes demographic information, loan information, and customer transaction history.

Below is a detailed table of results on the validation set and test set of the models used in the project.

![Screenshot 2023-06-04 015040](https://user-images.githubusercontent.com/81805609/243126890-4a7e0125-9083-4fc9-bbb5-03c68dbd58bc.png)

Below are the model results after selecting the feature based on the feature importance weight.

![image](https://user-images.githubusercontent.com/81805609/243127449-732a8d15-0e09-4198-a396-e5ac29d8956e.png)


## Future Improvements

In the future, the study could be replicated with a larger sample size of borrowers. This would help to increase the generalizability of the findings. In addition, the study could be extended to include the impact of macroeconomic factors on credit risk. This would help to make lending decisions more informed.

Furthermore, the study provides valuable insights and a blueprint for other banks and financial institutions seeking to revolutionize their credit scoring practices using machine learning techniques. The high-performance metrics achieved in our study serve as evidence for the potential of machine learning to transform credit risk management in the banking industry.
