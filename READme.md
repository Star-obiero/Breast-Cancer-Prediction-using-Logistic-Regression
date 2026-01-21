🩺 Breast Cancer Prediction using Logistic Regression
📌 Project Overview

This project uses a Logistic Regression machine learning model to predict whether a breast tumor is Benign or Malignant based on medical diagnostic features.

Breast cancer diagnosis is a binary classification problem, making logistic regression an effective and interpretable model for this task.

🎯 Objective

The main objective of this project is to:

Build a logistic regression model

Predict whether a patient’s breast tumor is Benign (0) or Malignant (1)

Evaluate the model’s performance using standard classification metrics

📊 Dataset

The dataset contains medical measurements related to breast tumors

Each record represents a patient’s tumor characteristics

The target variable indicates whether the tumor is benign or malignant

Target Variable:

4→ Benign

2→ Malignant

(Dataset commonly sourced from the Breast Cancer Wisconsin dataset)

⚙️ Technologies Used

Python 🐍

NumPy

Pandas

Matplotlib / Seaborn

Scikit-learn

🧠 Machine Learning Model

Algorithm: Logistic Regression

Problem Type: Binary Classification

Why Logistic Regression?

Simple and efficient for binary classification

Easy to interpret

Performs well on linearly separable data

🛠️ Project Workflow

Data Loading

Data Exploration and Cleaning

Feature Selection

Data Splitting (Training & Testing)

Model Training using Logistic Regression

Model Evaluation

Prediction on new data

📈 Model Evaluation

The model is evaluated using:

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

These metrics help assess how well the model distinguishes between benign and malignant tumors.

🔮 Prediction

The trained model can take new patient diagnostic values as input and predict:

Benign tumor

Malignant tumor

This can assist in early diagnosis and decision-making.

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git


Navigate to the project folder:

cd your-repo-name


Open the Jupyter Notebook:

jupyter notebook


Run all cells in the notebook

📌 Results & Conclusion

Logistic Regression successfully classified breast tumors with good accuracy

The model demonstrates that machine learning can support medical diagnosis

Further improvements could include:

Trying advanced models (SVM, Random Forest, XGBoost)

Hyperparameter tuning

Cross-validation

📚 Future Work

Deploy the model using Flask or FastAPI

Add a user interface for real-time predictions

Compare multiple classification models