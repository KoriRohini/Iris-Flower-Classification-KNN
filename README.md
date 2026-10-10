###Iris Flower Classification using K-Nearest Neighbors (KNN)

##Overview

This project uses K-Nearest Neighbors (KNN) to classify iris flowers into different species based on their sepal and petal measurements.

##Dataset

- **Source:** Seaborn Iris Dataset
- **Rows:** 150
- **Columns:** 5

##Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species

##Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

##Steps

1. Load the Iris dataset.
2. Inspect the data and check for missing values.
3. Perform Exploratory Data Analysis (EDA).
4. Create scatter plots and a correlation heatmap.
5. Encode species labels into numerical values.
6. Split the data into training and testing sets.
7. Train the KNN model with K = 5.
8. Predict flower species and evaluate the model.

##Train-Test Split

- Training data: 120 samples
- Testing data: 30 samples

##Model

The K-Nearest Neighbors (KNN) algorithm from Scikit-Learn is used to classify flowers into three species: Setosa, Versicolor, and Virginica.

##Result

- Accuracy: 100%
- Correct Predictions: 30 out of 30

Confusion Matrix

[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]

##Author

Rohini Kori
