Logistic Regression for Cancer Detection

Predict whether a tumor is benign or malignant using Logistic Regression, based on medical features from the Breast Cancer dataset.
The project focuses on training the model, evaluating its performance, and analyzing the results.

Dataset

The dataset contains the following medical features:

Clump Thickness

Uniformity of Cell Size

Uniformity of Cell Shape

Marginal Adhesion

Single Epithelial Cell Size

Bare Nuclei

Bland Chromatin

Normal Nucleoli

Mitoses

Class (Target variable)

2 → Benign

4 → Malignant

Non-informative columns (e.g., Sample Code Number) were removed during preprocessing.

Steps Performed

Loaded and inspected the dataset

Handled missing values by replacing ? with median values

Dropped non-informative columns

Separated features (X) and target (y)

Split data into:

70% training

30% testing

Scaled features using StandardScaler

Trained a Logistic Regression model

Made predictions on the test set

Evaluated performance using:

Accuracy Score

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

Results

The model achieved high accuracy on the test dataset.

The confusion matrix and classification report show that the model effectively distinguishes between benign and malignant tumors.

Logistic Regression proved to be effective for binary classification on structured medical data.

Conclusion

Logistic Regression can reliably predict tumor classification when the dataset is clean and properly preprocessed.
Model performance can be further improved through:

Feature engineering

Hyperparameter tuning

Using more advanced models (e.g., SVM, Random Forest)

How to Run the Project
Option 1: Google Colab

Open the notebook in Google Colab

Upload the breast_cancer.csv dataset

Run all cells sequentially

Option 2: Local Execution

Use the provided .csv and .py files

Run the Python script to observe the results
