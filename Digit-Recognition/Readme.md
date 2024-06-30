## Hand Written Digit Recognition

## Project Overview
This project predicts the hand written digit image using a multiple classification approach.

## Dataset
-The dataset is sourced from keras inbuilt library and has images converted to matrices of 28*28 with a value ranging between 0 to 255.
-More the intensity signifies the presence of the part of the written digit

## Data Preprocessing
- Convert the matrix of every data to a single dimensional array.
- Normalize the features for better fitting.
- Split data into training and testing sets.

## Model Building
This model uses Keras from the TensorFlow library. We use single layer and then multiple dense layers and different activation functions like 'relu' and 'sigmoid'. For compilation, we use:
- Learning rate: Adam
- Loss: 'sparse_crossentropy'
- Metrics: 'Accuracy'

## Model Evaluation
# Simple Model
On evaluation of the model, we get:
- Train loss: 0.2670
- Train accuracy: 0.9259
- Test loss: 0.2672
- Test accuracy: 0.9271

#Complex Model
On evaluation of the model, we get:
- Train loss: 0.0455 
- Train accuracy: 0.9865
- Test loss: 0.0731
- Test accuracy: 0.9802

## Tools and Technologies
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, TensorFlow/Keras, Sequential, Classification_Report, Confusion_matrix
- **IDE:** Jupyter Notebook

## Acknowledgments
Online resources and educators for providing guidance and insights.
