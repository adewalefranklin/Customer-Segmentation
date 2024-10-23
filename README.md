# TravelTide Customer Segmentation Project

## Project Overview
This project focuses on segmenting customer data for TravelTide, an e-booking startup, to help design a personalized rewards program. The goal was to group customers based on their behavior and assign perks that best suit their preferences, with the aim of increasing customer retention and satisfaction.

The analysis was conducted in four key stages:
1. **Exploratory Data Analysis (EDA):** Cleaning and understanding the dataset.
2. **Feature Engineering:** Creating meaningful metrics for customer segmentation.
3. **Customer Segmentation:** Grouping customers and assigning perks.
4. **Presentation of Results:** Visualizing and summarizing the findings for the marketing team.

## Dataset
The final dataset (`Adewale_Traveltide_final_query-2024-07-12_114713.csv`) contains customer-level information post-segmentation, which can be used to gain insights into their behavior, preferences, and the perks assigned to each customer.

### Key Columns:
- **user_id:** Unique identifier for each customer.
- **gender:** Gender of the customer.
- **age:** Age of the customer.
- **married:** Marital status (True/False).
- **has_children:** Indicates if the customer has children (True/False).
- **actual_trips:** Number of trips taken by the customer.
- **avg_click:** Average number of clicks per session.
- **session_count:** Total number of sessions.
- **num_flights:** Total number of flights booked.
- **avg_time_btw_booking_departure:** Average time between booking and departure (in days).
- **avg_checked_baggage:** Average number of checked baggage per flight.
- **rfm_rank:** RFM score based on recency, frequency, and monetary value.
- **user_type:** Customer tier (e.g., Silver Members).
- **perks:** Assigned perks for the customer (e.g., 20% hotel discount).

- Findings
  
● The analysis resulted in 5 different segmentations which consist of various other characteristics such as Family traveler(users with children), Couple Travelers(married users), Young and free Travelers(people under 30), Business Travelers(users that travel with less than 1 bag or maximum of 1 bag), and Senior citizens who are the users above 60.
● The segmentations as derived are:
Platinum (These are the best customers based on their RFM and the revenue they
generated the highest revenue among all the users) Gold (Generated Revenue and the RFM is very high)
Silver(They are the users who have generated revenues and grouped according to their RFM score)
Bronze ( this group was created based on the RFM score and they have generated a revenue)
Basic users(users who never booked anything but have online activities)

Recommendation

● The analysis is subject to further analysis to ensure accuracy
● There is a need to ensure data integrity and accuracy for future analysis.
● For future bookings, there may be the need to integrate a short survey during
bookings in order to ascertain users' special interes
