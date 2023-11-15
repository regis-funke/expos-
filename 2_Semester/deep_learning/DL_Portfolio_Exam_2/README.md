# Data Science Coursework Project: Neural Network-Based Credit Default Prediction

## Project Overview
This project, a part of data science coursework, focuses on developing a neural network model to predict credit default. It extends our previous work with a bank, analyzing anonymized data from 1000 customers using machine learning and now neural networks. The aim is to improve the prediction accuracy for credit defaults.

## Contents and Methods

### Data Ingestion and Preprocessing
- Downloading and preprocessing data from the UCI Machine Learning Repository's South German Credit dataset.
- Initial exploratory data analysis and data preparation for visualization and machine learning.

### Exploratory Data Analysis
- Analysis of correlations between various features and credit default.
- Visualization of key variables like credit compliance, account status, credit amount, and debtor's age.

### Neural Network Modeling
- Implementation of a flexible multilayer perceptron model in PyTorch.
- Experimentation with various architectures to determine the most effective model structure.

### Class Imbalance Handling
- Analysis of class distribution in the dataset.
- Implementation of strategies like class weight adjustment to handle class imbalance.

### Hyperparameter Tuning and Model Evaluation
- Hyperparameter tuning using `ray.tune`.
- Evaluation of the model's performance on the test set.
- Comparison of neural network performance with previous machine learning models.

### Results and Findings
- Discussion on the performance improvement achieved by the neural network model compared to traditional machine learning approaches.
- Insights on the impact of different neural network architectures and hyperparameters on model accuracy.

## Technologies Used
- Python
- Libraries: Pandas, NumPy, Matplotlib, Plotly Express, PyTorch, ray.tune

## Installation and Usage
To replicate the analysis:
1. Install Python and the necessary libraries.
2. Clone the GitHub repository containing the project.
3. Run the Jupyter notebooks to execute the data analysis and model training.

## License
This project is made available under standard open-source licenses and is intended for educational purposes as part of data science coursework.
