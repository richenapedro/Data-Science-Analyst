# Wind Power Forecasting

## Overview
This project analyzes a dataset related to wind energy generation from a specific turbine with the goal of forecasting its energy output over the next 15 days. The analysis employs various time series modeling techniques to provide insights into factors influencing energy production. The ultimate aim is to optimize the operation of wind farms and contribute to a more reliable supply of renewable energy.

## Motivation
The motivation for this project arises from the increasing need for accurate renewable energy forecasting. As the reliance on wind energy grows, so does the importance of understanding how different factors affect energy generation. By analyzing this data, we can enhance operational efficiency and better integrate wind energy into the power grid.

## Dataset Features
The dataset contains various features related to weather conditions, turbine specifications, and rotor characteristics, collected from January 2018 to March 2020 at 10-minute intervals. Key features include:

- **Temperature**: Ambient temperature in degrees Celsius.
- **Humidity**: Relative humidity percentage.
- **Wind Speed**: Speed of the wind in meters per second.
- **Atmospheric Pressure**: Atmospheric pressure in hPa.
- **Turbine Model**: Type of turbine used.
- **Operational Status**: Indicates whether the turbine was operational.
- **Maintenance Records**: Details of any maintenance performed on the turbine.
- **Rotor Diameter**: Diameter of the rotor in meters.
- **Height**: Height of the turbine in meters.

## Source Information
The dataset is sourced from [insert source or dataset link if available], providing relevant data for wind energy generation analysis.

## Technical Aspects
In this project, I utilized the following technologies and tools:
- **Languages**: Python
- **Libraries**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, Statsmodels
- **Development Environment**: Jupyter Notebook
- **Data**: The dataset was obtained from [insert source or dataset link if available].

## Package Installation
To run this project, ensure that the following Python packages are installed:
bash pip install numpy pandas matplotlib seaborn scikit-learn statsmodels

## Data Loading
Data is loaded from CSV files that contain information about wind energy generation and related factors. Initial checks are performed to identify any missing values or data integrity issues.

## Initial Data Exploration
An exploratory data analysis (EDA) is conducted to better understand the dataset, including examining data types, summary statistics, and identifying any missing values.

## Data Preparation and Visualization
Data visualization plays a crucial role in identifying trends and patterns. Correlation analysis is performed to determine relevant variables for the forecasting model, and missing values are addressed to maintain data quality.

## Modeling
Machine learning models are developed to predict energy generation based on the prepared dataset. The following models are implemented:
- ARIMA (AutoRegressive Integrated Moving Average)
- Exponential Smoothing
- Random Forest

## Model Evaluation
Models are evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score to assess their predictive performance and accuracy.

## Conclusion and Next Steps
The analysis indicates that the Random Forest model significantly outperforms the other models, achieving a mean absolute error (MAE) of just 13.77. This finding has important implications for the wind energy sector, as accurate forecasting can optimize operations and enhance grid stability.

Future work could focus on incorporating more detailed meteorological data and exploring additional datasets from multiple wind farms to further improve prediction accuracy.

## References
For more information on wind energy forecasting techniques, consider the following resources:
- [Hindawi: Modeling and Predicting Wind Power](https://www.hindawi.com/journals/mpe/2010/684742/)
- [ScienceDirect: Wind Power Forecasting](https://www.sciencedirect.com/science/article/abs/pii/S0925231201007020)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For inquiries, please contact richenapedro@gmail.com.
