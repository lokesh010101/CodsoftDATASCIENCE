# 🚢 Task 1 — Titanic Survival Prediction

## 📌 Objective
Build a classification model to predict whether a passenger survived the Titanic disaster.

## 📊 Dataset
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/brendan45774/test-file)
- **Features:** Age, Gender, Ticket Class, Fare, Cabin, Embarked, SibSp, Parch
- **Target:** Survived (0 = No, 1 = Yes)

## 🛠️ Steps Performed
1. Loaded and explored the dataset (EDA)
2. Handled missing values (Age, Embarked, Fare)
3. Encoded categorical variables (Sex, Embarked)
4. Split data into Train/Test sets (80/20)
5. Trained two models:
   - Logistic Regression
   - Random Forest Classifier
6. Evaluated using Accuracy, Precision, Recall, F1-Score
7. Plotted Confusion Matrices and Feature Importance

## 📈 Results

| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~80% |
| Random Forest | ~82% |

## 💡 Key Insights
- **Gender** is the most important survival predictor (females survived more)
- **Ticket Class** strongly influences survival (1st class = higher survival)
- Random Forest outperforms Logistic Regression

## 🔧 Libraries Used
```python
numpy, pandas, matplotlib, seaborn, scikit-learn
```
