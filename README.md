# Iris Flower Classification Using K-Nearest Neighbors (KNN)

## Project Overview

This project implements the K-Nearest Neighbors (KNN) machine learning algorithm to classify Iris flower species based on their physical measurements. The model is trained using the famous Iris dataset and predicts whether a flower belongs to Setosa, Versicolor, or Virginica species.

The project demonstrates the complete machine learning workflow, including data preprocessing, feature scaling, model training, hyperparameter tuning, evaluation, and prediction.

This project was developed as part of the DecodeLabs AI Internship Program.

---

## Objectives

* Understand the fundamentals of supervised machine learning.
* Implement the K-Nearest Neighbors (KNN) classification algorithm.
* Perform data preprocessing and feature scaling.
* Evaluate model performance using multiple classification metrics.
* Predict flower species based on input measurements.

---

## Features

* Loads and analyzes the Iris dataset.
* Displays dataset overview and statistical summary.
* Performs feature scaling using StandardScaler.
* Splits data into training and testing sets.
* Automatically finds the optimal value of K.
* Trains a KNN classification model.
* Evaluates performance using accuracy score and F1-score.
* Generates a confusion matrix and classification report.
* Predicts species for new flower samples.

---

## Technologies Used

* Python 3.x
* Pandas
* Scikit-learn
* K-Nearest Neighbors (KNN)
* StandardScaler
* Classification Metrics

---

## How It Works

The project follows a complete machine learning pipeline:

1. Load the Iris dataset from Scikit-learn.
2. Create a DataFrame for data exploration and analysis.
3. Scale numerical features using StandardScaler.
4. Split the dataset into training and testing sets.
5. Train multiple KNN models with different K values.
6. Select the K value with the highest accuracy.
7. Train the final KNN classifier.
8. Evaluate model performance using various metrics.
9. Predict species for new flower measurements.

### Machine Learning Workflow

```text
Load Dataset
      ↓
Data Analysis
      ↓
Feature Scaling
      ↓
Train-Test Split
      ↓
Find Optimal K
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Predictions
```

---

## Installation & Usage

### Clone the Repository

```bash
git clone https://github.com/atif929/DecodeLabs-Week2_Project_Classifier.git
```
## Sample Output

```text
==================================================
Iris Classification Using KNN
==================================================

Dataset Overview
Total Samples : 150

Classes :
['setosa', 'versicolor', 'virginica']

Finding Optimal K

k  | Accuracy
---|---------
1  | 1.0000
2  | 1.0000
3  | 1.0000
...

Selected K: 1

==================================================
Model Evaluation
==================================================

Accuracy : 100.00%
F1 Score : 1.0000
```

### Sample Predictions

```text
Sample                         Prediction
---------------------------------------------
[5.1, 3.5, 1.4, 0.2]          setosa
[6.0, 2.7, 5.1, 1.6]          virginica
[6.9, 3.1, 5.4, 2.1]          virginica
```

---

## Model Evaluation Metrics

The model is evaluated using:

### Accuracy Score

Measures the percentage of correctly classified samples.

### F1 Score

Provides a balance between precision and recall.

### Confusion Matrix

Displays actual versus predicted classifications.

### Classification Report

Includes:

* Precision
* Recall
* F1-score
* Support

for each flower species.

---

## Future Improvements

* Visualize data using Matplotlib and Seaborn.
* Implement cross-validation for more robust evaluation.
* Compare KNN with other classification algorithms.
* Build a web interface using Streamlit.
* Allow users to enter flower measurements interactively.
* Deploy the model as a web application.

---

## Learning Outcomes

Through this project, the following concepts were practiced:

* Supervised Machine Learning
* K-Nearest Neighbors (KNN)
* Data Preprocessing
* Feature Scaling
* Model Evaluation
* Hyperparameter Tuning
* Classification Metrics
* Predictive Modeling using Scikit-learn

---

## Author

**Atif Rameez**
Software Engineering Student
Sukkur IBA University

GitHub: https://github.com/atif929

---

## License

This project is created for educational and internship purposes under the DecodeLabs AI Internship Program.
