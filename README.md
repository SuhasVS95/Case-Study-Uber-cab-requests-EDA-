# Case-Study-Uber cab requests(EDA)

# Problem Statement:

We have a cab trip dataset wherein details regarding customer_request_id, pick up point, driver id, Status, Request timestamp and Drop timestamp. Based out of these features , I have cleaned the data and have applied basic EDA techniques to come to a broader conclusion.
NOTE: This is just an exercise for educational purpose.

An explanatory data analysis on the Uber cab requests data to bring out insights on cab traffic with relevant visualizations.

Dataset source: https://www.kaggle.com/anupammajhi/uber-request-data

# Tasks Completed:

1. Understnading the data
2. Data pre-processing
3. Visualize and Analyse the data
4. Key Takeaways

# Key Takeaways

#### 1) We understood the dataset with the number of user requests were done and the number of columns(6745,6) along with other facts such as number/percentage of NaNs in each columns and format of dataTime in the request and drop timestamp columns.
#### 2) We standardised format of dataTime in the request and drop timestamp columns.
#### 3) Figured a logical reason as to why the NaNs in Driver_id and drop timestamp columns should be ignored.
#### 4) Extracted the day number and hour from the request timestamp column to perform a deeper analysis.
#### 5) Between hours 5AM-9AM, the load on cabs are high with almost equal amount of trips getting completed and cancelled.
#### 6) Between hours 5PM-9PM, the load on cabs are significantly high. Hence, there is mismatch between cab demand and availabilty. Hence, we see more of "No cars Available Status".
#### 7) Between hours 5AM-9AM, the users from city is significantly high.
#### 8) Between hours 5PM-9PM, the users from Airport is significantly high.
#### 9) The "Morning_Rush" and "Evening_Rush" are the hours with maximum load(i.e more number of users requesting cab services).
#### 10) We also saw the load during "Morning_rush" and "Evening_Rush" from both pick-up points "City" and "Airport".
#### 11) During the evening rush hour, we saw a significant number of No CARS AVAILABLE status  for the trip bookings from "Airport".
