# Uber-Fares-Dataset-Analysis-using-Power-BI
Analysing uber  fare dataset

#Project Overview

This project analyzes the Uber Fares Dataset to identify patterns in fares, ride times, and operational metrics.
The goal is to build an interactive Power BI dashboard and provide insights that can help understand ride demand, pricing trends, and peak hours.

#Tools Used
Python (Pandas, Matplotlib, Seaborn) – for data cleaning, feature engineering, and initial analysis.

Jupyter Notebook – for running Python code step by step.

Power BI Desktop – for advanced visualizations and dashboard creation.


#Dataset
Source: Kaggle – Uber Fares Dataset

Rows: ~200,000

Main Columns:

fare_amount – The fare price in USD.

pickup_datetime – Date and time of ride start.

pickup_longitude, pickup_latitude – Pickup location coordinates.

dropoff_longitude, dropoff_latitude – Drop-off location coordinates.

passenger_count – Number of passengers.


#Steps Followed
 Data Cleaning
  Removed null values and duplicates.

  Converted pickup_datetime to proper datetime format.

  Extracted hour, day, month, year, day_of_week from pickup_datetime.
  

#Exploratory Data Analysis (EDA)
 Calculated descriptive statistics: mean, median, mode, standard deviation.

 Visualized:

 Fare distribution.

 Fare vs. distance relationship.

 Peak ride hours and days.


#Power BI Dashboard
Imported cleaned data (uber_fares_enhanced.csv).

Created visuals:

  Fare distribution (Histogram).

  Peak hour analysis (Bar/Line chart).

  Day-of-week patterns.

  Fare vs. distance (Scatter plot).

  Map visualization for pickup/drop-off locations.

  Added slicers for filtering by month, day, hour.


#Key Insights




Uber-Fares-Analysis/
│
├── data/
│   ├── uber.csv
│   └── uber_fares_enhanced.csv
│
├── notebooks/
│   └── Uber_Fares_Analysis.ipynb
│
├── screenshots/
│   ├── data_cleaning.png
│   ├── fare_distribution.png
│   ├── dashboard_preview.png
│
├── dashboard/
│   └── uber_fares_dashboard.pbix
│
└── README.md







#How to Use This Project
 Clone or download this repository.

 Open the uber_fares_dashboard.pbix file in Power BI Desktop.

 Explore the interactive dashboard with filters and slicers.
 
