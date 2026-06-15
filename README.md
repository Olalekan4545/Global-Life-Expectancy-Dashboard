# Global-Life-Expectancy-Dashboard

# Overview
Life expectancy is one of the most important indicators of a nation's health and development. It reflects the combined impact of healthcare access, economic conditions, education, disease burden, nutrition, and public health policies.This project analyzes global life expectancy trends from 2000 to 2015 using data from the World Health Organization (WHO). The goal is to identify patterns in life expectancy across countries and investigate the factors that influence longevity.The analysis was conducted using Power BI and focuses on life expectancy trends, socioeconomic drivers, healthcare investment, and child health indicators.

## Problem Statement
Despite significant improvements in global healthcare, life expectancy continues to vary widely across countries. Understanding the factors associated with longer and shorter lifespans can help policymakers and health organizations make informed decisions.
This project seeks to answer:
How has life expectancy changed globally over time?
Which countries have the highest and lowest life expectancy?
How do developed and developing countries compare?
What factors are most strongly associated with life expectancy?
How do healthcare investment and child health outcomes influence longevity?

## Objective
The aims of this project is to:
Analyze global life expectancy trends between 2000 and 2015.
Compare life expectancy across countries and development status.
Identify key drivers of life expectancy such as GDP, schooling, adult mortality, HIV/AIDS, and income composition.
Examine the role of healthcare expenditure, vaccination coverage, and child nutrition.
Provide data-driven insights into global health inequalities.

## Dataset Information
**Time Period**: 2000–2015
**Key Variables**
Country
Year
Status (Developed/Developing)
Life Expectancy
Adult Mortality
Infant Deaths
Alcohol Consumption
Percentage Expenditure
Hepatitis B 
Measles 
BMI
Under-Five Deaths
Polio 
Total Expenditure
Diphtheria 
HIV/AIDS
GDP
Population
Thinness (1–19 Years)
Thinness (5–9 Years)
Income Composition of Resources
Schooling

## Data Cleaning
The dataset contained missing values across several variables, including GDP, Life Expectancy,Population, Hepatitis B, Schooling, and Total Expenditure.

**Data Quality Approach**
Missing values were retained as nulls.
No imputation was performed to avoid introducing assumptions.
Aggregate calculations automatically excluded blank values.
Data types were validated before analysis.

## Dashboard Structure
Page 1: Global Life Expectancy 



**Focus**:
Global life expectancy
Country comparison
Developed vs Developing countries
Geographic distribution of life expectancy


**Visuals**:
KPI Cards
Life Expectancy Trend by Year
Top 10 Countries by Life Expectancy
Bottom 10 Countries by Life Expectancy
Life Expectancy by Status
GDP vs Life Expectancy
Global Map

Page 2: Drivers of Life Expectancy



**Focus**:
Socioeconomic and health-related factors associated with longevity



**Visuals**:
Schooling vs Life Expectancy
Adult Mortality vs Life Expectancy
HIV/AIDS vs Life Expectancy
Income Composition of Resources vs Life Expectancy

Page 3: Health Investment & Child Nutrition



**Focus**:
Healthcare spending
Vaccination coverage
Child mortality


**Visuals**:
Health Expenditure vs Life Expectancy
Vaccination Coverage Analysis
infact Deaths vs Life Expectancy
Thinness vs Life Expectancy
BMI vs Life Expectancy
Top 10 Thinness Countries

## Key Insights
1. Life Expectancy Improved Over Time
Global life expectancy generally increased between 2000 and 2015, indicating improvements in healthcare access and living conditions.
2. Developed Countries Outperformed Developing Countries
Developed countries consistently recorded higher life expectancy, highlighting disparities in healthcare, education, and economic development.
3. Adult Mortality Had a Strong Negative Relationship with Life Expectancy
Countries with higher adult mortality rates tended to have significantly lower life expectancy.
4. Education Matters
Higher levels of schooling were associated with longer life expectancy, emphasizing the importance of education in improving health outcomes.
5. Economic Prosperity Supports Longevity
Countries with higher GDP and stronger income composition generally exhibited longer lifespans.
6. HIV/AIDS Reduced Life Expectancy
A higher HIV/AIDS burden was associated with lower life expectancy across many countries.
7. Child Health Influences Longevity
Countries with high under-five mortality and child malnutrition generally recorded lower life expectancy.

## Tools Used
Power BI : For Visualization


Power Query : for cleaning and structuring the dataset


DAX : for calcuations

## Conclusion
The analysis demonstrates that life expectancy is influenced by a combination of economic, educational, healthcare, and social factors. Countries with stronger healthcare systems, higher educational attainment, lower mortality rates, and better socioeconomic conditions consistently achieved longer lifespans.
The findings highlight the importance of sustained investment in healthcare, education, disease prevention, and child welfare to improve population health outcomes and reduce global health inequalities.


## 📂File Included
Global_Life_Expectancy_dashboard.pbix / [`Life_Expectancy_Dashboard.pbix`](Life_Expectancy_Dashboard.pbix) 


├──  Global_life_Expectancy_dataset.CSV

│        └── data/[`Life Expectancy Data.csv`](Life Expectancy Data.csv) 

│ 

├── Global_Life_dashboard.png


│   └── Page 1/[`Global_Life_Expectancy_(Page1).png`](Global_Life_Expectancy_(Page1).png)

│

│   └── Page 2/[`Drivers_of_Life_Expectancy_(Page2).png`](Drivers_of_Life_Expectancy_(Page2).png)

│

│   └── Page 3/[`Health_Investment_and_Child_Nutrition_(page3).png`](Health_Investment_and_Child_Nutrition_(page3).png)

│
├── images.png


│   └── Images/[`Adult_Mortality_vs_Life_Expectancy.png`](Adult_Mortality_vs_Life_Expectancy.png) / [`Countries_with_Low_Life_Expectancy.png`](Countries_with_Low_Life_Expectancy.png) / [`HIV_vs_Life_Expectancy.png`](HIV_vs_Life_Expectancy.png) / [`Life_Expectancy_Trend.png`](Life_Expectancy_Trend.png) / [`Schooling_vs_Life_Expectancy.png`](Schooling_vs_Life_Expectancy.png) / [`Top_10_Countries_with_High_Life_Expectancy.png`](Top_10_Countries_with_High_Life_Expectancy.png) / [`Vaccination_Coverage_Comparison_Between_Developing_and_Develop_Countries.png`](Vaccination_Coverage_Comparison_Between_Developing_and_Develop_Countries.png) / [`Vaccination_Tread_Over_Year.png`](Vaccination_Tread_Over_Year.png)

│

├── Insight.md

│     └── Insights/ [`Insights.md`](Insights.md) 

│


└── README.md / [`README.md`](README.md) 




## How to Use
1. Download the .pbix file from the dashboard folder [`Life_Expectancy_Dashboard.pbix`](Life_Expectancy_Dashboard.pbix)
2. Open with Power BI Desktop [Power BI Desktop](https://powerbi.microsoft.com/).
3.  Use slicers to explore insights across different dimensions

   

### 👨‍💻 About Me
I am a Data Analyst specializing in Excel and Powerbi. I love turning messy data into clean and actionable stories.

🔗 [Linkdin_Profile](https://linkedin.com/in/afolakemi-olalekan-145174253)




