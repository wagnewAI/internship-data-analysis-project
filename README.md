# Internship-data-analysis-project
This project is focused on analyzing a dataset of restaurants across various cities and countries, with the goal of uncovering insights related to service offerings, pricing, and customer ratings.
The dataset contains detailed information about restaurants, including location, services, cuisine types, cost, and customer feedback. It includes the following key columns:

Restaurant ID, Name – Unique identifiers and names of the restaurants.

Country Code, City, Address, Locality – Geographical location details.

Longitude, Latitude – Coordinates for mapping.

Cuisines – Types of cuisine offered (e.g., Italian, Indian, etc.).

Average Cost for Two – Estimated cost for a meal for two people.

Currency – Currency used in the respective country.

Has Table Booking – Indicates if the restaurant offers table reservation.

Has Online Delivery – Indicates if online delivery is available.

Is Delivering Now – Real-time delivery status.

Switch to Order Menu – UI-related data, not used for analysis.

Price Range – Price tier of the restaurant (e.g., 1 to 4).

Aggregate Rating – Overall rating (0–5 scale).

Rating Color & Rating Text – Visual representation and label for the rating (e.g., "Excellent", "Good").

Votes – Number of user votes received.
- The analysis aims to explore patterns in restaurant performance, consumer preferences, and market differences across regions.
📈 Key Insights:
- City with Most Restaurants:
New Delhi – 5,473 restaurants

- Highest Average Rating:
Inner City – Average rating of 4.90

- Online Delivery Availability:
25.66% of restaurants offer online delivery

- Most Common Rating Range:
3.0 – 3.5 stars, with 2,502 restaurants falling in this category

🗣️ Sentiment Breakdown (Based on Rating Text):

Most Frequent Positive Ratings:

- Good – 2,100 times

- Very Good – 1,079 times

- Excellent – 301 times

Most Frequent Negative Ratings:

- Average – 3,737 times

- Not Rated – 2,148 times

- Poor – 186 times
  
🔥 Top Restaurants by Total Votes:

 Restaurant Name  
 
 Barbeque Nation           28,142
 
AB's - Absolute Barbecues  13,400

Toit                       10,934

📉 Statistical Analysis:

Correlation Between Votes and Aggregate Rating:

Pearson Correlation Coefficient: 0.243

P-value: 0.000

✅ This correlation is statistically significant (p < 0.05), indicating a positive, though modest, relationship between the number of votes a restaurant receives and its average rating.
