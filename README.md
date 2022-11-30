# Project 7: Energy Prices in Illinois

## Team Members

Noam Yan (xuy3)  
Yunqian Bao (yunqian4)  
Zhicong Fan (zhicong2)  


## Problem Explanation
### Goal:
We want to predict energy prices in Illinois: given features like forecasted load, day ahead energy price, date, time, energy prices in surrounding states, predicted weather, and etc., we need to predict the actual energy price.

### Dataset:
Currently, we have a matrix of (624,33) for debugging dataset whose time range spans from Oct,1,2022 to Oct,26,2022. And a matrix of (15937,33) for full dataset whose time range spans from Jan,1 2021 to Oct,26,2022. They are in the folder "dat\"

### Model:
We plan to use a Recurrent Neural Network.

## Weekly Plan
10/30/2022: Extract all the information and integrate into one dataframe. Save it in both .csv and .pkl.
11/2/2022: Data Visualization. Feature Engineering. Apply simple models (Linear Regression, Logistic Regression).

# Lisence:
Authors:  
Noam Yan (xuy3@illinois.edu)  
Yunqian Bao (yunqian4@illinois.edu)  
Zhicong Fan (zhicong2@illinois.edu)  

Data sources: 
http://www.energyonline.com/Data/GenericData.aspx?DataId=8&MISO___Actual_Energy_Price.
https://www.ncei.noaa.gov/products/land-based-station/integrated-surface-database.
