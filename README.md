
# NASA RUL Prediction with Linear Regression [ SE20UARI052 ]

This repository contains code that demonstrates how to predict the Remaining Useful Life (RUL) of NASA equipment using a Linear Regression approach. The code includes data loading, preprocessing, model training, and evaluation.

## Prerequisites

Before running the code, make sure you have the following dependencies installed:

- Python
- pandas
- scikit-learn

You can install these packages using `pip`:



## Logic Used

1. **Data Loading and Preprocessing**:
   - The code loads the dataset from the specified file and performs basic preprocessing.
   - It renames columns for clarity and calculates the RUL (Remaining Useful Life) for each row, indicating how many more cycles an engine is expected to run before failure.

2. **Feature and Target Definition**:
   - Features (sensor readings and operational information) and the target (RUL) are defined.

3. **Train-Test Split**:
   - The data is split into training and testing sets (80% training, 20% testing) to evaluate the model's performance.

4. **Feature Scaling**:
   - Standardization of features using `StandardScaler` ensures that all features have the same scale.

5. **Model Training**:
   - The code uses a Linear Regression model to train the RUL prediction model on the training data.

6. **Model Prediction and Evaluation**:
   - It predicts RUL values on the test set and calculates the Mean Squared Error (MSE) as a performance metric.

7. **Usage Instructions**:
   - A comment at the end of the code provides instructions on how to use the trained model to predict RUL on new, unseen data.

