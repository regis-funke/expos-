# Data Science Practice Projects

This repository hosts three machine learning projects, showcasing image classification techniques using Vision Transformer (ViT) models and PyTorch Lightning. Each project is a practice exercise in handling different datasets and image classification challenges.

## Project 1: CIFAR-10 Image Classification

### Overview
- **Objective**: Classify images from the CIFAR-10 dataset.
- **Methods**:
  - Data loading and splitting into training, validation, and test sets.
  - Image preprocessing using `ViTImageProcessor` and custom transforms.
  - Defining a PyTorch Lightning module for the ViT model.
  - Model training and evaluation, including accuracy measurement and confusion matrix visualization.

## Project 2: Dementia Image Classification

### Overview
- **Objective**: Classify images from a dementia dataset into various stages of severity.
- **Methods**:
  - Loading a subset of a dementia dataset.
  - Applying similar preprocessing steps as in Project 1.
  - Adapting the ViT model to classify images into different categories of dementia severity.
  - Training and evaluating the model with a focus on accuracy and loss metrics.

## Project 3: Snack Image Classification

### Overview
- **Objective**: Classify snack images into 20 different categories.
- **Methods**:
  - Loading and handling a custom snack dataset.
  - Image preprocessing and defining a ViT model suitable for the task.
  - Training the model with PyTorch Lightning and evaluating its performance.
  - Utilizing confusion matrices for a detailed analysis of the model's classification abilities.

## Technologies Used
- Python
- PyTorch
- PyTorch Lightning
- Transformers Library
- Sklearn (for evaluation metrics)

## Installation and Usage
- Clone this repository to access the project files.
- Install the required dependencies, including PyTorch, PyTorch Lightning, and Transformers.
- Each project folder contains scripts and Jupyter notebooks to train and evaluate the models.

## License
These projects are open-source and available for educational and practice purposes under standard open-source licenses.
