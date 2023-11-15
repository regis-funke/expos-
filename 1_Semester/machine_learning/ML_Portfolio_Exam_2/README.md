# Predictive Credit Compliance Analysis

## Project Overview
This project aims to analyze and predict credit compliance among bank customers using machine learning techniques. The task involves exploring whether certain features significantly influence credit compliance and employing different classification models to predict customer behavior.

## Customer and Task Description
- **Customer:** A bank providing anonymized data of 1000 customers.
- **Objective:** To create a statistical model that predicts which customers will fully pay back their credit and which will default on their credit obligations.

## Methodology
The project is structured into several phases, including data preparation, exploratory data analysis, and machine learning model training and testing.

### Preparation
- Libraries: `numpy`, `pandas`, `plotly_express`, `sklearn`
- Machine Learning Models: K-Nearest Neighbors (KNN), Decision Tree, Support Vector Classifier (SVC)

### Data Ingestion
- Data Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/00522/SouthGermanCredit.zip)
- Data consists of 21 features with a mix of categorical and numerical attributes.

### Exploratory Data Analysis
- Correlation analysis of variables.
- Visualization of distributions and relationships between various features and credit compliance.

### Machine Learning
- Baseline establishment for model performance comparison.
- Data preparation for machine learning including feature scaling and data splitting.
- Nested cross-validation for hyperparameter tuning and model evaluation.
- Performance comparison of KNN, Decision Tree, and SVC models using accuracy and balanced accuracy metrics.

## Results and Conclusion
- Best performing model: Polynomial kernel-based Support Vector Machine (SVM).
- The model provides predictions with higher accuracy compared to the established baseline.
- Confusion matrix analysis to understand model predictions.
- Suggestions for further improvements including incorporation of additional features and exploration of more complex models like neural networks.

## Usage
1. Ensure required Python libraries are installed.
2. Download and extract the dataset from the provided link.
3. Run the Jupyter Notebooks or Python scripts to replicate the analysis.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request for any enhancements or fixes.

## License
This project is open-source and available under standard open-source licenses.

## Contact
For any queries or suggestions related to this project, please reach out to [Your Contact Information].

## Acknowledgements
Special thanks to the UCI Machine Learning Repository for providing the dataset and to the community for resources that supported the understanding of machine learning algorithms.
