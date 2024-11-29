# CS3
This Github repository contains all of the information needed in order to replicate my project that used time series modeling to forecast future trends in air travel.

## Section 1: Software & Platform
The main software used for this project includes VS Code with Python. We used Python's Statsmodels library with SARIMA (Seasonal Autoregressive Integrated Moving Average), a forecasting model for time series data with a seasonal element.

The original code for this project was completed on a Windows machine, and reran on a Mac for the purposes of this case study.

## Section 2: Map of Documentation
### Project Folder Structure:
```
CS3/
│
├── MATERIALS/
│   ├── DATA
│   │ ├── cleaned_Air_Traffic_Data.csv
│   │ ├── air-traffic-passenger-statistics.csv
│   │ ├── monthly_passenger_data.csv
│   │ └── monthly_passenger_data_diff.csv
│   ├── EXAMPLECODE
│   │ ├── 1-InitialDataCleaning.py
│   │ ├── 2-InitialDataPlots.py
│   │ ├── 3-DataPreparationAggregation.py
│   │ ├── 4-StationarityDifferencingAnalysis.py
│   │ ├── 5-SARIMAModelFittingForecasting.py
│   │ └── StationaritySeasonalityAnalysis.cpython-36.pyc
│   ├── EXAMPLEPLOTS
│   │ ├── ACF_Of_Residuals.png
│   │ ├── Monthly_Adjusted_Passenger_Count.png
│   │ ├── SARIMA_Model_Forecast.png
│   │ ├── SARIMA_Model_Forecast_Extended.png
│   │ ├── Stationary_Differenced_Time_Series.png
│   │ └── domestic_vs_international.png
│   └── motivation
│
├── RUBRIC&HOOK/
│   ├── Hook.pdf
│   └── Rubric.pdf
│  
├── LICENSE.md
└── README.md
```
- **MATERIALS/**:
  - The materials folder contains three subfolders: data, example code, and example plots. Contained in all of the folders is all of the data and code you would need to execute the
    project. The example plots folder provides you with ideas of what your exploratory and final plots should look like. There is also some information in this folder that further
    contextualizes the project. Be sure to also check out the references for additional information.
- **RUBRIC&HOOK/**:
  - This is where you will find the hook document to inform you of the context of the project, as well as the rubric that should answer all questions regarding the successful execution
    of this project.

## References You Will Need
[1] “Air Traffic Passenger Statistics: DataSF: City and county of San Francisco,” Air Traffic Passenger Statistics | DataSF | City and County of San Francisco, https://data.sfgov.org/Transportation/Air-Traffic-Passenger-Statistics/rkru-6vcg

[2] “Air Traffic Passenger Data - dataset by data-society,” data.world, https://data.world/data-society/air-traffic-passenger-data/workspace/project-summary?agentid=data-society&datasetid=air-traffic-passenger-data

[3] “Predictive User Experience :: UXmatters,” www.uxmatters.com. https://www.uxmatters.com/mt/archives/2017/06/predictive-user-experience.php

[4] GeeksforGeeks. (2024, May 24). Sarima (seasonal autoregressive integrated moving average). https://www.geeksforgeeks.org/sarima-seasonal-autoregressive-integrated-moving-average/

[5] Ahmed, I. (2023, May 31). What are ACF and PACF plots in time series analysis?. Medium. https://ilyasbinsalih.medium.com/what-are-acf-and-pacf-plots-in-time-series-analysis-cb586b119c5d

[6] The Akaike Information Criterion. Statistical Modeling and Forecasting. (2024, June 23). https://timeseriesreasoning.com/contents/akaike-information-criterion/

[7] Jonatasv. (2024, February 26). Metrics evaluation: MSE, RMSE, Mae and mape. Medium. https://medium.com/@jonatasv/metrics-evaluation-mse-rmse-mae-and-mape-317cab85a26b
