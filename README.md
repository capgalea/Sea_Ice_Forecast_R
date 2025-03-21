# Sea Ice Forecast R

A repository containing R scripts for analyzing and forecasting Arctic sea ice extent. 

## Overview

This repository contains code for developing, training, and evaluating sea ice forecasting models using R. The forecasting models are designed to predict Arctic sea ice extent, an important climate indicator that has significant implications for global climate patterns, Arctic ecosystems, and human activities in the region. The seasonal ice covering the Arctic is becoming less extensive, younger and thinner. Observations were obtained from satellite data and drifting buoys which measure the formation, movement, persistence and disappearance of sea ice.

![image](https://github.com/user-attachments/assets/8cd14a49-4e96-4142-80af-f8c348b38256)

## Repository Structure

- `data/`: Contains datasets used for model training and evaluation
- `scripts/`: R scripts for data preprocessing, model training, and visualization
- `outputs/`: Folder for storing model outputs and visualization results
- `functions/`: Helper functions used across different scripts

## Features

- Data preprocessing and cleaning of sea ice observations
- Implementation of statistical models for sea ice extent forecasting
- Time series analysis tools for seasonal and trend decomposition
- Visualization functions for displaying sea ice extent and model predictions
- Cross-validation frameworks for model evaluation

## Getting Started

### Prerequisites

- R (version 3.6 or higher recommended)
- Required R packages (install using `install.packages()`):
  - tidyr
  - TSA
  - tseries
  - FSAdata
  - forecast
  - fUnitRoots
  - lmtest
  - dplyr
  - CombMSC
  - AID
  - nortest

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/capgalea/Sea_Ice_Forecast_R.git
   ```
2. Navigate to the project directory:
   ```
   cd Sea_Ice_Forecast_R
   ```
3. Install required R packages if not already installed:
   ```R
   install.packages(c("tidyr", "TSA", "tseries", "FSAdata", "forecast", "fUnitRoots", "lmtest", "dplyr". "CombMSC", "AID", "nortest"))
   ```

## Usage

1. Start with the data preprocessing scripts to prepare the sea ice datasets
2. Run model training scripts to develop forecast models
3. Use evaluation scripts to assess model performance
4. Generate visualizations to interpret results

Example workflow:
```R
# Load the required libraries
source("functions/load_libraries.R")

# Preprocess sea ice data
source("scripts/preprocess_sea_ice_data.R")

# Train forecast models
source("scripts/train_models.R")

# Evaluate model performance
source("scripts/evaluate_models.R")

# Generate visualizations
source("scripts/visualize_results.R")
```

## Data Sources

The models use sea ice concentration data from various sources including:
- National Oceanic and Atmospheric Administration (NOAA, https://www.ncei.noaa.gov/products/arctic-antarctic-products-data-information/arctic)

## Contributing

Contributions to improve the forecasting models or extend the functionality are welcome:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

Charles Galea - [@capgalea](https://github.com/capgalea)

Project Link: [https://github.com/capgalea/Sea_Ice_Forecast_R](https://github.com/capgalea/Sea_Ice_Forecast_R)

## Acknowledgments

- National Snow and Ice Data Center for providing sea ice data
- The R community for developing powerful packages for statistical analysis
- Climate researchers whose work has informed the development of these models
