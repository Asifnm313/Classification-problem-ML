# CLASSIFICATION PROBLEM-IN-MACHINE LEARNING
## Breast Cancer Classification Using Machine Learning
## Objective
The goal of this project is to classify breast cancer tumors as malignant or benign using machine learning algorithms. This project evaluates the performance of different classification techniques applied to the Breast Cancer Dataset from the scikit-learn library.

---

## Dataset
The dataset used for this project is the Breast Cancer Wisconsin Diagnostic Dataset available in the scikit-learn library.

---

## Features:
- **30 numeric features representing characteristics of cell nuclei in the breast mass.**
- **Target Variable:**
  - 0 - Malignant (Cancerous)
  - 1 - Benign (Non-Cancerous)

----

## Key Components
1. **Loading and Preprocessing** 
- **Loaded the dataset using scikit-learn's load_breast_cancer() function.**
- **Handled missing values (if any) and scaled the features using StandardScaler.**
- **Justification: Feature scaling is critical to ensure that machine learning algorithms perform optimally, especially distance-based models like SVM and k-NN.**
2. **Classification Algorithms**
Implemented the following classification algorithms:

- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Support Vector Machine (SVM)**
- **k-Nearest Neighbors (k-NN)**

  Each algorithm is explained briefly along with its strengths and suitability for this dataset.

3. **Model Comparison**
- **Evaluated the models based on accuracy, classification reports, and confusion matrices.**
- **Compared their performance and identified the best and worst performing models.**

---

## Technologies Used
- **Python 3**
- **Libraries:**
 - pandas, numpy - Data processing
 - seaborn, matplotlib - Visualization
 - scikit-learn - Machine Learning algorithms and utilities
