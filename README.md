# Breast Cancer Prediction

This project focuses on predicting whether a breast tumor is malignant or benign using machine learning techniques. The notebook explores various models, evaluates their performance, and selects the best one for breast cancer classification.

## Project Overview

The dataset contains information about the characteristics of cell nuclei in breast masses. By analyzing these features, machine learning algorithms can help predict whether a tumor is malignant or benign.

## Notebook Structure

1. *Importing Libraries*: 
   The notebook uses common Python libraries such as:
   - numpy, pandas: For data manipulation
   - seaborn, matplotlib: For data visualization
   - scikit-learn: For model building, evaluation, and feature selection

2. *Loading the Data*: 
   The dataset is loaded into a pandas DataFrame for exploration and preprocessing.

3. *Data Preprocessing*:
   - Handling missing values
   - Encoding categorical features
   - Scaling the data to improve model performance

4. *Feature Selection*:
   - Recursive Feature Elimination (RFE) and Recursive Feature Elimination with Cross-Validation (RFECV) are used to select the most important features.

5. *Model Training*:
   The notebook applies various machine learning models:
   - Logistic Regression
   - Random Forest Classifier
   - Naive Bayes Classifier
   
   These models are trained to predict the outcome (malignant or benign).

6. *Model Evaluation*:
   - The performance of each model is evaluated using metrics such as *accuracy score* and *classification report*.

## Results

The project achieves *a good accuracy* in predicting breast cancer tumors, with a detailed evaluation of precision, recall, and F1-score for each model.

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Llasheen-0/Breast-Cancer-Prediction.git
