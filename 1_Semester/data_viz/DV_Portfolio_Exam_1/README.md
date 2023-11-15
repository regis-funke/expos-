# Visualization Challenge

## Project Overview

This project, authored by Regis Funke, focuses on creating insightful and aesthetically pleasing visualizations of the Happy Planet Index (HPI) data. The HPI, an alternative to GDP, measures well-being and sustainability. This repository contains R scripts and data for visualizing various aspects of the HPI, using data from [Happy Planet Index](https://happyplanetindex.org).

### Key Objectives:
1. Reveal relationships between multiple variables in the HPI dataset.
2. Analyze the evolution of Zimbabwe's HPI over time.
3. Visualize HPI data on a world map with a specific projection.
4. Show the distribution of HPI per continent.

## Installation

Before running the scripts, ensure you have R installed along with the following packages:
- `tidyverse`
- `sf`
- `rnaturalearth`
- `GGally`
- `plotly`
- `viridis`

## Data Source

The data is sourced from the Happy Planet Index website and includes variables like life expectancy, experienced wellbeing, ecological footprint, and GDP per capita.

## Structure

- `happy-planet-index.csv`: The main dataset used for the analyses.
- `R Scripts`: Contains all the R scripts to generate visualizations.
  - `Setup.R`: Script for setting up the environment and loading necessary packages.
  - `Task1.R`: Script for visualizing relationships between variables for the year 2019.
  - `Task2.R`: Script for analyzing Zimbabwe's HPI evolution.
  - `Task3.R`: Script for mapping HPI data on a world map.
  - `Task4.R`: Script for visualizing HPI distribution per continent.

## Usage

Each script in the `R Scripts` folder corresponds to a specific task. Run these scripts in R to generate the visualizations. The scripts contain detailed comments explaining each step of the analysis.

## Contributing

Contributions to enhance the project are welcome. Please fork the repository and submit a pull request for review.

## License

This project is open-source and available under the MIT License.

## Contact

For any queries or suggestions, please reach out to Regis Funke at [regisfunke@example.com](mailto:regisfunke@example.com).

## Acknowledgements

Special thanks to the Happy Planet Index community for providing an insightful dataset that enables a deeper understanding of global well-being beyond economic metrics.
