# PowerBI-Project: Personal Expenditure

## Project Description

This PowerBI report allows users to track and analyze their personal spending habits in a year. The report is designed to help individuals better understand how their
money is spent,identify areas where they may be overspending, and make more informeddecisions about their finances. It allows users to view their spending data in
various ways, such as by month and by category. Users can also create custom views and filters to focus on specific sub-categories of their spending.


## Data Sources
The data for this project is sourced from an Excel sheet of real-world data on personal expenditure, that I aggregated over the past year (2022). The data was cleaned, 
transformed and validated using Microsoft Excel to ensure it was in the correct format and that any errors or inconsistencies were corrected.

The dataset includes the following data fields:
- DATE: Date of purchase in the format dd-mm-yy
- WEEK: Week count/index within a year (1-53)
- DAY: Day of the week (Mon, Tue etc.)
- PURCHASE: Item purchased
- CATEGORY: Category of the item purchased. (Grocery, Subscription, Shopping etc.)
- SUB-CATEGORY: Category of the item purchased. (Eg., Tesco, Sainsburys and Lidl are among the sub-categories for Grocery)
- AMOUNT: Amount spent on the purchase in GBP (£)

Please note that only a subset of rows of the original dataset is used in the github version (expenditure_subset.xlsx) due to privacy concerns. Users can analyze their personal spending patterns
by replacing the contents of the dataset by their custom data (keeping the column headers the same) and using this dataset as the source data for the PowerBI report 
(expenditure.pbix).

## Screenshots
The report.pdf file contains screenshots of each page in the report.
