# BRIGHT-MOTORS

***

# Bright Motors Car Sales Analysis

## Project Description
This project is a comprehensive data analysis case study for **Bright Motors**, focusing on providing actionable business insights to a new Head of Sales. The project involves analyzing daily transactional and pricing data to identify revenue drivers, understand regional performance, and track emerging customer preferences. The goal is to assist the dealership in expanding its network and optimizing its vehicle inventory.

## Raw Data - BrightLearn
The source material provided by **BrightLearn** consists of the **"Bright Car Sales" dataset**. 
*   **Dataset Content:** Daily transactional records for vehicles sold, including pricing, mileage, and manufacture details.
*   **Key Statistics:** The dataset includes **558,811 total sales** with manufacture dates ranging from 1982 to 2015.
*   **Total Revenue:** The analyzed data accounts for approximately **$7.6 billion** in revenue.

## Tools Used
*   **Project Planning:** Miro link https://miro.com/app/board/uXjVHaRURUE=/?moveToWidget=3458764670010099810&cot=14
*   **Data Processing:** **Databricks (SQL)** for ETL, cleaning, and transformation.
*   **Visualization:** Power BI and Microsoft Excel.
*   **Presentation:** Microsoft PowerPoint.

## Queries - Databricks
The data processing phase was handled within **Databricks** using SQL to transform raw transactional data into a format suitable for analysis. Key SQL tasks included:

*   **Data Cleaning:** Handling missing or inconsistent values and removing duplicates.
*   **Type Conversion:** Converting text-based prices (e.g., '15,000') and mileage into numeric formats for calculations.
*   **Calculation of Key Metrics:**
    *   `total_revenue`: `selling_price * units_sold`.
    *   `profit_margin`: `(selling_price - cost_price) / selling_price * 100`.
*   **Categorization:** Using conditional logic to tier cars into **High, Medium, and Low Margin** performance categories.
*   **Aggregation:** Grouping transactions by make, model, region, and time periods (month, quarter, or year).

## Key Insights Found
*   **Top Sellers:** Ford is the market leader, with trucks and SUVs (like the Ford F-150) dominating revenue due to high volume and premium pricing.
*   **Regional Hotspots:** **Florida** is the highest-performing region with over 82,000 sales, while Tennessee represents a lower-volume market in the top 10.
*   **Consumer Trends:** 
    *   **99.9%** of buyers prioritize the "Budget" segment.
    *   **85%** preference for automatic transmissions.
    *   **Neutral colors** (White, Black, Silver) lead the market due to higher resale value and lower maintenance.
*   **Vehicle Condition:** A clear trend shows that newer cars command significantly higher prices while maintaining much lower average mileage.

## Strategic Recommendations
*   **Optimize Inventory:** Focus on stocking automatic, neutral-colored Trucks and SUVs.
*   **Regional Strategy:** Heavily invest marketing spend in Florida to maintain dominance and target Tennessee to capture untapped potential.
*   **Customer Engagement:** Use social media influencer partnerships to build trust and highlight vehicle reliability for budget-conscious buyers.

## Repository Structure
*   `README.md`: This project overview.
*   `project description: ` https://github.com/nmchunu753-wq/BRIGHT-MOTORS/blob/main/BrightMotors_CarSales_CaseStudy.pdf
*   `car_sales_queries.sql: ` https://github.com/nmchunu753-wq/BRIGHT-MOTORS/blob/main/BRIGHTMOTORS.sql
*    `Miro Flowchart`: The image is unclear, for clear viewing open link: https://miro.com/app/board/uXjVHaRURUE=/?moveToWidget=3458764670010099810&cot=14
*    `Gantt time plan`:https://github.com/nmchunu753-wq/BRIGHT-MOTORS/blob/main/Blue%20Aesthetic%20Professional%20Gantt%20Graph.png
*    `Excel Analysis File - Pivots & Graphs:` https://github.com/nmchunu753-wq/BRIGHT-MOTORS/blob/main/PIVOTS%20AND%20GRAPHS.xlsx
*   `BrightMotors_Presentation.pdf`
*   `Dashboards`: https://github.com/nmchunu753-wq/BRIGHT-MOTORS/blob/main/BRIGHT%20MOTORS%20DASHBOARD..pbix

***
