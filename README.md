# Luxury Car Dealership Sales Analysis

### Objective
The dealership needed actionable insights to guide inventory stocking, optimize pricing, and improve customer satisfaction. I was given a 10,000-row dataset to clean, transform, and analyze using Power BI. The goal was to deliver an interactive dashboard that answered critical business questions and revealed sales patterns.

### Dashboard
<img width="1221" height="684" alt="Screenshot (344)" src="https://github.com/user-attachments/assets/4fcdad52-12ad-428e-8920-3057235d0dd9" />


### Tools & Skills Used
  - Power BI (data modeling & visualization)
  - Power Query (data cleaning & transformation)
  - DAX (KPIs, YoY Growth, Time Intelligence)

### Process & Technical Implementation:
### 1. Data Cleaning & Transformation (Power Query):
  - Split the Car column to extract the manufacturer name.
  - Standardized text fields for car colors, ownership categories, and transmission types.
  - Mapped manufacturing countries using Conditional Column Function.
  - Removed duplicates and validated key sales/price fields.

### 2. Data Modeling:
  - Built a Date Table using DAX (CALENDAR and ADDCOLUMNS) with Year, Quarter, Month, and MonthName columns to enable time intelligence.
  - Established relationships between fact tables (sales data) and dimension tables (date table).

### 3. DAX Measures & Calculations:
  - Created KPIs: Total Sales, Average Price, Units Sold.
  - Time Intelligence Measures: Previous Year Sales, YoY Growth, and Seasonal Trends.
  - Comparison Metrics: Automatic vs Manual sales, Average Price by Ownership Category.
  - Ranking Measures: Top Manufacturer, Least Popular Color.

### 4. Visualization & Dashboard Design:
  - Built an interactive Power BI dashboard with slicers for Manufacturer, Ownership Category, and Year.
  - Used column and bar charts for categorical comparisons, line charts for seasonal trends, and cards for headline KPIs.
  - Added a business insights summary box directly on the dashboard to communicate key takeaways for executives.

### 5. Key Insights & Findings:
  - Most Popular Manufacturer: BMW is the most popular car manufacturer, recording 193 sales which represents 32.3% of total dealership sales.
  - Manufacturing Country Trends: Cars manufactured in Germany account for 58% of total dealership sales, making it the most represented country by a significant margin.         Showing that Germany brands dominate the dealership’s inventory and customer demand, reflecting their strong reputation in the luxury car market. 
  - Customer Preference: Manual cars slightly outperformed automatic cars, with 51.2% of total transactions, reflecting customer preference for control and cost-                 effectiveness.
  - Ownership Category: Cars with 3rd ownership had the highest average price at $80.77K, followed closely by 4th ownership ($80.19K). Interestingly, 1st ($79.93K)               and 2nd ownership ($79.70K) cars showed slightly lower averages, suggesting that ownership count does not drastically reduce market value.
  - Least Popular Color: Among the recorded sales, Red emerged as the least popular color, with 1.42K units sold, slightly trailing behind Yellow and White. This suggests         that buyers leaned more toward neutral or classic tones, making vibrant colors less favored in the market.
  - Seasonality & Growth: Sales peaked in 2008 ($47.43M), showing strong demand before a dip in subsequent years. After some recovery in 2011 ($45.61M) and 2017 ($44.42M),       sales remained relatively stable, fluctuating between $38M–$43M from 2018 onward.

### Impact:
This project delivered a scalable Power BI solution that:
  - Automated data cleaning and reporting.
  - Enabled leadership to align inventory with customer demand.
  - Provided pricing and stocking insights that reduce excess inventory and improve margins.
  - Revealed seasonality and growth trends that guide marketing and promotional strategies.

### Business Recommendations
Analysis of dealership sales reveals clear growth opportunities.
  - Inventory Focus: Prioritize BMW and other German brands to meet strong market demand.
  - Color Strategy: Stock more Blue and Black cars, while limiting Red (least popular) to reduce slow-moving inventory.
  - Transmission Mix: Maintain a higher share of manual cars (51.2%) but run promotions on automatics to balance demand.
  - Expand trade-in programs to capture high-value 3rd ownership cars, boosting both resale opportunities and new car sales while improving customer loyalty.
  - Seasonal Sales: Introduce seasonal discounts and targeted campaigns during low-demand years to smooth sales volatility.

 ### Conclusion
This project demonstrates how data is more than numbers, it is a decision-making tool that transforms uncertainty into strategy. By uncovering trends in brand preference, pricing, and customer behavior, the dealership can shift from intuition-driven stocking to evidence-based planning. Data empowers businesses to see patterns competitors miss, align resources with demand, and act with precision. For the dealership, this means turning insights into profit, efficiency, and long-term growth.
