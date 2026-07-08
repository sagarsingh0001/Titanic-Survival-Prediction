# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Project Overview

This project aims to predict whether a passenger survived the Titanic disaster using supervised machine learning techniques. The workflow covers the complete machine learning pipeline, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison of multiple classification algorithms.

The objective is not only to build an accurate predictive model but also to compare the performance of different machine learning algorithms using standard evaluation metrics.

---

## 🎯 Objectives

- Perform data cleaning and preprocessing.
- Explore the dataset to identify patterns and relationships.
- Encode categorical variables and prepare features for modeling.
- Train multiple classification models.
- Evaluate and compare model performance.
- Identify the best-performing model based on evaluation metrics.

---

## 📂 Dataset

The project uses the **Titanic Survival Dataset**, which contains passenger information such as:

- Passenger Class
- Sex
- Age
- Fare
- Embarked Port
- Family Information
- Survival Status (Target Variable)

**Target Variable**

- `Survived`
  - 0 → Did Not Survive
  - 1 → Survived

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The notebook includes:

- Dataset overview
- Missing value analysis
- Statistical summary
- Feature distributions
- Correlation heatmap
- Survival analysis by different features
- Data visualization

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- Label Encoding of categorical variables
- Feature scaling using StandardScaler
- Train-Test Split (80:20)

---

## 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Decision Tree
- Support Vector Machine (SVM)

---

## 📈 Model Evaluation

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

The final comparison helps identify the model with the best predictive performance.

---

## 📁 Project Structure

```
Titanic-Survival-Prediction/
│
├── data/
│   ├── train.csv
│   └── test.csv
│
├── notebooks/
│   └── titanic-survival-prediction.ipynb
│
├── images/
│
├── requirements.txt
│
├── README.md
│
└── .gitignore
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Titanic-Survival-Prediction.git
```

Move into the project directory

```bash
cd Titanic-Survival-Prediction
```

Install the required packages

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
titanic-survival-prediction.ipynb
```

---

## 📊 Results

The notebook compares the performance of all implemented machine learning models using multiple evaluation metrics.

Example comparison table:

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|----------|-----------|--------|----------|
| Logistic Regression | 0.803371 | 0.736111 | 0.768116 | 0.751773 |
| KNN | 0.775281 | 0.710145 | 0.710145 | 0.710145 |
| Gaussian Naive Bayes | 0.775281 | 0.683544 | 0.782609 | 0.729730 |
| Decision Tree | 0.775281 | 0.704225 | 0.724638 | 0.714286 |
| Support Vector Machine | 0.825843 | 0.796875 | 0.739130 | 0.766917 |


---

## 🔍 Key Learnings

- Importance of data preprocessing in machine learning.
- Effect of feature scaling on distance-based algorithms.
- Comparison of multiple classification algorithms.
- Performance evaluation using multiple metrics instead of relying only on accuracy.
- End-to-end implementation of a supervised machine learning workflow.

---

## 📌 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Feature engineering
- Random Forest Classifier
- XGBoost
- LightGBM
- Ensemble Learning

---

## 👨‍💻 Author

**Sagar Singh**

If you found this project useful, feel free to ⭐ the repository.
