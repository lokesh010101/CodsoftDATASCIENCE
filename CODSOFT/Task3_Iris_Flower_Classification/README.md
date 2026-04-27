# 🌸 Task 3 — Iris Flower Classification

## 📌 Objective
Train a machine learning model to classify Iris flowers into 3 species based on sepal and petal measurements.

## 📊 Dataset
- **Source:** [Kaggle Iris Dataset](https://www.kaggle.com/datasets/uciml/iris) / Scikit-learn built-in
- **Features:** Sepal Length, Sepal Width, Petal Length, Petal Width
- **Target:** Species (Setosa, Versicolor, Virginica)
- **Size:** 150 samples, 3 balanced classes

## 🛠️ Steps Performed
1. Loaded dataset and performed EDA
2. Visualized with Pairplot, Boxplots, Heatmap
3. Scaled features using StandardScaler
4. Split data into Train/Test sets (80/20)
5. Trained three models:
   - K-Nearest Neighbors (KNN)
   - Random Forest Classifier
   - Support Vector Machine (SVM)
6. Evaluated with Accuracy, Classification Report, Confusion Matrix
7. Performed 5-Fold Cross Validation

## 📈 Results

| Model | Test Accuracy | CV Accuracy |
|-------|--------------|-------------|
| KNN | ~97% | ~96% |
| Random Forest | ~97% | ~96% |
| SVM (RBF) | ~97% | ~97% |

## 💡 Key Insights
- **Petal Length & Width** are the most discriminating features
- **Setosa** is perfectly separable from the other two species
- All three models achieve very high accuracy on this dataset

## 🔧 Libraries Used
```python
numpy, pandas, matplotlib, seaborn, scikit-learn
```
