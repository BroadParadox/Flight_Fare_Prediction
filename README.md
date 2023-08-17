# Flight_Fare_Prediction

A Time Series Forecasting Project. 
Time-series forecasting is a technique that utilizes historical and current data to predict future values over a period of time or a specific point in the future. By analyzing data that we stored in the past, we can make informed decisions that can guide our business strategy and help us understand future trends.

In this Project, we perform prediction of flight prices based on historic data available. 
The dataset contains details like Airline, Date, Source and Destination, Route, Time, Number of stops and Price.

Summary of the Project:
1. As the first step, we load our `FlightFare_Dataset` from Project Directory, using Pandas `read_excel` method
2. Then, we perform Feature Exploration and Engineering to transform our dataset
3. Once done, we use a Feature Selection technique to select the most important features
4. At this point, we train a Random Forest Regressor Model
5. As the next step, we do hyper-parameter tuning (using `RandomGridSearch`) to build the best model
6. Finally, we export the Model `.pkl` file back to Project Directory

This is a self-project I did to explore time series forecasting.
