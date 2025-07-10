🏨 AtliQ Hospitality Revenue Analysis Using Python
Author: Himanshu Kasaudhan
Domain: Hospitality | Tools: Python, Pandas, Plotly, Data Analysis
#My Practice Project

📌 Objective
This project analyzes historical booking and revenue data for AtliQ Hospitality to:

Uncover key performance insights.

Detect anomalies and outliers.

Recommend data-driven strategies to optimize revenue and efficiency.

🧩 Problem Statement
AtliQ Hospitality operates through multiple booking platforms. However, they lack:

Clarity on which platforms generate or realize the most revenue.

Insights on booking patterns and anomalies.

Strategies to minimize revenue leakages.

This analysis aims to bridge those gaps with actionable intelligence.

📊 Dataset Overview
The analysis is based on five datasets:

fact_bookings.csv – Booking-level data including platforms and revenue details.

dim_rooms.csv – Metadata for different room types.

dim_hotels.csv – Hotel-specific information.

dim_date.csv – Daily granularity for time-series analysis.

fact_aggregated_bookings.csv – Aggregated summary metrics for bookings.

🧹 Data Cleaning & Preparation
Loaded all datasets using Pandas.

Checked for missing values.

Generated descriptive statistics to understand distributions.

Detected outliers in revenue using the IQR method (flagged, not removed).

📈 Key Insights
💵 Revenue by Booking Platform
"Other" platforms lead both in generated and realized revenue.

Makemytrip and Logtrip are next in performance.

🏨 Revenue by Property
AtliQ Exotica tops the chart in realized revenue, indicating high popularity.

🛏️ Revenue by Room Category
RT2 rooms generated the most revenue.

Elite rooms had the highest number of successful bookings.

🌆 Realized Revenue by City
Mumbai is the top contributor.

Hyderabad shows the least performance.

✅ Successful Bookings Analysis
Presidential rooms had the highest successful booking rate at 59.22%, showing high reliability.

🔍 Outlier Detection
Used the Interquartile Range (IQR) method to detect revenue outliers.

Outliers were flagged (not removed) to maintain data integrity.

📌 Course of Action
Prioritize High-Performing Platforms
Allocate resources to platforms with the highest realized revenue.

Analyze Revenue Outliers
Investigate anomalies for potential fraud or system errors.

Improve Platform Conversions
Identify friction points in platforms where realized revenue lags behind generated revenue.

Implement Data Validation Pipelines
Introduce automation for outlier detection and revenue validation.

Forecast with Time-Series Analysis
Use dim_date.csv to analyze trends and predict seasonal performance.

📎 Tools & Libraries
Python

Pandas

Plotly (for dynamic data visualization)

Jupyter Notebook / VS Code (development)

✅ Conclusion
This project delivers actionable business intelligence using Python-based analysis. It demonstrates strong data handling, visualization, and problem-solving skills in a real-world hospitality context.

