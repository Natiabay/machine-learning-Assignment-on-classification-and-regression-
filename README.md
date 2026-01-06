# Machine Learning Regression Assignment - Parkinson's Disease Prediction

This project is about predicting Parkinson's disease severity using machine learning. I worked with the Parkinsons Telemonitoring dataset from UCI to build a regression model that can predict UPDRS (Unified Parkinson's Disease Rating Scale) scores from voice measurements.

## What's This About?

Parkinson's is a neurodegenerative disease, and doctors use UPDRS scores to track how severe it is. The idea here is to predict these scores using voice measurements, which could be useful for remote monitoring. Instead of patients having to visit clinics frequently, we could potentially assess their condition through voice analysis.

## The Dataset

I used the Parkinsons Telemonitoring Dataset from UCI. It has voice measurements and some patient info that we can use to predict the total UPDRS score. The dataset includes things like jitter, shimmer, and other voice features that are known to be affected by Parkinson's.

## What I Did

I went through the whole machine learning pipeline:

1. **Explored the data** - Looked at distributions, checked for missing values, and tried to understand what features might be important

2. **Cleaned and preprocessed** - Handled any missing data, scaled features, and got everything ready for modeling

3. **Tried different models** - I tested several regression algorithms:
   - Linear Regression (baseline)
   - Ridge and Lasso Regression
   - Random Forest
   - Gradient Boosting
   - Support Vector Regression
   - Neural Networks (MLP)

4. **Compared and selected** - Evaluated all models using RMSE, MAE, R² score, and explained variance to see which one worked best

5. **Tuned the best model** - Used hyperparameter tuning to squeeze out better performance

6. **Tested on unseen data** - Finally evaluated the tuned model on the test set to see how well it generalizes

## Results

The final model met all the target criteria. It achieved an R² score above 0.70, which means it explains more than 70% of the variance in UPDRS scores. The RMSE and MAE were also minimized, showing the model makes reasonably accurate predictions.

The model generalizes well - there wasn't a huge gap between training and validation performance, which is always a good sign.

## Files in This Repo

- `ML_Assignment_Regression_Parkinsons.ipynb` - The main notebook with all the code
- `Parkinsons-Telemonitoring-ucirvine.csv` - The dataset
- `README.md` - This file

## How to Run It

If you want to run this yourself:

1. Make sure you have Python installed (I used Python 3.x)
2. Install the required packages:
   
