Iris Flower Classification using Random Forest

Project Overview

This project demonstrates a simple Machine Learning classification model using the famous Iris Flower Dataset. The model predicts the species of an iris flower based on its flower measurements.

The project uses:

Python
Scikit-learn
Pandas
Seaborn
Matplotlib
Dataset

The dataset used is the built-in Iris dataset from Scikit-learn.

Features:

Sepal Length
Sepal Width
Petal Length
Petal Width
Target Classes:

Setosa
Versicolor
Virginica
Libraries Used

from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score, classification_report
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
Steps Performed

Load Dataset
The Iris dataset is loaded using Scikit-learn.

Create DataFrame
The dataset is converted into a Pandas DataFrame for easier analysis.

Data Visualization
A Seaborn pairplot is used to visualize relationships between features.

Train-Test Split
The dataset is divided into:

80% Training Data
20% Testing Data
Model Training
A Random Forest Classifier is trained using the training data.

Prediction
The trained model predicts flower species on test data.

Evaluation
Model performance is evaluated using:

Accuracy Score
Classification Report
Sample Prediction
The model predicts the species for a custom flower input.

Output Example

Accuracy: 1.0
Predicted Flower: setosa
Data Visualization

The project includes a Seaborn pairplot for visualizing feature distributions and class separations.

sns.pairplot(df, hue='species')
plt.show()
Machine Learning Algorithm Used

Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

Advantages:

High Accuracy
Handles classification problems efficiently
Reduces overfitting compared to single decision trees
Conclusion

This project successfully classifies iris flowers into different species using Machine Learning. The Random Forest model achieved high accuracy on the test dataset.

Future Improvements

Hyperparameter tuning
Deploying the model using Flask or Streamlit
Adding more visualizations
Saving the trained model using Pickle
Author

Developed as part of a Machine Learning practice project.

