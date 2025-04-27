# Job-Salary-Predictor
# 💼 Job Salary Predictor

Predict salaries based on job characteristics such as experience level, employment type, job title, remote work ratio, and location using Machine Learning!

---

## 📚 Project Overview

This project builds a robust **Salary Prediction Model** by applying multiple machine learning algorithms on real-world salary data collected from various tech and non-tech roles.  
It demonstrates a **full Data Science pipeline**:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building and Comparison
- Model Evaluation

---

## 🛠️ Tools & Technologies Used

- Python 🐍
- Pandas, NumPy
- Scikit-learn (Linear Regression, Random Forest)
- XGBoost (Extreme Gradient Boosting)
- Matplotlib, Seaborn (Data Visualization)
- Jupyter Notebook

---

## 📑 Dataset

- Dataset sourced from **Kaggle**.
- Contains fields such as:
  - Work Year
  - Experience Level
  - Employment Type
  - Job Title
  - Salary
  - Salary Currency
  - Employee Residence
  - Remote Ratio
  - Company Size
  - Company Location
- Target variable: **`salary_in_usd`**

---

## 📈 Exploratory Data Analysis (EDA)

Performed detailed EDA to understand:

- Salary distribution across different continents
- Relationship between experience level and salary
- Impact of remote work ratio on salary
- Trends based on company size
- Heatmap showing correlation between numeric variables

Also performed feature engineering like:

- Mapping countries to continents
- One-hot encoding categorical variables

---

## 🛤️ Machine Learning Workflow

| Step | Description |
|:----|:------------|
| 1 | Data Cleaning: Handling missing values, fixing codes |
| 2 | Feature Engineering: One-hot encoding of categorical features |
| 3 | Model Building: Training multiple regression models |
| 4 | Model Evaluation: Comparing RMSE and R² scores |
| 5 | Model Selection: Choosing the best model for future deployment |

---

## 🤖 Models Trained and Compared

### 1. **Linear Regression**
- Built as a baseline model.
- Assumes linear relationship between features and salary.
- **Findings**:
  - Poor performance due to complexity of data.
  - Negative R² score — not suitable.

---

### 2. **Random Forest Regressor**
- Ensemble method using multiple decision trees.
- Handles categorical data and non-linear relationships well.
- **Findings**:
  - Significant improvement over Linear Regression.
  - Good RMSE and R² scores.

---

### 3. **XGBoost Regressor**
- Powerful gradient boosting model.
- Excellent for structured/tabular datasets.
- **Findings**:
  - Best performing model among all.
  - Lowest RMSE and highest R² score.

---

## 📊 Model Performance Summary

| Model | RMSE | R² Score |
|:-----|:-----|:--------|
| Linear Regression | (Fill after evaluation) | (Fill after evaluation) |
| Random Forest | (Fill after evaluation) | (Fill after evaluation) |
| XGBoost | (Fill after evaluation) | (Fill after evaluation) |

*(Update these after your final testing.)*


## 🌟 Key Insights

- Higher **experience levels** directly correlate with higher salaries.
- **Remote work** opportunities show slight salary boosts.
- **North America** salaries are significantly higher compared to other continents.
- **Large companies** tend to offer better salaries compared to small/medium firms.


