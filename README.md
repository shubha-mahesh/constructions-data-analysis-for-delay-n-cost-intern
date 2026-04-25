# Construction Project Delay & Cost Overrun Analysis

This project analyzes construction project performance using SQL and Power BI to identify delays, cost overruns, productivity gaps, and high-risk projects.

## Business Problem
Construction projects often face schedule delays, budget overruns, and variable productivity across sites. This project helps identify the main drivers behind those issues so teams can prioritize corrective action.

## Objective
- Measure project delay and cost performance
- Identify location-wise and weather-wise delay patterns
- Find high-risk and high-overrun projects
- Compare labor effort with completion progress
- Prepare decision-ready insights for business reporting

## Dataset
Synthetic construction project dataset with 1,000 rows.

### Key Columns
- Project_ID
- Project_Type
- Location
- Start_Date
- End_Date
- Planned_Cost
- Actual_Cost
- Cost_Overrun
- Planned_Duration
- Actual_Duration
- Schedule_Deviation
- Weather_Condition
- Labor_Hours
- Completion_Percentage
- Risk_Level

## Tools Used
- SQL
- Power BI
- DAX
- Python
- Data Visualization

## SQL Workflow
1. Imported and validated the dataset in SQLite
2. Created a clean analysis view
3. Calculated KPI metrics with SQL
4. Ran business queries for location, weather, cost, and productivity analysis
5. Used results for Power BI visuals

## KPI Summary
- Total Projects: 1000
- Delayed Projects: 830
- Average Delay: 134.04 days
- Cost Overrun: 19.41%
- On-Time Completion: 17.0%

## Key Business Insights
- Delay is concentrated in specific locations, especially Chicago and Houston.
- Rainy weather shows the highest average delay.
- A small number of projects drive major cost overruns.
- Some projects show strong labor efficiency, while others consume high labor with low completion.
- Risk level helps identify projects that need early intervention.

## SQL Analysis Areas
- KPI summary
- Delay by location
- Weather impact on delay
- High-risk projects
- Top cost overrun projects
- Planned vs actual cost comparison
- Labor hours vs completion percentage

## Business Impact
- Helped identify major delay drivers
- Highlighted financial risk from cost overruns
- Showed productivity gaps across projects
- Supported better prioritization for at-risk projects

## Power BI Pages
- Executive Summary
- Delay Analysis
- Cost Analysis
- Productivity Analysis
- Risk Analysis

## Future Improvements
- Add vendor-level analysis
- Add time-based trend analysis
- Add drill-through pages for project details
- Add predictive delay scoring
- Connect dashboard directly to the SQL database

## Interview Pitch
“I built a construction analytics project using SQL and Power BI to analyze delays, cost overruns, and productivity. The main insight was that weather, location, and a few high-risk projects drive most of the execution problems.”

