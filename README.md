
# Weather Data Analysis Project

## Summary

Analysing weather data using Python in Jupyter Notebook to uncover patterns, trends and insights from meteorological measurements.




## About the Dataset

Source: Kaggle 

Time Period: Jan 2012 - September 2012 (hour-wise)

Records: 8784 rows 

Key Features: Temperature, Dew Point Temperature, Relative Humidity, Wind Speed (kmph), 
Visibility (kmph), Pressure(Kpa), Weather Condition
## Data Transformation

- Aggregated data by time periods (daily, monthly averages)
- Standardized column names and data formats
- Converted date/time fields to proper datetime objects





## Analysis & Visualizations

- Daily Temperature Patterns: Analyzed what an average day's temperature looks like

- Seasonal Trends: Examined temperature variations across different seasons

- Weather Factor Correlations: Heatmap showing relationships between all weather variables

- Wind Speed Distribution: Pie chart showing percentage of days by wind speed ranges

- Weather Frequency: Bar chart showing how often each weather condition occurred




## Key Insights

1) Humidity & Precipitation: Average humidity on rainy days was 83.31%

2) Visibility Patterns: Visibility was poorest on days with snow

3) Low Visibility Conditions: When visibility was low:

- Average dew point temperature: -2.10°C

- Average temperature: -0.47°C

- Average relative humidity: 88.76%

4) Strong Correlations: Temperature and dew point show the strongest relationship

5) Wind Patterns: Most days had wind speeds below 15 km/h

6) Sky Conditions: Majority of days were either clear or cloudy
## Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)

- Jupyter Notebook in VS Code

- Statistical Analysis libraries


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
