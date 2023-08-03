## Data Preparation and Processing

Departmental December - Finance: This project involves processing financial data for different departments in December. It includes tasks like extracting and cleaning data tables, handling measure and year values, and creating a unified dataset for analysis.

Calculating Moving Average: The goal of this project is to calculate the weekly average of daily sales at the start of 2019. It focuses on identifying trends using a moving average based on seven days' sales data.

Compare Monthly Targets: This project aims to compare monthly sales targets with actual performance data for employees. It involves calculating average monthly sales, filtering underperforming employees, and determining the percentage of months they met/exceeded their targets.

Bookshop Data Model: The focus of this project is to build a physical data model for Tableau's Bookshop dataset. It includes tasks like data union, joining related data sets, maintaining data granularity, and removing duplicates for a clean and organized dataset.


# 1. Departmental December - Finance

## Requirements

 -  Input the data
 -   Extract each data table within the Excel workbook
 -   Extract the branch name from the table structure  
 -   Create a row per measure and year
 -   Remove the word 'Year' from the year values
 -   Create a True Value (i.e. the correct number of zeros for the measure)
 -   Remove the suffix of the measure (i.e. the (k) or (m) if the measure name has the units)
 -   Remove unneeded columns
 -   Output the data
 
 ## Solution
![Departmental Finance](https://user-images.githubusercontent.com/95032838/215356019-0cca5f78-daf0-4b3a-bc45-f419c90bcb95.png)


# 2. Calculating Moving Average
daily sales at the start of 2019 and how we can work out the weekly average (using the 7 days before the current date) to work that out.
## Requirements

- Input Data
- Determine the weekly average sales for the current day and the previous six
- Don't create a moving average if it isn't the average of seven days sales.
- Clean-up the data for output by removing unnecessary columns

## Solution
<img width="1564" alt="Calculate Moving Average" src="https://user-images.githubusercontent.com/95032838/215354128-96a112d8-126e-46c2-b5f8-89a4cc2373dd.png">

 
 # 3. Compare monthly targets
 Compare monthly targets with data stored on another sheet...

Requirements
- Input data
 - Calculate the Average Monthly Sales for each employee
- In the Targets sheet the Store Name needs cleaning up
- Filter the data so that only employees who are below 90% of their target on average remain
 -  For these employees, we also want to know the % of months that they met/exceeded their target
- Output the data


## Solution
![Project3](https://user-images.githubusercontent.com/95032838/215352957-11da830c-f38f-49c8-9cad-dcbf51ededbb.png)



# 4. Bookshop Data Model
Build the physical data model to help you understand what is happening in Tableau's main example data set for relationships, Bookshop. 


## Requirement- Input data


- Input data
- Union all the Sales data together to form one row per item in a sale
- This is the granularity of the data set throughout the whole challenge (56,350 rows)
- Join all other data sets in the workbook on to this data
- Never let the number of rows change
- You may need to disregard incomplete records or summarise useful data into a metric instead of including all the detail
- Remove any duplicate fields
- Remove the two fields created (in Prep at least) as the result of the Union:
- Table Names
- Sheet Names
- Output your resulting single table

## Solution
  ![Book Sales Data](https://user-images.githubusercontent.com/95032838/215351824-b29b004f-daa7-4165-983c-9c04d68aed42.png)

  

