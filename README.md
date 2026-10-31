Day 12 – Missing Value Identification
Internship
Organization: Veda Technology
Project: GlobalSuperstore Data Analysis
Task: Day 12 – Missing Value Identification
Objective
Identify missing values in the GlobalSuperstore dataset, count missing values by column, calculate missing-value percentages, and summarize the findings.
Dataset
- Worksheet analyzed: Day12_Missing_Values
- Records: 51,290 (excluding the header)
- Columns: 23
Method
1. Created a copy of the original Orders worksheet to preserve the source data.
2. Created a Day12_Missing_Summary worksheet.
3. Listed all 23 column names in the summary.
4. Used Excel COUNTBLANK with INDEX and MATCH to count blank cells in each column.
5. Calculated missing-value percentages using Missing Values / 51,290.
6. Documented the key finding without deleting or changing source records.
Results
Based on the values recorded during the task:
- Postal Code: 41,296 missing values.
- Other 22 columns: 0 missing values each.
- Postal Code missing-value percentage: approximately 80.54% (41,296 / 51,290 × 100).
Key Finding
The Postal Code field has a high proportion of blank values. These blanks should be investigated before deciding whether to impute, retain, or exclude them. No records were deleted as part of this identification task.
Workbook Sheets
- Orders – original dataset.
- Day12_Missing_Values – copied dataset used for analysis.
- Day12_Missing_Summary – column-wise missing-value counts and percentages.
Tools Used
- Microsoft Excel
- Excel formulas: COUNTBLANK, INDEX, MATCH
Note
This README documents the results reported during the task. Verify the workbook's final summary before submission.
