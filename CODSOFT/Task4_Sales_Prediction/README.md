# 📈 Task 4 — Sales Prediction Using Python

## 📌 Objective
Build a regression model to predict product sales based on advertising expenditure across TV, Radio, and Newspaper channels.

## 📊 Dataset
- **Source:** [Kaggle Advertising Dataset](https://www.kaggle.com/datasets/bumba5341/advertisingcsv)
- **Features:** TV (budget), Radio (budget), Newspaper (budget)
- **Target:** Sales (units sold)
- **Size:** 200 samples

## 🛠️ Steps Performed
1. Loaded and explored the dataset (EDA)
2. Visualized feature distributions and scatter plots
3. Analyzed correlations using heatmap
4. Scaled features using StandardScaler
5. Split data into Train/Test sets (80/20)
6. Trained three models:
   - Linear Regression
   - Random Forest Regressor
   - Gradient Boosting Regressor
7. Evaluated using MAE, RMSE, R² Score
8. Plotted Actual vs Predicted and Residual Analysis

## 📈 Results

| Model | R² Score | RMSE | MAE |
|-------|----------|------|-----|
| Linear Regression | ~0.88 | ~1.7 | ~1.4 |
| Random Forest | ~0.95 | ~1.1 | ~0.8 |
| Gradient Boosting | ~0.96 | ~1.0 | ~0.8 |

## 💡 Key Insights
- **TV advertising** has the strongest impact on sales
- **Newspaper** advertising has minimal effect on sales
- Gradient Boosting achieves the best prediction performance
- Businesses should prioritize TV and Radio budgets for maximum ROI

## 🔧 Libraries Used
```python
numpy, pandas, matplotlib, seaborn, scikit-learn
```
