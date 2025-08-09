# Hospitality-Revenue-Insights
![Dashboard Preview](https://github.com/giriaman610/Hospitality-Revenue-Insights-Dashboard/blob/main/Hospitality.%20Analytics.png)


## Project Background
A famous  hotel group owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, They are losing their market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of hotel group  wanted to incorporate "Business and Data Intelligence” to regain their market share and revenue.

### 3.	Tech Stack

The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
•	📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.

### 4.	Data Source
The dataset used for this project was sourced from publicly available hospitality industry data repositories and simulated transactional records relevant to hotel bookings, room occupancy, and revenue metrics. It includes key performance indicators (KPIs) such as Average Daily Rate (ADR), Revenue per Available Room (RevPAR), and Occupancy Rate, which are commonly used to analyze revenue trends in the hospitality sector.

Data on ~500 Hotel booking Sites  around the world, including details on their location, prices, Occupancy, Revenue  etc.

## Executive Summary
This project examines key hospitality performance metrics such as ADR, Occupancy, RevPAR, Revenue, Realisation, and DSRN over multiple weeks to uncover actionable insights for revenue optimization. While the Average Daily Rate (ADR) remains remarkably stable (with just a ₹152 range), the Revenue per Available Room (RevPAR) fluctuates significantly by ₹2,073 due to changing occupancy, which ranges from 50.5% to 67.0%. There is a perfect positive correlation between Occupancy% and RevPAR (correlation = 1.00), indicating that boosting occupancy is the most effective lever for increasing room revenue.<br>  

## Insights Deep-Dive

### ADR Trends by Week and Category

- The Business category consistently shows the highest ADR, staying around ₹12,900–₹13,000 across all weeks.
- The Business segment commands a ~2.4% premium over Luxury.
- Business travelers consistently pay higher rates with minimal volatility. The ~2% fluctuation across weeks indicates stable pricing potential.

  ![Annual Sales and Growth Rates](https://github.com/giriaman610/Hospitality-Revenue-Insights-Dashboard/blob/main/Screenshot%202025-08-07%20150201.png)


### Key Metric Summary (Across 16 Weeks)

- DR fluctuates by less than 1.2% from min to max (₹152), indicating strong price consistency.
- Despite a stable ADR, RevPAR has a wide range of ₹2,072.94, suggesting that Occupancy drives most of the revenue variance.
- ADR shows a slight negative correlation with both (−0.24 to −0.27), indicating that increasing prices may slightly reduce occupancy.
- Lowest occupancy is 50.49% while highest is 66.97%.
- If low-occupancy weeks matched high-occupancy levels, RevPAR could increase by ~₹2,000, a potential +28% revenue gain per room.


### Realisation% and ADR by platform

- Logtrip (70.59%), journey (70.52%), and direct online (70.27%) are the top 3 in terms of realization.
- Direct offline leads with the highest ADR at ₹12,791.17 despite being 4th in realization.
- Their ADRs are also significantly lower (around ₹11,800), indicating lower profitability.
- Direct channels (online and offline) perform competitively:

- Realisation % ~70.2–70.27%
- ADR ~₹12,633–₹12,791

### Performance Summary of 25 Properties

- Top revenue properties are earning ~3x more than the lowest earners.
- Some properties with ADR > ₹14,000 still have occupancy below 60%.
- The average cancellation rate is ~25%, which can significantly impact net revenue.
- Properties with higher average ratings (~4.3) also show higher RevPAR and occupancy.
- Across all properties, the Realisation % is narrowly ranged (69.13%–71.13%).























