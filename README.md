ReDI_COVID19_Forecast_Project

Project Overview

This project analyses and forecasts COVID-19 case trends in Bangalore, India, using time-series modelling techniques.
The analysis focuses primarily on Active COVID-19 cases from September 2020 to February 2021 and and to apply time-series forecasting techniques to predict short-term case trends. The analysis supports better understanding of pandemic patterns and demonstrates practical skills in data cleaning, visualisation, and forecasting.

Motive

COVID-19 had a profound impact on public health, mobility, and urban systems. Analysing case trends is crucial to understanding how infectious diseases spread and how authorities can prepare for future outbreaks. As a beginner in time-series analysis, I chose this dataset to practise skills in data preprocessing, exploratory analysis, and forecasting, while working on a socially relevant topic.

Data Source
Source: Corona Virus Statistics - BBMP - Covid19 https://ksdma.karnataka.gov.in/info-4/Covid-19+Orders/en 
File format available: data.pdf 
Manually collected
Format Origin: Data was available only as a PDF document
Processing Step: All values were manually transferred into an Excel file (COVID_Data.xlsx)
Timeline: September 2020 to February 2021
Columns include:
Date: Day-wise entry for COVID-19 reporting
Active cases: Number of active COVID-19 cases in Bangalore
Positive cases: Newly reported positive cases
Recovered: Number of recovered individuals
Death: Number of reported deaths

Data analysis
Data Loading & Cleaning
Loaded the Excel file using pandas
Converted the Date column to a datetime format
Checked for missing values and data inconsistencies

Installed packages Pandas, Matplotlib, Seaborn, Plotly, pmdarima, scikit-learn

Key Findings  Active COVID-19 cases showed noticeable fluctuations influenced by weekly patterns.
The 7-day and 14-day moving averages gave clear insights into overall trends. The ARIMA-based model showed reasonable accuracy for short-term forecasting.
Forecasts for 14-day days and longer forecasts (30 days) showed more deviation, reflecting the unpredictable nature of the pandemic.


Challenges

The dataset required manual transcription from PDF to Excel, which was time-consuming.
The forecast models could be improved with more extensive or higher-resolution data
The dataset had fewer columns

Future improvements

Use advanced forecasting models (e.g., Facebook Prophet, LSTM deep learning networks). Extend the forecasting for other columns
Build an interactive dashboard
