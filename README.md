# 🚀 Neurofive ML Track

## 📖 Project Overview

This repository contains my solutions for the **Neurofive Solutions Machine Learning Track**. Throughout this learning journey, I explore the complete machine learning pipeline—from data exploration and preprocessing to model development, evaluation, hyperparameter tuning, and solving real-world business problems.

Each task focuses on a different machine learning concept and demonstrates practical implementation using Python, Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn.

---

# 📂 Repository Structure

```text
neurofive-ml-track/
│
├── Titanic_EDA.ipynb
├── Titanic_Classification.ipynb
├── House_Price_Prediction.ipynb
├── Model_Evaluation_and_Tuning.ipynb
├── Customer_Churn_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

# 📊 Task 1 – Titanic Exploratory Data Analysis (EDA)

## Objective

Perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand its structure, identify missing values, and discover meaningful insights before building machine learning models.

### Activities Performed

* Loaded the dataset using Pandas
* Explored data using `head()`, `info()`, and `describe()`
* Identified missing values
* Distinguished numerical and categorical features
* Performed statistical analysis
* Created visualizations using Matplotlib and Seaborn
* Summarized key findings

### Outcome

Successfully explored the Titanic dataset and identified important relationships between passenger characteristics and survival.

---

# 🤖 Task 2 – Titanic Survival Prediction (Classification)

## Objective

Build a machine learning classification model to predict whether a passenger survived the Titanic disaster.

### Workflow

* Data Cleaning
* Missing Value Handling
* Feature Selection
* One-Hot Encoding
* Train-Test Split
* Logistic Regression
* Model Prediction
* Performance Evaluation

### Evaluation Metrics

* Accuracy
* Confusion Matrix
* Classification Report

### Outcome

Developed a Logistic Regression classifier capable of predicting passenger survival with strong baseline performance.

---

# 🏠 Task 3 – House Price Prediction (Regression)

## Objective

Predict California house prices using Linear Regression.

### Workflow

* Loaded the California Housing dataset
* Data Cleaning
* Feature Selection
* Train-Test Split
* Linear Regression Model
* Prediction
* Model Evaluation

### Evaluation Metrics

* Root Mean Squared Error (RMSE)
* R² Score

### Visualization

* Actual vs Predicted Scatter Plot
* Feature Coefficient Analysis

### Outcome

Built a regression model capable of estimating house prices while evaluating prediction quality using RMSE and R² Score.

---

# ⚙️ Task 4 – Model Evaluation & Hyperparameter Tuning

## Objective

Improve a classification model using advanced evaluation metrics and hyperparameter tuning.

### Workflow

* Revisited the Titanic dataset
* Trained a baseline Decision Tree Classifier
* Evaluated using multiple metrics
* Applied GridSearchCV
* Tuned multiple hyperparameters
* Compared baseline and tuned models

### Hyperparameters Tuned

* `max_depth`
* `min_samples_split`
* `criterion`

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### Outcome

Learned how hyperparameter tuning and comprehensive evaluation improve the reliability and performance of machine learning models.

---

# 📞 Task 5 – Customer Churn Prediction (Business Problem)

## Objective

Develop machine learning models to predict customer churn using the IBM Telco Customer Churn dataset and identify the factors that contribute most to customer attrition.

### Workflow

* Loaded the Telco Customer Churn dataset
* Performed Exploratory Data Analysis (EDA)
* Cleaned and preprocessed the data
* Handled categorical variables using label encoding
* Checked class imbalance
* Trained a Logistic Regression model
* Trained a Decision Tree Classifier
* Compared both models using evaluation metrics
* Identified the most important features influencing customer churn
* Prepared a business-focused summary of the results

### Models Used

* Logistic Regression
* Decision Tree Classifier

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

### Feature Importance

The Decision Tree model was used to identify the most influential features affecting customer churn through `feature_importances_`.

### Business Insights

* Customers with month-to-month contracts are more likely to churn.
* Customers with shorter tenure have a higher risk of leaving.
* Monthly charges and contract type play a significant role in predicting churn.
* Retention strategies focused on these customer groups can help reduce churn and improve long-term customer loyalty.

### Outcome

Successfully built and compared two classification models while analyzing customer behavior and presenting actionable business insights.

---

# 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# 🤖 Machine Learning Algorithms

* Logistic Regression
* Linear Regression
* Decision Tree Classifier

---

# 📈 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Feature Encoding
* Classification
* Regression
* Logistic Regression
* Linear Regression
* Decision Tree Classification
* Hyperparameter Tuning
* GridSearchCV
* Model Evaluation
* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* RMSE
* R² Score
* Business Analytics
* Customer Churn Analysis

---

# 📊 Datasets Used

### Titanic Dataset

* Titanic – Machine Learning from Disaster (Kaggle)

### California Housing Dataset

* California Housing Prices

### Customer Churn Dataset

* IBM Telco Customer Churn Dataset (Kaggle)

---

# 🚀 Future Improvements

As I continue the Neurofive ML Track, I plan to expand this repository with additional machine learning projects and techniques, including:

* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Naive Bayes
* XGBoost
* Clustering Algorithms
* Cross Validation
* Feature Engineering
* Model Comparison
* Streamlit Dashboard
* Machine Learning Model Deployment
* Explainable AI (XAI)

---

# 👨‍💻 Author

**Faizan Khan**

Computer Science Student | Machine Learning Enthusiast | Generative AI & Agentic AI Learner

* **GitHub:** https://github.com/faizankhanfreelancer
* **LinkedIn:** https://www.linkedin.com/in/faizankhan-cs

---

# ⭐ Acknowledgements

This repository documents my progress through the **Neurofive Solutions Machine Learning Track**, where I am developing practical skills in data analysis, machine learning, predictive modeling, and solving real-world business problems using Python and Scikit-learn.

Thank you for visiting this repository. If you find it useful, consider giving it a ⭐.
