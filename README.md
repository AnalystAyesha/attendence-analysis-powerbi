# attendence-analysis-powerbi
Table of Contents
	•	Project Overview
	•	Data Source
	•	Tools
	•	Data Cleaning / Preparation
	•	Exploratory Data Analysis (EDA)
	•	Data Analysis
	•	Results / Findings
	•	Recommendations
	•	References
  
Project Overview
This project is an Employee Attendance Analysis dashboard created using Power BI.
The main aim of this dashboard is to analyze employee attendance patterns such as Presence, Work From Home (WFH), and Sick Leave over a period of time.
I used this dashboard to understand trends based on date, month, employee name, and day of the week, and to present the insights in a clear and interactive way.

Data Source
The dataset used for this project is an employee attendance dataset containing daily attendance information.
It includes employee names, attendance status, and date-related fields.
The data was not clean initially and required multiple transformation steps before analysis.

Tools
	•	Power BI Desktop
	•	Power Query Editor
	•	DAX (Data Analysis Expressions)

Data Cleaning / Preparation
Data cleaning was done in Power Query. The following steps were performed:
	•	Removed unnecessary top rows
	•	Renamed columns for better understanding
	•	Unpivoted columns so that all dates are in a single column
	•	Filtered unwanted rows
	•	Checked and corrected data types

These steps helped in making the data structured and ready for analysis.

Exploratory Data Analysis (EDA)
During EDA, I focused on understanding:
	•	Overall attendance percentages
	•	Employee-wise attendance behavior
	•	Day-of-week patterns for presence, WFH, and sick leave
	•	Monthly trends for April, May, and June

Data Analysis
For analysis, I created multiple DAX measures to calculate:
	•	Presence Percentage
	•	Work From Home Percentage
	•	Sick Leave Percentage

The dashboard includes:
	•	KPI cards for key attendance metrics
	•	A table showing employee-wise attendance percentages
	•	A matrix visual with employee names, months, and totals
	•	Area charts for presence, WFH, and sick leave percentages by date
	•	Separate tables showing day-of-week analysis
	•	A month slicer (April, May, June) for interactive filtering

Results / Findings
	•	Attendance trends change across different days of the week
	•	Work-from-home patterns are clearly visible over time
	•	Monthly analysis shows variation in presence and leave percentages
	•	Employee-wise comparison helps identify attendance behavior easily

Recommendations
	•	Attendance trends can be used for better workforce planning
	•	Regular monitoring of sick leave patterns may help in early action
	•	WFH trends can support flexible work policy decisions
	•	Updating this dashboard regularly can provide ongoing insights

References
	•	Microsoft Power BI Documentation
	•	DAX Guide
	•	Power Query Documentation
