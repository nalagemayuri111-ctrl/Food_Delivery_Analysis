# Food Delivery Analysis

Analysis of 41,953 food delivery records to understand what affects delivery time, using Python, MySQL, Excel and Power BI.

## Project Overview

Delivery time is a key measure of service quality for food delivery platforms. In this project I cleaned a food delivery dataset, analyzed it with Python (Pandas) and SQL, and built a Power BI dashboard to show how delivery time changes with traffic, city, vehicle type and order type.

## Dataset

- **Records:** 41,953 food delivery orders
- **Source:** [add the dataset name and link]
- **Cleaned file:** `food_delivery_final.csv`
- **Key fields:** delivery time (minutes), road traffic density, city type, weather conditions, vehicle type, order type, delivery person age and ratings, restaurant and delivery locations

## Tools Used

- Python (Pandas) for data cleaning and analysis
- MySQL for SQL-based analysis
- Microsoft Excel
- Power BI for the dashboard

## What I Did

1. **Cleaned the data** with Python and Pandas: [list your real steps, e.g. fixed data types, converted delivery time to a numeric column, handled missing values].
2. **Handled missing values in Power BI:** replaced `NaN` entries in city, traffic and weather with "Unknown" so the charts show them as a separate group instead of raw errors.
3. **Analyzed delivery time** across traffic, city, vehicle type and order type using Pandas and SQL queries in MySQL.
4. **Built a Power BI dashboard** with summary cards, charts and filters for city, traffic density and weather conditions.

## Key Insights

- The average delivery time across all 41,953 deliveries is about **26 minutes**.
- **Traffic matters most:** deliveries in "Jam" traffic average about 31 minutes, compared with about 21 minutes in low traffic.
- **City type:** Semi-Urban deliveries take the longest, about 50 minutes on average, compared with about 27 in Metropolitan and 23 in Urban areas.
- **Order type makes almost no difference:** meals, snacks, buffets and drinks all average about 26 minutes.
- **Motorcycles** handle the most deliveries, followed by scooters, electric scooters and bicycles.
- [Add one insight on weather, from your own analysis]

## Dashboard Preview

![Food Delivery Analytics Dashboard](images/dashboard.png)

## Repository Files

| File | Description |
|---|---|
| `food_delivery_analysis.ipynb` | Python/Pandas cleaning and analysis |
| `food_delivery_final.csv` | Cleaned dataset |
| `Food_Delivery_Analytics.xlsx` | Excel workbook used as the Power BI data source |
| `food_delivery_analysis.pbix` | Power BI dashboard (open in Power BI Desktop) |

## How to Run

1. Open `food_delivery_analysis.ipynb` in Jupyter Notebook or VS Code.
2. Install the libraries: `pip install pandas numpy matplotlib`
3. Open `food_delivery_analysis.pbix` in Power BI Desktop. If it asks for the data source, point it to `Food_Delivery_Analytics.xlsx` from this repository.

## Author

Mayuri Nalage | nalagemayuri111@gmail.com
