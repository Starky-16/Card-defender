# Card defender
This project focuses on detecting fraudulent transactions using machine learning.
Credit card fraud is a critical financial crime, and early detection can help prevent massive losses.
The goal is to build a model that can classify whether a given transaction is fraudulent or genuine.

📌 Problem Statement

Given a dataset of credit card transactions, the task is to develop a model that can classify fraud (1) vs non-fraud (0).
The dataset is highly imbalanced, with very few fraud transactions compared to genuine ones — making this an excellent problem for classification and imbalance handling techniques.

🔍 Key Features of the Project

✔ Data preprocessing & feature scaling
✔ Handling class imbalance (SMOTE / Undersampling / Oversampling)
✔ Multiple ML algorithms tested
✔ Model evaluation using advanced metrics
✔ Visualization of fraud vs non-fraud patterns
✔ Final deployed notebook/script included

🗂 Dataset

Source: Kaggle – Credit Card Fraud Detection Dataset

Contains 284,807 transactions

Fraudulent cases: 492 (0.172% of dataset)

Column	Description
Time	Seconds elapsed between transaction & first transaction
V1-V28	PCA-transformed features (confidentiality protected)
Amount	Transaction amount
Class	1 = Fraud, 0 = Genuine
📦 Technologies Used
Tool / Library	Purpose
Python	Programming
Pandas, NumPy	Data handling
Scikit-Learn	Model training + evaluation
Matplotlib / Seaborn	Visualization
SMOTE / Imbalanced-Learn	Balancing dataset
Logistic Regression / Random Forest / XGBoost	Classifiers
🔥 Workflow — Step-by-Step

Load & explore dataset

Check null values + clean data

Visualize fraud distribution

Apply scaling using StandardScaler

Handle class imbalance (SMOTE/RUS/Oversampling)

Train ML Models

Evaluate using metrics

Save final model
