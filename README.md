The London Bike Sharing dataset represents data collected from a bike-sharing program in London. These types of datasets usually track how many bikes are rented over time along with environmental and temporal factors that may influence bike demand.

This project focuses on cleaning and preparing the London Bike Sharing dataset for visualization and analysis. The dataset is sourced from Kaggle and contains historical bike-sharing data, including weather conditions and temporal features. The main goal is to transform raw CSV data into a refined dataset that can be directly used for visual storytelling and insights generation, especially in Tableau dashboards.

This project involves the extraction, cleaning, and preparation of the **London Bike Sharing dataset** for visualization and analysis. The final dataset is exported as an Excel file, ready to be used in tools like **Tableau** for generating insights.

The dataset is sourced from Kaggle:
- [London Bike Sharing Dataset on Kaggle](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)

**Project Workflow**

1. **Download Dataset**
   - The dataset is downloaded using the Kaggle API.

2. **Extract Dataset**
   - The downloaded `.zip` file is extracted into a local directory.

3. **Data Loading**
   - The extracted CSV file is loaded into a Pandas DataFrame.

4. **Data Exploration**
   - Preliminary exploration using `.info()`, `.shape()`, `.value_counts()`.

5. **Data Cleaning**
   - Renamed columns for better readability.
   - Converted humidity to percentage.
   - Mapped numerical codes in the `season` and `weather_code` columns to readable values.

6. **Export Cleaned Data**
   - The cleaned dataset is exported to an Excel file (`london_bikes_final.xlsx`) for further visualization in Tableau.
  
**Scope**
- Build Tableau dashboards for visualizing bike demand patterns across seasons, weather conditions, and holidays.
