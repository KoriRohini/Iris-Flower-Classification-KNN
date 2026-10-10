# Iris Flower Classification (KNN)

This project uses **K-Nearest Neighbors (KNN)** to classify iris flowers into three species (*setosa*, *versicolor*, *virginica*) based on sepal and petal dimensions.

---

## Dataset
- **Source:** Iris dataset (150 samples, 5 columns)  
- **Features:**  
  - Sepal Length  
  - Sepal Width  
  - Petal Length  
  - Petal Width  
- **Target:** Species (encoded numerically)

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  

---

## Steps
1. Load the dataset  
2. Inspect data & check for missing values  
3. Perform Exploratory Data Analysis (EDA)  
4. Create scatter plots & correlation heatmap  
5. Encode target labels & split data (80/20)  
6. Train the KNN model (`k=5`)  
7. Predict species on test data  
8. Evaluate results with accuracy, confusion matrix, and classification report  

---

## Train-Test Split
- **Training data:** 120 samples  
- **Testing data:** 30 samples  

---

## Model
- Algorithm: **K-Nearest Neighbors (KNN)**  
- Task: Classify iris flowers into species  

---

## Results
- **Accuracy:** 100%  
- **Confusion Matrix:**

[[10  0  0]
[ 0  9  0]
[ 0  0 11]]

---

## 📌 About
A machine learning project implementing KNN in Python to classify iris flowers using sepal and petal measurements.
