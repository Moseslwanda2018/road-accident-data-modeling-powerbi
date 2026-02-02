# Road Accident Data Modeling and Analysis Dashboard (Power BI)

# Project Overview
This project analyzes road traffic collision data to uncover trends in fatalities, injuries,
and high-risk conditions. The dashboard demonstrates data modeling, DAX, and storytelling
capabilities using Power BI.

## Objective
The goal of this project is to:
-	Compare accident outcomes across counties
- Analyze differences between collision volume and fatality risk
- Explore monthly trends in injuries and fatality rates
- Identify vehicle types associated with higher death rates
- Demonstrate end-to-end BI development skills

  ## Dataset
- Type: Simulated data
- Geography: Kenya 
- Time Period: 2025
- Key Fields: Date, County, Vehicle Type, Collisions, Injuries, Time of Day

  ## Tools & Technologies
- Power BI
- Power Query
- DAX
- Star Schema Modeling
- Data Visualization

  ## Data Model
  The model follows a star schema design:
###	Fact table
-	fact_collisions
###	Dimension tables
-	dim_date
-	dim_location
-	dim_vehicle_type
-	dim_time_of_day
-	dim_lighting_condition
This structure enables efficient filtering, aggregation, and scalable analysis.

## Dashboard Features
-	KPI cards summarizing overall accident impact
-	Clustered bar chart comparing collisions, injuries, and deaths by county
-	Combo chart showing monthly injuries alongside fatality rate trends
-	Vehicle-type analysis highlighting differences in fatality risk
-	DAX-based metrics for dynamic calculations like total collisions, injuries, deaths, and death rate

## Key Insights
-	Counties with similar collision volumes can experience very different fatality outcomes
-	Fatality rates remain consistently above 20% throughout the year
-	Certain vehicle types show higher death rates despite comparable collision counts

## Disclaimer
This dashboard uses simulated data and is intended solely for learning and portfolio demonstration purposes.

## How to Use
1. Download the Power BI (.pbix) file
2. Open with Power BI Desktop
3. Explore the dashboard using filters and slicers

## Future Improvements
- Incorporate real accident datasets
- Add predictive analytics
- Include weather and road conditions




