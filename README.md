Healthcare Intelligence Dashboard

📊 Project Overview

This Power BI project offers a 360-degree view of hospital performance, designed to assist healthcare administrators in tracking patient flow, revenue generation, and staff efficiency. The report features navigation between three distinct views: Hospital Summary, Patient Summary, and Patient Details.

1. Hospital Summary (Executive View)

Key Metrics:

Total Patients: 2,506 (1,679 In-Patient vs 827 Out-Patient)

Financials: Avg Treatment Cost ($161.41) and Total Revenue breakdown by Age Group.

Operational Efficiency: * Avg ER Time: 65.63 minutes (Tracked by Department).

Staffing: Patient-Staff Ratio of 0.10.

Occupied Beds: 1,751 (Gauge Chart).

2. Patient Summary (Demographics & Trends)

Key Insights:

Admissions: 1,679 Admitted vs 209 Discharged.

Length of Stay (LOS): Average LOS is 1.70 days; trend analysis shows LOS decreases as patient age decreases.

Demographics: * Gender distribution (48.9% Female, 51.1% Male).

Age Group analysis showing highest patient volume in the 6-20Y bracket.

Outcomes: Tracking of Deaths (86), ICU cases (82), and Readmission rates by department.

3. Patient Details (Granular Data)

A detailed tabular view allowing granular access to specific patient records.

Includes Name, Age, Gender, Location (City/State), and current Status (Normal/Readmit).

fully filterable by Month and Department.

🛠️ Technical Workflow

Data Connectivity: Imported data from Excel/SQL sources.

Data Modeling: Established relationships between Patient Data, Staff Data, and Transaction tables.

DAX Calculations: Created measures for Avg ER Time, Occupied Bed Count, and Patient Sentiment Score.

UI/UX Design: Designed a dark-mode interface with custom navigation buttons ("Hospital Summary" -> "Patients Summary").

📂 How to use

Download the .pbix file from this repository.

Open in Power BI Desktop.

Use the top navigation bar to switch between summary and detail views.
