# Data_cleaning on Microsoft Excel

### Project overview
This is the first mini project on Excel and aims to implement lessons on data cleaning, using of the multiplication operator and Pivot chart for analysis.

### Objectives
1. To remove duplicate IDs – Aim was to ensure that each ID in the dataset is unique by identifying and removing any duplicate entries.
2.To handle infinite values – Aim was to identify and drop any rows where the Price Per Unit column contains "inf", as these values are not valid for analysis.
3. To conduct regional Analysis – Calculate the total quantity sold and total value (Quantity × Price Per Unit) for each region
4. Determine the region with the highest quantity and revenue made from sales.

### Data sources
Data provided by 3MTT 
### Tools
Microsoft Excel for data cleaning

### Data Cleaning and preparation
1. To identify duplicates: Used Styles> Conditional formatting, highlight cell rules> duplicate values.
2. To remove duplicates: Used Home, data tools> remove duplicates 
3. To remove inf form price per unit:Used filter to identify inf at column G and used delete rows

### Exploratory data analytics
1. What is the total value per unit?
2. What is the regional total quantity sold and total value(revenue accrued)?

### Result and findings
1 There were 3 duplicated IDs, 4 missing values on the region column and 7 rows on price per unit column shown as infinite (inf). Some rows had more than one problem. Cleaned data therefore reduced to 21 rows of data from the initial 32.
2.The West region sold the highest quantity and also made the highest revenue while the Asgard region made the least.

### Recommendations
1. The data entrants, entry platforms need to be reviewed to ensure completeness of data going forward
2. Determinants responsible for the sales at West should be studied and replicated on the other zones.

### Limitations
The IDs were for different persons and for different dates. This also goes to the missing regions. These errors might skew the analysis 
