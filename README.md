# capstone-data-analytics
Final Capstone Project for Data Analytics Course

Housing Affordability Analysis: Peoria, AZ (zip code 85382) 

## Overview
This GitHub folder contains files and Power BI file and template that pertains to the housing affordability crisis in Peoria, Arizona. Specifically focusing on the zip code 85382 from the years 2015 to 2025. This analysis highlights the increasing gap between the median household income and median home values. While median household income has increased by 39%, the median home values rose by 95% from 2015 to 2025. With the combination of using calculated measures such as the affordability index combined with Power BI, this project shows the average home price in this area has risen over five times the median household income. 

## Technologies use
- Power BI Desktop: Used for data modeling, calculated measures and interactive visualizations on a dashboard. 
- Power Query: Used inside Power BI for data cleaning, data merging, shaping datasets, and preparing the data model. Power Query was also used instead of Python to support the linear regression model and forecasting process.
- Excel: Used for first time examination of the data
- Zillow Research Data: Source for the historical median home value data  
- U.S. Census Bureau: Source for historical household income for the past 12 months

  
### **Important Note: This Housing Affordability Analysis used Power Query instead of Python for the Linear Regression Model and data cleaning, data merging and data modeling.** 
- This process is in the **Power BI Modeling and Data Documentation.pdf file.**

## How to reproduce the analysis 
1.	Clone the repository 
- Download and or clone this projects folder to your computer.
  
2.	Install Required Software
- Power BI Desktop
- Microsoft Excel
- Internet access
  
3.	Open the Power BI File
- Open the .pbix file that is located in the project folder
  
4.	Connecting the data sources
- In Power BI, go to Home -> Transform Data -> Data Source settings
- Update the folder path to the Data_From_Census folder
- Update the Zillow data source path to the Zillow_Yearly_Data file
- Click Refresh in Power BI to load the data

## File Structure 
- This website was used in order to my File Structure Tree: https://tree.nathanfriend.com/ 

```text to show File Structure
└── Housing Affordabilty Analysis Capstone Project
    ├── Data
    │   ├── Median_Household_Income
    │   └── Zillow_Yearly_Data.csv
    ├── Documentation 
    │   ├── Instructional Report.pdf
    │   └── Power BI Modeling and Data Documentation.pdf
    ├── Housing Affordability Analysis.pbix
    └── README.md
```


    
  README.md


## Author Name
Onail Nissan 

