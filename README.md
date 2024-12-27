# Customer Churn Prediction Using Random Forest - PowerCo

## Project Summary

This project aims to predict customer churn using machine learning techniques, specifically the Random Forest algorithm. By analyzing a dataset with customer information and various features, we identify patterns that indicate whether a customer is likely to churn or not. The project compares the performance of a simple Random Forest model with an enhanced version that uses the Synthetic Minority Over-sampling Technique (SMOTE) to handle class imbalance.

### Key Steps:

#### 1. **Data Preprocessing**:
   - The dataset is cleaned by removing unnecessary columns and handling missing values.
   - Features are scaled for consistency to ensure better model performance.

#### 2. **Churn Visualization**:
   - A count plot is used to visualize the distribution of churn (1) vs non-churn (0) instances in the dataset.

#### 3. **Modeling**:
   - A Random Forest Classifier is trained on the preprocessed data to predict churn based on various customer features.

#### 4. **Model Evaluation**:
   - The model’s performance is evaluated using a confusion matrix, classification report, and ROC curve.

#### 5. **Handling Imbalanced Data**:
   - The Synthetic Minority Over-sampling Technique (SMOTE) is applied to address the class imbalance between churn and non-churn instances. This technique helps improve the model's prediction for the minority class (churn).

#### 6. **Feature Importance**:
   - The most important features influencing churn prediction are identified and visualized using bar plots.

#### 7. **Comparison**:
   - The performance of the simple Random Forest model is compared with the SMOTE-enhanced version using ROC curves.
