# BI-Projects
# Power BI Reports: Product Sales Analysis, Pipeline Accidents, Call Center Performance, Customer Retention, and Sales Activity

This repository contains multiple Power BI reports for tracking and analyzing sales activities, product performance, pipeline accident statistics, and call center performance.

## 1. Product Sales Analysis
The "Product Sales Analysis" report provides detailed insights into order amounts, shipped amounts, and sales performance by week, country, product color, and more.

### Sections:
1. **Order Amount and Shipped Amount by Weekending**: A time series graph showing order amounts and shipped amounts on a weekly basis, with filter options to adjust by weekending, territory region, and product color.

2. **Sales Analysis by Country**: Displays average weekly sales per country, represented as a pie chart for easy visualization.
   - Countries tracked include the United States, Australia, United Kingdom, France, Canada, and Germany.

3. **Order and Shipped Amount by Month and Year**: A line graph illustrating the trends in order and shipped amounts over time.

4. **Quarterly and Year-to-Date Sales**: Provides quarterly sales data and year-to-date figures, with an easy-to-read table for comparison.

### Features:
- A dynamic dashboard with interactive filters for various dimensions like weekending, territory region, and product color.
- Visual insights into sales performance trends with graphical representation, making it easier to spot trends in product demand and shipment efficiency.

### Visuals:
- **Bar charts** for weekly order and shipped amounts.
- **Pie chart** for country-specific average weekly sales.
- **Line charts** for order and shipped amounts by month and year.
- **Quarterly and YTD tables** for detailed financial analysis.

<img width="1350" height="805" alt="image" src="github.com/sp3jossy/BI-Projects/blob/main/Product_Sales_Analysis.jpg" />


