 Ola Ride Analytics Dashboard: Performance and Insights (July 2024)
1. Project Title
Ola Ride Analytics: Performance and Insights (July 2024)This dashboard delivers a comprehensive analysis of Ola's ride-sharing operations for July 2024, encompassing total bookings, successful rides, cancellations, revenue, vehicle type distribution, customer and driver ratings, and payment method trends.
2. Purpose and Scope
The Ola Ride Analytics Dashboard is designed to provide actionable insights into Ola’s ride-sharing performance for the period of July 1–30, 2024. By visualizing and analyzing key performance indicators (KPIs) such as booking success rates, cancellation patterns, daily ride volumes, vehicle preferences, customer and driver satisfaction, and payment method distributions, the dashboard empowers stakeholders to identify operational inefficiencies, enhance service reliability, improve customer experience, and optimize revenue generation.
3. Technology Stack
The dashboard was developed using a robust and modern technology stack to ensure scalability, interactivity, and analytical depth:  

Power BI Desktop: Core platform for creating interactive visualizations and reports.  
Power Query: Utilized for data extraction, transformation, and cleaning to prepare structured datasets.  
DAX (Data Analysis Expressions): Employed for creating calculated measures, dynamic visuals, and advanced analytics logic.  
Data Modeling: Established relationships between tables (e.g., Date_Key, Location_Key, Temperature_Fahrenheit, Temperature_Celsius, Humidity_Percentage, WindSpeed_MPH, Precipitation_Chance_Percentage, AQI) to enable seamless cross-filtering and data aggregation.  
File Formats: .pbix for dashboard development and .png for static previews.

4. Data Source and Processing

Source: Ola’s ride-booking system database, covering ride data from July 1–30, 2024.  
Extraction: Key metrics, including total bookings, cancellations, and daily trends, were extracted and formatted into JSON for dashboard compatibility.  
Transformation Pipeline:  
Imported raw CSV data containing booking details (e.g., date, status, vehicle type).  
Aggregated data to compute totals, successful bookings, and cancellations (by driver, customer, or driver not found).  
Generated daily ride volume summaries for time-series analysis.  
Output structured JSON optimized for dashboard integration.



5. Key Features and Capabilities
Core Features

Automated Data Transformation  
Converts raw CSV data into structured JSON objects for efficient processing.  
Groups data by date, booking status, and other key dimensions for streamlined visualization.


Dashboard-Ready Output  
Produces JSON with summary totals, status breakdowns, and daily trends, compatible with BI tools, web dashboards, and APIs.


Booking Status Analysis  
Classifies bookings into categories: Successful, Canceled by Driver, Canceled by Customer, and Driver Not Found.  
Provides counts and percentage distributions for each category.


Time-Series Analysis  
Aggregates ride data daily to visualize trends, identify demand peaks, lows, and cancellation spikes.


Scalability and Flexibility  
Adaptable to any time period or additional metrics (e.g., revenue, trip distance).  
Supports integration with new booking statuses or data sources.


Analytics and Reporting Support  
Powers advanced visualizations in BI platforms (Power BI, Tableau), web frameworks (D3.js, Recharts), and mobile app APIs.



Business Problem Addressed
Raw booking data in CSV format lacks the structure and clarity needed for actionable insights. Without proper analysis, Ola struggles to:  

Track booking success rates and cancellation patterns.  
Identify operational bottlenecks, such as high "Driver Not Found" incidents.  
Monitor daily demand trends and customer behavior.This leads to inefficiencies in resource allocation, reduced customer satisfaction, and missed revenue opportunities. The dashboard addresses critical questions, including:  
What is the total number of bookings and their success rate?  
What are the reasons for cancellations, and how are they distributed?  
How do daily booking volumes and cancellations trend over time?  
Are cancellations concentrated around specific dates, times, or customer segments?

Dashboard Objectives
The dashboard aims to:  

Provide a holistic view of Ola’s ride-sharing performance for July 2024.  
Enable stakeholders to monitor KPIs, including bookings, cancellations, revenue, and customer/driver satisfaction.  
Highlight operational inefficiencies and high-cancellation patterns.  
Support data-driven decisions to enhance service reliability, reduce cancellations, and maximize revenue.

Business Impact and Insights

Booking Performance  
Calculates total bookings and success rates using the Booking_Status column.  
Quantifies total booking value to assess revenue generation.


Ride Dynamics and Customer Behavior  
Analyzes popular vehicle types (Vehicle_Type) and frequent pickup/drop-off locations (Pickup_Location, Drop_Location).  
Evaluates customer and driver satisfaction through ratings (Customer_Rating, Driver_Ratings).  
Examines payment method preferences (Payment_Method) to inform marketing strategies.


Operational Efficiency  
Assesses Vehicle Turnaround Time (V_TAT) and Customer Turnaround Time (C_TAT) to identify bottlenecks.  
Breaks down cancellation reasons (Canceled_Rides_by_Customer, Canceled_Rides_by_Driver, Incomplete_Rides) to pinpoint service pain points.


Strategic Impact  
Estimates revenue loss from cancellations by comparing successful and canceled ride values.  
Identifies high-cancellation locations, times, or segments for targeted operational improvements.  
Correlates ratings with cancellations to enhance user experience and reduce churn.



6. Visualizations
The dashboard includes interactive visuals to present data clearly and effectively:  

Main Dashboard Overview: Dashboard Preview  
Vehicle Type Distribution: Vehicle Type Preview
