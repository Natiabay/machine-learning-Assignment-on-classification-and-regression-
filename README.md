# Machine Learning Assignment: Classification and Regression

This repository contains two comprehensive machine learning projects covering the complete ML pipeline from data exploration to model deployment.

## 📋 Projects Overview

### 1. Classification: Healthcare Stroke Prediction
**Notebook**: `ML_Assignment_Classification.ipynb`  
**Dataset**: Healthcare Stroke Prediction Dataset (5,110 samples, 12 features)

**Objective**: Predict stroke occurrence based on patient health indicators

**Models Evaluated**:
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- Support Vector Machine (SVM)
- Neural Network (MLP)

**Best Model**: Neural Network (MLP)
- **Accuracy**: 92.47%
- **ROC-AUC**: 0.7736
- **Precision**: 0.1538
- **Recall**: 0.1200
- **F1-Score**: 0.1348

**Additional Task**: Regression to predict average glucose level
- **Best Model**: Neural Network
- **R² Score**: 0.9964
- **RMSE**: 2.6226
- **MAE**: 1.5287

---

### 2. Regression: Parkinson's Disease UPDRS Prediction
**Notebook**: `ML_Assignment_Regression_Parkinsons.ipynb`  
**Dataset**: Parkinsons Telemonitoring Dataset (UCI)

**Objective**: Predict Total UPDRS (Unified Parkinson's Disease Rating Scale) score based on voice measurements and patient characteristics

**Models Evaluated**:
- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)
- Neural Network (MLP)

**Best Model**: Gradient Boosting / Neural Network
- **R² Score**: > 0.70 (Target achieved)
- **RMSE**: Optimized
- **MAE**: Minimized
- **Explained Variance**: > 0.70

---

## 🛠️ Technologies Used

- **Python 3.x**
- **Libraries**:
  - `pandas`, `numpy` - Data manipulation
  - `matplotlib`, `seaborn` - Data visualization
  - `scikit-learn` - Machine learning models and preprocessing
  - `joblib`, `pickle` - Model serialization

---

## 📊 Key Features

### Complete ML Pipeline Implementation:
1. **Problem Definition** - Business objectives and success criteria
2. **Data Collection** - Loading and initial exploration
3. **Data Exploration (EDA)** - Statistical analysis and visualizations
4. **Data Cleaning** - Handling missing values, duplicates, outliers
5. **Data Preprocessing** - Feature encoding, scaling, imputation
6. **Model Development** - Training multiple algorithms
7. **Model Evaluation** - Cross-validation and performance metrics
8. **Hyperparameter Tuning** - GridSearchCV and RandomizedSearchCV
9. **Model Selection** - Best model identification
10. **Model Deployment** - Model serialization and deployment guidelines
11. **Monitoring & Maintenance** - Production monitoring strategies

---

## 📁 Repository Structure
