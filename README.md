# New York City Taxi Fare Prediction

We are tasked with predicting the fare amount (inclusive of tolls) for a taxi ride in New York City given the pickup and dropoff locations. The evaluation metric for this competition is the root mean-squared error or RMSE. Follow the link to see the [Kaggle Competition](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/overview/description). Note that it suggest using TensorFlow, but we will use sklearn and regression models to try and predict fare amount.

### Features
- `key` - Unique string identifying each row in both the training and test sets. Comprised of pickup_datetime plus a unique integer. Required for submission but not for training.
- `pickup_datetime` - timestamp value indicating when the taxi ride started.
- `pickup_longitude` - float for longitude coordinate of where the taxi ride started.
- `pickup_latitude` - float for latitude coordinate of where the taxi ride started.
- `dropoff_longitude` - float for longitude coordinate of where the taxi ride ended.
- `dropoff_latitude` - float for latitude coordinate of where the taxi ride ended.
- `passenger_count` - integer indicating the number of passengers in the taxi ride.

### Label
- `fare_amount` - a float dollar amount of the cost of the taxi ride. This is the value we want to predict
