Fraud Detection in Credit Card Transactions Using Machine Learning

Overview
Credit card fraud detection is a critical challenge in the financial sector, leading to significant financial losses and reputational damage for institutions. This project applies machine learning techniques to classify fraudulent credit card transactions using publicly available datasets.

We compare five machine learning models—Random Forest, Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, and Support Vector Machine (SVM)—to determine the most effective fraud detection approach. The project follows the CRISP-DM methodology to systematically analyze the data, preprocess imbalanced datasets, and evaluate model performance.

Dataset
We used three anonymized credit card transaction datasets from Kaggle, each containing:

Transaction features (e.g., amount, time, location)
Fraud indicators (binary labels: fraud/not fraud)
Highly imbalanced class distributions
Machine Learning Models Used
Random Forest
Decision Tree
K-Nearest Neighbors (KNN)
Logistic Regression
Support Vector Machine (SVM)
Linear Kernel
RBF Kernel
Data Preprocessing
To handle class imbalance and improve model performance, we applied:

Data Cleaning (removing duplicates, handling missing values)
Outlier Removal using Interquartile Range (IQR)
Feature Engineering (removing highly correlated features)
SMOTE (Synthetic Minority Oversampling Technique) to balance fraud and non-fraud transactions
Evaluation Metrics
To ensure a robust fraud detection model, we used multiple evaluation metrics:

Accuracy (overall model correctness)
Precision (minimizing false positives)
Recall (minimizing false negatives)
F1-Score (harmonic mean of precision and recall)
Cohen’s Kappa Score (classification agreement)
ROC-AUC Score (model’s ability to distinguish fraud vs. non-fraud)
Confusion Matrix Analysis
Mean Absolute Percentage Error (MAPE)
Root Mean Squared Error (RMSE)
Key Findings
Random Forest outperformed all other models in accuracy, recall, and precision across all datasets.
Decision Trees and SVM with RBF kernel were also effective but computationally expensive for large datasets.
KNN worked well for detecting anomalies, but was sensitive to parameter tuning.
Logistic Regression provided a good baseline model, but lacked robustness for complex fraud patterns.
SMOTE significantly improved fraud detection rates by balancing dataset classes.
