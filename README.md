# melb_house_prediction
housing price regression model and analysis (Melbourne)
# 🏠 Melbourne Housing Price Prediction

Predicting residential property prices using an end-to-end machine learning pipeline.

## Results
| Metric | Score |
|--------|-------|
| R² (Test) | 0.88 |
| MAE | ~$145,000 |
| MAPE | ~14% |

## Techniques Used
- Feature engineering (11 new features)
- Median imputation + RobustScaler
- Model comparison: Linear, Ridge, Lasso, Decision Tree, Random Forest, Gradient Boosting
- Hyperparameter tuning with GridSearchCV (5-fold CV)
- Residual analysis, learning curves, feature importance

## Stack
Python · scikit-learn · pandas · NumPy · matplotlib · seaborn

## Dataset
Melbourne Housing Market (34,857 transactions, 2016–2018)  
Source: [Kaggle](https://www.kaggle.com/datasets/anthonypino/melbourne-housing-market)
