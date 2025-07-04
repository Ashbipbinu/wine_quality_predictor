# Wine Quality Prediction – Machine Learning Project

This project aims to build and evaluate machine learning models to predict the quality of wine based on physicochemical features.

## Objective


The goal is to classify wine samples into quality categories using various supervised learning algorithms, and identify the most accurate and generalizable model through hyperparameter tuning and evaluation metrics.

## Dataset


The dataset includes the following physicochemical attributes for each wine sample:

Fixed Acidity

Volatile Acidity

Citric Acid

Residual Sugar

Chlorides

Free Sulfur Dioxide

Total Sulfur Dioxide

Density

pH

Sulphates

Alcohol

The target variable is quality, representing the sensory quality score of the wine.

## Workflow
### 1. Data Preprocessing:

    Handling missing values (if any)

    Scaling features using StandardScaler

    Splitting data into training and testing sets

2. Model Development:

    Random Forest Classifier: A bagging-based ensemble model trained with a range of hyperparameters using RandomizedSearchCV.

    AdaBoost Classifier: A boosting-based model using shallow decision trees as base estimators, also tuned using RandomizedSearchCV.

3. Hyperparameter Tuning:

    Used RandomizedSearchCV with 5-fold cross-validation to find optimal parameters for both models.

    Explored combinations of estimators, depth, learning rate, max features, and bootstrap strategies.

4. Evaluation Metrics:

    Accuracy Score

    Classification Report (Precision, Recall, F1-score)

    Comparison between tuned Random Forest and AdaBoost predictions on the test set.

## Conclusion:

Identified the best-performing model for predicting wine quality.

Discussed model reliability based on cross-validated performance metrics.
