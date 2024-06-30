# KNN for the IRIS dataset
This project demonstrates the implementation of the K-Nearest Neighbors (KNN) algorithm on the IRIS dataset using both sklearn and a custom-built KNN model from scratch. Comparisons between the models are made to analyze their performance.

## Introduction
The IRIS dataset is a classic dataset for pattern recognition, consisting of 150 samples from three species of iris flowers: setosa, versicolor, and virginica. Four features are measured for each sample: sepal length, sepal width, petal length, and petal width.

This project includes:
- Visualization of the IRIS dataset.
- Implementation of data preprocessing steps.
- Training and evaluation of the KNN model using  `sklearn`.
- Implementation of a custom KNN model from scratch.
- Comparison of the performance between the  `sklearn` KNN and the custom-built KNN.

## Implementation Details
The notebook includes the following sections:
- *Load and Visualize IRIS Dataset:* Load the dataset and visualize it using various plots.
- *Convert to Pandas DataFrame:* Convert the dataset to a Pandas DataFrame for easier manipulation.
- *Dataset Preprocessing and Cleaning:* Perform data preprocessing and cleaning steps.
- *Split into X and y:* Separate the dataset into features (X) and target labels (y).
- *Data Normalization:* Normalize the data for improved model performance.
- *Train Test Split:* Split the dataset into training and testing sets.
- *Training and Prediction using Built-in KNN Classifier:* Train and evaluate the KNN model using `sklearn`.
- *Finding the Best K Value (Built-in Classifier):* Determine the best value of K for the built-in KNN model.
- *Normalized Data:* Repeat the process using normalized data.
- *Building KNN from Scratch:* Implement the KNN algorithm from scratch and repeat the process.
- *Comparison:* Compare the performance of the `sklearn` KNN and the custom-built KNN.

## Results
Detailed results and visualizations are provided within the notebook, including accuracy metrics and comparison plots.
