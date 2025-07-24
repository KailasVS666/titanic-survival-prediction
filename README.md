# 🚢 Titanic Survival Prediction

This is a beginner-friendly machine learning project that predicts whether a passenger survived the Titanic disaster using data from the famous Kaggle competition: [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic).

---

## 📌 Project Overview

The goal of this project is to build a predictive model using historical passenger data such as age, gender, class, and fare to determine if a passenger would have survived. This is one of the most popular introductory datasets for exploring basic data science and machine learning techniques.

---

## 🛠️ Tools & Libraries Used

- **Python** 🐍
- **Pandas** – for data analysis and manipulation
- **NumPy** – for numerical operations
- **Matplotlib & Seaborn** – for data visualization
- **Scikit-learn** – for machine learning modeling

---

## 📊 Dataset

- `train.csv` – training dataset with survival labels
- `test.csv` – test dataset without labels
- `gender_submission.csv` – sample submission format

You can download the dataset from the [Kaggle competition page](https://www.kaggle.com/competitions/titanic/data) (login required).

---

## 📈 Workflow

1. **Load Data**
2. **Data Exploration & Cleaning**
   - Handle missing values (e.g., Age, Fare, Embarked)
   - Convert categorical variables (e.g., Sex, Embarked) to numeric
3. **Feature Selection**
   - Select useful features: `Pclass`, `Sex`, `Age`, `Fare`, `Embarked`
4. **Model Training**
   - Train a Logistic Regression model using `scikit-learn`
   - Split training data into training and validation sets
5. **Model Evaluation**
   - Evaluate model accuracy on validation data
6. **Prediction & Submission**
   - Make predictions on the test dataset
   - Generate a `submission.csv` file for Kaggle

---



