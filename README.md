# MLproject1FZT
Credit Card Fraud Detection
Project Overview
This project aims to detect fraudulent credit card transactions by analyzing a dataset of credit card transactions. The dataset contains various features related to transactions and is used to determine whether a transaction is fraudulent.

Contents
data/: Folder containing the datasets
notebooks/: Jupyter Notebook files for exploratory data analysis (EDA) and modeling
src/: Code files for data processing, modeling, etc.
results/: Model results and visualizations
README.md: Information about the project
Dataset
The dataset consists of 284,807 credit card transactions and 31 columns. The columns are as follows:

Time: Transaction time
Amount: Transaction amount
Class: Target variable (0 = Not Fraudulent, 1 = Fraudulent)
Data Preprocessing
Missing Values: Missing values were checked and necessary cleaning was performed.
Scaling: The Amount and Time columns were standardized using StandardScaler.
Exploratory Data Analysis (EDA)
Visualizations:
Scatter Plot: Transaction amounts over time
Histogram: Distribution of transaction amounts
Count Plot: Fraudulent vs. non-fraudulent transactions
Modeling
Model Selection: Basic classification models such as Logistic Regression, Decision Trees, and Random Forests will be used.
Class Imbalance: Class imbalance will be addressed using techniques such as SMOTE or class weighting.
Evaluation: Model performance will be evaluated using Precision, Recall, F1-score, and ROC-AUC metrics.
Libraries Used
pandas: Data processing
numpy: Numerical computations
matplotlib: Visualization
seaborn: Visualization
scikit-learn: Machine learning
