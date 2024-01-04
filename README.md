# sales-analysis

   **Learning:
   - Row into column.
   - Group column.
   - Reference table.
   - Trim.
   - append table
     
#let's break down the tasks.
1. *Task 1: Data Cleaning in dim_merchants table*
   - Split the 'Merchant' column into "Industry Segment" using a common delimiter.
   - Trim the "Industry Segment" column to remove leading and trailing spaces.
   - Use "Text Between Delimiters" to eliminate "(" and ")" from the "Industry Segment" column.
   - Remove duplicate merchants with different IDs.

2. *Task 2: Extracting Date Information (dim_date)*
   - Break down the date field in the Date Dimension table into separate components: year, month_name, and day_name.

3. *Task 3: Unpivot dim category table*
   - Perform row transformations and use the Unpivot column option to bring dim_category table into the desired format.
   - Rename the table to dim_category.

4. *Task 4: Filtering unwanted data*
   - Eliminate transactions with a debit amount below 100 from both fact_transactions_2022 and fact_transactions_2023 tables.

5. *Task 5: Append Tables*
   - Combine data from 2022 and 2023 transactions into a new table named 'fact_transactions'.

6. *Task 6: Merge Tables*
   - Integrate 'fact_transactions' with 'dim_category' and 'dim_merchants' to retrieve corresponding merchant names and category names.

7. *Task 7: Adding Conditional Column*
   - Create a conditional column 'Transaction Category' based on debit amounts: 'Low' for amounts below 1000 and 'High' for amounts above 1000.

8. *Task 8: Sorting and Grouping*
   - Analyze total transaction amount per merchant, duplicate 'fact_transactions' table, and sort merchants accordingly.

Learning:
   - Row into column.
   - Group column.
   - Reference table.
   - Trim.
   - append table
