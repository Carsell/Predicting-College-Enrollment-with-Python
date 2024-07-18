# Predicting College Enrollment with Python

This repository contains code and data for predicting college enrollment using machine learning techniques. The core analysis and modeling are done in Python using various libraries.

## Repository Structure

```plaintext
Predicting_College_Enrollment/
├── data/
│   └── data.csv
├── notebooks/
│   └── Predicting_College_Enrollment_with_Python.ipynb
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt

## Steps Included
Importing Required Libraries:
Utilizing essential libraries for data manipulation, visualization, and machine learning.

Loading and Inspecting the College Dataset:
Reading the dataset using pandas and performing an initial inspection.

Checking for Missing Values:
Utilizing isnull() and dtypes to identify and understand data types.

Visualizing Relationships with Pairplot:
Using seaborn to create a pairplot for visualizing relationships with data points.

Label Encoding Categorical Data:
Employing Label Encoder to convert categorical data to numeric format.

Splitting Data and Standard Scaling:
Separating data into features (X) and target label (y).
Utilizing StandardScaler to scale values in X columns.

Decision Tree Classifier:
Implementing Decision Tree Classifier.
Evaluating accuracy, precision, recall, F1 score, and checking for overfitting.
Performing cross-validation to ensure robustness and generalizability.

Random Forest Classifier:
Creating a Random Forest Classifier.
Determining optimal n_estimators.
Evaluating performance metrics - accuracy, precision, recall, F1 score.
Checking for overfitting.
Conducting cross-validation for a comprehensive assessment.

Usage:
Feel free to explore the provided Jupyter notebook for a detailed walkthrough of the analysis. This predictive modeling approach provides valuable insights for educational institutions to identify students likely to enroll in college, facilitating targeted interventions and strategic planning.
