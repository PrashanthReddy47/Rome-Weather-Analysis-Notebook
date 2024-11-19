# Rome Weather Analysis Project

## Overview

A comprehensive analysis of Rome's historical weather patterns from 1950 to 2022, examining temperature trends, precipitation patterns, and climate change indicators through statistical analysis and machine learning approaches.

## Quick Links

- [Interactive Dashboard](https://your-dashboard-url-here)
- [Complete Jupyter Notebook](https://github.com/your-repo/rome-weather-analysis/blob/main/analysis.ipynb)
- [Dataset](https://github.com/your-repo/rome-weather-analysis/blob/main/Roma_weather.csv)

## Key Findings

### Temperature Trends and Patterns

![Temperature trends in Rome from 1950-2022](https://hebbkx1anhila5yf.public.blob.vercel-storage.com/Temperature%20Trends-sVGqITSv8of8ScUyZdhNjltVGtv0ui.png)

The analysis reveals significant temperature patterns in Rome:
- Clear seasonal temperature cycles
- Long-term warming trend visible in the data
- Monthly temperature distribution shows peak temperatures in July-August
- Significant temperature variations between seasons

### Precipitation Analysis

![Monthly precipitation patterns in Rome](https://hebbkx1anhila5yf.public.blob.vercel-storage.com/monthly_precipitation-PtuzTOiMacbRNn4PQqH8H2aX6dhzUp.png)

Key precipitation findings include:
- Highest rainfall typically occurs in February (~225mm)
- Driest month is September (~5mm)
- Clear seasonal precipitation pattern
- Notable year-to-year variability in rainfall amounts

### Variable Correlations

![Correlation heatmap of weather variables](https://hebbkx1anhila5yf.public.blob.vercel-storage.com/correlation_heatmap-ruOXDTvMA9sz9xCndXfBwXarPwyqx0.png)

The correlation analysis shows:
- Strong positive correlation (0.99) between average and maximum temperatures
- Strong positive correlation (0.98) between average and minimum temperatures
- Weak negative correlation (-0.35) between precipitation and temperature variables

### Comprehensive Analysis Dashboard

![Comprehensive weather analysis dashboard](https://hebbkx1anhila5yf.public.blob.vercel-storage.com/comprehensive_weather_analysis-DfPjPeuadfAw2QiWtJA8Yg4nuNs7Cu.png)

The dashboard provides:
- Long-term temperature trends
- Temperature distribution analysis
- Monthly temperature patterns with standard deviation
- Average monthly precipitation
- Temperature vs. precipitation relationships
- Special weather conditions frequency
- Model performance comparisons
- Prediction error distributions

## Technical Details

### Analysis Techniques
- Time series analysis
- Seasonal decomposition
- Statistical testing (Mann-Kendall, Shapiro-Wilk)
- Machine learning models (Random Forest, Linear Regression)
- Data visualization using matplotlib, seaborn

### Model Performance
The analysis included multiple machine learning models:
- Linear Regression (R² = 0.884)
- Ridge Regression (R² = 0.884)
- Lasso Regression (R² = 0.838)
- Random Forest (R² = 0.918)

## Data Source
The analysis uses the 'Roma_weather.csv' dataset, containing daily weather records from 1950 to 2022, including:
- Average temperature (TAVG)
- Maximum temperature (TMAX)
- Minimum temperature (TMIN)
- Precipitation (PRCP)