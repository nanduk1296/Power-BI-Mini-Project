# Power-BI-Mini-Project
Power BI dashboard analyzing OSHA severe injury data (18K+ records, 2023-2024). Cleaned and categorized 2,000+ classification codes into readable groups. Includes trend analysis, severity breakdowns, geographic mapping, and AI-driven decomposition tree and key influencer visuals.
Construction & Industry Injury Insights- OSHA’s Severe Injury Report Analysis

1.	Project Overview
This project analyzes OSHA's Severe Injury Report (SIR) dataset, around 18,000 workplace incidents involving hospitalizations, amputations, and loss of eye across U.S. industries from 2023–2024. The raw data required significant cleaning (fixing misaligned records, correcting data types, standardizing formats) and was further enriched by grouping over 2,000 detailed injury classification codes, covering injury type, body part, event, and contributing source, into simplified, readable categories.
The Report aims to answer: which industries and sectors see the most severe incidents, what types of injuries and causes are most common, how incident patterns vary by geography and time, and which employers or equipment categories appear most frequently in severe injury reports. Given a construction/MEP background, particular attention is given to how the Construction sector compares to other industries in both incident volume and severity.
2.	Tools Used
-	Microsoft Excel for Data Cleaning.

-	Power BI for Data Transformation, Data Visualization and Dashboard Creation

3.	Dataset
-	Source: https://www.osha.gov/severe-injury-reports

-	Data contains: Incident date, employer, location, industry sector, severity outcomes (hospitalisation/amputation/eye loss), and injury classification (type, body part, cause) across ~18,000 records from 2023–2024.

4.	Steps Followed
5.	
•	Sourced OSHA's Severe Injury Report dataset from data.gov and identified it as suitable for construction and MEP focused safety analysis.

•	Cleaned data in Excel by removing irrelevant columns such as address details, raw classification codes, and inspection numbers, fixing data type inconsistencies in dates and NAICS codes, correcting misaligned records, and resolving blank or null values.

•	Built category mapping tables to simplify complex classification fields (injury type, body part, event, and source) from over 2,000 detailed codes into readable general categories. 

•	Imported the cleaned dataset and mapping tables into Power BI, linking them through table relationships. 

•	Added calculated columns and DAX measures for sector classification and ranking analysis.

•	Built dashboard pages using bar charts, trend lines, cross tab and heatmap visuals, KPI cards, and slicers for interactive filtering.


5.	Key Insights
6.	
•  Fractures and amputations dominate severity. Fractures account for 6,913 incidents (38.6%) and amputations 4,908 (27.4%) — together, two out of every three severe injuries in the dataset.

•  Hands and fingers are the most frequently injured body part, involved in 5,795 incidents (32.3%) — more than triple the next-highest category (Multiple/Whole Body, 2,027). 

•  Being struck by an object is the single leading cause of severe injury (4,259 incidents, 23.8%), followed closely by falls to a lower level (3,343) and being caught in/between equipment (3,311). 

•  Manufacturing has the highest amputation rate of any sector — 46.7% of Manufacturing incidents involved an amputation, more than double any other sector's rate. 

•  Construction has the lowest amputation rate (15.3%) but the highest hospitalization rate (90.5%) among sectors — incidents are less likely to result in amputation, but almost always serious enough to require hospitalization. 

•  Texas leads all states in incident volume (2,976 incidents, 16.6%), followed by Florida (2,179) — together nearly 29% of all incidents nationally. 

•  Postal and package-delivery employers dominate the top-incident list — USPS-related entities and UPS/United Parcel Service together account for well over 200 incidents among just a handful of employer names. 

•  Incident volume held essentially flat year over year — 8,938 incidents in 2023 vs. 8,985 in 2024, a marginal 0.5% increase, showing no meaningful improvement or decline. 

•  Loss of eye is rare relative to other severe outcomes — just 11 cases (0.06%) compared to 4,837 amputation cases and 14,616 hospitalization instances. 

•  Manufacturing and Construction together account for over half of all incidents outside the general "Other" sector bucket — reinforcing that heavy-industry and physical-labor sectors carry the bulk of severe-injury risk.


8.	Files Included
-	‘OSHA's Severe Injury Report (SIR) Cleaned Dataset.xlsx’ – Cleaned data worksheet named OSHA's Severe Injury Rprt Clean and Initial Data Worksheet

-	‘OSHA Severe Injury Report.pbix’ – Power BI Report

-	‘README.md’ – Project Description

7.	How to Use
-	Open `OSHA's Severe Injury Report (SIR) Cleaned Dataset.xlsx` to view the cleaned data.

-	Open `OSHA Severe Injury Report.pbix` in Power BI Desktop to explore the visuals.

