# Data Visualization Project: Analyzing Inflation Trends

## Overview
This project, part of a data sciences coursework, focuses on analyzing and visualizing inflation trends using data from DESTATIS (German Federal Office of Statistics). The project is hosted on GitHub and comprises two main components: a Python notebook for data preparation (`DV_data_prep.ipynb`) and an R Markdown document for data visualization and analysis (`DV_Exam_2.Rmd`).

## Data Preparation (`DV_data_prep.ipynb`)
The Python notebook is responsible for fetching, cleaning, and preparing the data for visualization. Key steps in the data preparation process include:

- Fetching data from DESTATIS using their API, with a fallback on stored XML and Excel files due to API reliability issues.
- Parsing and cleaning the data, including renaming columns, handling missing values, and normalizing data formats.
- Converting date-related columns into a datetime format and setting them as indices.
- Calculating year-over-year inflation rates and changes in percentage.
- Saving the cleaned and transformed data into CSV files for further analysis.

## Data Visualization and Analysis (`DV_Exam_2.Rmd`)
The R Markdown document provides a comprehensive analysis of the inflation trends using the prepared data. Key aspects include:

- **Technical Setup & Data Ingestion**: Utilizing libraries like `tidyverse` and `plotly` for data manipulation and visualization.
- **Historical Development of Inflation**: Visualizing the overall inflation trend since 1991, highlighting significant economic events.
- **Continuous Price Development in Consumer Spending Categories**: Analyzing specific categories of consumer spending to understand their contribution to overall inflation.
- **Cyclical Price Development in Consumer Spending Categories**: Investigating seasonal or cyclical trends in categories like clothing and leisure.
- **Conclusion**: Summarizing the findings, especially focusing on the impact of inflation on different consumer segments and potential strategies for coping with rising prices.

## How to Use
1. Clone the repository to get access to the `.ipynb` and `.Rmd` files.
2. Run the `DV_data_prep.ipynb` notebook to prepare the data. Ensure you have Python installed with required libraries (`pandas`, `numpy`, etc.).
3. Open `DV_Exam_2.Rmd` in an R environment (like RStudio) to view the analysis and visualizations. Required R packages (`tidyverse`, `plotly`, etc.) should be installed.
4. You can modify the code to focus on different aspects of the data or to update the analysis with new data.

## Dependencies
- Python (with `pandas`, `numpy`)
- R (with `tidyverse`, `plotly`)
- Access to DESTATIS data (either via API or downloaded files)

## Contributing
Contributions to this project are welcome. Please open an issue or a pull request with your suggestions or improvements.

## License
This project is open-source and available under the [MIT License](LICENSE).
