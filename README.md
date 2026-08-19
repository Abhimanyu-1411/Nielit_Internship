
````markdown
# Student Burnout Prediction

A machine learning project developed during my **30-day Summer Internship in Artificial Intelligence & Machine Learning using Python at NIELIT Guwahati**.

The project focuses on analysing student-related data, identifying patterns associated with burnout, and applying machine learning to classify students into different burnout levels.

## Project Overview

The dataset contains **150,000 student records and 20 features** related to academic performance, lifestyle, stress, sleep, study habits, screen time, and other student-related factors.

The project follows a complete data analysis and machine learning workflow:

```text
Dataset
   ↓
Data Inspection
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis
   ↓
Correlation Analysis
   ↓
Feature Encoding
   ↓
Feature Scaling
   ↓
Train-Test Split
   ↓
Random Forest Classification
   ↓
Model Evaluation
````

## Dataset

The dataset contains information related to:

* Academic performance
* Study hours
* Sleep quality
* Stress level
* Screen time
* Attendance
* Physical activity
* Social support
* Financial stress
* Other student-related factors

The target variable is:

**`burnout_level`**

with three classes:

* Low
* Medium
* High

## Objectives

* Understand the structure and characteristics of the dataset
* Identify missing and duplicate values
* Perform exploratory data analysis
* Analyse relationships between student factors and burnout
* Preprocess numerical and categorical variables
* Apply feature scaling
* Build a machine learning classification model
* Evaluate the model using classification metrics and a confusion matrix

## Exploratory Data Analysis

The analysis included:

* Statistical summaries
* Missing-value analysis
* Duplicate-value analysis
* Feature distributions
* Correlation analysis
* Burnout-level distribution
* Stress-level analysis
* Sleep-quality analysis
* Study-hours analysis
* Screen-time analysis
* Other relationship-based visualizations

## Data Preprocessing

The following preprocessing steps were performed:

* Checked for missing values
* Checked for duplicate records
* Analysed data types
* Encoded categorical variables
* Scaled numerical features
* Prepared training and testing datasets

## Machine Learning Model

### Random Forest Classifier

A **Random Forest Classifier** was trained to classify students into Low, Medium, and High burnout levels.

The model was implemented using **Scikit-learn**.

```python
from sklearn.ensemble import RandomForestClassifier

model = RandomForestClassifier(
    n_estimators=100,
    random_state=42
)

model.fit(X_train, y_train)
```

## Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

The classification results showed an overall accuracy of approximately **33.45%** on the test set.

The model performance indicates that further feature engineering, model selection, class analysis, and hyperparameter tuning could be explored to improve predictive performance.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Structure

```text
student-burnout-prediction/
│
├── Student_Burnout_Prediction.ipynb
├── README.md
└── dataset/
    └── student_burnout.csv
```

## Key Learning Outcomes

Through this project, I gained practical experience in:

* Data cleaning
* Exploratory Data Analysis
* Statistical analysis
* Data visualization
* Categorical encoding
* Feature scaling
* Machine learning classification
* Model evaluation
* Interpreting classification reports and confusion matrices

## Internship

This project was completed as part of my:

**30-Day Summer Internship**
**Artificial Intelligence & Machine Learning using Python**
**NIELIT Guwahati**

**Duration:** 20 June 2026 – 19 July 2026

## Author

**Abhimanyu Deb**

B.Tech Computer Science & Engineering
Royal Global University, Guwahati, Assam

**Email:** [abhimanyudeb53@gmail.com](mailto:abhimanyudeb53@gmail.com)

```

I deliberately included the **33.45% result** here because a GitHub README should be transparent about the actual model outcome. Your resume can omit it, but the project repository should document it accurately.
```
