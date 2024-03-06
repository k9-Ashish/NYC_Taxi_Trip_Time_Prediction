# NYC_Taxi_Trip_Time_Prediction

## Problem Description

**Your objective is to construct a predictive model capable of estimating the complete duration of taxi journeys in New York City. The central dataset at your disposal originates from the NYC Taxi and Limousine Commission. This dataset encompasses pickup timestamps, geographical coordinates, passenger count, and a variety of other factors.**

### Data Description

**The dataset we are working with originates from the 2016 NYC Yellow Cab trip records, which have been made accessible through Google Cloud Platform's Big Query. These records were initially released by the NYC Taxi and Limousine Commission (TLC). For this project, the data was both sampled and refined. Your task involves using specific attributes of each trip to forecast the duration of trips in the test set.**

#### NYC Taxi Data.csv - the training set (contains 1458644 trip records)
# Data fields
**1. ID: Unique trip identifier.**

**2. Vendor ID: Code indicating the service provider for the trip.**

**3. Pickup Date & Time: When the taxi ride started.**

**4. Dropoff Date & Time: When the taxi ride ended.**

**5. Passenger Count: Number of passengers (as entered by the driver).**

**6. Pickup Longitude & Latitude: Geographic coordinates where the ride began.**

**7. Dropoff Longitude & Latitude: Geographic coordinates where the ride ended.**

**8. Store and Forward Flag: Whether the trip data was stored in the vehicle's memory due to a lack of server connection.**

**9. Trip Duration: Duration of the trip in seconds.**

## Conclusion :

**We can observe that we have applied multiple models with different approaches and we can clearly see that in all cases XGBOOST was working very fine other than Decision Tree and Random Forest Regression**

**But after implementing the PCA to our features and we successfuly reduced our feature dimension and we observed that after transformation Decision Tree and Random Forest is also doing great job even far better that without transformation**

**And XGBOOST is also working better after PCA transformation and XGBOOST is showing slightly better scores in terms of RMSE | MSE which is lesser than other models and also R2 | Adj R2 scores are also not having that much difference and also higher than other models.**

**So our conclusion from this whole analysis is that we can go with XGBOOST Regressor to get Good Prediction rate and lesser Error prone and also it can be more optimized using more tuned hyperparameters.**

### Future Work:
**As this data set is of only almost 6 months and I think there should be more data for more than a year and also some more features should be there so that we can train our models with more significant information that will help our model to learn more efficiently so that we can get more higher performance from Machine Learning Models**

**And also we can extract more information about this data by getting more features so that we can explore more about this kind of data**
