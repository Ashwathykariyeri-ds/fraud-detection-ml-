# Credit Card Fraud Detection using Machine Learning

## Project Overview
This project aims to detect fraudulent credit card transactions using supervised machine learning models. We focus on identifying patterns that distinguish legitimate transactions from fraudulent ones to minimize financial loss.

## Dataset
•⁠  ⁠*Source:* [Kaggle: Credit Card Fraud 2025](https://www.kaggle.com/datasets/prince7489/credit-card-fraud-2025)

## Dataset Instructions
This dataset is not included in the repository due to its large size.
To run the project:
•⁠ Download the dataset from Kaggle:
  https://www.kaggle.com/datasets/prince7489/credit-card-fraud-2025
•⁠ Extract the file
•⁠ Place the CSV file in the same folder as notebook.ipynb
•⁠ Run the notebook

## Models Used
•⁠  ⁠*Logistic Regression* - For baseline classification.
•⁠  ⁠*Decision Tree* - To capture non-linear relationships.
•⁠  ⁠*Random Forest* - An ensemble method to improve accuracy and reduce overfitting.

## Methodology
1.⁠ ⁠*Data Preprocessing:* Handling missing values, scaling features, and addressing class imbalance.
2.⁠ ⁠*Exploratory Data Analysis (EDA):* Visualizing correlations and transaction distributions.
3.⁠ ⁠*Model Training & Evaluation:* Training multiple models and tuning hyperparameters.

## Evaluation Metrics
Since fraud detection is an imbalanced classification problem, we focus on:
•⁠  ⁠Accuracy & Precision
•⁠  ⁠*Recall* (Crucial for catching as many frauds as possible)
•⁠  ⁠F1 Score
•⁠  ⁠Confusion Matrix

## Results
The models are compared using evaluation metrics and confusion matrix visualizations to determine which algorithm performs best for this specific dataset.

## How to Run
1.⁠ ⁠*Install Requirements:*
   ```bash
   pip install -r requirements.txt
