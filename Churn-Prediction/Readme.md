# Telecom Customer Churn Prediction

## Project Overview
This project predicts customer churn in the telecom industry using a binary classification approach. The goal is to identify potential churners so that we can take measures to retain them.

## Dataset
The dataset is sourced from Kaggle and includes customer demographics, account information, and service usage patterns.

## Data Preprocessing
- Look up for missing values and drop those from the dataset.
- Convert categorical variables to numeric.
- Normalize the features for better fitting.
- Split data into training and testing sets.

## Model Building
This model uses Keras from the TensorFlow library. We use multiple dense layers and different activation functions like 'relu' and 'sigmoid'. For compilation, we use:
- Learning rate: Adam
- Loss: 'binary_crossentropy'
- Metrics: 'Accuracy'

## Model Evaluation
On evaluation of the model, we get:
- Train loss: 0.2854309380054474
- Train accuracy: 0.876800000667572
- Test loss: 0.5636970400810242
- Test accuracy: 0.7526652216911316

## Tools and Technologies
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, TensorFlow/Keras, Sequential, Classification_Report, Confusion_matrix
- **IDE:** Jupyter Notebook

## Acknowledgments
Online resources and educators for providing guidance and insights.
