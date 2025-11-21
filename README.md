# KNN Machine Learning Models – Classification & Regression

This repository contains two machine learning projects based on **K-Nearest Neighbors (KNN)**:
1. **KNN Classification** – Predicting iPhone purchase decisions.
2. **KNN Regression** – Predicting Bangalore house prices.

Both projects follow the ML pipeline: **EDA → Preprocessing → Scaling → Model Training → Evaluation**.

---

##  Use Case 1: KNN Classification – iPhone Purchase Prediction

### Objective
Predict whether a customer will purchase an iPhone based on:
- Age
- Salary
- Gender

### Key Steps & Insights
- Label Encoding used for gender (Male/Female → 0/1).
- Strong correlation observed between Age, Salary, and Purchase Decision.
- Data standardized using StandardScaler for optimal KNN performance.
- Best accuracy achieved with K = 3.
- Confusion matrix shows good classification performance.

### Tools & Techniques
- Python, Pandas, NumPy
- Seaborn, Matplotlib
- KNeighborsClassifier
- StandardScaler
- Accuracy Score, Confusion Matrix

---

##  Use Case 2: KNN Regression – Bangalore House Price Prediction

### Objective
Predict house prices using features such as bathrooms, balconies, area size, BHK, and price per square foot.

### Key Steps & Insights
- Selected only highly correlated features for accurate predictions.
- Visualized skewed distributions using boxplots and histograms.
- Applied an 80:20 train-test split.
- Used KNeighborsRegressor (K=5) for training.
- Achieved high prediction performance using R² Score and MAPE.

### Tools & Techniques
- Python, Pandas, NumPy
- Seaborn, Matplotlib
- KNeighborsRegressor
- Feature Selection
- R² Score, MAPE

---

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

##  Project Structure
```
KNN_Classification_Iphone/
    ├── iphone_purchase_records.csv
    ├── model.ipynb
    ├── Graphs/

KNN_Regression_houseprice/
    ├── bangalore house price prediction OHE-data.csv
    ├── model.ipynb
    ├── Graphs/

README.md
```

---

##  Keywords
KNN Machine Learning, KNN Classification, KNN Regression, Bangalore House Price Prediction, iPhone Purchase Prediction, Python ML Projects, Supervised Learning, Data Science Portfolio, Sklearn Models

---

##  Conclusion
These projects demonstrate the power of KNN in:
- **Classification tasks** (customer purchase behavior)
- **Regression tasks** (predicting numeric values such as house prices)

The notebooks include complete workflows with EDA, preprocessing, model building, and evaluation.
