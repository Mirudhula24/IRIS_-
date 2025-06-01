# Iris Flower Classification Project
This project is a machine learning and data visualization exploration based on the Iris Flower Dataset, one of the most well-known datasets in data science. It was completed as part of a group learning project to apply concepts of neural networks and classification algorithms.
 
The main goal of this project is to:
Visualize the dataset to understand the relationship between sepal and petal measurements.Preprocess the data for machine learning by encoding class labels.Build a neural network model using Keras to classify iris flowers into three species.Evaluate model performance using cross-validation.Compare the neural network with a baseline Logistic Regression model.
 
 Dataset Used
Features: Sepal length, Sepal width, Petal length, Petal width
Classes: Iris-setosa, Iris-versicolor, Iris-virginica
Format: CSV file (Iris_flower_dataset.csv)

 Data Visualization
We used matplotlib to plot:
Sepal Length vs Sepal Width
Petal Length vs Petal Width
Each species is color-coded to observe how well-separated they are in the feature space. This helps understand the feasibility of classification.

 Data Preprocessing
Loaded the CSV data using pandas.
Converted species names to numeric labels using LabelEncoder.
Used to_categorical to one-hot encode the output classes for neural network compatibility.

 Model Building
Neural Network:
Implemented using Keras (Sequential model).

Architecture:
Input layer: 4 neurons (for 4 features)
Hidden layer: 8 neurons, ReLU activation
Output layer: 3 neurons, softmax activation (multi-class)
Compiled using categorical_crossentropy loss and adam optimizer.

Baseline Model:
Used Logistic Regression from scikit-learn for comparison.
Evaluated with 10-fold cross-validation.

 Results
The logistic regression model achieved an average accuracy of ~93% using cross-validation.

Neural network model is defined and can be extended for training and evaluation.


