# Iris Dataset Classification

This repository contains Python code for classifying the Iris dataset using various machine learning algorithms. The Iris dataset is a classic dataset in machine learning and statistics, consisting of 150 samples from each of three species of Iris flowers (Iris setosa, Iris versicolor, and Iris virginica). Each sample has four features: sepal length, sepal width, petal length, and petal width.

## Features

- **Data Visualization**: Visualizes the entire dataset using a scatter plot with different colors representing different species.
- **K-Nearest Neighbors (KNN) Classification**: Implements KNN with distance-weighted metrics and visualizes the decision boundary.
- **Decision Tree Classification**: Trains a decision tree classifier and visualizes the decision surface and the tree structure.
- **Logistic Regression**: Implements logistic regression and visualizes the decision boundary.

## Libraries Used

- **NumPy**: For numerical operations.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For plotting and visualization.
- **Scikit-Learn**: For machine learning algorithms and metrics.

## Code Overview

1. **Data Import and Visualization**:
   - Imports the Iris dataset from `sklearn` and a CSV file.
   - Prints examples of each species with their sepal and petal lengths.
   - Visualizes the entire dataset using a scatter plot.

2. **K-Nearest Neighbors (KNN)**:
   - Splits the dataset into training and testing sets.
   - Trains a KNN classifier with distance-weighted metrics.
   - Visualizes the decision boundary of the KNN classifier.
   - Calculates and prints the accuracy score.

3. **Decision Tree**:
   - Trains a decision tree classifier.
   - Visualizes the decision surface and the tree structure.
   - Calculates and prints the accuracy score.

4. **Logistic Regression**:
   - Trains a logistic regression model.
   - Visualizes the decision boundary.
   - Calculates and prints the accuracy score.

## Usage

To run the code, ensure you have the required libraries installed. You can install them using:
```bash
pip install numpy pandas matplotlib scikit-learn
```

Then, simply run the Python script to see the visualizations and accuracy scores for each classification method.

## Results

- **KNN Accuracy**: 1.0
- **Decision Tree Accuracy**: 1.0
- **Logistic Regression Accuracy**: 0.9666666666666667

## Contributing

Feel free to fork this repository and contribute by adding more classification methods, improving visualizations, or optimizing the existing code.
