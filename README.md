# IMDb_Dashboard
This focuses on the company IMDb and study the analysis of Movies and Actors since the company was created.
# Project Covers:
ERD.
Normalization.
Data cleaning using Power Query in Excel.
Analysis by SQL Server.
Visualization by Tableau.
EDA by Python. (in progress)
# Step 1:
We Searched about alot of data that contains many types of columns,rows and we found suitable one >>>> Kaggle

# Step 2:
Data was in only one table and some columns were multivalued. We tried to clean it by SQL But after searching we decided to use Power Query in Microsoft Excel.
# Step 3:
We understood the data and developed an expressive scenario. Then Create ERD
And convert it to Actual dataset by Normalize the table of data by Power Query:

Split Columns (Director, Country, Listed in) in Row.
Create a table for each column with show_id .
Clean columns by trim spaces.
Remove duplicated rows and null values.
Create other tables for each row without show_id.
Set a new index column as PK for each table.
Join tables in step 2 and 5 to create tables that have show_id and id for each other tables.
Convert datatype of added_date to date type.
Split the Duration column and remove string from it.

Then we import these Tables into SQL Server and create a Diagram that explains relationships.

# Visulization:
We used Tableau in this stepm to show interactive dashboard: https://public.tableau.com/app/profile/eslam.elsagheer/viz/IMDBDashboard_16646322262000/DashboardPage1?publish=yes

