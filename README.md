# Assignment-_XGBM-LGBM_-Titanic_data-

The objective of this assignment is to compare the performance of Light GBM and XG Boost algorithms using the Titanic dataset. 
XGBoost (Extreme Gradient Boosting) and LightGBM (Light Gradient Boosting Machine) are two popular gradient boosting frameworks that are widely used in machine learning for their efficiency and performance. Here’s an overview of both, including their types, use cases, advantages, and disadvantages:

### XGBoost:

#### Overview:
XGBoost is an optimized gradient boosting library designed to be highly efficient, flexible, and portable. It implements machine learning algorithms under the Gradient Boosting framework and is known for its speed and performance.

#### Types:
1. **Tree Booster**: The default and most commonly used booster which builds decision trees sequentially.
2. **Linear Booster**: A linear model booster that combines the results of linear classifiers or regressors.
3. **DART Booster**: Adds dropout to the boosting process to prevent overfitting by randomly dropping trees during training.

#### When to Use:
- When you need a high-performance, scalable machine learning model.
- For problems involving tabular data with both classification and regression tasks.
- In scenarios requiring fine control over the training process and model performance.

#### Advantages:
- **High Performance**: Known for its execution speed and model performance.
- **Flexibility**: Provides a wide range of tuning parameters and supports custom objective functions.
- **Robustness**: Handles sparse data and missing values effectively.
- **Feature Importance**: Provides insights into feature importance which is useful for model interpretability.

#### Disadvantages:
- **Complexity**: Can be complex to tune with many hyperparameters.
- **Resource Intensive**: Requires significant computational resources and memory, especially for large datasets.
- **Training Time**: Though optimized, training can still be time-consuming for very large datasets.

### LightGBM:

#### Overview:
LightGBM is a gradient boosting framework that uses tree-based learning algorithms. It is designed to be distributed and efficient with the capability of handling large-scale data.

#### Types:
1. **GBDT (Gradient Boosting Decision Tree)**: The standard tree-based boosting algorithm.
2. **GOSS (Gradient-based One-Side Sampling)**: Optimizes computation by focusing on important data points.
3. **EFB (Exclusive Feature Bundling)**: Reduces the number of features by bundling mutually exclusive features.

#### When to Use:
- When you need a fast and efficient machine learning model for large datasets.
- For high-dimensional data and scenarios requiring fast training speed and low memory usage.
- In cases where distributed training and parallel processing are necessary.

#### Advantages:
- **Speed**: Extremely fast training and prediction times.
- **Efficiency**: Low memory usage and high efficiency, suitable for large datasets.
- **Scalability**: Scales well to large datasets and supports distributed training.
- **Accuracy**: Often provides competitive accuracy with less overfitting due to its sophisticated algorithms.

#### Disadvantages:
- **Complexity**: Can be difficult to understand and implement correctly due to its optimization techniques.
- **Compatibility**: Sometimes less flexible in terms of integrating with custom loss functions or objectives compared to XGBoost.
- **Hyperparameter Tuning**: Requires careful tuning of hyperparameters to achieve optimal performance, which can be complex.
