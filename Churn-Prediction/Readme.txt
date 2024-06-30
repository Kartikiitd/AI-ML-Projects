**Telecom Customer Churn Prediction**

*Project Overview*
This project predicts customer churn in the telecom industry using a binary classification approach. The goal is to identify potential churners so that we can take measures to retain them.

*Dataset*
The dataset is sourced from Kaggle and includes customer demographics, account information, and service usage patterns.


*Data Preprocessing:*
Look up for missing values and drop down those from the dataset
Converting categorical variables to numeric.
Normalise the features for better fitting
Splitting data into training and testing sets.

*Model Building:*
This model uses keras from tensorflow library
We use multiple dense layers and different activation functions like 'relu' & 'sigmoid'.
For Compilation we use learning rate as Adam ; loss as 'binary_crossentropy' and metrics as 'Accuracy'


*Model Evaluation:*
On evaluation of model we get :-
train loss = 0.2854309380054474, 
train accuracy = 0.876800000667572 ,
test loss = 0.5636970400810242, 
test accuracy = 0.7526652216911316

*Tools and Technologies*
Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn,TensorFlow/Keras , Sequential , Classification_Report ,Confusion_matrix
IDE: Jupyter Notebook

Acknowledgments
Online resources and educators for providing guidance and insights
