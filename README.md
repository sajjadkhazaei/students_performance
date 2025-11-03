# 🧠 Student Performance Analysis & Prediction

## 🎯 Project Overview
This project focuses on analyzing and predicting students' performance based on their demographic and academic background.  
The dataset includes attributes such as age, gender, country, study hours, previous education, and entry exam scores.

---

## 📊 Dataset Description

| Column | Description |
|--------|-------------|
| fNAME, lNAME | Student first and last name |
| Age | Student age |
| gender | Gender of the student |
| country | Country of residence |
| residence | Type of residence |
| entryEXAM | Entry exam score |
| prevEducation | Previous education level |
| studyHOURS | Total study hours per week |
| Python | Python course grade |
| DB | Database course grade |

---

## 🧹 Steps Performed

### 1️⃣ Data Cleaning
- Standardized categorical values (e.g., `Norway`, `norwey`, `norge` → `Norway`).
- Fixed inconsistent text in gender and education fields.
- Handled missing values in numeric columns.
- Removed or corrected invalid entries.

### 2️⃣ Exploratory Data Analysis (EDA)
- Distribution of age, gender, and countries.
- Correlation between `studyHOURS`, `entryEXAM`, `Python`, and `DB`.
- Comparison of performance across gender, country, and education level.

### 3️⃣ Feature Engineering
- Encoded categorical variables using `LabelEncoder`.
- Created new features such as:
  - binary column Pass_Python
  

### 4️⃣ Modeling
- Built regression models to predict python score :
  - `Linear Regression`
  - `RandomForestRegressor`
  - `Decision Tree Regressor `
  - `Gradient Boosting Regressor`
  - `Logistic Regression`

- Evaluated with metrics:
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)
  - R² Score

- Built Classifier models to predict Pass_Python :
  - `Random Forest Classifier`
  - `KNeighbors Classifier`
  - `Decision Tree Classifier `
  - `Gradient Boosting Classifier`
  - `SVC`
- Evaluated with metrics:
  - Accuracy
  - Precision
  - F1 Score
  - Recall
  - ROC-AUC


### 5️⃣ Visualization
- Boxplots to compare Python/DB scores across genders.
- Heatmap to visualize feature correlations.
- Bar charts for average scores by country and education level.

---

## 🧰 Tools & Libraries

Python
pandas
numpy
matplotlib
seaborn
scikit-learn

---

## 📈 Expected Outcomes
- Identify key factors affecting students’ performance.
- Discover relationship between study habits and academic success.
- Achieve accurate prediction of Python and Database grades.

---

## 👨‍💻 Author
Developed by **Sajjad Khazaei**  
For research and educational purposes.
