# 🚀 Neurofive ML Track

## 📖 Project Overview

This repository contains my solutions for the **Neurofive Solutions Machine Learning Track**. Throughout this learning journey, I explore the complete machine learning lifecycle—from data exploration and preprocessing to feature engineering, model development, evaluation, hyperparameter tuning, and solving real-world business problems using industry-standard tools and workflows.

Each task demonstrates practical implementation using Python, Pandas, NumPy, Scikit-learn, Matplotlib, and Seaborn while following machine learning best practices.

---

# 📂 Repository Structure

```text
neurofive-ml-track/
│
├── Week1_Titanic_EDA.ipynb
├── Week2_Titanic_Classification.ipynb
├── Week3_House_Price_Prediction.ipynb
├── Week4_Model_Evaluation_and_Tuning.ipynb
├── Week5_Handling_Imbalanced_Data.ipynb   ⭐ NEW
├── Customer_Churn_Prediction.ipynb
├── ML_Pipeline_Feature_Engineering.ipynb
├── Ensemble_Learning_RandomForest_vs_XGBoost.ipynb
│
├── datasets/
│   └── creditcard.csv
│
├── models/
│   └── Titanic_Pipeline.pkl
│
├── images/
│   ├── class_distribution.png
│   ├── confusion_matrix_before.png
│   ├── confusion_matrix_after.png
│   └── performance_comparison.png
│
├── README.md
├── requirements.txt
└── .gitignore
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

The Decision Tree model was used to identify the most influential features affecting customer churn using `feature_importances_`.

### Business Insights

* Customers with month-to-month contracts are more likely to churn.
* Customers with shorter tenure have a higher risk of leaving.
* Monthly charges and contract type significantly influence customer churn.
* Retention strategies targeting these customers can improve long-term loyalty.

### Outcome

Successfully built and compared two classification models while extracting meaningful business insights from customer behavior.

---

# 🔄 Task 6 – ML Pipeline with Feature Engineering

## Objective

Build a reusable machine learning pipeline using Scikit-learn's `Pipeline` and `ColumnTransformer` to automate preprocessing, feature engineering, and model training while preventing data leakage.

### Workflow

* Reused the Titanic dataset
* Created two engineered features:

  * **FamilySize**
  * **IsAlone**
* Applied **StandardScaler** to numerical features
* Applied **OneHotEncoder** to categorical features
* Combined preprocessing using **ColumnTransformer**
* Built an end-to-end **Pipeline**
* Trained and evaluated the pipeline
* Compared pipeline performance with the manual preprocessing approach
* Saved the trained pipeline using **Joblib**

### Feature Engineering

Two new features were introduced to improve model performance:

* **FamilySize = SibSp + Parch + 1**
* **IsAlone = 1 if FamilySize == 1 else 0**

### Technologies Used

* Pipeline
* ColumnTransformer
* StandardScaler
* OneHotEncoder
* Joblib

### Outcome

Developed a reusable, production-ready machine learning pipeline that automates preprocessing and modeling while reducing the risk of inconsistent preprocessing and train-test data leakage.

---

# 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

# 🤖 Machine Learning Algorithms

* Logistic Regression
* Linear Regression
* Decision Tree Classifier
* Pipeline-based Logistic Regression

---

# 📈 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Feature Engineering
* Feature Encoding
* Feature Scaling
* Pipeline Development
* ColumnTransformer
* StandardScaler
* OneHotEncoder
* Model Serialization
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
* Advanced Feature Engineering
* Model Comparison
* Streamlit Dashboard
* Machine Learning Model Deployment
* Explainable AI (XAI)
* MLOps and Model Monitoring

---
# 🌲 Task 7 – Ensemble Learning: Random Forest vs XGBoost

## 📖 Objective

The objective of this task was to explore ensemble learning techniques by implementing and comparing **Random Forest** and **XGBoost** with a baseline **Logistic Regression** model. This project demonstrates how ensemble methods improve predictive performance, generalization, and model robustness on a real-world classification problem.

---

## 🔄 Workflow

* Loaded and preprocessed the Titanic dataset.
* Performed data cleaning and handled missing values.
* Applied feature engineering by creating **FamilySize** and **IsAlone** features.
* Encoded categorical variables and scaled numerical features using **ColumnTransformer** and **Pipeline**.
* Trained a baseline **Logistic Regression** model.
* Trained a **Random Forest Classifier**.
* Installed and trained an **XGBoost Classifier**.
* Evaluated all models using multiple performance metrics.
* Compared model performance in a structured comparison table.
* Visualized and analyzed feature importance for both ensemble models.

---

## 🤖 Models Compared

* Logistic Regression (Baseline)
* Random Forest Classifier
* XGBoost Classifier

---

## 📊 Evaluation Metrics

The following evaluation metrics were used to compare model performance:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

## 📈 Feature Importance Analysis

Feature importance scores were extracted from both **Random Forest** and **XGBoost** models to identify the most influential features affecting passenger survival. The comparison illustrates how different ensemble algorithms prioritize features based on their learning strategies and decision-making processes.

---

## 🌟 Random Forest vs XGBoost

### Random Forest

* Uses the **Bagging (Bootstrap Aggregating)** technique.
* Builds multiple decision trees independently using random subsets of the training data.
* Combines predictions through majority voting.
* Primarily reduces variance and helps prevent overfitting.

### XGBoost

* Uses the **Gradient Boosting** technique.
* Builds trees sequentially, where each new tree learns from the errors of the previous trees.
* Optimizes model performance through gradient-based learning.
* Focuses on reducing both bias and variance while achieving high predictive accuracy.

---

## 📋 Model Comparison

The performance of all three models was compared using multiple evaluation metrics to identify the most effective classifier for the Titanic survival prediction problem.

| Model               | Accuracy                    | Precision  | Recall     | F1-Score   |
| ------------------- | --------------------------- | ---------- | ---------- | ---------- |
| Logistic Regression | *(Update with your result)* | *(Update)* | *(Update)* | *(Update)* |
| Random Forest       | *(Update with your result)* | *(Update)* | *(Update)* | *(Update)* |
| XGBoost             | *(Update with your result)* | *(Update)* | *(Update)* | *(Update)* |

---

## ✅ Outcome

Successfully implemented and evaluated two industry-standard ensemble learning algorithms alongside a baseline Logistic Regression model. The project demonstrates practical knowledge of **bagging**, **boosting**, **feature engineering**, **model evaluation**, and **feature importance analysis**, providing hands-on experience with machine learning techniques widely used in real-world production systems.

# Week 5 - Handling Imbalanced & Messy Real-World Data

## Objective

Learn how to identify and handle imbalanced datasets using the Credit Card Fraud Detection dataset.

## Dataset

- Credit Card Fraud Detection Dataset (Kaggle)

## Tasks Completed

- Loaded and explored the dataset
- Checked the class distribution
- Visualized the imbalance using a bar chart
- Trained a Logistic Regression model on the original data
- Evaluated Accuracy, Precision, Recall, and F1-score
- Applied SMOTE (Synthetic Minority Oversampling Technique)
- Retrained the model using balanced data
- Compared model performance before and after SMOTE
- Explained why Accuracy is a misleading metric for imbalanced datasets

## Results

The original dataset was highly imbalanced, with fraudulent transactions representing only a small fraction of the data.

After applying SMOTE:

- Improved Recall for the fraud class
- Improved F1-score
- Better detection of fraudulent transactions
- Demonstrated why Precision, Recall, and F1-score are more informative than Accuracy for imbalanced datasets

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

## Repository Structure

```
Week5_Handling_Imbalanced_Data.ipynb
datasets/creditcard.csv
images/
README.md
requirements.txt
```


# 👨‍💻 Author

**Faizan Khan**

Computer Science Student | Machine Learning Engineer | Generative AI & Agentic AI Enthusiast

* **GitHub:** https://github.com/faizankhanfreelancer
* **LinkedIn:** https://www.linkedin.com/in/faizankhan-cs

---

# ⭐ Acknowledgements

This repository documents my progress through the **Neurofive Solutions Machine Learning Track**, where I continue building practical skills in data analysis, feature engineering, machine learning, model evaluation, and production-ready ML pipelines using Python and Scikit-learn.

Thank you for visiting this repository. If you find it useful, consider giving it a ⭐.
