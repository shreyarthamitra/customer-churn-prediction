# Customer Churn Prediction

## About the Project

This project looks at customer churn using a telecom dataset. The goal is to understand which customers are likely to leave and build a model that can predict churn in advance.

---

## What I did

* Cleaned and prepared the dataset
* Explored the data to find patterns related to churn
* Built a classification model (Logistic Regression)
* Evaluated performance with focus on churn prediction

---

## Key Points

* Focused more on **recall for churn (1)** since missing a churned customer is costly
* Tried to balance model performance instead of just accuracy

---

## Results

Using Logistic Regression:

* Accuracy: **71%**
* Churn (1):

  * Precision: **0.48**
  * Recall: **0.83**
  * F1-score: **0.61**
* Non-churn (0):

  * Precision: **0.92**
  * Recall: **0.67**

The model does a good job at **identifying customers who are likely to churn (high recall)**, but at the cost of lower precision — meaning some non-churn customers are incorrectly predicted as churn.

---

## Tools Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib / Seaborn
* Jupyter Notebook

---



## Author

Shreyartha

