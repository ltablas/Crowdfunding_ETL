# Crowdfunding_ETL

Crowdfunding ETL Project is broken up into 4 distinct parts:

    1. Create the Category and Subcategory DataFrames
    2. Create the Campaign DataFrame
    3. Create the Contacts DataFrame
    4. Create the Crowdfunding Database

The jupyter notebook called "ETL_Mini_Project_LTablas" contains the deliverable for parts 1-3. Option 1 (Python dictionary methods) was used for creating the Contact Dataframe in Part 3.

Resources folder contains raw crowdfunding and contacts Excel files, as well as: 
        1. category and subcategory dataframes from part 1, exported as csv's,
        2. campaign dataframe from part 2 exported as csv,
        3. contacts dataframe from part 3 exported as csv.

Deliverables for Part 4 - Creating the Crowdfunding Database - are listed and described below:
            1. crowdfunding_ERD.png, which is the image of the ERD created using QuickDBD app
            2. crowdfunding_db_schema.sql, which is the exported database schema in postgres format
            3. crowdfunding_db_queries.sql, which are a series of SELECT * statements for each table to show that they were correctly imported.
            NOTE - the order in which the csv files were loaded into crowdfunding_db are: category, subcategory, contacts, and campaign
            4. pg4_Admin_screenshots.doc, which are screenshots showing results of the SELECT * statements referenced above.

