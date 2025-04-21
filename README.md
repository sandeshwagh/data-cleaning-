
Dataset Used: customer_data.csv
Objective: Clean and prepare the dataset by handling missing values, removing duplicates, standardizing formats, and fixing data types.

📝 Steps I Followed (Excel Only):
1. Opened the Dataset
I opened the CSV file in Excel to get an overview of the dataset.

I looked at column names and scanned a few rows to understand the type of data (e.g., demographics, behavioral, etc.).

2. Checked for Missing Values
I selected the entire dataset and used Conditional Formatting → Highlight Cells Rules → Blanks to visually identify missing values.

I manually reviewed columns with missing values.

For rows with too many missing fields, I deleted the row if the data was not salvageable.

For partially missing rows:

Filled missing values in categorical columns (like gender or country) using the most frequent value (mode).

For numerical columns, I used the average (mean) to fill in missing values where appropriate.

3. Removed Duplicate Rows
I selected the entire dataset, then used Data → Remove Duplicates.

I made sure all columns were selected to identify exact duplicate rows.

Excel removed any duplicates found and gave a message with the count.

4. Standardized Text Formats
I ensured uniform text formatting:

Converted all text values in columns like Gender, Country, etc., to lowercase using Excel’s =LOWER(A2) function, then copied and pasted as values.

Corrected spelling inconsistencies manually (e.g., “USA” vs “Usa” vs “usa” → all changed to “usa”).

5. Converted Date Formats
For any columns with date values, I selected the entire column.

I used Format Cells → Custom and set the format to DD-MM-YYYY.

This ensured that all dates were consistently formatted.

6. Cleaned and Renamed Column Headers
I made all column headers lowercase and removed any spaces by:

Double-clicking the header cell, rewriting them as e.g., customer_id, birth_date, gender, annual_income, etc.

This was done to make them clean and programming-friendly for future use.

7. Checked and Fixed Data Types
I scanned through each column:

For age or income columns that should be numeric, I verified and converted text-format cells to numbers using Text to Columns or pasting special values.

For date columns, I ensured they were properly recognized by Excel as date-type (verified with the filter dropdown showing calendar controls).

📄 Final Deliverable:
You now have a cleaned Excel dataset with:

No missing or duplicate entries.

Standardized formatting (text, date).

Consistent and clean column headers.

Correct data types.

