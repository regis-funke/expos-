# Credit Compliance Prediction Project

## Overview
This project aims to develop a statistical model to predict whether bank customers will fully repay their credit or default on their credit obligations. The analysis is based on anonymized data from 1000 bank customers. The project involves exploratory data analysis and the application of various machine learning techniques for classification.

## Data
The dataset comprises anonymized information of 1000 customers from a bank. It includes 21 features, with 17 categorical and 3 numerical attributes. The target variable is the credit compliance status of the customers.

### Features
- **Account Status, Contract Duration, Credit History, Purpose, Credit Amount, Savings, Employment Duration, Installment Rate, Other Installment Plans, Age, etc.**
- The categorical attributes are already encoded into ordinal values.
- The dataset includes both descriptive statistics and a detailed explanation of each feature.

## Methodology

### Exploratory Data Analysis
- The data is first inspected and prepared for visualization.
- Correlation analysis is conducted to understand the relationships between different features.
- Various plots (box plots, bar charts, histograms) are used to visualize the distribution and relationship of features with the target variable.

### Machine Learning
Three classes of classifiers are used:
1. **K-Nearest Neighbors (KNN)**
2. **Decision Tree**
3. **Support Vector Classifier (SVC)**

#### Data Preparation
- The data is shuffled and split into features and target labels.
- StandardScaler is used for feature scaling.

#### Nested Cross-Validation
- Nested cross-validation is implemented for model selection and evaluation.
- GridSearchCV is used for hyperparameter tuning.
- Performance metrics such as accuracy, balanced accuracy, and confusion matrix values are calculated.

#### Results
- The performance of each model is evaluated based on accuracy and balanced accuracy.
- The best performing model is identified based on these metrics.
- A confusion matrix is constructed to understand the model's performance in terms of false positives and negatives.

## Conclusion
- The best performing model is the Support Vector Machine with a polynomial kernel.
- The model's accuracy and balanced accuracy are compared against a baseline to assess its effectiveness.
- The confusion matrix provides insights into the model's predictive capabilities in a real-world scenario.

## Usage
To run the analysis:
1. Clone the repository.
2. Ensure all dependencies are installed.
3. Run the Jupyter Notebook to see the analysis and results.

## Dependencies
- Python libraries: Pandas, NumPy, Scikit-learn, Plotly Express, Matplotlib.

## License
This project is licensed under the [MIT License](LICENSE.md).
