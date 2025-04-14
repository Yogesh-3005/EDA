# EDA
in this repository i've uploaded my works on exploratory data analysis 
📊 Chicago Crime Data Analysis Dashboard
This project analyzes crime data in Chicago using Power BI to uncover patterns, trends, and insights. It includes detailed EDA, interactive dashboards, and a paginated report for stakeholders.

🧪 Exploratory Data Analysis (EDA)
Performed EDA to understand the structure and distribution of crime data:
Checked for missing values and nulls
Cleaned inconsistent crime type labels (e.g., merged “Crim Sexual Assault” and “Criminal Sexual Assault” into one)
Converted columns (e.g., Boolean fields like Arrest, Domestic to readable values)
Verified uniqueness of Case Number and ID fields
Checked frequency of values for key fields like Primary Type, District, Location Description

📌 Project Features
✅ Power BI Dashboard:
Created an interactive dashboard featuring:
Crime Type Distribution: Pie charts, bar charts, and tree maps
Arrest & Domestic Crime Analysis: Donut charts and side-by-side bar charts
Geospatial Maps: Filled and regular maps for districts, wards, and community areas
Seasonal Trends: Line graphs showing crimes across seasons using DAX-based categorization
Repeat Offenders (Recidivism): Attempts based on Case Number and ID
Severity Classification: Used DAX to categorize crimes as “Severe” or “Non-Severe”
Risk Assessment: Highlighted high-crime areas using conditional formatting
Interactive Filters: For year, crime type, arrest status, and location

📄 Paginated Report
Created a paginated report titled "Chicago Crime Summary Report" using Power BI Report Builder:
Manually connected to the dataset
Designed multi-page report layout
Included tables with conditional formatting and text headers
Exportable to PDF for stakeholder sharing

🛠️ Tools Used
Microsoft Power BI
Power BI Report Builder
DAX (Data Analysis Expressions)

🧠 Key DAX Examples
Severity Category Calculation
Season Identification from Month
Top Crime Type Calculation
District-to-Name Mapping
Arrest Rate Calculation
Crime Frequency Grouping by Type, District, and Location

📈 KPIs & Metrics
Total Number of Crimes
Arrest Rate (Formatted as Percentage)
Most Frequent Crime Type
High-Risk Areas by Location
Monthly & Seasonal Crime Trends

📤 Export
The Power BI dashboard can be exported to PDF or PowerPoint
Paginated report supports PDF export for detailed tabular summaries
