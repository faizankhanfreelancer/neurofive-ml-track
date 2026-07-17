# 🚢 Neurofive ML Track – Titanic Machine Learning Project

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-teal)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Project Overview

This repository contains my work for the **Neurofive Solutions Machine Learning Track**, where I explored the famous **Titanic - Machine Learning from Disaster** dataset from Kaggle.

The project demonstrates the complete machine learning workflow, starting from **Exploratory Data Analysis (EDA)** and ending with building a **Logistic Regression Classification Model** to predict passenger survival.

The primary objective of this project is to understand the dataset, clean and preprocess the data, explore hidden patterns, and build a predictive machine learning model using Python and Scikit-learn.

---

# 📊 Task 1 — Exploratory Data Analysis (EDA)

The first phase focuses on understanding the dataset before applying any machine learning algorithms.

### ✔ Activities Performed

- Loaded the Titanic dataset using Pandas
- Displayed dataset information using:
  - `head()`
  - `info()`
  - `describe()`
- Checked dataset dimensions
- Identified missing values
- Distinguished numerical and categorical features
- Checked duplicate records
- Performed descriptive statistics
- Created multiple visualizations using Matplotlib and Seaborn
- Wrote observations and business insights

### 📈 Visualizations

- Missing Values Analysis
- Survival Count
- Passenger Class Distribution
- Gender Distribution
- Age Distribution
- Fare Distribution
- Correlation Heatmap
- Survival by Gender
- Survival by Passenger Class

### 📌 Key Findings

- The dataset contains **891 passengers** and **12 columns**.
- The **Cabin** column contains a large number of missing values.
- Female passengers had a significantly higher survival rate than males.
- First-class passengers survived more frequently than third-class passengers.
- Passenger age and fare played an important role in survival.

---

# 🤖 Task 2 — Titanic Survival Prediction

The second phase focuses on building a machine learning model capable of predicting passenger survival.

### ✔ Machine Learning Workflow

- Data Cleaning
- Missing Value Handling
- Feature Selection
- One-Hot Encoding using `pd.get_dummies()`
- Train-Test Split
- Logistic Regression Model
- Model Prediction
- Accuracy Evaluation
- Confusion Matrix
- Classification Report

---

# 📊 Model Performance

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score

The Logistic Regression model achieved a strong baseline performance for this binary classification problem.

---

# 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 📂 Repository Structure

```
neurofive-ml-track/
│
├── Titanic_EDA.ipynb
├── Titanic_Classification.ipynb
├── README.md
└── requirements.txt
```

---

# 🎯 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Data Preprocessing
- Machine Learning
- Logistic Regression
- Model Evaluation
- Classification Metrics
- Python Programming

---

# 🚀 Future Improvements

This project will be extended with additional machine learning techniques, including:

- Decision Tree Classifier
- Random Forest Classifier
- Support Vector Machine (SVM)
- XGBoost
- Hyperparameter Tuning
- Cross Validation
- Model Comparison
- Feature Importance Analysis
- Streamlit Dashboard
- Model Deployment

---

# 📊 Dataset

**Titanic - Machine Learning from Disaster**

Dataset Source:
https://www.kaggle.com/competitions/titanic

---

# 👨‍💻 Author

**Faizan Khan**

Computer Science Student | Machine Learning Enthusiast | Generative AI & Agentic AI Learner

- GitHub: https://github.com/faizankhanfreelancer
- LinkedIn: https://www.linkedin.com/in/faizankhan-cs

---

## ⭐ Acknowledgements

This project was completed as part of the **Neurofive Solutions Machine Learning Track**, with the goal of building practical skills in data analysis, machine learning, and predictive modeling using Python and Scikit-learn.

If you found this project helpful, consider giving the repository a ⭐.
