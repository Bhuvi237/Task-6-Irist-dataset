# K-Nearest Neighbors on Iris Dataset

# Overview
Today, I explored the K-Nearest Neighbors (KNN) algorithm using the Iris dataset. The workflow included data preprocessing, model training, evaluation, and visualization of decision boundaries.

# Steps Performed
1.Loaded the Iris dataset

2.Feature Normalization
-Scaled the features using StandardScaler to ensure all variables have equal weight in KNN distance calculations.

3.Model Training with KNN
-Implemented KNeighborsClassifier from sklearn.
-Experimented with different values of k to observe the effect on accuracy.

4.Model Evaluation
-Calculated accuracy for each k value.
-Created an accuracy vs k plot to identify optimal k.
-Generated a confusion matrix to check class-level performance.

5.Decision Boundary Visualization
-Plotted decision boundaries for the first two features for easy 2D visualization.
-Used distinct colors for each class to illustrate classification regions.

# Findings
-Accuracy remained consistently high (~1.00) across multiple k values, indicating strong separation in the dataset.
-The decision boundary plot clearly showed well-separated clusters for the classes.

# Skills & Concepts Practiced
-Data normalization
-KNN classification
-Model evaluation (accuracy, confusion matrix)
-Hyperparameter tuning (k selection)
-Decision boundary visualization
