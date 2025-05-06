# Predicting-Employee-Attrition-Using-Machine-Learning
This is a Machine Learning project focused on predicting employee attrition using HR analytics data. Employee attrition, or turnover, refers to employees leaving an organization for reasons such as poor management, limited growth opportunities, low compensation, work-life imbalance, or lack of recognition (Keserer, 2024). High attrition can disrupt operations, increase hiring costs, lower productivity, and harm relationships with customers and partners, ultimately affecting an organization's performance and reputation (Keserer, 2024; Kurian, 2024). Understanding and predicting employee attrition is therefore vital for organizations seeking to retain top talent and maintain a stable, efficient workforce.

## Objectives
This project aims to:

 * Develop a reliable machine learning model to accurately predict which employees are at high risk of leaving the organization.
 * Identify the most influential factors contributing to employee attrition.

## Data Description
The dataset used for this analysis is publicly available on Kaggle. [Link](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset). It contains HR-related data from a fictional organization, including features such as age, gender, marital status, job satisfaction, environment satisfaction, performance rating, monthly income, years at company, years with the current manager and more.

## Methodology Overview
The workflow includes:

<<<<<<< HEAD
**Data Preprocessing** – Handling missing values & duplicated observations, encoding categorical features, and scaling numerical features.

**Exploratory Data Analysis (EDA)** – Generating summary statistics and visualizing trends and patterns associated with attrition.

**Model Building** – Training various Machine Learning models (e.g., Logistic Regression, Random Forest, SVM, XGBoost) to classify attrition.

**Model Evaluation** – Using performance metrics like accuracy, precision, recall, F1-score, and AUC-ROC to select the best model.

**Feature Importance Analysis** – Determining which features most influence attrition predictions.

## Results

XGBoost algorithm performed best with a validation accuracy of 89.76%, Precision of 81.48%, and a ROC AUC value of 0.83. When this model predicts a positive case, it is correct 81.48% of the time, and when it predicts a negative case, it is correct 90.6% of the time.
=======
**1. Data Preprocessing** – Handling missing values & duplicated observations, encoding categorical features, and scaling numerical features.

**2. Exploratory Data Analysis (EDA)** – Generating summary statistics and visualizing trends and patterns associated with attrition.

**3. Model Building** – Training various Machine Learning models (e.g., Logistic Regression, Random Forest, SVM, XGBoost) to classify attrition.

**4. Model Evaluation** – Using performance metrics like accuracy, precision, recall, F1-score, and AUC-ROC to select the best model.

**5. Feature Importance Analysis** – Determining which features most influence attrition predictions.

## Results

SVM algorithm performed best with a validation accuracy of 88.05%, Precision of 80%, and a ROC AUC value of 0.80. When this model predicts a positive case, it is correct 80% of the time, and when it predicts a negative case, it is correct 88.64% of the time.
>>>>>>> e0793cb7bc8aabbc3829e03221c3b990a810b040

## Technologies Used
Rstudio software (Packages: tidyverse, janitor, caret, mlr, pROC, yardstick, vip, corrplot, parallel, parallelMap).
The packages should be installed prior to running the attached R markdown file. Note that running the entire document takes quite some time (about 4 hours on 8 CPU machine)

## Contributions
Contributions are welcome! Feel free to fork the repository, open issues, or submit pull requests to improve the project.
