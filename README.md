# Clustering
## Task 1
Datasets posted with the project (“Data1.csv”, “Data2.csv”, “Data3.csv”, “Data4.csv”, “Data5.csv”) contain the data points and their respective class information. For each of the 5 datasets, follow the steps below:
1. Use K-means and hierarchical clustering methods to generate clusters.
2. Evaluate the performance of the clustering algorithm using external validation metrics.
3. Plot (2D or 3D) the data points for each dataset and color them according to the original class
4. Plot (2D or 3D) the data points for each dataset and color them according to the class allocated by each clustering algorithm
## Task 2
The world indicators dataset compares different countries based on selected attributes. Do the following tasks using the “WorldIndicators.csv” dataset posted with the project:
1. Use K-means and hierarchical clustering methods to group similar countries together
2. Use internal validation metrics to report the cluster quality
3. Report the best clustering solution. Give a detailed list of all the groups and the countries included within the groups
4. Generate 3 different scatter plots of your choice and color the data points according to the group. (Example: “Life expectancy vs GDP”, “Infant Mortality vs GDP”, etc.)

# Time Series Analysis and Forecasting
Google has made available some mobility data around the world since the COVID-19 pandemic began. You can find their datasets [here](https://www.google.com/covid19/mobility/). For this task, you will be forecasting using data from
the King County. There are 2 ways to get these data:
● Download the Global file (not recommended, it’s huge)
● Download the folder of all Regional files. There should be 3 years of CSV files for each region, you should locate and grab the 3 corresponding to “US”.   
Once you have the proper data files, you should be able to isolate just the data from King county via the `sub_region_#` columns. In this activity, we will be concerned with describing and forecasting the time series concerning “Residential”, “Work”, and “Grocery and Pharmacy”
1. Put together your entire time series using all the data from 2020-2022. You should end up with 1 dataframe that contains all the data points.
2. Trim down your time series to remove the months before April 2020. This will remove the very early pandemic and the pre-pandemic conditions.
3. For each of the 3 time series, perform an additive Time Series Decomposition and plot the results. You should show the trend, seasonality, and remainder in your plots.
4. For each time series, build a forecasting model using Exponential Smoothing (ES). You should test out at least 2 different ES models and use forecast evaluation metrics (e.g. MAE, RMSE) to demonstrate why you chose your best ES model
5. For each time series, build a forecasting model using ARIMA. You must show why you chose your ARIMA model.
6. Compare your best ES and best ARIMA models for each time series using forecast evaluation metrics. Show which model is best in each case.
7. Using your best model, forecast the rest of 2022 for each time series. Show these forecasts by plotting the past data points in 1 color and the future data points in a second color.

