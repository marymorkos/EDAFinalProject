# Nashville Exploratory Data Analysis (EDA)

This project focuses on the analysis of Airbnb listings and local restaurant data in Nashville, Tennessee. Using data science and exploratory data analysis (EDA) techniques, we aim to uncover insights related to neighborhood trends, affordability, walkability, and the correlation between Airbnb listings and restaurants. This analysis provides actionable insights for both budget-conscious travelers and Airbnb hosts, as well as local stakeholders.

## Project Overview

In this project, we explore the following:

- Pricing trends and distribution of Airbnb listings across Nashville neighborhoods
- Correlations between Airbnb listing prices, number of reviews, and other features
- Restaurant density and distribution in Nashville, and its relation to Airbnb listings
- Walkability analysis across different neighborhoods
- Geospatial visualization of Airbnb listings and restaurants to analyze proximity

This analysis ties into the **"Bucket for Your Budget"** initiative, aimed at helping travelers make informed decisions based on their budget, preferences, and desired neighborhood characteristics.

## Team Members

- **Alara Kaymak**
- **Seema Dhungana**
- **Mary Morkos** (Project Lead)

## Data Sources

1. **Airbnb Listings**: A dataset containing information about Airbnb properties, including room type, price, neighborhood, and reviews.
2. **Nashville Restaurants**: A dataset containing details about restaurants in Nashville, including categories, ratings, and location.
3. **Neighborhood Data**: Additional data regarding Nashville's neighborhoods for geographic analysis.

## Project Structure

```
├── README.md
├── notebooks/
│   ├── EDA_Analysis.ipynb    # Jupyter notebook with the exploratory data analysis
├── data/
│   ├── listings.csv          # Airbnb listings data
│   ├── nashville_restaurants.csv    # Restaurant data
├── visuals/
│   ├── price_distribution.png    # Visualization of price distribution
│   ├── price_vs_reviews.png      # Scatter plot of price vs reviews
│   ├── correlation_heatmap.png   # Correlation heatmap
├── requirements.txt          # List of dependencies for the project
└── app.py                    # Streamlit app for interactive exploration (if applicable)
```

## How to Run the Project

### 1. **Clone the Repository**
```bash
git clone https://github.com/your-username/nashville-eda.git
cd nashville-eda
```

### 2. **Install Dependencies**
Make sure you have Python 3.x installed. Then install the necessary dependencies from the requirements.txt file:
```bash
pip install -r requirements.txt
```

### 3. **Running the Jupyter Notebook**
Start the Jupyter Notebook to explore the analysis:
```bash
jupyter notebook notebooks/EDA_Analysis.ipynb
```

### 4. **Streamlit App (Optional)**
If you're running a Streamlit app for the interactive recommendations, use the following command to launch it:
```bash
streamlit run app.py
```

## Visualizations

This repository includes the following visualizations:

- Price Distribution Across Neighborhoods: Box plot displaying how prices vary across different neighborhoods in Nashville.
- Price vs. Number of Reviews: Scatter plot showing the correlation between listing prices and the number of reviews.
- Correlation Heatmap: Visualizing the relationships between numeric variables such as price, reviews, and others.
- Restaurant Density by Neighborhood: Bar chart showing the number of restaurants in each neighborhood.
- Geospatial Visualizations: Folium map showing the locations of Airbnb listings and restaurants in Nashville.
