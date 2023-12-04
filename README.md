## Project 2 (Extract, Transform, and Load) README Summary
### Project Overview
`This one-week ETL mini project involves partnering to build an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions. The main tasks include extracting and transforming data, creating CSV files, developing an Entity-Relationship Diagram (ERD), defining a table schema, and uploading data to a Postgres database. Key to success is collaboration and regular communication with your partner, aiming for at least half of the project completion before the third class day.`

### Instructions
1. Create Category and Subcategory DataFrames:

`Extract and transform data from crowdfunding.xlsx to create category and subcategory DataFrames.`

`The category DataFrame should have category_id and category columns; export as category.csv.`
`The subcategory DataFrame should have subcategory_id and subcategory columns; export as subcategory.csv.`

2. Create the Campaign DataFrame:

`Create a campaign DataFrame with multiple specified columns, including ID fields, financial goals, dates, and more.`
`Export this as campaign.csv.`

3. Create the Contacts DataFrame:

`Choose between Python dictionary methods or regular expressions for data extraction and transformation.`
`Tasks include data import, transformation, data splitting, and DataFrame cleaning.`
`Export the final DataFrame as contacts.csv.`

4. Create the Crowdfunding Database:

`Inspect the four CSV files and sketch an ERD.`
`Create a table schema for each CSV file, considering data types, keys, and constraints.`
`Save the schema as crowdfunding_db_schema.sql.`
`Create a new Postgres database (crowdfunding_db), implement the schema, and import CSV data.``Verify data integrity with SELECT statements.`