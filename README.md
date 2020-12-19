# New York City Taxi Fare Prediction

<img src="/image/taxi_cover.jpg" width="350">

We are tasked with predicting the fare amount (inclusive of tolls) for a taxi ride in New York City given the pickup and dropoff locations. The evaluation metric for this competition is the root mean-squared error or RMSE. Follow the link to see the [Kaggle Competition](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/overview/description). Note that it suggest using TensorFlow, but we will use sklearn and regression models to try and predict fare amount.

#### The focus of the project is:
- Cleaning the data by removing any extreme outliers and missing values from the training subset.
- Visualizing distributions and correlations for features in our datase.
- Engineering new features such as distance traveled and extracting more information from the datetime feature.
- Modeling Linear Regression through both sklearn and keras.

#### Requirements to run this project:
- [Kaggle Data](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data) that must be ran through the Data_Prep Notebook. Note that the data is around 5.5GB and only a subset of it was used for this project (slightly under 4,000,000 observations) which still amounted to around 440MB and could not be uploaded to this repository.
- [Keras](https://keras.io/) and [Scikit-learn](https://scikit-learn.org/stable/)
- Seaborn, matplotlib, NumPy, Pandas, and Python.
