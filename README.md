# Week-1
A machine learning project to predict machine failure using the AI4I 2020 Predictive Maintenance dataset. 

**Predictive Maintenance with Machine Learning**

This project is a complete data science workflow to predict machine failure using the **"AI4I 2020 Predictive Maintenance Dataset"** from Kaggle.

The primary goal was to build a reliable classification model that could identify potential failures despite the data being highly imbalanced (96.6% "No Failure" vs. 3.4% "Failure").

**Key Steps:**

**Data:** ai4i2020.csv

**Preprocessing**: Scaled numerical features (like Torque, Tool wear) and One-Hot Encoded categorical features (Type).

**Imbalance Handling**: Used the SMOTE (Synthetic Minority Over-sampling TEchnique) on the training data to create a balanced dataset.

Model: Trained a Random Forest Classifier.

**Final Result:**
The final model achieved a 74% Recall on the unseen test data, meaning it successfully identified 74% of all actual machine failures.
