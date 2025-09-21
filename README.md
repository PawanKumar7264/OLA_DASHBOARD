 # Ola Ride Analytics: Performance and Insights (July 2024)

## 1. Project Title / Headline
**Ola Ride Analytics: Performance and Insights (July 2024)**  
This dashboard provides a comprehensive analysis of Ola's ride-sharing services for July 2024, covering total bookings, successful rides, cancellations, revenue, vehicle type distribution, customer and driver ratings, and payment methods.

## 2. Short Description / Purpose
The **Ola Ride Analytics Dashboard** aims to deliver actionable insights into Ola's ride-sharing performance for July 2024. By analyzing key metrics such as booking success rates, cancellation patterns, daily ride volume trends, vehicle types, ratings, and payment methods, the dashboard enables stakeholders to identify operational inefficiencies, enhance customer satisfaction, and optimize revenue generation.

## 3. Tech Stack
The dashboard leverages the following technologies:  
- **Power BI Desktop**: Primary platform for data visualization and report creation.  
- **Power Query**: Used for data transformation and cleaning to prepare data for analysis.  
- **DAX (Data Analysis Expressions)**: Employed for calculated measures, dynamic visuals, and conditional logic.  
- **Data Modeling**: Relationships established among tables (e.g., Date_Key, Location_Key, Temperature_Fahrenheit, Temperature_Celsius, Humidity_Percentage, WindSpeed_MPH, Precipitation_Chance_Percentage, AQI) for cross-filtering and aggregation.  
- **File Formats**: .pbix for development, .png for dashboard previews.

## 4. Data Source
- **Source**: Ola’s ride-booking system database for July 1–30, 2024.  
- **Extraction**: Key metrics (e.g., total bookings, cancellations, daily trends) extracted and output as JSON for dashboard use.  
- **Transformation**:  
  - Read CSV data containing booking records (date, status, etc.).  
  - Aggregate data to calculate totals, successful bookings, cancellations (by driver, customer, or driver not found).  
  - Summarize daily ride counts for time-series analysis ("Ride Volume Over Time").  
  - Output structured, dashboard-ready JSON.  

## 5. Features / Highlights
### Key Features
1. **Automated Data Restructuring**  
   - Transforms raw CSV data into structured JSON objects.  
   - Groups data by date and status for seamless visualization.  
2. **Dashboard-Ready Format**  
   - JSON includes summary totals, status breakdowns, and daily ride volume trends.  
   - Compatible with BI tools, web dashboards, or APIs.  
3. **Booking Status Classification**  
   - Categories: Success, Canceled by Driver, Canceled by Customer, Driver Not Found.  
   - Displays count and percentage share for each category.  
4. **Time-Series Insights**  
   - Aggregates rides daily to visualize trends, peaks, lows, and cancellation spikes.  
5. **Scalable & Flexible**  
   - Adaptable to any time period or additional metrics (e.g., revenue, distance).  
6. **Supports Analytics & Reporting**  
   - Powers BI dashboards (Power BI, Tableau), web visualizations (D3.js, Recharts), and mobile app APIs.

### Business Problem
Raw booking data in CSV format lacks actionable insights, hindering Ola’s ability to track success rates, identify cancellation patterns, or monitor demand trends. This leads to inefficiencies in resource allocation, reduced customer satisfaction, and lost revenue opportunities. The dashboard addresses key questions:  
- What is the total number of bookings?  
- What are the success and cancellation rates (by driver, customer, or driver not found)?  
- How do daily booking volumes and cancellations trend?  
- Are cancellations concentrated around specific dates, times, or customer segments?  

### Goal of the Dashboard
To provide a comprehensive overview of Ola’s ride-sharing performance for July 2024, enabling stakeholders to:  
- Monitor key metrics (bookings, success rates, cancellations, daily trends).  
- Identify operational inefficiencies (e.g., high "Driver Not Found" incidents).  
- Assess customer and driver behavior.  
- Support data-driven decisions to improve service reliability, reduce cancellations, and optimize revenue.

### Business Impact & Insights
1. **Booking Performance**  
   - Total bookings and success rates calculated using the Booking_Status column.  
   - Total booking value generated to assess revenue.  
2. **Ride Dynamics & Customer Behavior**  
   - Analysis of popular vehicle types (Vehicle_Type).  
   - Identification of frequent pickup and drop-off locations (Pickup_Location, Drop_Location).  
   - Insights into customer and driver satisfaction via ratings (Customer_Rating, Driver_Ratings).  
   - Distribution of payment methods (Payment_Method) to understand preferences.  
3. **Operational Efficiency**  
   - Analysis of Vehicle Turnaround Time (V_TAT) and Customer Turnaround Time (C_TAT) to identify bottlenecks.  
   - Breakdown of cancellation reasons (Canceled_Rides_by_Customer, Canceled_Rides_by_Driver, Incomplete_Rides).  
4. **Potential Business Impact**  
   - Estimation of revenue loss from cancellations by comparing successful and canceled ride values.  
   - Identification of high-cancellation locations or times for targeted improvements.  
   - Correlation of ratings with cancellations to enhance user experience and reduce churn.

## 6. Screenshots / Demos
Below are previews of the Ola Ride Analytics Dashboard:  
- **Main Dashboard**: [Dashboard Preview](https://github.com/PawanKumar7264/OLA_DASHBOARD/blob/main/Snapshort_%20dashboard%20.png)  
- **Vehicle Type Analysis**: [Vehicle Type Preview](https://github.com/PawanKumar7264/OLA_DASHBOARD/blob/main/snapshot_vechicle.png)  
- **Revenue Insights**: [Revenue Preview](https://github.com/PawanKumar7264/OLA_DASHBOARD/blob/main/snapshot_revenu%20(2).png)  
- **Cancellation Breakdown**: [Cancellation Preview](https://github.com/PawanKumar7264/OLA_DASHBOARD/blob/main/cancelation_of_snapshot.png)  
- **Ratings Overview**: [Ratings Preview](https://github.com/PawanKumar7264/OLA_DASHBOARD/blob/main/snapshot_rating.png)  

These visuals provide a clear, interactive representation of Ola’s performance metrics, enabling stakeholders to derive actionable insights efficiently.
