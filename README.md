#**Problem Description**:

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

#**Data Description**:

The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Attribute Information:

Date : year-month-day

Rented Bike count - Count of bikes rented at each hour

Hour - Hour of he day

Temperature-Temperature in Celsius

Humidity - %

Windspeed - m/s

Visibility - 10m

Dew point temperature - Celsius

Solar radiation - MJ/m2

Rainfall - mm

Snowfall - cm

Seasons - Winter, Spring, Summer, Autumn

Holiday - Holiday/No holiday

Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)

#**Exploratory Data Analysis (EDA)**:

In this part we have done some EDA on the features to see the trend.

#**regression models**:

Then regression models were trained and the performance is evaluated using a testing set:

linear regression, lasso regression, ridge regression, XG Boost, decision tree and random forest. After that I use SHAPE and elif5 to explain the model in a better way.

#**Observations**:

 Observation 1: In the Model Evaluation Matrices table, Linear Regression,lassoregression,Ridge regression,XGBoost are not giving much great results.

 Observation 2: Decision Tree & Random forest  have performed equally good in terms of r2 score.

#**Conclusion**:

Decision tree gives accuracy score around 84%.
random forest model gives better accuracy than decision tree around 92%




