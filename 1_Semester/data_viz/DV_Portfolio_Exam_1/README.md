# Visualization Challenge

## Overview
This project, created by Regis Funke, is a comprehensive analysis of the Happy Planet Index (HPI) using data visualization techniques. The project is structured as a series of tasks, each focusing on different aspects of the data. The primary goal is to explore and visualize the relationships between various factors like GDP per capita, life expectancy, experienced wellbeing, ecological footprint, and their impact on the Happy Planet Index.

## Data Source
The data for this project is sourced from the [Happy Planet Index website](https://happyplanetindex.org), which provides an alternative to mainstream indicators of ecological growth. The Happy Planet Index is computed from three variables: life expectancy, experienced wellbeing, and ecological footprint.

## Tools and Libraries Used
- R Language
- Tidyverse
- sf (Simple Features for R)
- rnaturalearth
- GGally
- Plotly
- Viridis

## Tasks and Analysis

### Task 1: Visualizing Relationships (2019 Data)
- Focus: Relationships between `gdp_capita`, `experienced_wellbeing`, `footprint`, `life_expectancy`, and `hpi`.
- Method: Correlation matrix and scatter plots with annotations.
- Insights: Examines the correlation between different variables and the Happy Planet Index, highlighting the lack of correlation between GDP per capita and HPI, among other findings.

### Task 2: Zimbabwe's HPI Evolution (2006-2020)
- Focus: Time series analysis of Zimbabwe's HPI and related factors.
- Method: Line plots showing percentage changes over time.
- Insights: Observes two distinct periods in Zimbabwe's HPI history, analyzing the impact of life expectancy, experienced wellbeing, and ecological footprint on the HPI.

### Task 3: Global HPI Visualization (2019)
- Focus: Worldwide visualization of HPI.
- Method: Lambert azimuthal equal-area projection map.
- Insights: Presents a global view of the Happy Planet Index, with a focus on the country with the highest HPI in 2019.

### Task 4: HPI Distribution by Continent
- Focus: Comparative analysis of HPI across continents.
- Method: Violin plots.
- Insights: Compares the mean and distribution of HPI across different continents, revealing interesting patterns and outliers.

## Conclusion
This project provides a deep dive into the Happy Planet Index, offering valuable insights into how various factors correlate with happiness and sustainability across different countries and continents. It stands as a testament to the power of data visualization in understanding complex datasets.

## Repository Structure
- R Markdown files containing the analysis code and comments.
- CSV files with the Happy Planet Index data.
- Additional resources and references.

## How to Use
1. Clone the repository.
2. Open the R Markdown files in an R environment.
3. Install the required libraries.
4. Run the code to reproduce the analysis and visualizations.

## Author
Regis Funke

## License
This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments
Thanks to the Happy Planet Index for providing the data used in this project.
