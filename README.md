**#Summary of Changes for netflix_titles.csv**

Here is a proper summary of the data cleaning and preprocessing steps you performed:

Dataset: Netflix Movies and TV Shows.

Tools Used: Microsoft Excel.

Objective: To clean and prepare the raw dataset for analysis by handling missing values, standardizing formats, and removing inconsistencies.

**##Key Changes and Actions Performed:**

**Missing Values:**

Missing values in the director, cast, and country columns were identified and replaced with "Unknown" to ensure the rows were not deleted.

A small number of rows with missing date_added values were deleted as the data was unrecoverable and crucial for analysis.

**Duplicate Records:**

All duplicate rows in the dataset were identified and removed based on matching values across all columns.

**Text Standardization:**

The country column was cleaned by replacing trailing commas and inconsistent delimiters. For entries with multiple countries, the format was standardized to use a semicolon and a space (e.g., "United States; Canada").

The rating and type columns were reviewed to ensure all text was in a consistent case (e.g., "TV-MA" instead of "tv-ma").

**Date Format Consistency:**

The date_added column was converted from a text-based format (e.g., "September 25, 2021") to a standardized date format that Excel can recognize. This was done by first using Find and Replace to convert month names to numbers and then using the "Text to Columns" feature.

The entire dataset was then sorted by the date_added column from oldest to newest.

**Column Headers:**

Column headers were reviewed to ensure they were clean and uniform (e.g., release_year).

##Final Output:

A cleaned and structured dataset ready for analysis, saved as a .csv file.







