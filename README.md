#  Flight Ticket Price Analysis with Python & Power BI

This project presents an in-depth analysis of flight ticket prices using Python for Exploratory Data Analysis (EDA) and Power BI for visual storytelling. By examining key factors that influence flight prices, this project aims to offer actionable insights for travelers, airlines, and data enthusiasts.

---

##  Overview

Air travel pricing is dynamic and influenced by various factors such as the airline, journey time, duration, number of stops, and booking date. Understanding these patterns can help optimize travel planning and cost-saving strategies. This project explores a flight dataset through two major components:

- **Python-based EDA**: Cleaning, transforming, and visualizing the data using Python libraries.
- **Power BI Dashboard**: An interactive report highlighting key trends and comparisons.

---

##  Files Included

| File | Description |
|------|-------------|
| `Flight_Ticket_EDA.ipynb` | Jupyter Notebook containing data loading, cleaning, feature engineering, and visual analysis using Python. |
| `Flight_Ticket(Power_Bi).pbix` | Power BI file showcasing interactive visualizations and summary metrics for flight pricing. |

---

##  Objectives

- Analyze how various features (airlines, stops, duration, time of day) affect flight prices.
- Visualize trends in pricing across different cities, dates, and airlines.
- Identify patterns that can help users choose cost-effective flights.
- Build an intuitive dashboard to present findings clearly and interactively.

---

## Tools & Technologies Used

- **Python**
  - Libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`, `datetime`
- **Jupyter Notebook** – for writing and running Python code
- **Power BI Desktop** – for interactive data visualization and dashboard creation


---

##  Exploratory Data Analysis (EDA)

In the notebook `Flight_Ticket_EDA.ipynb`, the following steps were performed:

1. **Data Cleaning**:
   - Handled missing values
   - Converted categorical and datetime features
   - Extracted useful features from the date/time columns

2. **Feature Engineering**:
   - Created new columns like journey day/month, duration in minutes, time of departure/arrival, etc.

3. **Visualization**:
   - Correlation heatmaps
   - Distribution plots for price
   - Box plots for price by airline and number of stops
   - Line graphs for price trends over time

4. **Key Observations**:
   - Prices vary drastically between airlines
   - Flights with multiple stops are generally cheaper but take longer
   - Evening and night flights tend to be less expensive than morning ones

---

##  Power BI Dashboard

The `Flight_Ticket(Power_Bi).pbix` file offers an interactive experience to explore the data with:

- Bar charts: Average ticket price by airline and source/destination
- Slicers: Filter data by airline, source city, stops, and more
- Line charts: Price trends over journey dates
- Pie charts: Flight distribution by number of stops

## Dataset Source

The dataset used in this project was sourced from Kaggle:https://www.kaggle.com/datasets/soylevbeytullah/flight-prices/data


