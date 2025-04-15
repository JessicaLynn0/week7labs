# Instructor-led Lab: Manipulating Data

In this assignment you will practice utilizing DataFrames in a program. 

For this lab, you will use the [github_teams.csv](/data/github_team.csv) which contains behavioral trace data extracted from GitHub.

## Accessing Data

Using the `github_teams` dataset, please perform the following operations in order:

* 1. Open the file within Python.
* 2. Find out what the column header names are.
* 3. Determine the number of columns.
* 4. Determine the number of rows.
* 5. Determine which columns are categorical and convert them from *object* to *category*.
* 6. How many unique values does `Team_type` have?
* 7. How many unique values does `Team_size_class` have?
* 8. What is the value of the 63rd row and 6th column?
* 9. What are the values for the 300th row?
* 10. Using three different methods, select row with index value 595 with 1st, 2nd, 3rd columns.
* 11. Using two different methods, select the row with index value 46 with the 3rd and 7th columns.
* 12. Create a new DataFrame for the column `bot_work` using two different methods.

## Sorting and Ordering data 

Now that you have learned to subsample data, it is your turn to apply your new knowledge. Using the `github_teams` dataset, please perform the following operations in order:

* 1. Select `human-bot` teams that have a `bot_members_count` value greater than and equal to 2.
* 2. Find the `human` teams that are `Large` and have a `human_gini` value greater than and equal to 0.75.
* 3. How many teams are in the `Small` or `Large` category?
* 4. How many teams are in the `Small` or `Large` cateogry with a `human_gini` value less than and equal to 0.20?
* 5. How many `human-bot` teams are in the `Medium` category?
* 6. Create a subsample of 50% of your data.
* 7. Create samples for a 8-fold cross validation test.
* 8. Select columns that are numeric and save it as a new DataFrame.
* 9. Remove the columns `bot_PRReviewComment` and `bot_MergedPR` from the DataFrame.
* 10. Save the columns `Team_size_class` and `human_members_count` as a new DataFrame.
* 11.Rename these two columns in the new DataFrame.

Save your notebook with output displayed within it and submit for grading.