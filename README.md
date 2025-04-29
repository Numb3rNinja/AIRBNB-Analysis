# Project Background
With the rapid growth of the short-term rental industry, platforms like Airbnb have transformed the way people travel, offering unique experiences beyond traditional hotels. As the market becomes increasingly competitive, understanding the dynamics of pricing, host performance, and guest preferences has become essential for both property owners and travelers.
This project was inspired by the desire to explore the global landscape of Airbnb listings and uncover what drives affordability, popularity, and success on the platform. By analyzing real-world data from diverse countries and host profiles, the goal was to gain a clearer picture of how Airbnb functions across different regions and to identify trends that reflect the evolving demands of modern tourism.

Key Insights and Recommendations Focused on:
- **Country-Level Price Trends:** An evaluation of country-level pricing to understand which markets offer the most budget-friendly listings and where pricing opportunities exist for expansion or targeting.
- **Hosting Activity and Listing Volume:** Analysis of host listing distribution to identify the scale of host operations and assess the competitive landscape among hosts.
- **Price vs. Guest Capacity and Bedrooms:** Evaluation of how pricing scales with property size to help inform dynamic pricing strategies and optimal listing configurations.
- **Price vs. Ratings and Guest Satisfaction:** Analysis of the relationship between pricing and customer ratings to determine whether higher prices correlare with better guest experience.

The Excel dashboard and table for this project can be found [here](https://github.com/Numb3rNinja/Excel-Dashboard-and-Table-AIRBNB-Analysis-.git)

## Data Structure & Initial Checks

The AIRBNB main data structure for this project involved a single Excel table with 12808 rows, containing key fields such as:
price
country
bathrooms
beds
guests
toilets
bedrooms
studios
checkin
checkout

Key early checks included:
To ensure data reliability and readiness for analysis, the following preliminary checks were conducted:
- **Null Value Check:** Verified that critical columns such as country, average price, and average rating did not contain null or missing values. Minor missing data was excluded from the aggegation metric.
- **Data Type Validation:** Ensure numeric fields (e.g., price, ratings, reviews) were properly formatted and free from text entries or symbols that could disrupt calculations.
- **Duplicate Removal:** Checked for duplicate country entries or host records to prevent overrepresentation in summaries and visualizations.
- **Consistency Check:** Confirmed that countries with extremely low listing counts (e.g., one listing) were not incorrectly aggregated or mislabeled.

# Executive Summary
## Overview of Findings
1. Affordability and Market Gaps – Several countries offer exceptionally low average prices (e.g., Jordan and Georgia), representing strong opportunities for Airbnb to grow its presence in underpenetrated regions with low competition and high value for travelers.

2. Host Distribution and Platform Use – The data shows a clear divide between casual hosts and large-scale operators, with a few managing thousands of listings. This duality suggests a maturing marketplace that supports both entrepreneurial individuals and professional property managers.

3. Price Sensitivity by Property Attributes – Guest capacity and bedroom count significantly impact listing price, but diminishing returns appear beyond certain thresholds. This informs smarter capacity planning and pricing optimization strategies for hosts and platform algorithms.

4. Guest Experience Consistency – Price does not determine guest satisfaction. High average ratings are consistently achieved across price tiers, emphasizing the importance of service quality over cost.

For a stakeholder like a Regional Market Manager or Pricing Strategist, these insights highlight the importance of tailoring expansion plans, host support programs, and pricing tools to fit the nuanced behavior of local markets and listing types.












