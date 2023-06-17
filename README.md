# Data_Cleaning_2
We conducted a beginner's data cleaning process on a file with the following steps:

1. Imported the required CSV file.
2. Verified the columns present and their respective data types.
3. Created a new dataset containing only the relevant columns.
4. Calculated the total row counts for each item in the 'product' column, as well as identified the rows with the five smallest unit prices and the five largest total prices.
5. Utilized the 'groupby' function to generate a table that showcased the products sold in specified cities, along with the corresponding total quantities sold and total earned revenue.
6. Introduced a new column indicating the total price of each item sold on a particular day, factoring in a 10% discount if applicable.
7. Created another column by merging the city name with the product column.
8. Utilized the 'replace' function to replace the full city names with their respective initials.
9. Added a new column displaying the percentage of total price in relation to the sum of all total prices.
10. Performed data sorting operations.
11. Implemented an 'if-else' condition using NumPy's 'where' function to categorize the quantities sold as "200+", "100-200", or "<100" under the 'sales' column.
12. Repeated the above process using the '.loc' function, this time labeling the total prices as "300+", "100-300", or "<100".
13. Created a pivot table for each city, presenting the sum, mean, and maximum values of their individual total prices.
14. Generated a second pivot table categorizing each product under its respective category, providing the total quantities and total prices sold across all cities.
15. Finally, the resulting data was downloaded and saved to a specified folder on the desktop.
