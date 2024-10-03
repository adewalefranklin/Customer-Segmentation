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
