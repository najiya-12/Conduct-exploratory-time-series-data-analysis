# Exploratory Data Analysis (EDA) Project

## Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on multiple open datasets obtained through various sources, including **APIs, CSV files, and JSON data**. Each dataset is analyzed in a separate Jupyter Notebook, with a unique focus on extracting meaningful insights through data exploration and visualization.

## Data Sources

The project utilizes three different datasets, each representing a unique domain:

1. **Carbon Intensity Data (API Source)**
   - The data is obtained via the **Carbon Intensity API**.
   - The API provides real-time and historical carbon intensity metrics, which can help assess energy sustainability.
   - Data is retrieved and processed into **Pandas DataFrames** for further analysis.
2. **Solar Radiation Data (CSV Source)**
   - This dataset is sourced from the **National Solar Radiation Database (NSRDB)**.
   - It contains **hourly** meteorological data and solar radiation metrics, including:
     - **Global Horizontal Irradiance (GHI)**
     - **Direct Normal Irradiance (DNI)**
     - **Diffuse Horizontal Irradiance (DHI)**
   - The dataset is loaded into Pandas DataFrames and analyzed for solar energy trends.
3. **Ocean Observations Data (JSON Source)**
   - The data is retrieved from the **Ocean Observatories Initiative (OOI)**.
   - The dataset consists of **minute-resolution** **Sea Surface Temperature (SST)** measurements from deployed buoys.
   - The dataset helps in understanding ocean ecosystems and the long-term impacts of climate change.

## Methodology

### 1. Data Acquisition

- Data is downloaded using APIs, CSV files, and JSON formats.
- The data is loaded into **Pandas DataFrames** for processing.

### 2. Exploratory Data Analysis (EDA)

Each dataset is analyzed to answer **key questions** related to trends, anomalies, and insights. EDA includes:

- Checking for missing values and handling them appropriately.
- Performing **statistical summaries** of numerical features.
- Identifying **patterns and trends** over time.

### 3. Visualization with Matplotlib

To effectively communicate findings, the project includes visual representations such as:

- **Line plots** for time series analysis.
- **Scatter plots** to observe correlations.
- **Bar charts** for categorical comparisons.
- **Histograms** to analyze data distributions.

## Key Insights

- **Carbon Intensity Data**: Analysis of carbon footprint variations across different regions and time periods.
- **Solar Radiation Data**: Understanding the influence of meteorological parameters on solar energy availability.
- **Ocean Observations Data**: Examining sea surface temperature fluctuations and potential climate change impacts.

## Conclusion

This project demonstrates the process of retrieving, processing, and analyzing real-world data from open sources. It provides insights into energy sustainability, solar radiation trends, and oceanic temperature variations, showcasing the importance of data exploration in scientific and environmental research.

## Requirements

To run the analysis, ensure you have the following dependencies installed:

```bash
pip install pandas matplotlib requests json
```

## References

- [Carbon Intensity API](https://carbon-intensity.github.io/api-definitions/)
- [National Solar Radiation Database (NSRDB)](https://nsrdb.nrel.gov/)
- [Ocean Observatories Initiative (OOI)](https://dataexplorer.oceanobservatories.org/#)

## Repository Structure



This project provides a structured approach to **data exploration**, helping derive valuable insights from diverse datasets!

