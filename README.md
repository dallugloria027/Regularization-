# Regularization in Machine Learning

## Project Overview

This project explores regression models and regularization techniques using Python and Scikit-learn. Using the California Housing dataset, I implemented and compared Linear Regression, Ridge Regression, Lasso Regression, and Elastic Net Regression.

The project focuses on data preprocessing, feature scaling, regression model evaluation, coefficient comparison, and hyperparameter tuning.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Models Implemented
1. Linear Regression
2. Ridge Regression (L2 Regularization)
3. Lasso Regression (L1 Regularization)
4. Elastic Net Regression (L1 + L2 Regularization)

## Workflow
- Loaded and inspected the dataset
- Handled missing values in `total_bedrooms`
- Encoded the categorical `ocean_proximity` feature
- Split the data into training and testing sets
- Applied StandardScaler
- Trained and evaluated four regression models
- Compared model coefficients
- Tested different alpha values
- Visualized RMSE comparisons

## Results

| Model | RMSE | R² |
|---|---:|---:|
| Linear Regression | 70,060.52 | 0.6254 |
| Ridge Regression | 70,057.42 | 0.6255 |
| Lasso Regression | 70,060.52 | 0.6254 |
| Elastic Net | 69,906.46 | 0.6271 |

*Results are from the experiments documented in the notebook. RMSE is expressed in the target variable's units.*

## Key Learnings
- Understanding L1 and L2 regularization
- Comparing regression models using evaluation metrics
- Scaling numerical features
- Encoding categorical variables
- Exploring the effect of alpha on model performance
- Interpreting model coefficients

## Future Improvements
- Use a preprocessing pipeline to prevent data leakage
- Tune hyperparameters using cross-validation
- Compare results with a baseline and additional regression models
- Improve feature engineering and model performance

## Author
Gloria Daniel Dallu

This project is part of my hands-on learning journey in Data Science and Machine Learning.
