# Wind Power Forecasting

## Introduction
This project focuses on forecasting wind energy generation from a specific turbine over the next 15 days using comprehensive time series analysis. Accurate forecasting is essential for optimizing the operation of wind farms, ensuring a reliable supply of renewable energy, and balancing supply and demand in the increasingly renewable-focused power grid.

To achieve our forecasting objectives, we explore several modeling techniques including ARIMA (AutoRegressive Integrated Moving Average), Exponential Smoothing, and Random Forest. Each model is evaluated based on its predictive accuracy using various performance metrics.

## About the Dataset

### Context
This dataset pertains to a specific wind turbine, with the objective of predicting the wind power that could be generated over the next 15 days. A long-term wind forecasting technique is thus required to achieve accurate predictions.

### Content
The dataset includes various features related to weather conditions, turbine specifications, and rotor characteristics, collected from January 2018 to March 2020 at 10-minute intervals.

### Features
- **Weather Features:** Temperature, humidity, wind speed, atmospheric pressure, etc.
- **Turbine Features:** Turbine model, operational status, maintenance records, etc.
- **Rotor Features:** Rotor diameter, height, and other relevant specifications.

## Package Installation
To run this project, ensure that the following Python packages are installed:
bash pip install numpy pandas matplotlib seaborn scikit-learn statsmodels

## Data Loading
Data is loaded from CSV files containing information about wind energy generation and related factors. The dataset is examined for initial issues such as missing values, ensuring its integrity for further analysis.

## Initial Data Exploration
An exploratory data analysis (EDA) is performed to understand the dataset better, including data types, summary statistics, and identifying missing values.

## Data Preparation and Visualization
Data visualization is key to understanding trends and patterns. Correlation analysis is performed to identify relevant variables for the forecasting model. Missing values are handled using appropriate techniques to ensure data quality.

## Modeling
Machine learning models are built to predict energy generation based on the prepared dataset. The following models are implemented:
- ARIMA
- Exponential Smoothing
- Random Forest

## Model Evaluation
Models are evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score to determine their performance and accuracy in predictions.

## Conclusion and Next Steps
The analysis reveals that the Random Forest model significantly outperforms the others, yielding a mean absolute error (MAE) of just 13.77. This has important implications for the wind energy industry, as accurate forecasts can optimize operations and enhance grid stability.

Future research could incorporate more detailed meteorological data and datasets from multiple wind farms to further improve prediction accuracy.

## References
For more information on wind energy forecasting techniques, consider the following resources:
- [Hindawi: Modeling and Predicting Wind Power](https://www.hindawi.com/journals/mpe/2010/684742/)
- [ScienceDirect: Wind Power Forecasting](https://www.sciencedirect.com/science/article/abs/pii/S0925231201007020)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For inquiries, please contact richenapedro@gmail.com.
