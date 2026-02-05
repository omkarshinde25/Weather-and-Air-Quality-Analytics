# Weather and Air Quality Analytics Dashboard using Power BI

## 1. Introduction
The Weather and Air Qualytics Analysis Dashboard is a comprehensive Power BI project developed to analyze and visualize real-time and historical weather data. The goal of the project is to identify trends in temperature, humidity, rainfall, and air quality across different locations and time periods. This project demonstrates strong data analytics capabilities including data extraction, cleaning, modeling, DAX calculations, and dashboard design.

## 2. Project Overview
This project focuses on using Power BI as a complete business intelligence solution for weather data monitoring. Data is extracted from an external API, transformed through Power Query, modeled using relationships, and visualized through interactive charts and KPIs. The final dashboard helps users understand weather patterns and supports data-driven environmental analysis.

For a deeper overview of the project (including report and documentation), please visit the project report available here:  
[Project Report – Weather Data Analysis Dashboard using Power BI](https://github.com/omkarshinde25/Weather-Data-Analysis-/blob/main/Project%20Report%20-Weather%20Data%20Analysis%20Dashboard%20using%20Power%20BI.pdf)


<img src="https://github.com/omkarshinde25/Weather-Data-Analysis-/blob/main/Dashboard/Weather%20Data%20Analysis%20Dashboard.png" width="800"> <br>

## 3. Objectives
- To integrate external weather data through API connections.
- To clean, transform, and model data for efficient analysis.
- To apply DAX calculations for dynamic measures and summaries.
- To design an interactive dashboard for city-wise weather insights.
- To present analytical insights that help in environmental planning.

## 4. Data Source and Extraction
The data for this project was extracted from the Weather API available at https://www.weatherapi.com/. The API provides real-time and forecasted weather information in JSON format, including temperature, humidity, wind speed, and air quality data. Power BI was connected directly to the API endpoint to import the data. Multiple cities and date ranges were included to allow for trend-based and comparative analysis.

## 5. Data Cleaning and Transformation
Data transformation was performed using Power Query Editor in Power BI. The main steps included:
- Converting the JSON structure into a readable tabular format.
- Removing null values and redundant columns.
- Renaming columns for clarity.
- Formatting data types for numerical and date fields.
- Splitting nested tables for detailed weather metrics.
- Creating custom columns for calculated daily averages.
These transformations ensured that the dataset was accurate and properly structured for reporting and analysis.

## 6. Data Modeling
<img src="https://github.com/omkarshinde25/Weather-Data-Analysis-/blob/main/Dashboard/Star%20Schema%20Weather%20Data%20Analysis.png" width="800"> <br>
A star schema data model was created to establish logical relationships between tables. The model included:
- A central fact table containing weather records such as temperature, humidity, rainfall, and air quality.
- Dimension tables for date, location, and environmental categories.
- Relationships established between fact and dimension tables to enable filtering and aggregation across multiple perspectives.
This model improved performance and enabled more flexible analysis in the dashboard.

## 7. DAX Measures and Dynamic Calculations 
DAX (Data Analysis Expressions) played a key role in creating dynamic and interactive calculations within the dashboard. DAX was used to calculate averages, totals, and conditional summaries across multiple dimensions such as city and time period. It was also used for generating key performance indicators and comparative analysis like day-over-day or month-over-month changes.  
The use of DAX enabled the dashboard to respond dynamically to user selections, providing real-time analytical results for temperature, humidity, rainfall, and air quality indicators.

For the complete documentation of all DAX formulas and logic used in this project, please refer to the file below:  
[View Full DAX Documentation](https://github.com/omkarshinde25/Weather-Data-Analysis-/blob/main/DAX%20Weather%20Data%20Analysis%20Dashboard%20using%20Power%20BI.pdf)


## 8. Dashboard Design and Visualization
The Power BI dashboard was designed to be clean, professional, and interactive. It included several visual components such as:
- Line charts for temperature and humidity trends.
- Bar charts for rainfall and air quality comparisons.
- KPI cards for key metrics like average temperature and AQI.
- Map visuals to show weather distribution across cities.
- Filters and slicers to allow users to select specific locations and time frames.  
Consistent colors, fonts, and layout design ensured that the dashboard maintained a professional look and effectively communicated insights.

## 9. Insights and Analysis
The dashboard provided multiple actionable insights:
- City-wise and seasonal variations in temperature and humidity.
- Identification of peak rainfall periods and air quality fluctuations.
- Comparison of environmental conditions across different regions.
- Understanding correlations between temperature, rainfall, and pollution levels.
These insights could be used for environmental monitoring, urban planning, and decision-making processes related to public health and resource management.

## 10. Tools and Technologies Used
- Microsoft Power BI for visualization and analytics.
- Power Query Editor for data cleaning and preparation.
- DAX (Data Analysis Expressions) for calculated fields and dynamic measures.
- JSON data from Weather API as the data source.
- Microsoft Excel for secondary data validation.
- Star schema data modeling technique for optimized data relationships.

## 11. Project Workflow
1. Establish a connection to the Weather API and import data into Power BI.  
2. Clean and transform the data using Power Query Editor.  
3. Build a structured data model using relationships and hierarchies.  
4. Apply DAX calculations to create measures and KPIs.  
5. Design visuals for each weather metric and integrate interactive elements.  
6. Test the dashboard and validate analytical outputs.  
7. Document findings and prepare the final report.

## 12. Conclusion
This project highlights the complete end-to-end development of a data analytics solution using Power BI. It demonstrates proficiency in integrating APIs, transforming and modeling data, applying DAX for analytical logic, and designing a visually compelling dashboard. The final solution provides valuable insights into weather and environmental patterns, which can assist researchers, policymakers, and organizations in data-driven decision-making.

## 13. Future Enhancements
- Integration of live data streaming for real-time updates.
- Implementation of predictive models for forecasting weather trends.
- Automation of data refresh through Power BI Service.
- Addition of new metrics such as wind speed and UV index.
- Expansion of the dataset to include global weather comparisons.

## 14. Key Learnings
- Understanding of end-to-end Power BI project workflow.
- Experience in using Power Query for cleaning and data preparation.
- Development of analytical logic through DAX measures.
- Designing effective, interactive visual dashboards.
- Improving data storytelling and presentation skills.
omkar-shinde-64a479245  
GitHub: https://github.com/omkarshinde25

For a deeper overview of the project (including report and documentation), please visit the project report available here:  
[Project Report – Weather Data Analysis Dashboard using Power BI](https://github.com/omkarshinde25/Weather-Data-Analysis-/blob/main/Project%20Report%20-Weather%20Data%20Analysis%20Dashboard%20using%20Power%20BI.pdf)
