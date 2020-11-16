# Airbnb_Listing_Price_Regression

This dataset has columns describing:

- host id: unique host id
- host name: name of host
- listing id: unique listing id
- listing name: name of listing
- latitude
- longitude
- the neighbourhood: name of neighbourhood
- room type
- minimum number of nights
- number of reviews
- last review date
- reviews per month
- availability_365: number of days in year the listing is available for rent
- host listings
- city
- price: price of listing per night

This project aimed to train a regression model to predict price of listing per night given some features.
The models trained were an Extreme Gradient Boosting regressor and a Linear Regression

### Results:

#### Linear regression
MSE 0.8719020312856749
RMSE 0.9337569444377241
R2 Score 0.12616838160768917
Adj R^2 value: 0.12591044297042475

### XGBoost
MSE 0.6066817843460006
RMSE 0.7788978009636441
R2 Score 0.3919755816115271
Adj R^2 value: 0.39179610425387423

Data: https://www.kaggle.com/kritikseth/us-airbnb-open-data
