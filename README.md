# Kagge Competetion - Predict Rent in New York

Submitted by: **NING YANG**

Time spent: **70** hours spent in total

This project is a part of Course APANPS5200- APPLIED ANALYTICS FRAMEWORKS & METHODS I(R programming) in Columbia University.


## Description

People interested in renting an apartment or home, share information about themselves and their property on Airbnb. Those who end up renting the property share their experiences through reviews. The dataset describes property, host, and reviews for over 40,000 Airbnb rentals in New York along 90 variables.*

### Goal

Construct a model using the dataset supplied and use it to predict the price of a set of Airbnb rentals included in scoringData.csv.

### Metric

Submissions will be evaluated based on RMSE (root mean squared error) (Wikipedia). Lower the RMSE, better the model.

## Summary
There are a number of predictive techniques discussed in this course, some strong in one area while others strong in another. Furthermore, default model parameters seldom yield the best fit. Each problem is different, therefore deserves a model that is tuned for it.
Predictive modeling is an iterative exercise. I have tried and transformed variables to improved my model, and I submitted 7 times in total. The best model is XGboost model which has the least MSE.

### Lessons learned
1. The importance of Random Forest is useful to check the variables importance and select features. To improve the performance, I will try it for future explorations.
2. The model of linear regression and decision tree cost a lot of time to run when the datase. is large.XGBoost model saves almost half of  time.
3. Missing values may have multiple specifications , such as “N/A”, “N A”, and “Not Available”. 


## License

    Copyright [2022] [NING YANG]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
