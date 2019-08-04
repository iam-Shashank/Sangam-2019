# Sangam-2019

output1.csv : 4/100/99.7
output2.csv : 2/15/99.8314
output3.csv : 2/15/99.93395
output6.csv :


file1.csv: 99.37812 / XGBRegressor(objective ='reg:linear', colsample_bytree = 0.3, learning_rate = 0.1,
                max_depth = 10, alpha = 10, n_estimators = 10)

Observations: 

- dew_point is highly correlated with visibility_in_miles (ρ = 1). So, one column rejected?

- Maximum days no rain or snow.( as there are lots of zeroes)

- Most days are cloudy, windy (as no. of zeroes is low)

- Temperature value has one 0 Kelvin value 



Categorical: Date-Time, weather_description, weather_type, is_holiday

Date-Time: split into Date and Time



