# Customer-Lifetime-Value-Stroke-analysis
# 🧠 Stroke Prediction Using Machine Learning & Explainable AI

## 📌 About the Project

This project focuses on predicting the likelihood of stroke using machine learning techniques and explaining model predictions through Explainable Artificial Intelligence (XAI).

The project includes data exploration, preprocessing, handling class imbalance, model training, evaluation, and model interpretability using SHAP. A Random Forest model is trained and evaluated using various performance metrics to understand its ability to identify stroke cases.

The goal is to explore how machine learning and explainable AI can support the analysis of stroke-related risk factors.

## 🎯 Project Objectives

* Analyze stroke prediction data using Exploratory Data Analysis (EDA).
* Perform data preprocessing and handle missing values.
* Address class imbalance using oversampling techniques.
* Train and evaluate a machine learning model for stroke prediction.
* Interpret model predictions using SHAP.
* Analyze individual patient predictions and model errors.

##  Technologies Used

* **Python** – Programming language
* **Pandas & NumPy** – Data manipulation and numerical computation
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Machine learning and model evaluation
* **SHAP** – Explainable AI and feature importance analysis

## 📂 Project Structure

```text
Stroke-Prediction/
│
├── EDA/
│   └── Exploratory data analysis
│
├── Global Explanation/
│   └── Global feature importance analysis
│
├── Kernel SHAP (Neural Network)/
│   └── Neural network prediction explanations
│
├── Local Explanation/
│   └── Individual patient prediction analysis
│
├── Model Training & Evaluation/
│   └── Model training and performance evaluation
│
├── Preprocessing & Strategy/
│   └── Data preprocessing and oversampling
│
├── Set up and Data loader/
│   └── Dataset loading and preprocessing
│
└── README.md
```

##  Project Workflow

### 1. Exploratory Data Analysis (EDA)

* Loaded and explored the stroke prediction dataset.
* Visualized class imbalance.
* Examined feature distributions and relationships.

### 2. Data Preprocessing

* Handled missing values.
* Encoded categorical variables.
* Prepared training and testing datasets.
* Applied oversampling to address class imbalance.

### 3. Model Training & Evaluation

* Trained a Random Forest classifier.
* Evaluated model performance using:

  * Accuracy
  * Precision
  * Recall
  * F1-score
* Visualized the confusion matrix.

### 4. Explainable AI (XAI)

Used SHAP to interpret model behavior:

* **Global Explanation:** Analyzed overall feature importance and their contributions to model predictions.
* **Local Explanation:** Examined individual patient predictions, including true positives, false positives, and false negatives.
* **Kernel SHAP:** Explored explanations for Neural Network predictions.

##  Key Features

* End-to-end machine learning workflow.
* Data preprocessing and class imbalance handling.
* Random Forest model training and evaluation.
* SHAP-based model interpretability.
* Individual prediction analysis and error visualization.

##  Learning Outcomes

Through this project, I gained practical experience in:

* Exploratory Data Analysis and data visualization.
* Machine learning model development.
* Handling imbalanced datasets.
* Model evaluation using classification metrics.
* Explainable AI using SHAP.
* Interpreting model predictions and understanding classification errors.

##  Disclaimer

This project is intended for educational and research purposes only. It is not a medical diagnostic tool and should not be used to make clinical decisions.

##  Author

**Sushma Sundhar**

GitHub: [@sushmasundhar07-wq](https://github.com/sushmasundhar07-wq)

##  Acknowledgment

This project was developed as a learning exercise to explore machine learning, stroke prediction, and explainable AI.

If you find this project interesting, feel free to explore the repository and share your feedback!
