# Airbnb-python-EDA-project

## Project Overview
This project performs Exploratory Data Analysis (EDA) on New York Airbnb data to uncover trends and patterns in rental listings. We use libraries like Pandas, Numpy, Matplotlib, Seaborn for cleaning, visualization, and analysis.
![Airbnb Logo](https://github.com/user-attachments/assets/2333476d-967e-46b6-b4ab-8965e7a15eaf)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## About Dataset - 
The dataset contains 20,765 records and 22 columns.

The columns are -

**• id:** Unique identifier for each listing

**• name:** Title of the Airbnb listing

**• host_name:** Name of the host

**• neighbourhood_group:** Group (borough) where the listing is located

**• latitude/longitude:** Geolocation of listings

**• price:** Nightly rental price

**• room_type:** Type of accommodation (e.g., entire home, private room)

**• reviews_per_month:** Average monthly reviews for the listing

**• availability_365:** Number of available days in the year

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Objective

The goal of this project is to:

1. Analyze room types, prices, and availability across different neighborhoods.
   
2. Understand host behavior and listing patterns.
   
3. Detect potential outliers in prices.
   
4. Provide recommendations for guests and hosts based on insights.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Project Steps - 

### 1. Data Cleaning

• Handle missing data: price, neighborhood, and beds columns had null values.

• Fix data types: Converted last_review to a datetime object.

• Remove outliers: Listings with prices > $1,000 were capped to avoid skewed visualizations.


## 2. EDA (Exploratory Data Analysis)

• Room type distribution.

• Neighborhood group insights.

• Availability trends.

• Price distribution.

• Host listings.

• Review behavior.


## 3. Data Visualization

• Histograms and Boxplots: To detect outliers in price.

• Bar Charts: Displaying room types and neighborhood group distributions.

• Scatter Plot: To visualize correlations.

• Pairplot: To see correlations among price, availability, and number of reviews.

• Heatmap: Showing correlations among numerical features.



-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Key Findings and Insights - 

1. Price Trends:
   
       • Manhattan has the most expensive listings, followed by Brooklyn.
   
       • Entire homes/apartments cost significantly more than private or shared rooms.
   
2. Room Type Distribution:
   
       • Entire homes/apartments are the most common, but private rooms offer budget-friendly options.
   
3. Outliers in Price:

       • Few listings priced at $10,000+ were detected, indicating the need to filter such extreme values.
   
5. Availability Patterns:

       • Listings with high availability tend to have lower prices and more reviews, likely due to better guest experience.
   
5. Host Behavior:

        • Some hosts manage multiple listings, indicating a trend toward professional hosting.
   

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Conclusion

This project offers valuable insights into the New York Airbnb market, helping both guests and hosts make informed decisions. By using EDA techniques, we identified key trends and developed actionable recommendations. Future improvements can involve advanced analytics and predictive modeling to further enhance the findings.
