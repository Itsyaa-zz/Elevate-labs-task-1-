# Elevate-labs-task-1
Netflix Dataset – Data Cleaning Summary:
Changes Made:
Missing Values Identified (but not deleted):

director: 2634 missing

cast: 825 missing

country: 831 missing

date_added: 10 missing

rating: 4 missing

duration: 3 missing

Duplicate Rows: 0 duplicates found (none removed).

Text Standardization:

country values were stripped and title-cased for consistency.

Date Formatting:

date_added converted to consistent format: dd-mm-yyyy.

Column Headers:

Renamed to lowercase with underscores (e.g., date_added, release_year).

Data Types Fixed:

release_year: converted to integer.

date_added: converted to datetime.
