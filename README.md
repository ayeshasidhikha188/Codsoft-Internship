# CodSoft Data Science Internship Tasks

This repository contains the projects completed as part of the **CodSoft Data Science Internship**. Each project tackles a real-world problem, applying data analysis, preprocessing, and machine learning techniques. Below is a detailed overview of the tasks and their outcomes.



---

## Task 1: Titanic Survival Prediction

### Objective:
Build a model to predict whether a passenger on the Titanic survived based on features like age, gender, ticket class, fare, cabin, and more.

### Key Steps:
1. **Data Analysis**: Exploratory data analysis (EDA) to understand the dataset.
2. **Preprocessing**: Handle missing values, encode categorical features, and scale numerical features.
3. **Modeling**: Train multiple machine learning models such as Logistic Regression, Random Forest, and Support Vector Machines.

### Best Model: Logistic Regression
**Why Logistic Regression?**
- **High Accuracy (86%)**: Achieved the best performance with minimal error, making it ideal for reliable predictions.
- **No Overfitting**: Generalizes well to unseen data.
- **Fast Training & Prediction**: Efficient for real-time applications.
- **Simplicity & Interpretability**: Easy to understand and explain, ideal for decision-making.

**Conclusion**: Logistic Regression was the clear winner due to its balance of high accuracy, efficiency, and interpretability.

---

## Task 2: Movie Rating Prediction

### Objective:
Build a model to predict movie ratings based on features like genre, director, and actors, using regression techniques.

### Key Steps:
1. **Data Analysis**: Understand historical movie data and identify key factors influencing ratings.
2. **Feature Engineering**: Preprocess data, handle missing values, and create new features to improve model performance.
3. **Modeling**: Experiment with regression models, including Linear Regression, Decision Trees, and Support Vector Regressors (SVR).

### Best Model: Support Vector Regressor (SVR)
**Why SVR?**
- **Test R² Score (0.2281)**: Outperformed other models with a higher score.
- **Train-Test Gap**: The gap between Train R² (0.791) and Test R² (0.2281) is acceptable, indicating a good balance between fitting and generalization.
- **Reliability**: Strikes a balance between overfitting and underfitting, making it the most dependable choice.

**Conclusion**: The SVR model was selected for its ability to generalize well and deliver reliable predictions.

---

## Task 3: Credit Card Fraud Detection

### Objective:
Identify fraudulent credit card transactions using machine learning models.

### Key Steps:
1. **Data Preprocessing**: Normalize transaction data, handle class imbalance with oversampling or undersampling techniques.
2. **Model Training**: Train various classification algorithms, such as Logistic Regression, Random Forest, and XGBoost.
3. **Evaluation**: Use metrics like precision, recall, and F1-score to evaluate model performance.

### Best Model: Logistic Regression
**Why Logistic Regression?**
- **Fast Training (3.01 seconds)**: Highly efficient training process.
- **High Accuracy**: Achieved an F1 score of **0.9990** on the validation set and **0.9991** on the test set.
- **No Overfitting**: Consistent performance on validation and test sets ensures good generalization.

**Conclusion**: Logistic Regression emerged as the best model for its speed, accuracy, and ability to generalize well, making it the most reliable choice.

---

## Final Remarks

These tasks demonstrate the practical application of data science techniques to solve diverse real-world problems. Key skills showcased include:
- **Exploratory Data Analysis (EDA)**.
- **Feature Engineering and Preprocessing**.
- **Machine Learning Modeling and Evaluation**.

Each task highlights the importance of selecting the right model for the problem and balancing performance, efficiency, and reliability.

