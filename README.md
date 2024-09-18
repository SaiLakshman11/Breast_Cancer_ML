Breast Cancer Classification:

Summary: 
Developed a breast cancer classification model using Logistic Regression, Decision tree, Random Forest, Support Vector Machines. Achieving an accuracy of over 90%.

Problem Statement: 
The goal is to build and evaluate various machine learning models for breast cancer classification using a dataset that includes several features related to cell characteristics. The dataset is used to predict whether a tumor is malignant (class 1) or benign (class 0).

Steps and Explanation:
1. Importing libraries:
   Libraries are imported for data handling (pandas, numpy), visualization (matplotlib, seaborn), machine learning (scikit-learn), and performance metrics (scikit-learn).
2. Loading the Dataset:
   The dataset is loaded from a CSV file.
3. Renaming Columns:
   Column names are updated for clarity and consistency.
4. Data Cleaning or preprocessing:
   Class Mapping: Convert class labels from [2, 4] to [0, 1].
   Drop Irrelevant Column: Remove the Sample_code_number column as it’s not useful for classification.
   Handle Missing Values: Replace '?' with NaN, then drop rows containing missing values.
   Convert Data Types: Convert Bare_Nuclei and Class columns to numeric types.
5. Splitting Data:
   Feature and Target Separation: Separate features (X) and target (y).
   Train-Test Split: Split the dataset into training (80%) and testing (20%) sets.
6. Training models:
   Four different classification models are trained:
   Logistic Regression
   Decision Tree
   Random Forest
   Support Vector Machine (SVM)
7. Predicting and Evaluating models:
   Each model makes predictions on the test set.
9. Preformance Metrics:
   Accuracy: Measures the proportion of correctly classified instances.
   Confusion Matrix: Shows the counts of true positives, true negatives, false positives, and false negatives.
   Recall: Measures the ability of the model to identify all positive cases.
   Precision: Measures the ability of the model to identify only positive cases.
   F1 Score: The harmonic mean of precision and recall, providing a balanced measure.

Thank You!!
