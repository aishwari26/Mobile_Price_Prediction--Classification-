# 📱 Mobile Price Classification

## 📌 Overview

This project builds a Machine Learning classification model to predict the **price range of a mobile phone** based on its hardware specifications. The project follows a complete machine learning workflow, from data preprocessing and exploratory data analysis (EDA) to model training, evaluation, hyperparameter tuning, and model selection.

The primary objective was to compare multiple classification algorithms and identify the best-performing model for the dataset.

---

## 🎯 Problem Statement

Given various specifications of a mobile phone such as battery capacity, RAM, processor speed, camera resolution, screen dimensions, and connectivity features, predict the mobile phone's **price range**.

---

## 📂 Dataset

The dataset contains multiple hardware specifications of mobile phones along with their corresponding price category.

**Target Variable:**

* `price_range`

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook

### Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## ⚙️ Project Workflow

* Data Loading
* Exploratory Data Analysis (EDA)
* Data Preprocessing
* Feature and Target Selection
* Train-Test Split
* Model Training
* Model Evaluation
* Model Comparison
* Hyperparameter Tuning
* Final Model Selection

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

* Linear Support Vector Classifier (LinearSVC)
* K-Nearest Neighbors (KNN)
* Random Forest Classifier

---

## 🔍 Hyperparameter Tuning

To improve model performance, multiple tuning approaches were explored:

* Manual Hyperparameter Tuning
* RandomizedSearchCV
* GridSearchCV

The tuned models were further validated using **5-Fold Cross Validation** to ensure consistent and reliable performance.

---

## 📊 Model Evaluation

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cross Validation Score

The best-performing model was selected based on overall classification performance after tuning and validation.

---

## 📁 Project Structure

```text
Mobile-Price-Classification/
│
├── mobile_price_classification.ipynb
├── dataset.csv
└── README.md
```

---



## ✨ Key Highlights

* Complete Machine Learning Workflow
* Exploratory Data Analysis (EDA)
* Data Preprocessing
* Multiple Classification Algorithms
* Manual Hyperparameter Tuning
* RandomizedSearchCV
* GridSearchCV
* 5-Fold Cross Validation
* Confusion Matrix Analysis
* Classification Report
* Model Comparison and Final Model Selection

---

## 📚 Concepts Covered

* Supervised Machine Learning
* Classification Algorithms
* Feature Analysis
* Model Evaluation
* Cross Validation
* Hyperparameter Tuning
* Scikit-learn

## 🏆 Final Model Selection

Three classification models—**LinearSVC**, **K-Nearest Neighbors (KNN)**, and **Random Forest Classifier**—were trained and evaluated. After performing manual hyperparameter tuning, RandomizedSearchCV, GridSearchCV, and 5-Fold Cross Validation, **K-Nearest Neighbors (KNN)** achieved the best overall performance and was selected as the final model.

---

## 🚀 Future Improvements

* Deploy the trained model using Streamlit
* Save the final model using Joblib
* Build a prediction interface for end users
* Experiment with boosting algorithms such as XGBoost and LightGBM
* Perform feature engineering for further performance improvements

---

## 👩‍💻 Author

**Aishwari Bambale**

B.Tech in Artificial Intelligence & Data Science

Aspiring Machine Learning Engineer
