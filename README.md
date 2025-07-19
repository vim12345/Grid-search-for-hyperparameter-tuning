# Grid-search-for-hyperparameter-tuning
# Description:
Grid Search is a brute-force approach to hyperparameter tuning, where we evaluate model performance over a predefined grid of parameters. This helps in finding the best combination that yields the highest accuracy. In this project, we use GridSearchCV to tune a Support Vector Machine (SVM) on the Iris dataset.

# 🔍 What This Does:
* Searches all combinations of C, gamma, and kernel

* Uses 5-fold cross-validation to evaluate each combination

* Selects the best hyperparameters and evaluates the model on the test set
