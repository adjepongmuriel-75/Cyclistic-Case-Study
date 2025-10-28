# 🚲 Cyclistic Bike-Share Case Study

## 📌 Business Task
Analyze and compare usage patterns between casual riders and annual members to inform marketing strategies aimed at converting casual riders into members.

## 📊 Data Sources
- Divvy bike-share trip data (Q1 2019 & Q1 2020)
- Tools used: Google Sheets and SQL

## 🧹 Data Cleaning & Transformation
- Removed duplicates and irrelevant columns
- Created `ride_length` and `day_of_week` fields
- Merged monthly datasets in BigQuery
- Calculated summary statistics and trends

## 📈 Key Insights
- **Members**: 716,592 rides, avg. duration **12.83 mins**
- **Casual Riders**: 67,692 rides, avg. duration **89.3 mins**
- Members ride more during weekdays; casual riders peak on weekends

## 📊 Visualizations

### Total Rides & Average Duration by Rider Type
![Total Rides and Average Duration](visuals/total_rides_avg_duration.png)

### Ride Count by Day of Week
![Ride Count by Day](visuals/ride_count_by_day.png)

## 📄 Full Report
[Download the full case study (PDF)](documentation/cyclistic_case_study.pdf)

## 🎯 Recommendations
- Offer weekend promotions to casual riders
- Emphasize member benefits for frequent commuters
- Promote scenic routes and social experiences to convert casual users


Updated README with summary and visuals
