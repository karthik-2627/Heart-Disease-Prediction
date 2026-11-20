# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview

Heart disease is one of the major health concerns worldwide. Identifying potential heart disease at an early stage can help people take preventive measures and seek medical attention at the right time.

In this project, I developed a Machine Learning model to predict whether a person is likely to have heart disease based on medical attributes such as age, cholesterol level, blood pressure, chest pain type, maximum heart rate and other health-related factors.

The main aim of this project is to explore healthcare data, understand important patterns and build predictive models that can support early risk identification.

## 🎯 Project Objective

- Analyze patient health data to identify patterns associated with heart disease.
- Perform Exploratory Data Analysis (EDA) to understand the dataset.
- Clean and prepare the data for machine learning.
- Build and compare different classification models.
- Evaluate model performance using appropriate evaluation metrics.
- Identify important features that influence predictions.

## 📝 Problem Statement

The objective of this project is to analyze patient medical data and develop a machine learning model that predicts the presence or absence of heart disease.

By using different patient health indicators, the project aims to identify patterns associated with heart disease and understand how machine learning can support early risk assessment.

## 📂 Dataset Description

The dataset contains patient health information and medical attributes used to predict heart disease.

**Input features include:**
- Age
- Sex
- Resting Blood Pressure
- Serum Cholesterol
- Chest Pain Type
- Maximum Heart Rate Achieved
- Exercise-Induced Angina
- Resting ECG Results
- Number of Major Vessels
- Thalassemia
- Other exercise-related health indicators

**Target variable:**
- `heart_disease_present`
  - `0` – No heart disease
  - `1` – Heart disease present

The dataset was provided as part of my DataMites project.

## 🛠️ Technologies & Libraries Used

**Programming Language:** Python

**Environment:** Google Colab

**Libraries:**
- Pandas – Data manipulation and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Scikit-learn – Machine learning and model evaluation

## 🔍 Project Workflow

### 1. Data Loading and Understanding
- Loaded the dataset into Python.
- Merged patient details and target labels using `patient_id`.
- Checked dataset shape, data types and statistical information.

### 2. Data Preprocessing
- Checked for missing values and duplicate records.
- Removed unnecessary identifier columns.
- Converted categorical variables into numerical format.
- Prepared the dataset for model building.

### 3. Exploratory Data Analysis (EDA)
- Analyzed the distribution of heart disease cases.
- Studied relationships between different health indicators.
- Used visualizations to understand patterns and correlations.
- Examined potential outliers.

### 4. Feature Engineering
- Separated independent and dependent variables.
- Applied One-Hot Encoding to categorical features where required.
- Used feature scaling for Logistic Regression.

### 5. Model Building

I experimented with the following machine learning algorithms:

**Logistic Regression**
- Built a baseline classification model.
- Used it to understand the relationship between input features and the target variable.

**Random Forest Classifier**
- Built an ensemble-based classification model.
- Compared its performance with Logistic Regression.

**Hyperparameter Tuning**
- Used GridSearchCV to identify better Random Forest hyperparameter combinations.
- Selected the best model based on cross-validation ROC-AUC.

### 6. Model Evaluation

Evaluated the models using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score
- ROC Curve

### 7. Feature Importance

Analyzed feature importance to understand which patient health attributes contributed most to the Random Forest model's predictions.

## 📊 Results and Conclusion

The project helped me understand how machine learning classification algorithms can be applied to healthcare-related datasets.

I compared Logistic Regression and Random Forest, performed hyperparameter tuning, and evaluated the models using multiple performance metrics.

The final model was selected based on its evaluation results. The project also helped me understand the importance of data preprocessing, feature engineering, model evaluation and selecting appropriate machine learning algorithms.

**Note:** Add your actual accuracy, precision, recall, F1-score and ROC-AUC values here after running your final notebook.

## 🚧 Challenges Faced

During this project, I worked through several challenges:

- Understanding the dataset and its medical features.
- Combining input data and target labels correctly.
- Handling categorical variables through encoding.
- Preparing numerical features for model training.
- Comparing different classification algorithms.
- Avoiding overfitting and improving model generalization.
- Selecting suitable hyperparameters using GridSearchCV.
- Working with a relatively small dataset.

## 🎓 Key Learnings

Through this project, I gained practical experience in:

- Data cleaning and preprocessing.
- Exploratory Data Analysis.
- Feature engineering and encoding.
- Classification algorithms.
- Model evaluation techniques.
- Hyperparameter tuning.
- Interpreting feature importance.
- Building an end-to-end machine learning workflow.

## 🚀 Future Improvements

- Train and validate the model using a larger dataset.
- Test the model on independent external data.
- Explore additional machine learning algorithms.
- Improve model generalization and reliability.
- Develop a simple web application for demonstration purposes.

## 👨‍💻 Author

**Tirunam Karthik**

Aspiring AI & ML Engineer | Python | Machine Learning | Data Science

## ⚠️ Disclaimer

This project is developed for educational and learning purposes only. It is not a clinically validated medical diagnostic system and should not be used to diagnose heart disease or make medical decisions. Any real-world application would require clinical validation, appropriate regulatory review and medical professional supervision.
