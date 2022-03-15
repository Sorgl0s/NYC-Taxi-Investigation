This project involves investigating the NYC TLC data set of Green Taxis over 2018 and 2019. Time and weather conditions of the trips were used to predict the most profitable times for drivers to pickup passengers. The datasets are very large, so pySpark has been utilised to enable cleaning and representation of the raw data.

# MAST30034 Project 1 - Quantitative Analysis
- Student Name: Tristan Cooper

# Dependencies
- Language: Python 3.8.10
- Packages / Libraries: pandas, numpy, pyspark (+ pyspark monitor), sklearn, seaborn, glmnet, statsmodels.

# Datasets
- NYC TLC: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page
- NOAA Hourly Weather 9Laguardia Airport 2018): https://www.ncei.noaa.gov/data/local-climatological-data/access/2018/72503014732.csv
- NOAA Hourly Weather 9Laguardia Airport 2018): https://www.ncei.noaa.gov/data/local-climatological-data/access/2019/72503014732.csv

# Directory
- `Hourly weather`: Contains the raw weather data from 2018 and 2019, each a separate csv. 
- `TLC Data`: Contains folders with raw data for 2018 and 2019 Green Taxis.
- `Notebooks`: Contains the three Notebooks used to download data, preprocess and model.
    - Notebook 00 for downloading the TLC datasets.
    - Notebook 01 for data cleaning, pre-processing, transforming and some data visualisation.
    - Notebook 02 for analysis and modelling.
