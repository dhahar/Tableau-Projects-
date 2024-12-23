# Short Term Rent Tableau-Project

# 

  # Project Overview
This analysis provides insights into pricing trends and revenue for short-term rental listings. The dataset focuses on the following key metrics:

 # Description of  the Dataset
 # 1. Listing Details:
id: Unique identifier for the property listing.
listing_url: URL of the listing on the platform.
scrape_id: ID assigned to the scraping instance.
last_scraped: Date the listing data was last scraped.
name: Name of the property.
summary: A brief description of the property.
space: Description of the space available in the listing (e.g., bedrooms, bathrooms).
description: Detailed description of the property.
experiences_offered: Types of experiences or activities offered by the host (e.g., tours, cooking classes).
neighborhood_overview: Overview of the neighborhood where the property is located.
notes: Any additional notes provided by the host.
transit: Information about public transport accessibility near the property.
thumbnail_url, medium_url, picture_url, xl_picture_url: URLs for images of the listing in different resolutions.
# 2. Host Details:
host_id: Unique identifier for the host.
host_url: URL of the host’s profile page.
host_name: Name of the host.
host_since: Year the host started listing properties.
host_location: Location of the host.
host_about: Description of the host provided by them.
host_response_time: Average response time of the host.
host_response_rate: Percentage of messages the host responds to.
host_acceptance_rate: Percentage of booking requests accepted by the host.
host_is_superhost: Whether the host is a verified Superhost.
host_thumbnail_url, host_picture_url: URLs for images of the host's profile.
# 3. Location Details:
street: Street address of the property.
neighborhood, neighborhood_cleansed: Neighborhood where the property is located (raw and cleaned data).
city, state, zipcode, country_code, country: Geographical information about the listing’s location.
latityeude, longitude: Geographic coordinates of the property.
is_location_exact: Indicates if the location provided is accurate.
# key findings 
Average Price per Bedroom
Average Price by Zip Code
Revenue by Year
 # 1. Average Price per Bedroom
This analysis calculates the average price per bedroom based on the dataset:

1 Bedroom: $96.2
2 Bedrooms: $175.4
3 Bedrooms: $249.7
4 Bedrooms: $315.4
5 Bedrooms: $450
6 Bedrooms: $584.8
From the data, we can observe that as the number of bedrooms increases, the average price also rises, indicating that larger properties tend to have higher rental prices.

 # 2. Average Price by Zip Code
The average price for rental listings in different zip codes reveals the following:

Most Expensive: Zip code 98134 with an average price of $206.6.
Middle Price: Zip code 98144 with an average price of $109.9.
Cheapest: Zip code 98125 with an average price of $64.7.
This data indicates that the prices vary significantly depending on the location, with zip code 98134 being the most expensive and 98125 being the least expensive.

 # 3. Revenue by Year (2016)
Revenue generated over the year 2016 is analyzed by dividing the year into four quarters:

First Quarter (Jan-Mar): $1,896,838
Second Quarter (Apr-Jun): $1,991,762
Third Quarter (Jul-Sep): $2,009,293
Fourth Quarter (Oct-Dec): $1,818,398
The revenue shows steady growth from the first to the third quarter, followed by a slight decrease in the fourth quarter. This could be influenced by seasonal trends or external factors impacting demand in the last months of the year.

 # Conclusion
The data provides valuable insights into pricing trends based on bedroom count and zip code location, along with revenue generation patterns throughout 2016. The findings suggest that both the size of the property and its geographical location significantly affect rental prices, and revenue tends to be higher in mid-year periods.

