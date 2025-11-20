# tree-models-classification
Overview:-This project demonstrates how to build and analyze Decision Tree and Random Forest models for classification. It also covers tree visualization, overfitting control, feature importance interpretation, and evaluation using cross-validation.
 Tools Used
Python
Scikit-learn
Matplotlib
Graphviz (optional for visualization)
 Steps Performed
1️. Train a Decision Tree Classifier
Fit a decision tree model
Visualize the tree structure
Evaluate train & test accuracy
2️. Analyze Overfitting
Compare full tree vs controlled depth (max_depth)
Plot training vs cross-validation accuracy for different depths
3️. Train a Random Forest Classifier
Fit a Random Forest with multiple trees
Compare accuracy with Decision Tree
Check OOB (Out-of-Bag) score

4. Feature Importance Analysis

Extract top contributing features from both models

Visualize feature importance

5️. Evaluate with Cross-Validation

Perform 5-fold cross-validation

Compare model stability and generalization

Results

Decision Trees may overfit if the depth is not controlled.

Random Forests reduce variance and generally achieve higher accuracy.

Feature importance helps identify influential predictors.

 How to Run

Install dependencies:

pip install scikit-learn matplotlib pandas graphviz


Run the Python script or Jupyter Notebook to view:

Model training

Tree visualization

Accuracy comparison

Feature importance plots

Project Structure

├── decision_tree_random_forest.ipynb   # Main notebook
├── rf_feature_importances.csv          # Output importance file
├── depth_vs_accuracy.csv               # Overfitting analysis
└── README.md                           # Documentation
