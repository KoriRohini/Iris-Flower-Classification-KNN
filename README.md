Iris Flower Classification using KNN

Overview

This project uses the K-Nearest Neighbors (KNN) algorithm to classify iris flowers into different species based on their sepal and petal measurements.

Dataset

- Dataset: Iris dataset (loaded using Seaborn)
- Rows: 150
- Columns: 5

Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species (Target)

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

Steps

1. Load the Iris dataset.
2. Inspect the data and check for missing values.
3. Perform Exploratory Data Analysis (EDA).
4. Create scatter plots and a correlation heatmap.
5. Encode the species labels into numerical values.
6. Split the data into training and testing sets.
7. Train the KNN model with K = 5.
8. Predict flower species using the trained model.
9. Evaluate the model using accuracy and a confusion matrix.

Train-Test Split

- Training data: 120 rows
- Testing data: 30 rows

Model

The K-Nearest Neighbors (KNN) algorithm from Scikit-Learn is used to classify iris flowers into three species:

- Setosa
- Versicolor
- Virginica

Result

- Accuracy: 100%
- Correct Predictions: 30 out of 30 test samples.
- Misclassified Samples: 0

The model achieved 100% accuracy on the selected test dataset.

Author

Rohini Kori
