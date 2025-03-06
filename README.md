Overview

This project focuses on predicting customer churn using machine learning techniques. The model is built using an Artificial Neural Network (ANN) implemented with Keras and TensorFlow. The dataset undergoes preprocessing, including one-hot encoding of categorical variables and train-test splitting.

Features

Data Preprocessing (handling categorical variables, normalization)

Train-test split for model evaluation

ANN model implementation using Keras/TensorFlow

Model training and performance evaluation

Requirements

Ensure you have the following dependencies installed:

Python 3.x

Jupyter Notebook

pandas

numpy

scikit-learn

TensorFlow

Keras

You can install the required libraries using:

pip install pandas numpy scikit-learn tensorflow keras

Usage

Open the Jupyter Notebook:

jupyter notebook Customer_Churn_Pred.ipynb

Run the cells step by step to preprocess data, build the ANN, and evaluate model performance.

Dataset

The dataset contains customer-related features such as demographics and transaction history. It is processed using one-hot encoding for categorical variables and normalized for optimal model training.

Model Architecture

Input Layer: Preprocessed customer data

Hidden Layers: Multiple dense layers with activation functions

Output Layer: Binary classification (Churn/No Churn)

Loss Function: Binary Crossentropy

Optimizer: Adam

Evaluation

The model is evaluated using accuracy, precision, recall, and other metrics to measure its effectiveness in predicting customer churn.

License

This project is open-source and free to use for educational and research purposes.

