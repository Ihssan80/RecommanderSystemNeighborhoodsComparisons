# Neighborhood Clustering Project

## Project Overview
The main goal of this project is to analyze neighborhoods in three different cities (Cairo, Istanbul, and Marrakesh), categorize them based on the types of venues they contain, and then cluster these neighborhoods to understand their similarities and differences.

## Data Collection
Data about neighborhoods in the three cities was collected from Wikipedia using web scraping techniques. The data was then geocoded to obtain latitude and longitude information for each neighborhood.

## Neighborhood Clustering
The neighborhoods were clustered using the K-Means clustering algorithm. The clustering was performed separately for each city and for all cities combined. The most common venue categories for each neighborhood were used as features for clustering.

## Visualization
The results of the clustering were visualized on interactive maps using the Folium library. Each neighborhood was marked with a circle, and neighborhoods belonging to the same cluster were assigned the same color.

## Usage
To run this project, you can follow these steps:

1. **Install the necessary dependencies (see Dependencies section).**
2. **Run the Python script provided to collect data, perform clustering, and generate maps.**
3. **Examine the generated maps to understand neighborhood clusters in the three cities.**

## Dependencies
This project relies on the following Python libraries and tools:

- pandas
- numpy
- requests
- BeautifulSoup
- geopy
- folium
- scikit-learn

You can install these dependencies using pip:

```bash
pip install pandas numpy requests beautifulsoup4 geopy folium scikit-learn
