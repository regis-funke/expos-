# Weather Pattern Analysis for Halle Tourist-Information

## Overview
This project, commissioned by the Halle Tourist-Information, focuses on analyzing the local weather conditions in Halle using data from the Saaleaue weather station. The primary goal is to identify characteristic weather patterns to aid in providing clothing recommendations for tourists.

## Data Source
- **Weather Data**: The analysis uses data for the year 2020 from the Saaleaue weather station.
  - [Weather Station Link](https://www.bgc-jena.mpg.de/wetter/)
  - [Weather Station Data Documentation](https://www.bgc-jena.mpg.de/wetter/Weatherstation.pdf)

## Methodology
### Data Preparation and Analysis
- **Ingesting Data**: Data for the entire year 2020 is loaded and concatenated into a single DataFrame.
- **Data Cleaning**: The dataset is cleaned by standardizing the date format, setting the index, and discarding invalid values.
- **Data Reduction**: The dataset is reduced to the most interpretable variables, such as temperature, wind speed, and solar radiation.
- **Resampling**: Data is resampled to a daily timeframe for interpretability and computational efficiency.
- **Standardization**: The data is standardized using the `StandardScaler` function.

### Clustering Analysis
- **KMeans Clustering**: The data is clustered using the KMeans algorithm. The optimal number of clusters is determined through inertia and silhouette coefficient analysis.
- **Gaussian Mixture Models (GMM)**: GMM clustering is performed as a complementary analysis to KMeans. Optimal number of components is determined using BIC, AIC, and silhouette scores.
- **Hierarchical Agglomerative Clustering (HAC)**: An alternative clustering approach is explored with HAC.

### Results Interpretation
- **Characteristic Weather Patterns**: The analysis identifies typical weather patterns such as autumn/winter days, sunny summer days, windy days, and summer thunderstorms.
- **Feature Distribution**: The distribution of key weather features across different clusters is visualized and interpreted.

## Technologies and Libraries Used
- Python
- Pandas
- Scikit-learn
- Plotly Express
- Numpy

## Installation and Usage
1. Clone the repository to your local machine.
2. Ensure that Python and the required libraries are installed.
3. Run the Jupyter Notebooks or Python scripts to view the analysis and results.

## Acknowledgements
Special thanks to the Halle Tourist-Information for providing the motivation for this project and to the providers of the Saaleaue weather station data.
