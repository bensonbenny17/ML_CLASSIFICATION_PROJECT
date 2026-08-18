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


Example:


```python
df["BMI"] = df["BMI"].fillna(df["BMI"].mean())
🔍 Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the dataset and identify patterns and relationships.

The project uses:

Pandas
NumPy
Matplotlib
Seaborn

Various visualizations and statistical analyses were used to understand the data before applying Machine Learning models.

🤖 Classification Algorithms
1. Logistic Regression

Logistic Regression is a statistical Machine Learning algorithm commonly used for binary classification problems. It predicts the probability of an observation belonging to a particular class.

2. K-Nearest Neighbors (KNN)

KNN classifies a new data point based on the classes of its nearest neighboring observations.

3. Decision Tree

Decision Tree is a supervised Machine Learning algorithm that makes predictions using a tree-like structure of decision rules.

4. Random Forest

Random Forest is an ensemble learning algorithm that combines multiple decision trees to make a final classification.

5. Naive Bayes

Naive Bayes is a probabilistic classification algorithm based on Bayes' theorem.

6. Support Vector Machine (SVM)

SVM finds an optimal decision boundary that separates different classes while maximizing the margin between them.

📈 Model Performance

All six classification algorithms achieved 100% accuracy on the evaluated test dataset.

Algorithm	Accuracy	Conclusion
Logistic Regression	100%	Perfect classification on the evaluated test set.
K-Nearest Neighbors (KNN)	100%	Correctly classified all test observations.
Decision Tree	100%	Achieved perfect test accuracy.
Random Forest	100%	Achieved perfect test accuracy.
Naive Bayes	100%	Correctly classified all test observations.
Support Vector Machine (SVM)	100%	Achieved perfect test accuracy.
🏆 Conclusion

In this project, six different Machine Learning classification algorithms were implemented for breast cancer prediction.

Logistic Regression, KNN, Decision Tree, Random Forest, Naive Bayes, and SVM all achieved 100% accuracy on the evaluated test dataset.

Since all models produced the same accuracy, there is no single best-performing algorithm based on accuracy alone. The results indicate that the models were able to classify the observations in the test set successfully.

However, because this is a medical classification problem, accuracy should not be the only evaluation metric. Further evaluation using Precision, Recall, F1-Score, Confusion Matrix, and ROC-AUC would provide a more comprehensive assessment of model performance.

The reported 100% accuracy should also be validated using cross-validation and checks for possible data leakage before considering the models for real-world medical prediction.

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
📂 Project Structure
Breast-Cancer-Prediction/
│
├── breast_cancer_prediction.ipynb
├── breast_cancer_prediction.csv
└── README.md
🔄 Machine Learning Workflow
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
📚 Key Learning Outcomes

Through this project, I gained practical experience in:

Python for Data Analysis
Pandas DataFrame operations
NumPy
Data Cleaning
Handling Missing Values
Exploratory Data Analysis
Data Visualization
Machine Learning Classification
Model Training and Prediction
Model Evaluation
Comparing Multiple Classification Algorithms
👨‍💻 Author

Benson Mathew

Skills Demonstrated

Python Pandas NumPy Machine Learning Scikit-learn Data Analysis EDA Data Visualization Classification



### ⭐ One thing I'd change before uploading


Because **100% accuracy across all six models is unusually high**, keep the wording **“100% accura
