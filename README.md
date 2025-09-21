# OLA_DASHBOARD
This OLA dashboard provides a comprehensive view of bookings, cancellations, revenues, vehicle types, and ratings for July 2024.
### 1.	Project Title / Headline
"Ola Ride Analytics: Performance and Insights (July 2024)"
Example: 
This title reflects the comprehensive data analysis of Ola's ride services, including total bookings, successful bookings, cancellations, revenue, vehicle types, ratings, and payment methods, covering the period from July 1 to July 30, 2024. 

### 2.	Short Description / Purpose
The purpose of "Ola Ride Analytics: Performance and Insights (July 2024)" is to analyze and visualize key performance metrics, including total bookings, successful bookings, cancellations, revenue, vehicle type distribution, customer and driver ratings, and payment methods, to provide actionable insights for optimizing Ola's ride-sharing services during the specified period. 

### 3.	Tech Stack
List the key technologies used to build the dashboard.
Example:
The dashboard was built using the following tools and technologies:<br>
•	📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
•	📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.<br>
•	🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.<br>
•	📝 Data Modeling – Relationships established among tables  Date_Key, Location_Key, Temperature_Fahrenheit, Temperature_Celsius, Humidity_Percentage, WindSpeed_MPH, Precipitation_Chance_Percentage, AQI (Air Quality Index) to enable cross-filtering and aggregation.<br>
•	📁 File Format – .pbix for development and .png for dashboard previews.

### 4.	Data Source<br>
More info on where the data comes from and how it’s structured.<br>
Source: Ola’s ride-booking system database for the period July 1–30, 2024.<br>
Extraction: Pull key insights (like total bookings, cancellations, daily trends) and output JSON formatted for dashboard use.<br>
Transformation:  <br>
-Read the CSV → Extract booking records (date, status, etc.).<br>
-Aggregate → Calculate totals, successful bookings, cancellations (by driver, by customer, driver not found).<br>
-Trend → Summarize daily ride counts for "Ride Volume Over Time".<br>
-Output → Produce structured dashboard-ready JSON.<br>

### 5.	Features / Highlights
1. Automated Data Restructuring
-Raw CSV rows are transformed into structured JSON objects.
-Data is grouped by date and status for easier visualization.
2.Dashboard-Ready Format
-JSON includes summary totals, status breakdown, and daily ride volume trends.
-Can be directly used in BI tools, web dashboards, or APIs.
3.Booking Status Classification
-Categories: Success, Canceled by Driver, Canceled by Customer, Driver Not Found.
-Each category shows count and percentage share.
4.Time-Series Insights
-Rides are aggregated day by day for trend charts.
-Helps track peaks, lows, and cancellation spikes.
5.Scalable & Flexible
-Works for any time period, not just July 2024.
-Can adapt to new booking statuses or additional metrics (e.g., revenue, distance).
6.Supports Analytics & Reporting
-Ready JSON can power:<br>
-📊 BI dashboards (Power BI, Tableau)<br>
-📈 Web visualizations (D3.js, Recharts)<br>
-📂 APIs for mobile apps<br>
 
•Business Problem
The raw booking data in CSV form does not provide clear, actionable insights. Without structured analysis, Ola cannot effectively track booking success rates, identify high cancellation patterns, or monitor daily demand trends. This lack of visibility leads to inefficiencies in resource allocation, reduced customer satisfaction, and missed opportunities to improve operational performance and revenue.

Key questions such as:<br>
✅ What is the total number of bookings in the selected time period?<br>
✅ How many bookings were successful versus canceled (by driver, by customer, or due to no driver found)?<br>
✅ What is the percentage breakdown of each booking status?<br>
✅ How do daily booking volumes change over time — where are the peaks and lows?<br>
✅ Which days show the highest cancellations, and what patterns can be observed?<br>
✅ How does the success rate trend over the month?<br>
✅ Are cancellations concentrated around certain dates, times, or customer segments?<br>

•Goal of the Dashboard
The dashboard aims to provide a comprehensive overview of OLA's ride booking performance for July 2024, enabling stakeholders to monitor key metrics such as total bookings, success rates, cancellation breakdowns by cause, and daily ride volume trends. This facilitates identifying operational inefficiencies (e.g., high "Driver Not Found" incidents), assessing customer and driver behavior, and supporting data-driven decisions to enhance service reliability, reduce cancellations, and optimize revenue generation

•Business Impact & Insights
  1. Booking Performance:
I can calculate the total number of bookings in July.
I can determine the overall success rate of rides by analyzing the Booking_Status column.
I can calculate the total booking value generated.

2. Ride Dynamics & Customer Behavior:
I can analyze the most popular vehicle types (Vehicle_Type).
I can identify the most frequent pickup and drop-off locations (Pickup_Location, Drop_Location).
I can gain insights into customer ratings (Customer_Rating) and driver ratings (Driver_Ratings) to understand satisfaction levels.
I can analyze the distribution of different payment methods (Payment_Method) to understand customer preferences.

3. Operational Efficiency:
I can analyze the V_TAT (Vehicle Turnaround Time) and C_TAT (Customer Turnaround Time) to assess operational efficiency and identify potential bottlenecks.
I can break down the reasons for cancellations, particularly Canceled_Rides_by_Customer and Canceled_Rides_by_Driver, to understand the primary pain points in the service.
I can also investigate the number and reasons for Incomplete_Rides.

4. Potential Business Impact:
By analyzing the booking values of successful rides and comparing them to those that were canceled, I can estimate the potential revenue loss.
I can also identify specific locations or times with high cancellation rates to pinpoint areas for operational improvement.
Analyzing the relationship between driver/customer ratings and cancellation rates could reveal opportunities to improve the user experience and reduce churn.

### 6.	Screenshots / Demos
Show what the dashboard looks like. - ![Alt text](https://github.com/PawanKumar7264/OLA_DASHBOARD/blob/main/ola.pbix)
Example: ![Dashboard Preview](https://github.com/PawanKumar7264/OLA_DASHBOARD/blob/main/Snapshort_%20dashboard%20.png)<br>
 ![Dashboard Preview](https://github.com/PawanKumar7264/OLA_DASHBOARD/blob/main/snapshot_vechicle.png)<br>
 ![Dashboard Preview]( https://github.com/PawanKumar7264/OLA_DASHBOARD/blob/main/snapshot_revenu%20(2).png)<br>
 ![Dashboard Preview](https://github.com/PawanKumar7264/OLA_DASHBOARD/blob/main/cancelation_of_snapshot.png)<br>
 ![Dashboard Preview](https://github.com/PawanKumar7264/OLA_DASHBOARD/blob/main/snapshot_rating.png)<br>
