# 🏠 Nashville Exploratory Data Analysis (EDA)

This project focuses on the analysis of Airbnb listings and local restaurant data in Nashville, Tennessee. Using data science and exploratory data analysis (EDA) techniques, we aim to uncover insights related to neighborhood trends, affordability, walkability, and the correlation between Airbnb listings and restaurants. This analysis provides actionable insights for both budget-conscious travelers and Airbnb hosts, as well as local stakeholders.

## 🎯 Project Overview

In this project, we explore the following:

- Pricing trends and distribution of Airbnb listings across Nashville neighborhoods
- Correlations between Airbnb listing prices, number of reviews, and other features
- Restaurant density and distribution in Nashville, and its relation to Airbnb listings
- Walkability analysis across different neighborhoods
- Geospatial visualization of Airbnb listings and restaurants to analyze proximity

This analysis ties into the **"Bucket for Your Budget"** initiative, aimed at helping travelers make informed decisions based on their budget, preferences, and desired neighborhood characteristics.

## 👥 Team Members

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/alarakaymak">
        <img src="https://github.com/alarakaymak.png" width="100px;" alt=""/>
        <br />
        <sub><b>Alara Kaymak</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/seemadhungana">
        <img src="https://github.com/seemadhungana.png" width="100px;" alt=""/>
        <br />
        <sub><b>Seema Dhungana</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/marymorkos">
        <img src="https://github.com/marymorkos.png" width="100px;" alt=""/>
        <br />
        <sub><b>Mary Morkos</b></sub>
      </a>
    </td>
  </tr>
</table>

## 📁 Repository Structure

```
├── EDA_consolidated_code.ipynb    # Main Jupyter notebook containing all analysis
├── README.md                      # Project documentation
├── listings.csv                   # Airbnb listings dataset
├── nashville_businesses.csv    # Yelp Businesses dataset
├── nashville_restaurants.csv      # Restaurant dataset
├── nashville_zipcodes.geojson    # Nashville zipcodes info
└── neighbourhoods.geojson            # Neighborhood information
```

## 📊 Data Sources

1. **Airbnb Listings** (`listings.csv`): Contains detailed information about Airbnb properties, including room type, price, neighborhood, and reviews.
2. **Nashville Restaurants** (`nashville_restaurants.csv`): Details about restaurants in Nashville, including categories, ratings, and location.
3. **Nashville Businesses** (`nashville_businesses.csv`): Details about businesses in Nashville, including categories, ratings, and location. (Includes restaurants)
4. **Neighborhood Data** (`neighbourhoods.geojson`): Information about Nashville's neighborhoods for geographic analysis.

## 📈 Analysis and Visualizations

Our analysis is contained in the `EDA_consolidated_code.ipynb` notebook, which includes:

- 💰 Price distribution analysis across Nashville neighborhoods
- ⭐ Correlation studies between listing prices and reviews
- 🍽️ Restaurant density analysis

## 🚀 How to Run the Project

1. **Clone the Repository** 📥
```bash
git clone https://github.com/marymorkos/nashville-eda.git
cd nashville-eda
```

2. **Install Required Dependencies** 🔧
```bash
pip install jupyter pandas numpy folium seaborn matplotlib
```

3. **Open the Jupyter Notebook** 📓
```bash
jupyter notebook EDA_consolidated_code.ipynb
```
