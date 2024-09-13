# SmartRide: Bike Demand Prediction: Machine Learning
![Bike1](https://github.com/user-attachments/assets/0ba2ecbd-5df9-4345-945e-fc185542d282)

# Problem Statement:-
Nowadays rental bikes are introduced in many urban cities for the improvement of mobile comfort. It is important to make rental bikes available to the public at the right time as it is a waste of time. Eventually providing cities with a supply of rental bikes became a major concern. The main objective is to predict the bike count required at each hour for the supply of rental bikes.
# Variables:-
Date:Date of the day

Rented_bike_count: Number of rented bikes per hour

Hour:The hour of the day

Temperature (°C): Temprature in celcius

Humidity: Humidity in the air

Wind_speed(m/s):speed of wind

Visibility (10cm): Visibility in cm

Dew_Point: Temperature of the beginning of the day

Solar_rediation(MJ/m2):Sun contributions in m


Rainfall(mm):Amount of rain in cm

Snowfall (cm): Amount of snowing in cm

Season: Season of the year

Holidays:If the day is holiday or not

Functioning_day:If the day is a functioning day or not

# Approach:-

# Data Preparation:-
• Checked for null values using isnull() method

•.Checked For duplicate values using the duplicated() method

• Checked info of data, and columns in dataset.
# Feature Engineering:-
• Checked outliers from the dataset and handled them.

• Created Year, Month and day columns from the Date feature.

• Created new features like Weekend and month.

• Dropped the columns which are not needed.

• Scaled the features of data.
# Used Models:-
•Linear Regression

•Random Forest

•Lasso 

• Linear Regression with GridSearchCV

• Ridge with GridSearchCV

• Gradient Boost with GridSearchCV
# Conclusion:-
- Important features that affect the model most are winter, and summer seasons and Functioning_day, Temperature, Holiday.
- Rented bike count is high on Functioning day.
- Feature importance values for all models are different.
- We can deploy Random Forest,Lasso, Linear regression,Ridge with RandmizedSearchCV.
- Using Using Random Forest I got the highest r2 score for the test dataset which is 93%.


















