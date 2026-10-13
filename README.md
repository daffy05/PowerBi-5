Healthcare Data Analysis Dashboard
Project Overview
This project uses Power BI to explore and analyze healthcare admission data. The dashboard is designed to help users understand patient admissions, hospital activity, medical conditions, billing, and other healthcare trends through data visualization.
Objectives
Analyze healthcare admission records.
Explore patient demographics, including age and gender.
Examine admissions by medical condition, hospital, doctor, and admission type.
Review billing amounts and insurance-provider information.
Present healthcare data in an interactive Power BI report.
Tools Used
Microsoft Power BI Desktop — data cleaning, data modeling, and visualization
Power Query — data transformation
Power BI data model — dimension and fact tables
Data Model
The project organizes the data into the following tables:
`DimPatient` — patient details such as name, age, age group, gender, and blood type
`DimDoctor` — doctor information
`DimHospital` — hospital information
`DimDate` — date attributes such as year, month, month number, and quarter
`FactAdmission` — admission records and related measures/details
`healthcare_dataset2` — source/staging query used to prepare the model
Key Analysis Areas
Depending on the visuals included in the report, the dashboard can analyze:
Total admissions
Admissions by month and year
Patient age-group and gender distribution
Admissions by medical condition and admission type
Hospital and doctor activity
Billing amounts and insurance providers
Medication and test-result patterns
How to Open the Project
Download or clone this repository.
Open `PowerBI-5.pbix` in Power BI Desktop.
If Power BI requests access to the source data, update the data-source path or credentials as required.
Select Refresh if the source data is available.
Explore the report pages and visuals.
Repository Contents
`PowerBI-5.pbix` — Power BI report file
`README.md` — project documentation
> If the original source dataset is not included in this repository, users will need their own copy of it to refresh the report.
Notes
This is a data-analysis and visualization project. Findings depend on the contents and quality of the source healthcare dataset. The project should not be used to make clinical decisions.
