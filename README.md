# ML-for-IDS
Intrusion Detection System (IDS) using Machine Learning
This project implements an Intrusion Detection System (IDS) using machine learning techniques to classify network activities as "Attack" or "Non-Attack". The code preprocesses the NSL-KDD dataset, performs feature extraction using PCA, and evaluates two classifiers: Support Vector Machine (SVM) and Random Forest (RF).

Features of the Project
Data Preprocessing:

Handles missing values using imputation.
Encodes categorical variables using Label Encoding.
Applies PCA for dimensionality reduction.
Model Training & Evaluation:

Uses Stratified K-Fold Cross-Validation with Random OverSampling to handle class imbalance.
Evaluates models (SVM and RF) using metrics like Accuracy, Sensitivity, Specificity, and Execution Time.
Visualization:

Plots PCA results for feature visualization.
Compares model performance through bar plots.
Prediction:

Allows the user to predict whether a specific data point is an "Attack" or "Non-Attack".
How to Run?
Install the required libraries:
pip install pandas numpy scikit-learn matplotlib seaborn imbalanced-learn streamlit
Place the NSL-KDD Dataset file in the specified directory and ensure the path is correct in the code.
Run the script in your Python environment.
Outputs
Model metrics: Accuracy, Error Rate, Sensitivity, Specificity, and Execution Time.
Graphical comparison of SVM and RF models.
Prediction of attack classification for specific data points.
