# Data-Engineering-Wizardry-Using-Tableau

**Fundamentals of Data Engineering - Tableau ETL Processes**

**Overview**

This repository provides a comprehensive guide to performing Extract, Transform, and Load (ETL) processes using Tableau for efficient data engineering. The ETL processes are divided into four phases, each containing a series of steps to cleanse, merge, and engineer the data to create meaningful insights.

**Phase 1**

Connect to Customer file.

Add a "Clean" step to initiate data cleaning.

Rename the field "LastNa" to "LastName".

Group the Education field and replace it with "College Degree".

Change marital status codes "M" and "S" to "Married" and "Single", respectively.

Clean up the prefix "MrR" to "MR".

Remove numbers from the "FirstName" field.

Remove punctuations from the "Occupation" field.

Split the email addresses and remove the characters before "@".

**Phase 2**

Add the "Adventure Works Customer New" file.

Replace null values in the Social Media Account field with "NoSocialMedia".

Split the Social Media fields into separate columns.

Load the cleaned data into the "DimCustomer" table.

**Phase 3**

Add the following files:

"AdventureWorks_Sales_2015"

"AdventureWorks_Sales_2016"

"AdventureWorks_Sales_2017"

Clean the "OrderQuantity" field from "Quantite de Ventes" to "OrderQuantity".

Union all three files to consolidate the data.

Add a calculation to extract the "Year" from the "Order Date" field.

Remove table names from the dataset.

Load the aggregated data into the "FactSales" table.

**Phase 4**

Add the "Returns" table and the "Product" table.

Perform an inner join on the Product key to combine the data.

Add aggregation to calculate various metrics.

Calculate the sum of prices for product returns.

Create a new table with the following columns:

Product Key

Territory Key

Create a new table in the database called "DMReturns".

**Conclusion:**
Feel free to explore the repository and learn the intricacies of ETL processes in Tableau. Happy data engineering!

If you encounter any issues or have suggestions, please feel free to raise an issue or submit a pull request. Your contributions are appreciated. Enjoy the journey of data engineering with Tableau!
