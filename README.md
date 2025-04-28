# Credit Card Fraud Detection using Logistic Regression

## Brief Overview
This project focuses on building a machine learning model to detect fraudulent credit card transactions using the **Credit Card Fraud Detection Dataset**. The goal is to predict whether a transaction is fraudulent or not using a **Logistic Regression** model. Techniques like **SMOTE** and **StandardScaler** are used to preprocess and balance the data.

## Objectives
- Detect fraudulent credit card transactions using machine learning.
- Preprocess the dataset by handling missing values and scaling the data.
- Handle class imbalance using **SMOTE**.
- Train and evaluate a **Logistic Regression** model.
- Evaluate model performance using metrics like Accuracy, Precision, Recall, and F1 Score.
- Visualize results using a **confusion matrix**.

## Steps to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
Install Dependencies Install the required libraries:

pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
Download the Dataset

Download the dataset from here.

Place the dataset (creditcard.csv) in the project directory.

Run the Code Run the Python script or Jupyter Notebook to:

Load the dataset.

Preprocess the data.

Apply SMOTE to balance the dataset.

Train the Logistic Regression model.

Evaluate the model's performance.

Results After running the script, you will see:

Evaluation metrics (Accuracy, Precision, Recall, F1 Score).

A confusion matrix visualization.

Code Structure
Data Preprocessing: Clean the dataset and handle missing values.

SMOTE: Balance the dataset by oversampling the minority class.

Model Training: Train the Logistic Regression model.

Evaluation: Evaluate the model using different metrics.

Visualization: Display the confusion matrix.

Conclusion
This project shows how machine learning can be applied to detect fraudulent credit card transactions. By preprocessing the data, handling class imbalance, and thoroughly evaluating the model, this project demonstrates how to build reliable fraud detection systems.

