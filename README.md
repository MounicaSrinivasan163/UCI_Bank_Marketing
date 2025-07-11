# UCI_Bank_Marketing
# 🏦 Bank Marketing Dataset Analysis

## 📌 Project Title
**Predicting Customer Term Deposit Subscription Using Bank Marketing Data**

---

## 📘 Dataset Overview

This project uses the [UCI Bank Marketing Dataset](https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing), which contains data on direct telemarketing campaigns of a Portuguese banking institution. The goal is to analyze customer behavior and build predictive models to determine whether a client will subscribe to a term deposit (`y`).

---

## 📂 Dataset Details

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **Kaggle Mirror**: [Henriqueyamahata’s version](https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing)
- **File Used**: `bank-additional-full.csv`
- **Rows**: 41,188  
- **Columns**: 21

---

## 🔢 Feature Description

| Column               | Type         | Description |
|----------------------|--------------|-------------|
| `age`                | Numeric      | Age of the client |
| `job`                | Categorical  | Job type (e.g., admin., technician, retired) |
| `marital`            | Categorical  | Marital status |
| `education`          | Categorical  | Education level |
| `default`            | Categorical  | Has credit in default? |
| `housing`            | Categorical  | Has housing loan? |
| `loan`               | Categorical  | Has personal loan? |
| `contact`            | Categorical  | Contact communication type |
| `month`              | Categorical  | Last contact month of year |
| `day_of_week`        | Categorical  | Last contact day of the week |
| `duration`           | Numeric      | Last contact duration (in seconds) |
| `campaign`           | Numeric      | Number of contacts performed during this campaign |
| `pdays`              | Numeric      | Days since last contact |
| `previous`           | Numeric      | Number of contacts performed before this campaign |
| `poutcome`           | Categorical  | Outcome of the previous campaign |
| `emp.var.rate`       | Numeric      | Employment variation rate |
| `cons.price.idx`     | Numeric      | Consumer price index |
| `cons.conf.idx`      | Numeric      | Consumer confidence index |
| `euribor3m`          | Numeric      | Euribor 3 month rate |
| `nr.employed`        | Numeric      | Number of employees |
| `y`                  | Binary       | Target: has the client subscribed to a term deposit? (`yes`/`no`) |

---

## 🎯 Objective

- Perform exploratory data analysis (EDA)
- Encode categorical variables
- Apply statistical tests to assess feature relationships
- Build predictive models (e.g., Logistic Regression, Random Forest, XGBoost)
- Evaluate performance using classification metrics

---

## ⚙️ Tools & Technologies

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- statsmodels, scipy

---

## 📊 Statistical Tests Used

| Test                     | Condition                      | Purpose |
|--------------------------|-------------------------------|---------|
| Two-sample t-test        | Continuous vs Continuous       | Check difference in means |
| ANOVA                    | Continuous vs Categorical      | Check group-wise mean difference |
| Chi-square test          | Categorical vs Categorical     | Check dependency between two categorical variables |

---

## 📈 Modeling Steps

1. Data cleaning and type conversion
2. Encoding categorical variables:
   - OneHotEncoder for nominal features
   - OrdinalEncoder for ordered features
3. Train-test split
4. Model training
5. Evaluation using accuracy, precision, recall, F1-score, ROC AUC

---

## 💡 Future Work

- Time-series analysis on campaign duration
- Hyperparameter tuning using cross-validation
- Model deployment using Streamlit or Flask

