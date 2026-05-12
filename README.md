# 📚 Book Recommendation System

## 📌 Project Overview

This project focuses on building a Book Recommendation System using machine learning techniques and the Kaggle Book Recommendation Dataset. The main objective is to analyze user rating behavior and predict whether a book should be recommended based on historical ratings and book-related information.

The project covers the complete data analysis workflow, including:

- Data Inspection
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Modeling
- Model Evaluation

---

# 📂 Dataset

Dataset Source: Kaggle Book Recommendation Dataset

The dataset consists of three CSV files:

| File Name | Description |
|---|---|
| `Books.csv` | Contains metadata information about books |
| `Users.csv` | Contains demographic information about users |
| `Ratings.csv` | Contains user-book rating interactions |

---

# 🎯 Objectives

The objectives of this project are:

- Analyze user reading and rating behavior
- Identify factors affecting book ratings
- Build a classification model for recommendation prediction
- Compare machine learning algorithms
- Evaluate model performance using classification metrics

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

# 🧹 Data Preprocessing

The preprocessing stage includes:

- Encoding verification
- Missing value handling
- Invalid value correction
- Duplicate removal
- Data type standardization
- Dataset merging

Additional preprocessing tasks:

- Removing implicit ratings
- Cleaning unrealistic publication years
- Cleaning abnormal age values

---

# 📊 Exploratory Data Analysis (EDA)

EDA was conducted to analyze:

- Rating distribution
- User activity patterns
- Most popular books
- Top authors and publishers
- Age distribution
- Correlation between features
- Recommendation dataset sparsity

---

# 🤖 Machine Learning Models

The following classification algorithms were used:

- Logistic Regression
- Decision Tree
- Random Forest

Ratings were converted into binary classes:

- Rating ≥ 7 → Recommended
- Rating < 7 → Not Recommended

---

# 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
