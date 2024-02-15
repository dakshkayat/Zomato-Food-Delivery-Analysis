# Zomato-Food-Delivery-Analysis

This project scrapes data from the food delivery platform Zomato to collect information about restaurants in Bangalore. It organizes the data into two tables: `restaurant_info` and `restaurant_details`, which contain essential details about each restaurant.

## Project Overview

The project aims to gather data from Zomato to analyze the restaurant landscape in Bangalore. It includes two main components:

1. **Web Scraping**: The script uses BeautifulSoup to scrape restaurant information from Zomato. It collects details such as restaurant name, rating, price range, cuisine types, location, and delivery review statistics.

2. **Data Analysis**: Once the data is collected and organized into tables, the script performs data analysis to generate insights for users. It includes aggregations and visualizations to understand area-wise distribution of restaurants, pricing trends, popular cuisines, and suitable locations for opening a new restaurant.

## Data Tables

### Table 1: `restaurant_info`

- `restaurant_id`: Unique identifier for each restaurant (Primary Key)
- `restaurant_link`: Zomato URL for the restaurant
- `name`: Name of the restaurant
- `rating`: Zomato rating of the restaurant
- `price_for_one`: Price range for one person
- `cuisines`: Types of cuisine offered by the restaurant

### Table 2: `restaurant_details`

- `restaurant_id`: Unique identifier for each restaurant (Primary Key)
- `restaurant_name`: Name of the restaurant
- `latitude`: Latitude of the restaurant
- `longitude`: Longitude of the restaurant
- `location`: Location of the restaurant
- `delivery_review_number`: Number of delivery reviews for the restaurant

## Data Analysis Insights

The project generates various insights from the collected data to help users understand the restaurant landscape in Bangalore. Some of the insights include:

- Area-wise distribution of restaurants
- Cheapest and most expensive restaurants for each type of cuisine
- Locations with a high number of restaurants with delivery reviews over 1000
- Insights on less rated restaurants in specific locations
- Recommendations for suitable locations and pricing strategies for new restaurant ventures

## Phase 2: Recommendation Model

In the second phase of the project, a recommendation model is built to assist individuals planning to open a restaurant in Bangalore. The model takes inputs such as cuisine preference, preferred location, and price range and provides recommendations based on popular cuisines, average prices, and optimal locations.

### Output Part 1

- Display of popular cuisine for the selected area
- Average price for one person
- Most popular restaurant and the cuisine they serve
- Most popular restaurant serving the same cuisine as the user's preference

### Output Part 2: Recommendation

- Suggested price for one person based on the model prediction
- Optimal location recommendation based on cuisine and price preference

## Usage

1. **Prerequisites**: Ensure you have Python installed along with the required libraries (BeautifulSoup, pandas).
2. **Run the Script**: Execute the Python script to start scraping data from Zomato.
3. **Data Analysis**: Once scraping is complete, perform data analysis using the generated tables to derive insights and recommendations.

Feel free to customize the script and analysis based on specific requirements and preferences.
