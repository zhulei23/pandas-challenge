Pandas_Challenge:

Option 1: Heroes of Pymoli

Challenge/Task:
1. Player Count
2. Purchasing Analysis (Total)
3. Gender Demographics
4. Purchasing Analysis (Gender)
5. Age Demographics
6. Top Spenders
7. Most Popular Items
8. Most Profitable Items

Process for running script:
1. Player Count
Collecting data for Total Players
Create dataframe for Total Players result

2. Purchasing Analysis (Total)
Collecting data for Number of Unique Items
Collecting data for Average Price 
Collecting data for Number of Purchases
Collecting data for Total Revenue
Create a summary DataFrame using above value

3. Gender Demographics
Grouping data of Gender by calculating SN column
Calculate data for Percentage of Players
Merging two dataframes by using Inner join
Rename columns to 'Total Count' & 'Percentage of Players'
Rename index
Adding % sign onto Percentage of Players column
Sorting data in ascending order

4. Purchasing Analysis (Gender)
Calculate data for Purchase Count
Calculate Total Purchase Value
Calculate Average Purchase Price
Calculate Avg Total Purchase Per Person
Create dataframes which conclude all the calculations above & add $ sign on the final results

5. Age Demographics
Define dataframe for age_bin
Create bins to hold values for ages
Create the labels for the bins
Slice the data and place it into bins
Categorize the existing players using the age bins
Calculate Total Count for each age group
Calculate Total count for all unique players
Calculate Percentage of Players for each age group
Create a summary data frame to hold the calculated results
Remove header on index
Adding % sign onto Percentage of Players column

6. Purchasing Analysis (Age)
Create bins to hold values for ages
Create the labels for the bins
Slice the data and place it into bins
Categorize the existing players using the age bins
Calculate Total Count for each age group
Calculate Total Purchase Value
Calculate Average Purchase Price
Calculate Avg Total Purchase per Person
Create dataframes which conclude all the calculations above & add $ sign on the final results

7. Top Spenders
Calculate data for Purchase Count
Calculate Total Purchase Value
Calculate Average Purchase Price
Create dataframes which conclude all the calculations above & add $ sign on the final results
Sorting Total Purchase Value column in descending order & display a preview of the summary data frame

8. Most Popular Items
Collecting data for Item ID, Item Name, and Item Price Columns
Group by retrieved data by Item ID & Item Name 
Calcuation for Purchase Count
Calculation for Total Purchase Value
Calculation for Item Price
Create dataframes which conclude all the calculations above & add $ sign on the final results
Sort the Purchase Count volume in descending order & display a preview of the summary data frame

9. Most Profitable Items
Sort the Total Purchase Value column in descending order & preview top 5 rows of dataframe


Three osbervable trends:
1. Male players are the primary players (84.03%) for the game of Heroes of Pymoli;
2. The top age group of the players are between 20 and 24 years old, and it is 44.79% of the age 
demographics; it is also the same group that purchase the most items;
3. The top 2 most popular items & most profitable items are Final Critic & Oathbreaker, Last Hope of the Breaking
Storm.