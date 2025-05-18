
# 📍 Location-Based Restaurant Analysis

This project performs a comprehensive location-based analysis of restaurant data using Python. It includes data cleaning, visualization, and geospatial mapping to uncover insights about restaurant distribution, popularity, cost, and cuisine trends across different Indian cities.

## 📁 Dataset

The dataset used includes information such as:

- Restaurant name
- City
- Latitude and Longitude
- Average cost for two
- Aggregate rating
- Cuisine types

> Note: The dataset is loaded from a local CSV file named `Dataset  (1).csv`.

## 🧰 Technologies Used

- **Python**
- **Pandas** - for data manipulation
- **Matplotlib & Seaborn** - for data visualization
- **Folium** - for interactive maps
- **MarkerCluster (Folium plugin)** - to cluster location markers on the map

## 📊 Features & Analysis

- ✅ Dropped rows with missing geolocation data
- 🗺️ Created an interactive map centered on India showing restaurant locations
- 📌 Clustered restaurant markers using `MarkerCluster` for better map readability
- 📈 Visualized the top 10 cities with the most restaurants
- 📊 Aggregated city-wise insights:
  - Average cost for two
  - Average rating
  - Number of restaurants
  - Most common cuisine

## 🔍 Output

- An interactive map rendered using Folium
- A bar chart showing cities with the most restaurants
- A CSV file (`city_insights.csv`) summarizing key metrics per city

## 📦 File Structure

```bash
location_based_anyalsis.py       # Main analysis script (converted from Colab)
Dataset  (1).csv                 # Source dataset (not included here)
city_insights.csv                # Output with city-level insights
```

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/location-based-analysis.git
   cd location-based-analysis
   ```

2. Make sure all required Python packages are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn folium
   ```

3. Run the script:
   ```bash
   python location_based_anyalsis.py
   ```

> ⚠️ Ensure that `Dataset  (1).csv` is in the correct directory when running the script.

## 📌 Credits

Originally developed in Google Colab. Converted to a standalone Python script for GitHub deployment.
