# Covid-19 Analysis

This repository contains a Jupyter Notebook that performs an exploratory data analysis (EDA) on the COVID-19 pandemic data. The analysis aims to investigate the relationship between various socio-economic factors and the maximum infection rate of COVID-19 across different countries.

## Data Sources

The analysis utilizes two datasets:

1. **COVID-19 Confirmed Cases Dataset**: This dataset contains information on the confirmed COVID-19 cases across different countries and regions over time.

2. **World Happiness Report Dataset**: This dataset provides information on various socio-economic factors, such as GDP per capita, social support, healthy life expectancy, and freedom to make life choices for different countries and regions.

## Analysis Steps

The analysis follows these steps:

1. **Data Loading**: The necessary Python libraries (NumPy, Pandas, Seaborn, and Matplotlib) are imported, and the datasets are loaded into Pandas DataFrames.

2. **Data Preprocessing**: The COVID-19 dataset is preprocessed by removing unnecessary columns and aggregating the data by country.

3. **Exploratory Data Analysis**: The COVID-19 data is visualized for selected countries to understand the trend of confirmed cases over time.

4. **Feature Engineering**: A new feature, "max_infection_rate," is created by calculating the maximum daily increase in confirmed cases for each country.

5. **Data Merging**: The COVID-19 dataset and the World Happiness Report dataset are merged based on the country or region column, creating a combined dataset for analysis.

6. **Correlation Analysis**: The correlation between the "max_infection_rate" and various socio-economic factors (GDP per capita, social support, healthy life expectancy, and freedom to make life choices) is analyzed.

7. **Visualization**: Scatter plots and regression plots are created to visualize the relationship between the "max_infection_rate" and the socio-economic factors.

## Key Findings

The analysis reveals a positive correlation between the maximum infection rate of COVID-19 and the following socio-economic factors:

- GDP per capita
- Social support
- Healthy life expectancy
- Freedom to make life choices

These findings suggest that countries with higher socio-economic development tend to have higher maximum infection rates during the COVID-19 pandemic.
