# Applied Machine Learning using scikit-learn and XGBoost

# 1. Prepare Environment & Data
- Load Libraries
- Load Dataset

# 2. Summarize Data: Statistics & Visualization
- Data Exploration: Descriptive Statistics
    - describe(): statistics - mean, stdev, min/max
    - class distribution
    - correlations
    - skew
    - data types
- Data Exploration: Visualization
    - histogram
    - density plot
    - box whisker plot
    - correlation matrix plot
    - scatter plot matrix

# 3. Data Pre-Processing
- Data Cleaning
- Data Pre-Processing
    - Rescale
    - Standardize
    - Normalize
    - Binarize
- Feature Selection
     - Univariate selection
     - Recursive Feature Elimination
     - Principal Component Analysis
     - Feature Importance
- Data Transform

# 4. Model Evaluation: Data -> Model -> Performance Metrics
- Split-out validation dataset: Resampling
    - Train-Test Data split
    - k-fold cross validation
    - LOOCV
    - Repeated Random train-test splits
- Algorithm Performance Metrics
    - Classification Metrics
         - Classification Accuracy
         - Logarithmic Loss
         - Area under ROC curve
         - Confusion Matrix
         - Classification Report: precision, recall, F1 score, support
    - Regression Metrics
         - Mean Absolute Error
         - Mean Squared Error
         - R^2
- Algorithm Performance
    - Classification
        - Linear Algorithms
            - Logistic Regression
            - Linear Discriminant Analysis
        - Non-Linear Algorithms
            - kNN
            - Naive Bayes
            - CART
            - SVM (SVC)
    - Regression
        - Linear Algorithms
            - Linear Regression
            - Ridge Regression
            - LASSO Linear Regression
            - ElasticNet Regression
        - Non-Linear Algorithms
            - kNN
            - CART
            - SVM (SVR)
- Algorithm Comparison
     - Test harness to compare multiple algorithms efficiently on a single dataset
     - Comparison visualization
- Preventing Data Leakage using Pipelines
    - Data Preparation and Modeling Pipeling
    - Feature Extractions and Modeling Pipeling

# 5. Improve Accuracy
- Algorithm Tuning: Hyperparameter Optimization
    - Grid Search Parameter Tuning
    - Random Search Parameter Tuning
- Ensembles
    - Bagging
        - Bagged Decision Trees: Best for high variance algorithms
        - Random Forests
        - Extra Trees
    - Boosting
        - AdaBoost
        - XGBoost: Stochastic Gradient Boosting (Gradient Boosting Machines - GBM)
    - Voting

# 6. Finalize Model
- Predictions on validation dataset
- Create standalone model on entire dataset
- Model persistence
    - pickle
    - joblib
