# Honda Global Performance Report (2014-2024) -- Dashboard

#### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiODkwNzQ0ODQtNGFkYS00OWVhLWFiNjAtNTdhZWJiZDQzNzFjIiwidCI6ImYyYWY0MGVlLTVjMzQtNDg2YS1hNmM5LWFkNzY4NjBjMDk2YiJ9

## Introduction
This dynamic Power BI dashboard provides a comprehensive view of Honda's global car production, exports, and sales over a decade, from 2014 to 2024. The dashboard is designed to offer a detailed analysis of key metrics, allowing users to explore trends, compare year-on-year performance, and gain insights into Honda's global automotive operations.

<img src="Images and screenshots/Screenshot 2024-08-29 152330 (2).png" alt="Power bi dashboard" width="100%" height="500" />
<img src="Images and screenshots/Screenshot 2024-08-29 152406 (2).png" alt="Power bi dashboard" width="100%" height="500" />
<img src="Images and screenshots/Screenshot 2024-08-29 152440 (2).png" alt="Power bi dashboard" width="100%" height="500" />

## Project Overview
The goal of this project is to create an interactive and user-friendly dashboard that visualizes Honda’s production, export, and sales data. By leveraging the capabilities of Power BI, the dashboard provides a holistic view of the data, enabling stakeholders to make informed decisions based on real-time analytics.

## Key Features
- Global Coverage: The dashboard includes data from all major regions where Honda operates, including North America, Europe, Asia, and others.
- Yearly Trends: Visualizations that display trends from 2014 to 2024, allowing users to identify patterns in production, exports, and sales.
- Interactive Filters: Users can apply filters by year, region, and other dimensions to focus on specific data points.
- Comparative Analysis: Tools for comparing year-on-year performance, with insights into growth or decline in different regions.
- Export Insights: Detailed breakdown of export data, showing the distribution of Honda cars across various countries.
- Sales Performance: Analysis of sales data, highlighting the best-performing models and regions.

## Data Sources
The data used in this dashboard was sourced from Honda’s annual reports, global automotive industry reports, and other reliable automotive data providers. The data was cleaned, transformed, and loaded into Power BI for visualization.

## Technical Details
- Tools Used: Power BI for data visualization, Excel for initial data cleaning and preparation.

Raw data

<img src="Images and screenshots/Screenshot 2024-08-29 153955.png" alt="Power bi dashboard" width="50%" height="400" /><img src="Images and screenshots/Screenshot 2024-08-29 154506.png" alt="Power bi dashboard" width="50%" height="400" />

Transformned data


<img src="Images and screenshots/Screenshot 2024-08-29 154624.png" alt="Power bi dashboard" width="60%" height="400" /><img src="Images and screenshots/Screenshot 2024-08-29 154529.png" alt="Power bi dashboard" width="40%" height="400" />

- Data Models: The dashboard is built on a star schema with fact tables for production, exports, and sales, and dimension tables for time, regions, and models.

<img src="Images and screenshots/Screenshot 2024-08-29 155555.png" alt="Power bi dashboard" width="100%" height="500" />

- Calculated Metrics: Custom DAX measures were created to calculate metrics such as year-over-year growth, total production, and regional sales distribution.

<img src="Images and screenshots/Screenshot 2024-08-29 155831.png" alt="Power bi dashboard" width="100%" height="200" />
<img src="Images and screenshots/Screenshot 2024-08-29 155901.png" alt="Power bi dashboard" width="100%" height="250" />
<img src="Images and screenshots/Screenshot 2024-08-29 160124.png" alt="Power bi dashboard" width="45%" height="700" />

- ChatGPT: Prompt engineering was used for ideas, DAX codes, chart selection and other parts of the project. 

## Insights and Findings
- Production Trends: Honda's production showed a steady increase from 2014 to 2019, followed by a dip in 2020 due to global events, with recovery and growth in the subsequent years.

<img src="Images and screenshots/Screenshot 2024-08-29 161037.png" alt="Power bi dashboard" width="100%" height="500" />
<img src="Images and screenshots/Screenshot 2024-08-29 161023.png" alt="Power bi dashboard" width="55%" height="700" />

- Export Markets: The data reveals shifts in Honda’s export strategies, with increasing focus on markets in Europe and Africa where domestic production is the least.

<img src="Images and screenshots/Screenshot 2024-08-29 162928.png" alt="Power bi dashboard" width="100%" height="450" />
<img src="Images and screenshots/Screenshot 2024-08-29 162951.png" alt="Power bi dashboard" width="100%" height="450" />

- Sales Dynamics: Sales data highlights the decrease in overall sales from 2018 to 2024. Domestic sales in Japan has also gone down in recent years. 

<img src="Images and screenshots/Screenshot 2024-08-29 163752.png" alt="Power bi dashboard" width="100%" height="450" />

## How to Use the Dashboard
- Navigate Through Pages: The dashboard is divided into sections focusing on production, exports, and sales. Use the navigation pane to switch between these sections.

<img src="Images and screenshots/Screenshot 2024-08-29 164559 (2).png" alt="Power bi dashboard" width="20%" height="200" />

- Apply Filters: Use the slicers to filter data by years.

<img src="Images and screenshots/Screenshot 2024-08-29 164647 (2).png" alt="Power bi dashboard" width="20%" height="300" />

- Key Performance Indicator's (KPI) like Year to date (YTD), Prior Year to date (PYTD), difference between YTD and PYTD and the Year on year % change are shown in the cards of each page.

<img src="Images and screenshots/Screenshot 2024-08-29 165757.png" alt="Power bi dashboard" width="100%" height="125" />
<img src="Images and screenshots/Screenshot 2024-08-29 165821.png" alt="Power bi dashboard" width="100%" height="125" />
<img src="Images and screenshots/Screenshot 2024-08-29 165837.png" alt="Power bi dashboard" width="100%" height="125" />

- Hover for Details: Hover over data points in charts to see detailed information.

<img src="Images and screenshots/Screenshot 2024-08-29 165019.png" alt="Power bi dashboard" width="80%" height="450" />

- Export Reports: Users can export specific reports or data views for offline analysis.

## Conclusion
This Power BI dashboard provides a powerful tool for analyzing Honda's global automotive data. It offers valuable insights into the company's operations, helping stakeholders to understand trends and make data-driven decisions. The project demonstrates the potential of Power BI in transforming raw data into actionable business intelligence.

## Future Enhancements
- Incorporate Forecasting: Adding predictive analytics to forecast future trends based on historical data.
- Real-Time Data Integration: Connecting to live data sources for real-time updates.
- Mobile Optimization: Enhancing the dashboard for better accessibility on mobile devices.
