# Breast-Cancer-Classification-Model-Using-Neural-Networking

A deep learning–based predictive modeling project that classifies breast cancer tumors as malignant or benign based on diagnostic medical features.


**Description**

Breast Cancer Classification using Deep Learning aims to assist early and accurate diagnosis of breast cancer by analyzing patient diagnostic data.
This project leverages a Neural Network model to predict whether a tumor is malignant (cancerous) or benign (non-cancerous) based on multiple cellular and structural characteristics.

By using deep learning techniques, the model automatically learns complex relationships among features, helping to build an intelligent, data-driven healthcare prediction system.
Such models can significantly improve early detection accuracy and support oncologists in making faster and more reliable clinical decisions.

**Tech Stack**


This project uses the following tools and technologies:

Python – data processing, model development, and evaluation

Pandas  – data cleaning and feature engineering

Matplotlib  – data visualization and exploratory analysis

Scikit-learn – preprocessing and performance evaluation

TensorFlow & Keras  – designing and training the Neural Network model

Jupyter Notebook – experimentation, testing, and model documentation


**Data Source**


Source: Breast Cancer Wisconsin Dataset (CSV)

The dataset includes multiple diagnostic attributes derived from cell nuclei images, such as:

Mean Radius

Mean Texture

Mean Smoothness

Mean Compactness

Mean Concavity

Mean Symmetry

Mean Fractal Dimension

Diagnosis Label: Malignant / Benign

This dataset helps understand key cellular characteristics and provides input for predictive modeling to classify tumor types accurately.

**Features**


• **Business Problem**

Breast cancer remains one of the most common and life-threatening diseases among women worldwide.
Traditional diagnostic methods often require significant human expertise and time. There is a growing need for an automated deep learning system that can classify tumors quickly and accurately, assisting healthcare professionals in early diagnosis.


• **Goal of the Project**


To build a Deep Learning Neural Network model that can:

Accurately classify tumors as Malignant or Benign

Learn important diagnostic feature patterns automatically

Enhance medical decision-making through AI-powered insights


•**Deep Learning Modelling & Flow**

Data Understanding & Cleaning

Exploratory Visualizations & Correlation Analysis

Feature Scaling & Normalization

Model Building using TensorFlow/Keras Neural Network

Input layer with normalized features

Hidden layers with ReLU activation

Output layer with Sigmoid activation (for binary classification)

Model Training & Evaluation

Evaluated using Accuracy

Optimization & Fine-Tuning

Adjusted network architecture, batch size, and epochs

Used regularization and dropout to reduce overfitting

Model Saving & Deployment Preparation


• **Business Impact & Value**


Enables early and accurate breast cancer detection

Supports medical professionals in clinical decision-making

Reduces diagnosis time and human error through automation

Improves predictive healthcare analytics and research efficiency

Demonstrates how Deep Learning can transform real-world healthcare problems
