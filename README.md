# Student Math Score Prediction

## 📌 Project Overview

This project focuses on predicting students' mathematics scores using Machine Learning regression techniques.

The project uses a Student Performance dataset and compares three regression models:

- Linear Regression
- Decision Tree Regression
- Random Forest Regression

The models are evaluated using the R² (R-squared) score to determine how well they predict the mathematics scores.

## 🎯 Objective

The main objective of this project is to understand the basic workflow of a Machine Learning regression problem, including data exploration, preprocessing, feature encoding, model training, prediction, and model evaluation.

## 📊 Dataset

The dataset contains information related to student performance, including:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

The target variable for this project is **Math Score**.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn

## 🤖 Machine Learning Models

### 1. Linear Regression
A supervised learning algorithm used to predict a continuous numerical value.

### 2. Decision Tree Regression
A tree-based regression algorithm that makes predictions using a sequence of decision rules.

### 3. Random Forest Regression
An ensemble learning method that combines multiple decision trees to improve prediction performance.

## 🔄 Project Workflow

1. Load the dataset
2. Explore the dataset
3. Check and handle missing values
4. Prepare the features and target variable
5. Encode categorical features
6. Split the dataset into training and testing sets
7. Train the regression models
8. Generate predictions
9. Evaluate the models using R² score
10. Compare the model performances

## 📈 Results

| Model | R² Score |
|---|---:|
| Linear Regression | 0.8875 |
| Random Forest Regression | 0.8510 |
| Decision Tree Regression | 0.7604 |

Among the three models tested, **Linear Regression achieved the highest R² score** on the test dataset.

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Working with datasets using Pandas
- Performing basic data preprocessing
- Encoding categorical variables
- Splitting data into training and testing sets
- Training regression models using Scikit-learn
- Evaluating models using R² score
- Comparing the performance of different Machine Learning models

## 🚀 Future Improvements

The project can be further improved by experimenting with additional regression techniques, feature engineering, hyperparameter tuning, and other evaluation metrics.
## 📂 Dataset Source

The dataset used in this project was obtained from Kaggle.

The dataset contains information about students' demographic background, parental education, lunch type, test preparation, and mathematics, reading, and writing scores.

The dataset was used for educational and Machine Learning practice purposes.
## 📁 Repository Contents

```text
student-math-score-prediction/
│
├── Student_Math_Score_Prediction.ipynb
├── README.md
└── .gitignore
