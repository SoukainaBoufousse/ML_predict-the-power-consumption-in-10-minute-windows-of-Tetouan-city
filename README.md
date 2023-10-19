## Project Overview

The goal of the project is to accurately predict the power consumption in 10-minute windows of Tetouan city using machine learning techniques and the provided dataset. we have used models like xgboost and randomforest that can accurately forecast power consumption based on historical data, weather conditions, and other relevant factors.

## Context

The Power consumption of Tetouan city dataset was collected by The Supervisory Control and Data Acquisition System (SCADA) of Amendis, a public service operator. The goal is to use machine learning algorithms to analyze the dataset and make predictions about the power consumption of Tetouan city. The city's distribution network is powered by 3 zone stations, namely: Quads, Smir and Boussafou. The dataset contains information on power consumption in these zones over a period of one year starting from January 1st, 2017, all the way through December 30th of the same year. , including data on temperature, humidity, and other environmental factors that may influence power consumption.

## Dataset Description

The data has observations in 10-minute windows starting from January 1st, 2017, through December 30th of the same year. Some of the features are:

- Date Time: Time window of ten minutes in the format "dd/mm/yyyy hour:minute:second"
- Temperature: Weather Temperature in °C
- Humidity: Weather Humidity in %
- Wind Speed: Wind Speed in km/h
- General Diffuse Flows: The general diffuse flows in the city, which may include air or water flows.
- Diffuse Flows: This attribute represents a specific type of diffuse flow in the city.
- Zone 1 Power Consumption in KiloWatts (KW)
- Zone 2 Power Consumption in KW
- Zone 3 Power Consumption in KW

## Repository Structure

- `machine learning prediction` contains the notebooks.
- `dataset` contains three files:
  - `train_data.csv` - the training set.
  - `test_data.csv` - the test set.
  - `sample_data.csv` - a sample submission file in the correct format.

`README.md` provides information about the project.
