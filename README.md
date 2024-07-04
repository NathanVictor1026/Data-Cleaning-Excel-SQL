

# Data Cleaning Process using Microsoft Excel

## 1. File Conversion
- Converted the XLSX file to CSV format for easier data manipulation.

## 2. Filter Application
- Applied filters to all column headers to facilitate data examination and modification.

## 3. Whitespace Removal
- Identified and removed leading, trailing, and excess whitespace within company names using the TRIM() function, specifically in the location column.

## 4. Duplicate Removal
- Detected and eliminated duplicate entries from the dataset to ensure data integrity.

## 5. Special Character Correction
- Identified discrepancies in city names containing special characters (e.g., DÃ¼sseldorf), verified correct spellings using external sources, and performed replacements (e.g., corrected to "Dusseldorf").

## 6. Standardization of Terms
- Consolidated similar terms within the industry column, such as "crypto," "crypto currency," and "cryptocurrency," into a single term for consistency.

## 7. Data Consistency
- Rectified variations in country names (e.g., "United States" with differing punctuation) to maintain uniformity throughout the dataset.

## 8. Data Deletion
- Removed irrelevant rows, such as those where both "total laid off" and "percentage" fields were null, to streamline the dataset.

## 9. Date Formatting
- Encountered formatting issues with certain date entries that did not conform to Excel's date format; imported the CSV file to properly format dates.

## 10. Data Completion
- Addressed empty fields within the industry column by populating them with appropriate data entries.

## Conclusion
The cleaned dataset is now ready for import into Tableau for further analysis and visualization.

