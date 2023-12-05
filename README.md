## Project 2 (Extract, Transform, and Load) README Summary
### Project Overview
`This one-week ETL mini project is building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions. The main tasks include extracting and transforming data, creating CSV files, developing an Entity-Relationship Diagram (ERD), defining a table schema, and finally uploading data to a Postgres database.`

### Working Files
1. [ETL_Mini_Project_MJardinico.ipynb](https://github.com/mjardinico/crowdfunding_ETL/commit/77f93b7a276fe4f7a8e75e2254bcc7dd872b3f07)
2. [Data files are located in Resources/ folder](https://github.com/mjardinico/crowdfunding_ETL/tree/main/Resources)

### Instructions
1. Create Category and Subcategory DataFrames:

* `Extract and transform data from crowdfunding.xlsx to create category and subcategory DataFrames.`
* `The category DataFrame should have category_id and category columns; export as [category.csv](https://media.githubusercontent.com/media/mjardinico/crowdfunding_ETL/main/Resources/category.csv).`
* `The subcategory DataFrame should have subcategory_id and subcategory columns; export as [subcategory.csv](https://media.githubusercontent.com/media/mjardinico/crowdfunding_ETL/main/Resources/subcategory.csv).`

2. Create the Campaign DataFrame:

`Create a campaign DataFrame with multiple specified columns, including ID fields, financial goals, dates, and more.`
`Export this as campaign.csv.`

![`Campaign Screenshot`](https://github.com/mjardinico/crowdfunding_ETL/blob/main/images/cat_id%26scat_id.png)

3. Create the Contacts DataFrame:

`Choose between Python dictionary methods or regular expressions for data extraction and transformation.`
`Tasks include data import, transformation, data splitting, and DataFrame cleaning.`
`Export the final DataFrame as contacts.csv.`

4. Create the Crowdfunding Database:

`Inspect the four CSV files and sketch an ERD.`
`Create a table schema for each CSV file, considering data types, keys, and constraints.`
`Save the schema as crowdfunding_db_schema.sql.`
`Create a new Postgres database (crowdfunding_db), implement the schema, and import CSV data.``Verify data integrity with SELECT statements.`