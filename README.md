# Bike1_Sharing_Prediction
# Problem Statement:-
Nowadays rental bikes are introduced in many urban cities for the improvement of mobile comfort.It is important to make tental bikes available to the public at the right time.As it makes waste of time . Eventually providing a cities with supply of rental bikes become a major concern.Themain objective is to predict the bikes count required at each hour for supply of rental bikes.
# Variables:-
Date:Date of the day

Rented_bike_count:Number of rented bike per hour

Hour:The hour of the day

Temperature (°C): Temprature in celcius

Humidity:Humidity in the air

Wind_speed(m/s):speed of wind

Visibility (10cm): Visibility in cm

Dew_Point: Temperature of beginning of day

Solar_rediation(MJ/m2):Sun contributions in m


Rainfall(mm):Amount of raining in cm

Snowfall (cm): Amount of snowing in cm

Season:Season of the year

Holidays:If the day is holiday or not

Functioning_day:If the day is functioning day or not

# Approach:-

# Data Preperation:-
• Checked for null values using isnull() method

•.Checked For duplicate values using duplicated() method

• Checked info of data, columns in dataset.
# Feature Engineering:-
• Checked outliers from dataset and handled them.

• Created Year,Month and day column from Date feature.

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
- Important features which affects the model most are winter, summer seasons and Functioning_day, Temperature,Holiday.
- Rented bike count is high on Functioning day.
- Feature impotance values for all models are diffrent.
- We can deploy Random Forest ,Lasso,Linear regression ,Ridge with RandmizedSearchCV.
- Using Linear regression and Lasso algorithm I got 83% r2 score for test dataset.










