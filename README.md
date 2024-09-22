# Crowdfunding_ETL Mini Project

# Resources: crowdfunding.xlsx and contacts.xlsx used 

# Catgory and Subcategory DataFrames are created and extracted to csv files 
## category_id is created based on number of unique categories
## subcategory_id is created based on number of unique subcategories 

# Campaign DataFrame is created and extracted to csv file
## subcategory_id and category_id added at the end of Campaign DataFrame to identify the unique identifiers 

# Contacts DataFrame is created and extracted to csv file
## Two seperate columns are craeted for First Name and Last Name and the columns are re-arranged

# Crowfunding Database is created
## crowfunding_db_schema.sql is cretaed and each csv files are loaded. 
## crowfunding_table_schema.png is created to indicate the mapping 
### Each table is inspected using the using "select * from " statement to ensure 1) tables are created and 2) the data is loaded
### For each table, the data type is defined 
### "contacts" table -- > the primary key is contact_id
### "category" table --> the primary key is category_id 
### "subcategory" table --> the primary key is subcategory_id 
### "campaign" table --> the primary key is cf_id and includes the contact_id, category_id and subcategory_id as foreign key



