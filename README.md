# 🚀 Neurofive ML Track

## 📖 Project Overview

This repository contains my solutions for the **Neurofive Solutions Machine Learning Track**. Throughout this track, I explore the complete machine learning workflow, starting from data exploration and preprocessing to building, evaluating, and improving machine learning models.

The projects in this repository demonstrate practical applications of Python, data analysis, machine learning algorithms, and model evaluation techniques using real-world datasets.

---

# 📂 Repository Structure

```text
neurofive-ml-track/
│
├── Titanic_EDA.ipynb
├── Titanic_Classification.ipynb
├── House_Price_Prediction.ipynb
├── Model_Evaluation_and_Tuning.ipynb
├── README.md
└── requirements.txt
```

---

# 📊 Task 1 – Titanic Exploratory Data Analysis (EDA)

## Objective

Perform Exploratory Data Analysis (EDA) on the Titanic dataset to understand the data before applying machine learning algorithms.

### Activities Performed

* Loaded the Titanic dataset using Pandas
* Explored the dataset using `head()`, `info()`, and `describe()`
* Identified missing values
* Distinguished numerical and categorical features
* Performed descriptive statistical analysis
* Created visualizations using Matplotlib and Seaborn
* Summarized key findings and insights

### Key Findings

* The dataset contains **891 passengers** and **12 features**.
* Cabin contains the highest number of missing values.
* Female passengers had a higher survival rate than male passengers.
* First-class passengers were more likely to survive.
* Age and fare influenced passenger survival.

---

# 🤖 Task 2 – Titanic Survival Prediction (Classification)

## Objective

Develop a machine learning classification model to predict passenger survival using the Titanic dataset.

### Workflow

* Data Cleaning
* Missing Value Handling
* Feature Selection
* One-Hot Encoding using `pd.get_dummies()`
* Train-Test Split
* Logistic Regression Model
* Prediction on Test Data
* Model Evaluation

### Evaluation Metrics

* Accuracy Score
* Confusion Matrix
* Classification Report

### Outcome

Successfully trained and evaluated a Logistic Regression model capable of predicting passenger survival with strong baseline performance.

---

# 🏠 Task 3 – House Price Prediction (Regression)

## Objective

Build a Linear Regression model to predict California house prices using selected housing features.

### Workflow

* Dataset Loading
* Data Cleaning
* Feature Selection
* Data Preprocessing
* Train-Test Split
* Linear Regression Model
* Prediction
* Model Evaluation

### Selected Features

* Median Income
* Housing Median Age
* Total Rooms
* Population
* Latitude

### Evaluation Metrics

* Root Mean Squared Error (RMSE)
* R² Score

### Visualization

* Actual vs Predicted House Prices Scatter Plot
* Feature Coefficient Analysis

### Outcome

Successfully developed and evaluated a Linear Regression model for predicting house prices and interpreted its performance using RMSE and R² score.

---

# ⚙️ Task 4 – Model Evaluation & Hyperparameter Tuning

## Objective

Improve a classification model by evaluating it beyond accuracy and optimizing its performance using hyperparameter tuning.

### Workflow

* Revisited the Titanic classification dataset
* Trained a baseline Decision Tree Classifier
* Evaluated model performance using multiple metrics
* Applied GridSearchCV for hyperparameter tuning
* Tuned multiple model parameters
* Compared baseline and tuned models
* Visualized the confusion matrix

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

### Why Accuracy Alone Is Not Enough

Accuracy measures the overall percentage of correct predictions, but it may not reflect how well a model performs on minority classes. Precision, Recall, and F1-score provide a more complete evaluation by measuring prediction quality, the ability to identify positive cases, and the balance between both metrics.

### Outcome

Improved the Decision Tree model using GridSearchCV and compared the tuned model with the baseline model to understand the impact of hyperparameter optimization.

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

# 💡 Machine Learning Algorithms

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
* Machine Learning
* Classification
* Regression
* Logistic Regression
* Linear Regression
* Decision Tree Classification
* Hyperparameter Tuning
* GridSearchCV
* Model Evaluation
* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* RMSE
* R² Score

---

# 📊 Datasets

### Titanic Dataset

* Titanic – Machine Learning from Disaster (Kaggle)

### California Housing Dataset

* California Housing Prices

---

# 🚀 Future Improvements

This repository will continue to grow as I complete additional machine learning projects in the Neurofive ML Track, including:

* Random Forest
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Naive Bayes
* XGBoost
* Clustering Algorithms
* Feature Engineering
* Cross Validation
* Model Comparison
* Streamlit Dashboard
* Machine Learning Model Deployment

---

# 👨‍💻 Author

**Faizan Khan**

Computer Science Student | Machine Learning Enthusiast | Generative AI & Agentic AI Learner

**GitHub:** https://github.com/faizankhanfreelancer

**LinkedIn:** https://www.linkedin.com/in/faizankhan-cs

---

# ⭐ Acknowledgements

This repository is part of my learning journey in the **Neurofive Solutions Machine Learning Track**, where I am building practical skills in data analysis, machine learning, model evaluation, and predictive analytics using Python and Scikit-learn.

Thank you for visiting this repository. If you find it useful, consider giving it a ⭐.
