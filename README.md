# ML_CLASSIFICATION_PROJECT
# 🩺 Breast Cancer Prediction Using Machine Learning


## 📌 Project Overview


This project focuses on predicting breast cancer using Machine Learning classification algorithms.


The dataset contains medical and demographic information of **10,000 patients**. The project follows a complete Machine Learning workflow, including data loading, data cleaning, exploratory data analysis (EDA), preprocessing, model training, prediction, and model evaluation.


Six different classification algorithms were implemented and compared:


1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree
4. Random Forest
5. Naive Bayes
6. Support Vector Machine (SVM)


---


## 🎯 Objectives


- Understand and analyze the breast cancer dataset.
- Perform data cleaning and preprocessing.
- Handle missing values.
- Perform Exploratory Data Analysis (EDA).
- Prepare features and target variables.
- Train multiple classification models.
- Evaluate and compare model performance.
- Identify the performance of different classification algorithms.


---


## 📊 Dataset


The dataset contains medical and demographic information for **10,000 patients**.


The target variable is used to predict whether a patient is likely to have breast cancer.


The dataset includes different patient-related features such as:


- Age
- Gender
- BMI
- Family History
- Genetic Risk
- Hormone Therapy
- Physical Activity
- Alcohol Consumption
- Smoking
- Tumor Size
- Medical History
- Other medical and demographic attributes


---


## 🧹 Data Preprocessing


The following preprocessing steps were performed:


- Loaded the dataset using Pandas.
- Removed the `Annual_Income_USD` column.
- Checked dataset information using `info()`.
- Generated statistical summaries using `describe()`.
- Checked the dataset shape and column names.
- Checked for missing values.
- Handled missing categorical values using `"Unknown"`.
- Filled missing numerical values using the mean.

Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the dataset and identify patterns and relationships between different variables.

Libraries Used for EDA
Pandas
NumPy
Matplotlib
Seaborn

The analysis included statistical summaries and data visualizations to better understand the characteristics of the dataset before applying Machine Learning models.

Machine Learning Classification Algorithms
1. Logistic Regression

Logistic Regression is a supervised Machine Learning algorithm commonly used for binary classification problems. It estimates the probability of an observation belonging to a particular class.

2. K-Nearest Neighbors (KNN)

KNN classifies a new observation based on the classes of its nearest neighboring observations.

3. Decision Tree

A Decision Tree is a supervised Machine Learning algorithm that makes predictions using a tree-like structure of decision rules.

4. Random Forest

Random Forest is an ensemble learning algorithm that combines multiple decision trees to make a final classification.

5. Naive Bayes

Naive Bayes is a probabilistic classification algorithm based on Bayes' theorem and assumes conditional independence between features.

6. Support Vector Machine (SVM)

Support Vector Machine finds a decision boundary that separates different classes while maximizing the margin between them.

Model Evaluation

The classification models were evaluated using accuracy on the test dataset.

Results
Algorithm	Accuracy
Logistic Regression	100%
K-Nearest Neighbors (KNN)	100%
Decision Tree	100%
Random Forest	100%
Naive Bayes	100%
Support Vector Machine (SVM)	100%

All six models achieved 100% accuracy on the evaluated test dataset.

Since all models achieved the same accuracy, no single model can be identified as the best-performing model based on accuracy alone.

Important: A 100% test accuracy result is unusually high for a medical classification problem. This result should not be interpreted as evidence of real-world clinical performance. Further validation using cross-validation, additional evaluation metrics, and checks for possible data leakage would be necessary before drawing conclusions about real-world use.

Recommended Evaluation Metrics

For a medical classification problem, accuracy alone may not provide a complete picture of model performance.

Future evaluation can include:

Precision
Recall
F1-Score
Confusion Matrix
ROC-AUC
Cross-Validation

These metrics can provide a more comprehensive understanding of how the models classify different classes.

Machine Learning Workflow
Dataset
   ↓
Data Loading
   ↓
Data Cleaning
   ↓
Missing Value Handling
   ↓
Exploratory Data Analysis
   ↓
Data Preprocessing
   ↓
Feature & Target Selection
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Model Comparison
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Project Structure
Breast-Cancer-Prediction/
│
├── breast_cancer_prediction.ipynb
├── breast_cancer_prediction.csv
├── README.md
└── requirements.txt
How to Run the Project
1. Clone the Repository
git clone https://github.com/bensonbenny17/ML_CLASSIFICATION_PROJECT.git
2. Navigate to the Project Directory
cd ML_CLASSIFICATION_PROJECT
3. Install Required Libraries
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
4. Launch Jupyter Notebook
jupyter notebook
5. Open the Notebook

Open:

breast_cancer_prediction.ipynb

Run the notebook cells sequentially to reproduce the analysis and model evaluation.

Key Learning Outcomes

Through this project, I gained practical experience in:

Python for Data Analysis
Pandas DataFrame operations
NumPy
Data Cleaning
Missing Value Handling
Exploratory Data Analysis
Data Visualization
Machine Learning Classification
Model Training
Model Prediction
Model Evaluation
Comparing Multiple Classification Algorithms
Future Improvements

The project can be further improved by:

Applying cross-validation.
Evaluating Precision, Recall, F1-Score, and ROC-AUC.
Creating confusion matrices for each model.
Investigating possible data leakage.
Performing feature selection.
Applying hyperparameter tuning.
Comparing additional classification algorithms.
Testing the models on an independent dataset.
Conclusion

This project demonstrates an end-to-end approach to Machine Learning classification, from data cleaning and exploratory analysis to model training, prediction, evaluation, and comparison.

Six classification algorithms were implemented: Logistic Regression, KNN, Decision Tree, Random Forest, Naive Bayes, and SVM.

All six models achieved 100% accuracy on the evaluated test dataset. However, because this is a medical classification problem, the result requires further validation using additional evaluation metrics, cross-validation, and data-leakage checks before making any conclusions about real-world performance.

The project provided valuable hands-on experience with Python, Pandas, Scikit-learn, EDA, data preprocessing, classification, and model evaluation.

Author

Benson Mathew

Skills Demonstrated

Python Pandas NumPy Scikit-learn Machine Learning Data Analysis EDA Data Visualization Classification
