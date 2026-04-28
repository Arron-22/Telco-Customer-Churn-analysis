# Data Cleaning and Preparation

This document shows the process involved to make sure the dataset was cleaned and prepared using Excel before being imported into Power BI for analysis.

## Data type Conversion:

•	The Monthly Charges and Total Charges columns were originally stored as text.

•	These columns were converted into numeric format to all accurate calculations and aggregation in Power BI

## Handling Missing Values:

•	The dataset was checked for missing or null values using filters

•	After converting data types, no missing values were found

## Data Validation and Consistency Checks:

•	Verified that all numerical columns contained valid values

•	Ensured categorical filed (Contract, Internet Service, Payment Method) were consistent and no formatting issues

•	Checked for duplicates and inconsistencies across records

## Derived Columns:

•	Customers were grouped based on their tenure to enable better analysis of churn patterns across different stages of customer lifecycle.

<img width="462" height="193" alt="image" src="https://github.com/user-attachments/assets/8ae8e648-15c5-44de-8b70-2843aa744ab4" />


•	Customers were categorized into pricing brands under the MonthlyChargeGroup column to allow easier comparison of churn behaviour across different pricing levels:

£0-30, £30-60, £60-90, £90+

•	Added an extra column called Churn to indicate whether a customer has left the service(Yes) or remained with the service(No).
