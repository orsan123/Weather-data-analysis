
# Weather Data Analysis Project

## Summary

Analysis of 8,784+ hourly weather records using Python to uncover meteorological patterns and relationships between key climate variables.





## Project Objectives

- Identify relationships between weather variables
- Analyze seasonal patterns and trends  
- Understand conditions leading to poor visibility
- Build foundational data analysis skills with real-world dataset
## About the Dataset

Source: Kaggle 

Time Period: Jan 2012 - September 2012 (hour-wise)

Records: 8784 rows 

Key Features: Temperature, Dew Point Temperature, Relative Humidity, Wind Speed (kmph), 
Visibility (kmph), Pressure(Kpa), Weather Condition
## Data Transformation

- Aggregated hourly data to daily and monthly averages for trend analysis
- Standardized column names for consistency across the dataset
- Converted timestamp strings to proper datetime objects for time series analysis
- Handled missing values and validated data integrity





## Analysis & Visualizations

- **Daily Temperature Patterns:** Analyzed what an average day's temperature looks like

- **Seasonal Trends:** Examined temperature variations across different seasons

- **Weather Factor Correlations:** Heatmap showing relationships between all weather variables

- **Wind Speed Distribution:** Pie chart showing percentage of days by wind speed ranges

- **Weather Frequency:** Bar chart showing how often each weather condition occurred




## Visualizations

![Weather Analysis Dashboard](/visualizations/temp_dew_point_scatter_plot.png)

*Correlation between Temperature and Dew Point Temperature*

## Key Insights

1. **Precipitation Indicators**: 83.31% average humidity on rainy days suggests humidity as a reliable rain predictor
2. **Safety Concerns**: Poor visibility during snow conditions highlights transportation risks
3. **Meteorological Relationships**: Strong temperature-dew point correlation confirms fundamental atmospheric principles
4. **Weather Patterns**: Predominance of clear/cloudy days with light winds characterizes the regional climate
## Technologies


**Python | Pandas | NumPy | Matplotlib | Seaborn | Jupyter Notebook**
## Tools Used

- **Python Libraries**: Pandas (data manipulation), NumPy (numerical computing), Matplotlib/Seaborn (visualization)
- **Development**: Jupyter Notebook, VS Code
- **Analysis**: Statistical analysis, correlation studies, trend analysis


## Key Skills Demonstrated

- **Data Cleaning**: Handling datetime conversion and data standardization
- **Exploratory Data Analysis**: Uncovering patterns and correlations
- **Data Visualization**: Creating informative charts and heatmaps
- **Statistical Analysis**: Drawing meaningful insights from numerical data
- **Problem Solving**: Addressing data quality issues and analytical challenges
## Structure

```

weather-analysis/
├── weather_analysis.ipynb
├── data/
│   └── weather_dataset.csv
├── images/
│   └── visualizations/
└── README.md

```
## Conclusion

This analysis successfully identified key weather patterns, including the strong temperature-dew point relationship and humidity's role as a rain predictor. The project demonstrates practical data analysis skills and the ability to derive meaningful insights from real-world datasets.
