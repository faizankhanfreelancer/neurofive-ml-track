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
├── Week5_Handling_Imbalanced_Data.ipynb
├── Week6_ML_Pipeline_Feature_Engineering.ipynb
├── Week7_KNN_Classification.ipynb
├── Week8_SVM_Classification.ipynb
│
├── Customer_Churn_Prediction.ipynb
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

# 📊 week 1 – Titanic Exploratory Data Analysis (EDA)

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

# 🤖 week 2 – Titanic Survival Prediction (Classification)

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

# 🏠 week 3 – House Price Prediction (Regression)

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

# ⚙️ week 4 – Model Evaluation & Hyperparameter Tuning

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

# 📞 week 5 – Customer Churn Prediction (Business Problem)

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

# 🔄 week 6 – ML Pipeline with Feature Engineering

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

Two new features were introduced:

* **FamilySize = SibSp + Parch + 1**
* **IsAlone = 1 if FamilySize == 1 else 0**

### Technologies Used

* Pipeline
* ColumnTransformer
* StandardScaler
* OneHotEncoder
* Joblib

### Outcome

Developed a reusable machine learning pipeline that automates preprocessing and modeling while reducing the risk of inconsistent preprocessing and train-test data leakage.

---

# 📍 week 7 – K-Nearest Neighbors (KNN) Classification

## Objective

Implement a K-Nearest Neighbors (KNN) classification model to understand distance-based classification and analyze how different values of K affect model performance.

### Workflow

* Prepared and preprocessed the dataset
* Selected relevant features for classification
* Applied feature scaling
* Implemented the KNN Classifier using Scikit-learn
* Tested different values of K
* Compared model performance for different K values
* Generated predictions
* Evaluated the model using classification metrics
* Analyzed the confusion matrix

### Hyperparameter

* `n_neighbors (K)`

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

### Key Learning

KNN is a distance-based algorithm, so feature scaling is important to ensure that features with larger numerical ranges do not dominate the distance calculations.

### Outcome

Successfully implemented KNN classification and learned how the choice of K and feature scaling can influence classification performance.

---

# 🧠 week 8 – Support Vector Machine (SVM) Classification

## Objective

Implement a Support Vector Machine (SVM) classification model to understand how SVM separates different classes and how kernel selection affects classification performance.

### Workflow

* Prepared and preprocessed the dataset
* Selected relevant features for classification
* Applied feature scaling
* Implemented an SVM Classifier using Scikit-learn
* Experimented with different kernel configurations
* Generated predictions
* Evaluated model performance
* Compared classification results using standard evaluation metrics

### Kernels Explored

* Linear Kernel
* RBF Kernel
* Polynomial Kernel

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

### Key Learning

SVM attempts to find an optimal decision boundary that separates different classes while maximizing the margin between them. Kernel functions allow SVM to handle non-linear classification problems.

### Outcome

Successfully implemented an SVM classification model and gained practical experience with feature scaling, kernel selection, decision boundaries, and model evaluation.

---

# 🌲 Task 9 – Ensemble Learning: Random Forest vs XGBoost

## Objective

The objective of this task was to explore ensemble learning techniques by implementing and comparing **Random Forest** and **XGBoost** with a baseline **Logistic Regression** model.

### Models Compared

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

### Key Concepts

* Bagging
* Boosting
* Feature Importance
* Model Comparison
* Ensemble Learning

### Outcome

Successfully implemented and evaluated ensemble learning algorithms and compared their performance with a baseline classification model.

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
* Imbalanced-learn
* XGBoost

---

# 🤖 Machine Learning Algorithms

* Logistic Regression
* Linear Regression
* Decision Tree Classifier
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Random Forest Classifier
* XGBoost Classifier
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
* KNN Classification
* SVM Classification
* Ensemble Learning
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
* Feature Importance

---

# 📊 Datasets Used

### Titanic Dataset

* Titanic – Machine Learning from Disaster (Kaggle)

### California Housing Dataset

* California Housing Prices

### Customer Churn Dataset

* IBM Telco Customer Churn Dataset (Kaggle)

### Credit Card Fraud Dataset

* Credit Card Fraud Detection Dataset (Kaggle)

---

# 🚀 Future Improvements

As I continue the Neurofive ML Track, I plan to expand this repository with additional machine learning projects and techniques, including:

* Naive Bayes
* Clustering Algorithms
* Advanced Feature Engineering
* Cross Validation
* Model Comparison
* XGBoost Hyperparameter Tuning
* Streamlit Dashboard
* Machine Learning Model Deployment
* Explainable AI (XAI)
* MLOps and Model Monitoring

---

# 👨‍💻 Author

**Faizan Khan**

Computer Science Student | Machine Learning Engineer | Generative AI & Agentic AI Enthusiast

* **GitHub:** https://github.com/faizankhanfreelancer
* **LinkedIn:** https://www.linkedin.com/in/faizankhan-cs

---

# ⭐ Acknowledgements

This repository documents my progress through the **Neurofive Solutions Machine Learning Track**, where I continue building practical skills in data analysis, feature engineering, machine learning, model evaluation, and production-ready ML pipelines using Python and Scikit-learn.

Thank you for visiting this repository. If you find it useful, consider giving it a ⭐.
