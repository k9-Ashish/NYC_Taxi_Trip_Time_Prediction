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
