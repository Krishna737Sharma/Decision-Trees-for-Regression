# Decision Trees for Regression

## Objective
In this assignment, you will implement a Decision Tree Regressor from scratch and compare its performance with scikit-learn's implementation. The tasks include preprocessing the Auto MPG dataset, handling duplicates and missing values, performing hyperparameter tuning using K-fold cross-validation, and evaluating the models with appropriate metrics. You will also visualize the decision tree and analyze the results.

## Tasks

### Task 1: Load and Preprocess the Auto MPG Dataset [Marks - 0]
- Load the Auto MPG dataset.
- The dataset contains 7 features, and the target variable is the MPG of the car.
- Note: Car ID (string) is not a feature.

### Task 2: Handle Duplicates and Missing Values [Marks - 1]
- Check for duplicate and missing features in the dataset.
- Handle duplicates and missing values appropriately.
- Partition the data into training (80%) and test sets (20%).

### Task 3: Implement Decision Tree Regressor from Scratch [Marks - 6]
- Implement a decision tree regressor using Mean Squared Error (MSE) reduction as the criterion for splitting nodes.

### Task 4: Hyperparameter Tuning with Cross-Validation [Marks - 4]
- Treat the maximum depth of the tree and the minimum samples in a leaf (similar to scikit-learn's `min_samples_leaf`) as hyperparameters.
- Perform K-fold cross-validation with grid search on the training set (80%) to find the best values for the hyperparameters.
- Use the learned decision tree regressor to predict on the test set and report the MSE.

### Task 5: Decision Tree Regressor using scikit-learn [Marks - 3]
- Fit a decision tree regressor model on the training set using scikit-learn.
- Perform cross-validation to find the best values for the hyperparameters in the same way as for the from-scratch implementation.

### Task 6: Compare Results [Marks - 2]
- Compare the best hyperparameter values obtained from your implementation and scikit-learn's implementation.
- Compare the MSE values obtained from your implementation with those from scikit-learn.

### Task 7: Scatter Plots [Marks - 2]
- Show scatter plots of predicted MPG vs. True MPG for both:
  1. Your from-scratch implementation.
  2. Scikit-learn's implementation.

### Task 8: Decision Tree Visualization [Marks - 2]
- Visualize the decision tree learned by scikit-learn.

## Files
- `auto_mpg_dataset.csv`: Dataset file containing the Auto MPG data.
- `decision_tree_regressor.py`: Python script containing the implementation for all tasks.
- `README.md`: Project documentation in Markdown format.

## How to Run
1. Clone the repository.
2. Ensure the dataset `auto_mpg_dataset.csv` is in the working directory.
3. Install the required Python libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`.
4. Run the `decision_tree_regressor.py` file to execute all tasks.

## Results
- Hyperparameter tuning results from cross-validation.
- Comparison of MSE and hyperparameter values between your implementation and scikit-learn.
- Scatter plots of predicted vs. true MPG.
- Visualization of the decision tree.

## License
This project is licensed under the MIT License.
