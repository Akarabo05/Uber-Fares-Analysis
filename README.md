# Uber-Fares-Analysis

# Uber Fares Data Analysis Dashboard and Overview

>This project analyzes the Uber Fares dataset to uncover meaningful trends in fare behavior, ride timing, and high-demand periods the Kaggle Uber Fares dataset. Data preprocessing and feature engineering were carried out using Python, while Power BI was used to design an interactive dashboard that presents key insights through dynamic visualizations.
 
---

## 📊 Tools Used

- **Python (Jupyter Notebook)**— Data cleaning, EDA, feature engineering
- **Power BI Desktop** — Visual dashboards and interactivity
- **Pandas, Seaborn, NumPy**— Core data analysis
- **GitHub** — Project hosting and documentation

---

## Project Structure

| File                        | Purpose                                       |
|-----------------------------|-----------------------------------------------|
| `analysis.ipynb`            | Python notebook: EDA, cleaning, new features  |
| `cleaned_uber_data.csv`     | Final cleaned and enhanced dataset            |
| `Uber_Fares_Dashboard.pbix` | Power BI Dashboard (interactive)              |
| `screenshots/`              | Images of dashboard stages                    |
| `final_report.md`           | Report with insights & recommendations        |
| `README.md`                 | Project documentation                         |

---

## Feature Engineering Highlights

- Extracted:
  - `hour`, `day`, `month`, `weekday`, `year` from `pickup_datetime`
- Created:
  - `peak_hour` indicator
  - `trip_distance` using Haversine formula
- Encoded:
  - Day names (`weekday_label`)
  - Peak vs Off-Peak hours

---

##  Visualizations in Power BI

| Visual                              | Description                            |
|-------------------------------------|----------------------------------------|
| Fare Distribution                   | Histogram and box plot                 |
| Fare by Hour of Day                 | Line and box charts                    |
| Fare vs Distance                    | Scatter plot with hover tooltip        |
| Fare by Weekday                     | Box plot & slicer                      |
| Avg Fare by Passenger Count         | Bar chart                              |
| Interactive Filters                 | Hour, month, passenger count, etc.     |
| Map of Pickups                      | Geo-analysis                           |

---

##  Screenshots

| Screenshot Name            | Visual/Step                        |
|----------------------------|------------------------------------|
| `1_data_load.png`          | CSV loaded into Power BI           |
| `2_powerquery_editor.png`  | Column types and query view        |
| `3_hour_fare_plot.png`     | Fare by hour line chart            |
| `4_weekday_boxplot.png`    | Box plot for day of week           |
| `5_distance_scatter.png`   | Fare vs distance scatterplot       |
| `6_passenger_chart.png`    | Avg fare per passenger             |
| `7_final_dashboard.png`    | Complete dashboard view            |
| `8_interactivity_slicers.png` | Slicer panels for time filters   |

---

##  Key Insights

- Fare amounts are highest during **peak hours (7–9AM and 5–7PM)**
- Most rides have 1–2 passengers; average fare increases slightly with count
- Fare is **linearly correlated with distance**, as expected
- Weekends show slightly higher fare variability

---
## Recommendations
Enhance driver availability during peak hours to effectively meet increased rider demand and reduce wait times.

Introduce off-peak fare discounts to encourage higher ridership during slower periods and balance demand throughout the day.

Leverage ride trend insights to develop targeted marketing campaigns and optimize incentive programs based on rider behavior.

## Dataset Info

**Source**: [Kaggle Uber Fares Dataset](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)  
**Fields**: Fare amount, pickup datetime, location coordinates, passenger count, etc.

---

## Author

**Name**: _[AKARABO Ines ID: 28040]_  
**Course**: Introduction to Big Data Analytics (INSY 8413)  Group A  
**Instructor**: Eric Maniraguha  
**University**: AUCA





