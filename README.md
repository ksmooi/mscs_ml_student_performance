# Predicting Student Performance: An Analytical Approach

This repository contains the code and analysis for predicting student performance based on various factors using multiple machine learning algorithms.

## [Project Overview](notebooks/student_performance_insights.ipynb)

The objective of this project is to predict students' final grades (G3) based on their demographic information, family background, educational support, extracurricular activities, and personal attributes.

## [Dataset](notebooks/student_performance_insights.ipynb)

The dataset includes information about students such as:
- Demographics: school, sex, age, address
- Family Background: famsize, Pstatus, Medu, Fedu, Mjob, Fjob, guardian
- Educational Support: traveltime, studytime, failures, schoolsup, famsup, paid, activities, nursery, higher, internet, romantic
- Personal Information: famrel, freetime, goout, Dalc, Walc, health, absences
- Grades: G1, G2, G3

## [Exploratory Data Analysis (EDA)](notebooks/student_performance_insights.ipynb)

The EDA involves:
- Visualizing the distribution of numerical features
- Visualizing categorical features
- Analyzing feature relationships with the target variable (G3)

## [Model Selection](notebooks/student_performance_insights.ipynb)

We evaluated several machine learning algorithms to find the best model for predicting student performance:
1. Logistic Regression
2. Decision Tree Classifier
3. Support Vector Machine
4. Random Forest Classifier
5. AdaBoost Classifier
6. Gradient Boosting Classifier
7. K Neighbors Classifier
8. Gaussian Naive Bayes

## [StudentPerformanceAnalyzer Class](notebooks/student_performance_insights.ipynb)

This class is designed to:
- Load the dataset and initialize models
- Preprocess data by encoding, splitting into train/test, and standardizing features
- Train various classifiers and evaluate their metrics
- Compare model performance
- Plot feature importances for selected models

## [Model Training and Evaluation](notebooks/student_performance_insights.ipynb)

Each model was trained on the training data and evaluated on the testing data. Evaluation metrics include accuracy, precision, recall, and F1 score.

## [Analysis Results](notebooks/student_performance_insights.ipynb)

### Model Performance

- **Gradient Boosting Classifier**: Highest accuracy (0.515385)
- **Random Forest Classifier**: Moderate accuracy (0.446154)
- **Decision Tree Classifier**: Lower accuracy (0.384615)
- **Other Models**: Showed lower performance

### Feature Importance

- **Gradient Boosting Classifier**: Top features are G2, G1, absences, age, and free time
- **Random Forest and Decision Tree Classifiers**: Similar top features, emphasizing G1, G2, absences, free time, and parental education

## [Insights and Recommendations](notebooks/student_performance_insights.ipynb)

1. **Importance of Continuous Assessment**:
   - G1 and G2 are crucial for predicting G3.
   - Implement regular assessments and feedback.

2. **Attendance and Engagement**:
   - Absences and free time impact performance.
   - Improve attendance and participation programs.

3. **Family Background**:
   - Parental education affects performance.
   - Engage families and provide support for equal opportunities.

4. **Holistic Approach**:
   - Address academic, social, and emotional needs for student success.

## [References](notebooks/student_performance_insights.ipynb)

- Project: [Jupyter Notebook](notebooks/student_performance_insights.ipynb)
- Dataset: [Kaggle: Student Performance Data Set](https://www.kaggle.com/datasets/larsen0966/student-performance-data-set/data)
- Additional Analysis: [Kaggle Notebook: Annual Grades Average 5-Level Classification](https://www.kaggle.com/code/sharonyaroshetsky/annual-grades-average-5-level-classification#Outliers-Detection)
