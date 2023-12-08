# BusinessAnalytics42577

This group project was completed in a group of 5 as part of course 42577 Introduction to Business Analytics, at DTU in Fall 2023.

Pandas and scikit-learn packages are used to prepare data frames and train different models using the 2018 data from [Citi Bike (New York)](https://citibikenyc.com/system-data), which contained over 17 million record entries. The notebook is divided into 4 sections:

- Section 1: Data Preprocessing & Visualization
- Section 2: Prediction Challenge
- Section 3: Exploratory Component
- Section 4: Conclusion

My main contributions are in sections 1 and 2.

## Section 1: Data Preprocessing & Visualization

The data is cleaned by removing improbable outliers, missing values, and rectifying the data types. A few visualizations are illustrated to identify patterns in the data.

## Section 2: Prediction Challenge

The stations are placed into geographical clusters. Models are built to predict the demand for bike usage over the next 24 hours for a specific cluster of stations. Bike demand includes pick ups, drop offs, and consequently shortages in bikes available in these clusters.

A baseline model, linear regression model, and gradient boosted regressor model are used for comparison in performance.

## Section 3: Exploratory

The effect of seasonal and weather factors on the total and average bike trip durations is analyzsed using daily weather data in New York City extracted from [Weather Data Services by Visual Crossing](https://www.visualcrossing.com/weather/weather-data-services/new%20york/metric/2018-10-01/2018-10-31).