View Image (https://github.com/sp3jossy/BI-Projects/blob/main/Product_Sales_Analysis.jpg)
Play Video (https://github.com/sp3jossy/BI-Projects/blob/main/ProductSalesAnalysis.mp4)

---

## 2. Pipeline Accidents in the USA
This report analyzes the significant rate of pipeline accidents across the USA, focusing on causes, incident types, and year-over-year (YOY) variances.

### Sections:
1. **Significant Rate of Pipeline Accidents**: Displays the significant rate of accidents in the USA and compares it to the previous year's rate.
   - Key metric: **Significant Rate** for the current and prior year (34.94% vs. 35.93%).
   - YOY variance: -2.76%.

2. **Pipeline Accidents by State**: A map visualizing the rate of accidents across the USA, with states shaded based on incident rate (low, medium, high).
   
3. **Top 10 Operators with Major Incidents**: A table showing the top operators responsible for the highest number of major incidents.

4. **Cause Categories and Yearly Comparison**: A breakdown of pipeline accidents by cause category, such as:
   - Excavation Damage
   - Other Outside Force Damage
   - Corrosion
   - All Other Causes

### Features:
- Dynamic filtering by **Cause Category**, **Incident Type**, **Liquid Type**, **Pipeline Location**, and **US Regions**.
- Comparison of significant rate and YOY variance across different cause categories with visual charts.
- Interactive visuals for **significant rate** and **YOY** by cause category to help identify areas of concern.

### Visuals:
- **Map visualization** of significant accident rates by state.
- **Bar charts** for accident causes and YOY variances.
- **Dynamic filters** for various data dimensions.
- **Table of top 10 operators** with major pipeline incidents.

<img width="1383" height="790" alt="image" src="https://github.com/sp3jossy/BI-Projects/blob/main/Pipeline.png" />

View Image (https://github.com/sp3jossy/BI-Projects/blob/main/Pipeline.png)
Play Video (https://github.com/sp3jossy/BI-Projects/blob/main/Pipeline-Accidents.mp4)

---

## 3. Call Center Performance
The "Quarterly Call Center Performance" report tracks key metrics related to call center efficiency, such as call answering rate, abandonment rate, and handle time.

### Sections:
1. **Overall Performance**: Displays key metrics such as:
   - **Call Answering Rate**: Measures the percentage of calls answered.
   - **Average Handle Time**: Measures the average time taken to handle calls.
   - **Call Abandonment Rate**: Percentage of calls abandoned before being answered.
   - **Average Hold Time**: Measures the time callers spend on hold.

2. **Rolling 7-Day Call Answer Rate**: Displays the daily call answer rate for the past 7 days, broken down by queue.

3. **Answer Rate and Speed of Answer by Queue**: Visualizes answer rate and speed of answering for each queue.

4. **Call Abandonment Rate and Average Time Before Abandonment**: Shows abandonment rates and the average time before abandonment for each queue.

### Features:
- Data is segmented by **Quarter**, **Month**, and **Week Number** for detailed trend analysis.
- **Dynamic filters** allow filtering by performance metrics and queue name.
- **Rolling 7-day data** shows call answering trends over a week.

### Visuals:
- **Bar charts** for average handle time, abandonment rates, and speed of answer.
- **Line charts** for call answering rate trends.
- **Interactive filters** for granularity in data analysis, such as by queue and time period.

<img width="1347" height="782" alt="image" src="https://github.com/sp3jossy/BI-Projects/blob/main/Call%20Center.jpg" />

View Image (https://github.com/sp3jossy/BI-Projects/blob/main/Call%20Center.jpg)
Play Video (https://github.com/sp3jossy/BI-Projects/blob/main/Call-Center-Record.mp4)

----

## 4. Customer Retention
The Customer Retention Simulation dashboard provides a comprehensive analysis of sales performance, profitability, and customer loyalty trends. It is designed to track how effectively the business retains its customer base over time across different regions and product categories.

### Sections:
1. **Key Performance Indicators (KPIs)**: Displays high-level summaries of business health, including:
   - **Total Sales**: Aggregate revenue generated across the selected periods (currently $9.77M).
   - **Total Profit**: Total bottom-line earnings (currently $4.05M).
   - **Yearly Customer Count**: The total number of unique customers (currently 2,659).
   - **Trend Sparklines**: Visual indicators of performance fluctuations over time for each KPI.

2. **Returning Customers Analysis: A detailed cohort table that tracks customer behavior based on their first purchase month. It measures:
   - **Active vs. First-Time Customers**: Breakdown of the customer volume.
   - **Retention Rates**: The percentage of customers returning within 90 days and the following 3 months.

3. **Product & Category Performance: Visualizes sales and profit distribution across different segments:
   - **Subcategory Analysis**: A horizontal bar chart comparing "Total Sales" and "Total Profit" for items like Road Bikes, Mountain Bikes, and Accessories.
   - **Global Reach**: A list of "Sales by Countries" showcasing top-performing markets like the United States and Australia.

4. **Demographic & Growth Insights**:
   - **English Occupation**: A combo chart to identify which professional segments are driving growth.

### Features:
- **Time-Based Slicers**: Data can be filtered by specific years (2001–2004).
- **Categorical Filters**: Users can drill down into specific product families (Accessories, Bikes, Clothing, Components).
- **Geographic Segmentation**: Global data can be toggled by Continent (Europe, North America, Pacific).
- **Retention Tracking**: Enables "Cohort Analysis" to identify seasonal trends in customer loyalty.

### Visuals:
- **KPI Cards**: Summary tiles with integrated sparklines for immediate trend recognition.
- **Cohort Table**: A data grid for granular tracking of customer return percentages.
- **Grouped Bar Charts**: Comparison of revenue vs. profit across subcategories and occupations.
- **Combination Charts**: Line and bar overlays to highlight Year-Over-Year (YOY) growth against volume.

<img width="1347" height="782" alt="image" src="https://github.com/sp3jossy/BI-Projects/blob/main/Customer_Retention.jpg" />

View Image (https://github.com/sp3jossy/BI-Projects/blob/main/Customer_Retention.jpg)
Play Video (https://github.com/sp3jossy/BI-Projects/blob/main/Customer_Retention.mp4)

------

## 5. Sales Activity KPIs (Sales Efforts)
The "Sales Activity KPIs" dashboard tracks the following key metrics:

### Sections:
1. **Effectiveness**: Tracks the performance of Business Development Managers (BDMs) across different time ranges.
   - Number of BDMs less than 6 months, less than 12 months, and greater than 12 months (Actual vs. Target).

2. **New Sales Activity (Effort)**: Measures sales efforts through metrics such as:
   - Reach Outs (Actual vs. Target)
   - New Prospect Appointments (Actual vs. Target)
   - Visits (Actual vs. Target)
   - Proposals (Actual)

### Features:
- Visual comparisons between **Actual** and **Target** values, using color-coded cells (e.g., green, red, yellow).
- Data split by **Week** for easy trend analysis.
- Custom filters for BDMs, industry, lead source, and NPG to drill into specific datasets.

### Visuals:
- Color-coded tables for easy understanding of sales activities.
- Interactive filters to drill through different weeks and metrics.

<img width="1722" height="980" alt="Sales Activities Screenshot" src="https://github.com/user-attachments/assets/a7ff5b4b-ee67-4d05-825e-ffecc4e85a81" />

---

## How to Use the Reports

### Prerequisites:
- Power BI Desktop or Power BI Service account.

### Steps:
1. Open the Power BI report in Power BI Desktop.
2. Use the **filters** available to adjust the metrics and analyze specific data.
3. Review the **visuals** to understand trends and performance across weeks, countries, sales activities, pipeline accidents, or call center operations.
4. Customize the report as needed by adding new visualizations or adjusting current metrics.

---

## Data Sources
The data for these reports is gathered from various internal sources, including:
- Sales Activity Tracking System
- Order and Shipment Data
- Regional Sales Performance Systems
- Pipeline Incident and Accident Databases
- Call Center Data

---

## License
These reports and their visualizations are provided as-is. Feel free to use and customize them for your organization's sales performance tracking, product analysis, pipeline accident reporting, or call center performance monitoring needs.

---

---

