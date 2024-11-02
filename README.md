# Pittsburgh-Apartment-Choice-Evaluation-Tool
This project focuses on evaluating apartment choices for Pittsburgh residents using Python. The program integrates data-driven analysis to help users make informed decisions based on key factors such as rental prices, commuting situations, nearby amenities, and neighborhood safety.

## Project Overview

The primary objective of this project is to assist Pittsburgh residents in selecting the best apartment options by considering various aspects that influence the quality of living. By leveraging Python libraries and APIs, the application provides a comprehensive analysis to help users make data-driven choices.

## Key Features

- **Rental Price Analysis**: Web scraping is used to gather live rental prices from various sources to provide users with up-to-date information.
- **Commute Time & Cost Calculation**: Utilizes Google Maps API and geopy to compute commute times and costs across different modes of transportation for each apartment.
- **Local Amenities Aggregation**: Identifies nearby amenities such as grocery stores, parks, gyms, and schools, helping users understand the apartment's convenience.
- **Neighborhood Safety Assessment**: Analyzes historical crime data using CSV processing to evaluate the safety level of each neighborhood.
- **Apartment Ranking**: The final output ranks apartments based on user-defined weightings for each factor, enabling a customized recommendation.
- **Interactive Mapping**: Visualizes apartment locations and nearby amenities on an interactive map using Folium for easy reference.

## Models and Techniques

- **Data Collection**: Uses `BeautifulSoup` for web scraping live rent prices, and `googlemaps` API to retrieve commute information.
- **Data Processing**: `pandas` and `geopy` are used for data manipulation and geographical calculations.
- **Data Visualization**: `matplotlib` and `seaborn` provide visualizations of crime data and other statistics, making it easier to interpret safety and neighborhood metrics.

## Evaluation Metrics

The program evaluates apartment choices using the following metrics:

- **Rental Price**: Comparison based on current market rent prices.
- **Commute Cost and Time**: Assessment of commuting feasibility based on distance, time, and transport modes.
- **Safety Score**: Calculated from historical crime data to gauge neighborhood safety.
- **Amenities Proximity**: Counts and ranks nearby amenities to understand convenience.

## Libraries and APIs Used

- `googlemaps`: To calculate commute times and distance.
- `pandas`: For data analysis and manipulation.
- `BeautifulSoup`: For scraping live rent prices from websites.
- `geopy`: For geolocation and distance calculations.
- `matplotlib` and `seaborn`: For data visualization.
- `folium`: For interactive mapping and apartment location visualization.

## Conclusion

This Python-based tool serves as a practical solution for residents navigating the complexities of apartment hunting in Pittsburgh. By integrating various data sources and providing customizable rankings, the program enables users to find an apartment that best matches their personal preferences and lifestyle.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/username/Pittsburgh_Apartment_Choice_Evaluator.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Set up API keys for Google Maps API and add them to the configuration file.
4. Run the main script to start evaluating apartments based on your criteria.
