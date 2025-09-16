# 🌏 Indian City Air Quality Analysis  

This project analyzes daily air quality data collected from multiple Indian cities.  
The goal is to clean the dataset, perform Exploratory Data Analysis (EDA), and generate actionable insights and visualizations about pollution patterns and air quality indices.
---
## 🚀 Project Overview  
This project replicates and extends a COVID-19 time-series analysis style on an air quality dataset.  
It answers 10 key EDA questions and creates 5 impactful visualizations using Python’s data science stack.

---

## 🎯 Objectives  
- Identify cities with the highest and lowest average AQI over time.  
- Analyze correlations between major pollutants and AQI.  
- Study temporal (yearly) and seasonal (monthly) patterns of air quality.  
- Detect improvement or worsening of AQI levels across cities.  
- Communicate insights through clear, impactful visualizations.  

---

## 📊 Dataset  
- **Source:** Indian City Air Quality Dataset (`city_day.csv`)  
- **Features:** City, Date, PM2.5, PM10, NO2, SO2, CO, O3, AQI, AQI_Bucket  
- **Size:** ~29,000 rows x 16 columns  

---

## 🛠️ Methodology  
- **Data Cleaning:**  
  - Filled missing numeric values with median.  
  - Converted `Date` to datetime.  
  - Removed duplicates.  
- **EDA:**  
  - Formulated 10 exploratory questions covering city-level, pollutant-level, and temporal analysis.  
  - Used pandas, seaborn, and matplotlib to compute statistics and generate plots.  

---

## ❓ Key EDA Questions  
1. Which cities have the highest average AQI and which have the lowest over the entire period?  
2. How do major pollutants (PM2.5, PM10, NO2, SO2, CO, O3) correlate with each other?  
3. How has the average AQI changed over the years for all cities combined?  
4. Are there seasonal patterns (monthly variation) in pollutants like PM2.5 and PM10?  
5. Which cities show improvement in AQI over time, and which are getting worse?  
6. Which pollutant contributes the most to poor AQI levels in each city?  
7. Which cities recorded the highest spikes (max values) in PM2.5 or AQI during the time period?  
8. How do metro cities compare to non-metro cities in terms of average AQI?  
9. What is the distribution of AQI_Bucket categories across all cities?  
10. What are the top 10 most polluted days across all cities and which cities did they occur in?  

---
## 📈 Visualizations  
- **Bar Chart:** Top 10 Cities with Highest Average AQI  
- **Heatmap:** Correlation Between Pollutants & AQI  
- **Line Chart:** Yearly AQI Trend (All Cities Combined)  
- **Boxplots:** Monthly Variation of PM2.5 & PM10  
- **Pie Chart:** Distribution of AQI_Bucket Categories  

---

## 💡 Insights  
- Metro cities like Delhi, Mumbai, and Kolkata show consistently higher AQI levels.  
- PM2.5 and PM10 are the dominant pollutants correlating most strongly with AQI.  
- Seasonal spikes in pollutants occur during winter months.  
- Some cities are improving over time while others are worsening.

## 🖥️ How to Run  

1. Clone this repository
2. Install requirements
3. Open the notebook
   
