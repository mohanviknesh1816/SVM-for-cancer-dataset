# Breast Cancer Classification using Support Vector Machines (SVM)

This project demonstrates the application of the Support Vector Machine (SVM) algorithm for binary classification tasks. The objective is to classify breast cancer tumors as malignant or benign based on numerical input features and to visualize how the SVM model separates classes in a 2D space.

## Train and Evaluate SVM Classifiers
- Trained two `SVC` models using scikit-learn with linear and RBF kernels.
- Selected two features (`radius_mean` and `texture_mean`) from the dataset for 2D visualization.
- Split the dataset into training and testing subsets.
- Predicted class labels for the test data and evaluated model accuracy.

## Tune Hyperparameters (C and gamma)
- Used grid search (`GridSearchCV`) to experiment with different values of `C` and `gamma`.
- Identified the best-performing parameters based on cross-validation accuracy.
- Improved model performance with optimized SVM hyperparameters.

## Evaluate with Cross-Validation
- Performed 5-fold cross-validation on the full dataset.
- Calculated accuracy scores for each fold.
- Reported the average accuracy and standard deviation to assess model stability.

## Visualize Decision Boundaries
- Used two selected features to enable 2D plotting.
- Created a mesh grid across the feature space.
- Plotted decision boundaries for both linear and RBF SVM classifiers.
- Overlaid the training data to show class regions and support vectors.

## Results
- The linear SVM achieved good accuracy with a straight-line decision boundary.
- The RBF SVM provided better accuracy with a flexible, non-linear boundary.
- Grid search tuning improved model generalization.
- Cross-validation confirmed consistent performance across folds.

## Requirements
- Python 3.x  
- scikit-learn  
- pandas  
- matplotlib  
- numpy
