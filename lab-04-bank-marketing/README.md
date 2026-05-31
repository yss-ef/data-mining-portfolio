# Lab 04: bank marketing binary classification analysis

This laboratory builds and evaluates machine learning models to predict whether
a client will subscribe to a term deposit. The project follows a complete
machine learning pipeline from exploratory data analysis to model performance
comparison.

## Key technical tasks

- Exploratory data analysis (EDA): Investigates feature distributions and
  relationships with the target variable.
- Data preprocessing:
    - Imputed missing values with the mode.
    - Implemented binary encoding for the target variable.
    - Used one-hot encoding for categorical features.
    - Applied standard scaling for numerical features.
- Model implementation:
    - Logistic regression: Serves as a baseline classifier.
    - Decision tree: Explores non-linear patterns.
    - Random forest: Uses ensemble learning for improved robustness.
- Performance evaluation: Uses recall, F1-score, and confusion matrices to
  prioritize identifying potential subscribers.

## Analytical findings

- Class imbalance: The dataset is imbalanced, requiring the use of F1-score
  over accuracy as a primary metric.
- Key predictors: Call duration and previous campaign outcomes serve as
  significant indicators of success.
- Model comparison: The random forest model provides the best balance between
  precision and recall for this task.

## Dataset

- `bank-marketing.csv`: Contains 4,119 records with 20 features related to
  client demographics, social-economic indicators, and campaign contact
  history.

Authored by Youssef Fellah.
Developed for the Engineering Cycle at Mundiapolis University.
