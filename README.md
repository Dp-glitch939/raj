# This project demonstrates the use of logistic regression for authenticating banknotes using a dataset. Here's a detailed breakdown of the approach:

1. Data Loading and Exploration
The dataset is read and loaded into the program.

The distribution of the target variable (authentic vs. fake banknotes) is visualized using a count plot to understand the class balance.

2. Data Preprocessing
The dataset is balanced by reducing excess entries from the majority class to ensure a fair training process.

The dataset is then split into training and testing sets for model evaluation.

Feature scaling is applied to standardize input values, ensuring all features have zero mean and unit variance to optimize model performance.

3. Model Training
A logistic regression model is trained using the processed data.

The model learns patterns that differentiate real banknotes from fraudulent ones based on input features.

4. Model Evaluation
A confusion matrix is used to assess the model's predictions, showing true positives, false positives, true negatives, and false negatives.

The overall accuracy of the model is calculated, ensuring reliable authentication performance.

5. Prediction
The trained model predicts the class (real or fake) for a new banknote sample.

It also provides the probability associated with the prediction to indicate confidence levels.

This structured process ensures accurate and reliable banknote authentication using logistic regression
