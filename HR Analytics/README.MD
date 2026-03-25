HR Report – Power BI Data Analysis Project
Type: Educational / Portfolio Project

Key Business Questions
How do social and professional aspects of headcount contribute to the current workforce structure of the analyzed company?
What is the level of employee retention during the company’s operations?How has employee turnover impacted the company?
Power of data visualization equips HR teams with the knowledge and allow to identify patterns, analyze attrition trends and develop targeted startegies for talent retention?

Data Overview
The analysis is based on two datasets containing 4,138 unique employee records. The first dataset includes employment history, while the second covers social and demographic information.
Data review enabled the creation of a main people_fact table and eight dimension tables, forming the basis of a star schema data model. The model includes seven many-to-one relationships with single cross-filter direction. The Manager table has a one-to-one relationship with bidirectional filtering.

Analysis Scope
The HR report provides analysis across three core dimensions, reflecting employment trends over time based on the timeframe selected in the slicer:
Headcount – shows the evolution of staffing levels over time, dynamically adjusting to the selected date range.
Retention – reflects the organization’s ability to retain employees over time, indicating how many employees remain within the selected period.
Turnover – represents the rate at which employees leave the organization, indicating workforce outflow during the selected period.

Key Insights & Business Conclusions
In 2021, headcount reached 3,414 employees, while the lowest level was 409 employees in 2012, during the early stage of company development.
The organization has been steadily strengthening its market position and culture year by year, becoming an increasingly attractive workplace. This is reflected in the rising employee retention trend.
Additionally, the turnover analysis confirms this positive trend, with a clear decrease in the number of employees leaving the company over time.
Recommendations
Focus attention on areas with the highest turnover rates, particularly R&D, Sales, and Legal departments.
Special attention should be given to employees at Director and Manager levels, as this may indicate challenges in quickly hiring professionals with the required competencies.

Skills Demonstrated
Power BI Desktop & Service
Data cleaning & transformation
Data modelling (star schema)
DAX measures & calculations (e.g., CALCULATE, FILTER, dynamic titles)
HR measures, dynamic titles of chosen visualizations
Business-focused data storytelling
HR related analytics
