# Student Performance Prediction

This project analyzes how student background, test preparation, and demographics influence academic performance.
Using exploratory data analysis and a Decision Tree classifier, I predict student performance categories.

---

## Dataset
Source: Kaggle – Students’ Academic Performance dataset (1,000 records).  
Features include demographics, parental education, lunch type, test preparation, and exam scores.

---

## Goal
- Identify key factors associated with student performance.
- Build a classification model to predict performance category.

---

## What I Did
- Cleaned and validated the dataset (no missing values, removed duplicates, standardized categories).
- Performed EDA to identify trends and correlations.
- Created a categorical performance target from exam scores.
- Trained a Decision Tree classifier using a 70/30 train-test split.
- Evaluated performance using accuracy, precision, and confusion matrix.

---

## Model & Results
- **Model:** Decision Tree Classifier  
- **Primary features:** reading score, writing score, gender, race/ethnicity  
- **Key insight:** Reading and writing scores were the strongest predictors of overall performance.

---

## Decision Tree Visualization

![Decision Tree](images/decision_tree.png)

This visualization shows how the model splits on reading and writing scores first, confirming their strong influence on student performance outcomes.

---

## How to Run
```bash
git clone <your-repo-link>
cd <repo-folder>
