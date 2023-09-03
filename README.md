# EXCEL-ANALYSIS
HOSPITAL ER ANALYSIS
Data Cleaning:
The first step was to clean the data. Here are the tasks I performed:
•	Identifying Missing Values: The dataset had some missing values in the Patient_sat_score column. I used mean imputation to fill these gaps, ensuring the overall distribution was not affected.
•	Duplicate Entries: I found no duplicate values in this dataset and used conditional formatting to ensure its accuracy.
•	Splitting Columns for Enhanced Analysis: The original dataset had a 'Date-Time' column. To enable separate analyses for day-wise trends and hourly activity, I split this into two distinct columns: 'Date' and 'Time', using Excel's text-to-columns functionality.
📈 Data Analysis:
After cleaning the data, I proceeded to the analysis stage, focusing on patient demographics, operational metrics, and temporal patterns. My key findings include:
•	Significant variance in patient_waittime depending on the department_referral.
•	Older patients (patient_age) generally experience longer wait times.
•	A noticeable spike in patient activity in February, which could inform staffing schedules.
•	A higher frequency of visits among the White race compared to other racial groups.
•	The General Practice unit tends to receive a higher influx of patients over time.
🎨 Dashboard Creation:
Here's how I approached dashboard creation:
•	Defining Objectives: The main aim was to provide healthcare administrators and stakeholders with insights into patient demographics, wait times, and departmental referrals.
•	Selecting Metrics: Key metrics displayed include Average Patient Wait Time, Age Distribution, and Number of Referrals by Department.
•	Design and Layout: Given the sensitive and diverse nature of the data, I chose a multi-tab layout, each focusing on a different aspect like demographics or wait times. The color scheme is subdued and professional.
•	Data Visualization Tools: I used column graphs for Race and Department Referrals, line charts for wait time trends, and pie charts for average age and wait times.
•	Interactivity: To make the dashboard more user-friendly, I added slicers for gender and departments, and a timeline for date ranges.
