# Iris Flower Classification using K-Nearest Neighbors (KNN)

This repository contains a machine learning experiment that implements a **K-Nearest Neighbors (KNN)** classifier to categorize iris flowers into their respective species based on their sepal and petal dimensions[span_5](start_span)[span_5](end_span)[span_6](start_span)[span_6](end_span)[span_7](start_span)[span_7](end_span)[span_8](start_span)[span_8](end_span).

---

## 📊 Dataset Overview

The project uses the classic **Iris dataset** (loaded via Seaborn), which consists of 150 samples with 5 columns[span_9](start_span)[span_9](end_span):
* **Features (`X`)**:
  * Sepal Length (cm)[span_10](start_span)[span_10](end_span)
  * Sepal Width (cm)[span_11](start_span)[span_11](end_span)
  * Petal Length (cm)[span_12](start_span)[span_12](end_span)
  * Petal Width (cm)[span_13](start_span)[span_13](end_span)
* **Target (`y`)**:
  * Species: `setosa`, `versicolor`, and `virginica` (encoded numerically using `LabelEncoder`)[span_14](start_span)[span_14](end_span)[span_15](start_span)[span_15](end_span)[span_16](start_span)[span_16](end_span)

---

## 🛠️ Workflow & Steps

1. **Exploratory Data Analysis (EDA):**
   * Inspected dataset structure, shape ($150 \times 5$), data types, and verified that there are no missing values[span_17](start_span)[span_17](end_span)[span_18](start_span)[span_18](end_span).
   * Generated descriptive statistics and correlation matrices for the numerical features[span_19](start_span)[span_19](end_span)[span_20](start_span)[span_20](end_span).
2. **Data Visualization:**
   * Created a Seaborn scatter plot illustrating the relationship between **Sepal Length vs. Petal Length** categorized by species[span_21](start_span)[span_21](end_span).
   * Generated a correlation heatmap to analyze feature relationships[span_22](start_span)[span_22](end_span)[span_23](start_span)[span_23](end_span).
3. **Data Preprocessing:**
   * Encoded categorical target labels (`species`) into numeric values using `LabelEncoder`[span_24](start_span)[span_24](end_span)[span_25](start_span)[span_25](end_span).
   * Split the dataset into training ($80\%$) and testing ($20\%$) sets using `train_test_split` (`random_state=42`)[span_26](start_span)[span_26](end_span).
4. **Model Training & Prediction:**
   * Trained a **K-Nearest Neighbors (KNN)** classifier with $k=5$ (`KNeighborsClassifier`) on the training data ($120$ samples)[span_27](start_span)[span_27](end_span).
   * Evaluated predictions on the test set ($30$ samples)[span_28](start_span)[span_28](end_span)[span_29](start_span)[span_29](end_span).
5. **Model Evaluation:**
   * Achieved an **accuracy of 1.0 ($100\%$)** on the test dataset[span_30](start_span)[span_30](end_span).
   * Generated a **Confusion Matrix** and a full **Classification Report** detailing precision, recall, and f1-scores[span_31](start_span)[span_31](end_span).

---

## 📈 Results & Evaluation

* **Accuracy:** 1.0[span_32](start_span)[span_32](end_span)
* **Confusion Matrix:**
  ```text
  [[10  0  0]
   [ 0  9  0]
   [ 0  0 11]]
