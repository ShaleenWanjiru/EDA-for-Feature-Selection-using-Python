# EDA-for-Feature-Selection-using-Python

Feature selection is a crucial process in building machine learning models which involves selecting a subset of relevant features (variables, predictors) for use in model construction.

The given dataset consists of data related to ride-sharing service costs, encompassing various factors that could influence the dynamic pricing model of rides. It includes 1,000 records with the following key attributes:

1. Number_of_Riders: The number of riders participating in the ride.
2. Number_of_Drivers: The number of drivers available at the time of booking.
3. Location_Category: The category of the location (Urban, Suburban, Rural).
4. Customer_Loyalty_Status: The loyalty status of the customer (e.g., Silver, Regular).
5. Number_of_Past_Rides: The number of past rides the customer has had.
6. Average_Ratings: The average ratings given to the drivers by the customer.
7. Time_of_Booking: The time of the day when the booking was made.
8. Vehicle_Type: The type of vehicle booked for the ride.
9. Expected_Ride_Duration: The expected duration of the ride in minutes.
10. Historical_Cost_of_Ride: The cost of the ride, which serves as the target variable for predictive modeling.
    
Your task is to conduct an Exploratory Data Analysis (EDA) to identify and select the most important features that influence the historical cost of a ride.

# Insights Gathered from EDA for Feature Selection on the EDA, the following features are identified as potentially important for predicting ride costs:

1. Expected_Ride_Duration: Shows a clear relationship with ride cost.
2. Location_Category: Significant variance in costs by location.
3. Customer_Loyalty_Status: Variability in costs suggests an impact on pricing.
4. Time_of_Booking: Variations in costs indicate an influence of demand at different times.
5. Vehicle_Type: Directly influences cost with clear distinctions between vehicle types.


The other numerical features (Number_of_Riders, Number_of_Drivers, Number_of_Past_Rides, Average_Ratings) do not show strong linear relationships with the target variable but could still be useful, especially when combined with other features or through engineered features that capture non-linear relationships or interactions.
