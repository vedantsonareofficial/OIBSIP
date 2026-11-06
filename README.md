# Iris Flower Classification

## Objective
Predict the species of an iris flower (Setosa, Versicolor, Virginica) from its measurements.

## Dataset
Iris dataset from scikit-learn: 150 flowers, 4 features, 3 classes.

## What I did
- Explored the data (shape, nulls, statistics)
- Made a pairplot and box plots
- Found that petal length and petal width separate the species best
- Split the data 80/20 into train and test sets
- Trained 4 models: Logistic Regression, KNN, Decision Tree, Random Forest
- Evaluated them with accuracy, confusion matrix and classification report

## Results
Best model: KNN
Test accuracy:1.0
Reason: It is the best model , based on acccurecy , it provides an accuracy of 1.0 which is the gretest among all models. 

## Tools
Python, pandas, scikit-learn, matplotlib, seaborn, Jupyter Notebook