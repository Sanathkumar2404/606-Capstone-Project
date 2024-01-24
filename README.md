# Predicting Electric Bike Usage in the D.C. Area - README
## Overview
This project, conducted by Vinay Kota and Sanathkumar Chiluveru, focuses on analyzing electric bike rentals in Washington D.C. using machine learning techniques and weather data. The aim is to understand usage patterns and factors affecting bike rentals for companies like Capital Bikeshare.

### Abstract
Electric bikes have gained popularity for their ease of use and eco-friendly nature. The project combines Capital Bikeshare's rental data with Washington D.C. weather data to analyze usage patterns. Machine learning algorithms, specifically the random forest algorithm, were applied to predict rental demand based on various features. The project achieved an RMSE of 3.2 and an R2 value of 0.6.

### Introduction
With increasing awareness of pollution caused by fuel vehicles, electric bikes offer an alternative for daily commutes. Capital Bikeshare, operated by LYFT in D.C., provides a bike-sharing program with flexible plans. The project aims to analyze bike rentals, considering factors like time, distance, and weather. The study draws inspiration from similar research in New York City, Seoul, and a French city, highlighting the impact of weather, pollution, and transportation infrastructure on bike-sharing demand.

### Methods
The project utilizes two main data sources: Capital Bikeshare rental data for 2022 and weather data from Washington D.C. obtained through the Visual Crossing API. Python, Jupyter Notebook, and libraries like pandas, matplotlib, seaborn, and sci-kit learn are employed for data analysis and machine learning. The dataset is preprocessed, handling missing values and creating additional features like start hour and quarter. K-Means clustering is applied to group stations, and hourly weather data is aggregated. Station-wise data is incorporated into the final dataframe.

### Results and Analysis
The results include machine learning predictions of rental demand based on hourly and cluster-wise patterns. Further analysis is needed for a comprehensive understanding of the results.

### Conclusion
The study concludes that weather is a crucial factor in e-bike usage, and machine learning techniques can aid in predicting usage patterns. The findings can be valuable for companies like Capital Bikeshare in making informed decisions for additional docks and bikes in specific localities. Despite challenges in maintaining e-bikes, the project indicates promising improvements in urban transportation.
