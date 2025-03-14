
# Weather Trend Forecasting

This project focuses on analyzing historical weather data, performing exploratory data analysis (EDA), and building forecasting models to predict future weather trends. The goal is to understand patterns in weather data and evaluate the performance of different forecasting models.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Methodology](#methodology)
   - [Data Cleaning](#data-cleaning)
   - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
   - [Forecasting Models](#forecasting-models)
   - [Advanced Analyses](#advanced-analyses)
4. [Results and Insights](#results-and-insights)
5. [Visualizations](#visualizations)
6. [How to Run the Code](#how-to-run-the-code)
7. [Dependencies](#dependencies)
8. [Contributing](#contributing)


---

## Project Overview

This project aims to analyze historical weather data to identify trends and patterns. Using this data, we build forecasting models to predict future weather conditions. The project includes data cleaning, exploratory data analysis (EDA), and the evaluation of multiple forecasting models.

---

## Dataset

The dataset used in this project contains historical weather data, including:
- **Date**: The date of the weather record.
- **Temperature**: Daily average temperature.
- **Precipitation**: Daily precipitation levels.
- **Humidity**: Daily average humidity.
- **Wind Speed**: Daily average wind speed.



---

## Methodology

### Data Cleaning
- **Handling Missing Values**: Missing data was addressed by either imputing values or dropping incomplete records.
- **Outlier Detection**: Outliers were identified and handled using statistical methods (e.g., Z-scores or IQR).
- **Data Normalization**: Numerical features were normalized to ensure consistency across the dataset.

### Exploratory Data Analysis (EDA)
- **Trend Analysis**: Visualized trends in temperature, precipitation, humidity, and wind speed over time.
- **Seasonality Analysis**: Identified seasonal patterns in weather data.
- **Correlation Analysis**: Explored relationships between different weather variables using correlation matrices and heatmaps.

### Forecasting Models
- **ARIMA (AutoRegressive Integrated Moving Average)**: Used for time series forecasting of temperature and precipitation.
- **Prophet**: A forecasting tool developed by Facebook for time series data with seasonality.
- **Linear Regression**: A baseline model for predicting weather variables based on historical data.
- **Random Forest Regression**: A machine learning model used for more complex predictions.

### Advanced Analyses
- **Cross-Validation**: Evaluated model performance using time-series cross-validation.
- **Hyperparameter Tuning**: Optimized model parameters using grid search and random search.
- **Model Evaluation**: Compared models using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared.

---

## Results and Insights

- **Trends**: Identified a gradual increase in average temperature over the years, indicating potential climate change effects.
- **Seasonality**: Strong seasonal patterns were observed in temperature and precipitation.
- **Model Performance**: The ARIMA model performed best for temperature forecasting, while Prophet was more effective for precipitation predictions.
- **Key Insights**: Humidity and wind speed showed weaker correlations with temperature, suggesting they are less influential in predicting temperature trends.

---

## Visualizations

Below are some key visualizations from the analysis:

### 1. Temperature Trends Over Time
![Temperature Trends](images/temperature_trends.png)

### 2. Seasonal Patterns in Precipitation
![Seasonal Precipitation](images/seasonal_precipitation.png)

### 3. Correlation Heatmap
![Correlation Heatmap](images/correlation_heatmap.png)

### 4. Model Performance Comparison
![Model Performance](images/model_performance.png)

---

## How to Run the Code

1. Clone the repository:
   ```bash
   git clone https://github.com/sid150/Weather-Trend-Forecating.git
   cd Weather-Trend-Forecating
   ```

2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Weather_Trend_Forecasting.ipynb
   ```

3. Run the notebook cells to reproduce the analysis and visualizations.

---

## Dependencies

The project requires the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `statsmodels`
- `fbprophet`
- `scikit-learn`

Install them using:
```bash
pip install pandas numpy matplotlib seaborn statsmodels fbprophet scikit-learn
```

---


## Mission
By making industry-leading tools and education available to individuals from all backgrounds, we level the playing field for future PM leaders. This is the PM Accelerator motto, as we grant aspiring and experienced PMs what they need most – Access. We introduce you to industry leaders, surround you with the right PM ecosystem, and discover the new world of AI product management skills.

