# Data cleaning and basic analytics on Microsoft Excel

### Project overview
This is the first mini project on Excel and aims to implement lessons on data cleaning, using of the multiplication operator and Pivot chart for analysis. Data cleaning is a necessary step after data collection and is a serious step that may make or mar the analysis thereby directly affecting the making of data driven decision. For small datasets Microsoft Excel simplifies this process with her tools that provides fast and correct insights and are better than manual calculation/computation. The data provided was a small data set therefore Excel was appropriate for its cleaning and basic analytics using pivot tables.

### Objectives
1. To remove duplicate IDs – Aim was to ensure that each ID in the dataset is unique by identifying and removing any duplicate entries. 
2.To handle infinite values – Aim was to identify and drop any rows where the Price Per Unit column contains "inf", as these values are not valid for analysis.
3. Calculate the total value (revenue) by multiplying the total quantity sold by the price per unit.
4. To conduct regional Analysis – Calculate the total quantity sold and total value (Quantity × Price Per Unit) for each region; determine the total quantity and revenue made from sales by region.

### Data sources
Data provided by 3MTT 
### Tools
Microsoft Excel for data cleaning and pivot table for data analysis

### Data Cleaning and preparation
  -To identify duplicates: At the styles interface, conditional formatting was selected, followed by the highlight cell rules and then duplicate values. This was an essential step in the data cleaning process as it assisted in investigating and identifying duplicate values. Further investigation showed that these were not true duplicates as they other columns had different parameters. This may have been a data entry error. This may not be possible if the remove duplicates is used directly. 
  
   -To remove duplicates: From the home tab, with the ID column highlighted, data tools was accessed and the remove duplicates was clicked and all duplicate IDs were removed
   
   -To remove inf form price per unit: At the home tab and on the editing interface, the sort and filter icon was accessed and with one of the headers as active cell, filter was selected. This inserted arrows on all the headers and the arrow on the column for price per unit was selected and the inf selected from the drop down. The “inf” rows were highlighted by clicking on the first-row number and using shift+ control+ down key to select all affected rows. The selected part was right clicked on and the delete row Used filter to identify inf at column G and used delete rows option was chosen to delete the rows.
  
  -Use of multiplication operators in calculating total values: The cells containing the quantity values (G2 and G3) were multiplied with those containing price per unit (H2 and H3) to derive the total value
For example: 
Quantity	Price Per Unit	Total value
10	$20.00 	=G2*H2
15	$10.00 	=G3*H3

  
   -To conduct a regional analysis: A pivot table was activated. The region was applied to the row field while the quantity aggregated as sum and the total value aggregated as sum were inserted into the value field. This formed two columns at the field from which the regional data was adapted. The insights derived from tis is the ease and rapidity with which data was summarized. This is time saving and not only will it save man hours, it will also ensure that decisions are made promptly by the business owners.

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
The data cleaning and use of pivot table method of data analysis in Excel may not be adequate with larger volumes of data (big data). Other tools such as structured query language can be used in this case.
