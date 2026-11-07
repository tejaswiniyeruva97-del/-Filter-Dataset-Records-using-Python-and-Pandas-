# -Filter-Dataset-Records-using-Python-and-Pandas-
readme_content = """

## Project Overview
This project demonstrates how to filter dataset records
using Python and the Pandas library.

## Objective
To learn how to retrieve relevant records from a dataset
using single and multiple filtering conditions.

## Tools and Technologies
- Python
- Pandas
- Google Colab
- Jupyter Notebook

## Dataset
A Student Performance Dataset containing:
- Name
- Age
- Marks
- Department

## Project Implementation

### 1. Import Pandas
Import the Pandas library for data manipulation.

### 2. Create Dataset
Create a student dataset using a Python dictionary
and convert it into a Pandas DataFrame.

### 3. Filtering Examples

Example 1: Filter students with marks above 80.

Example 2: Filter students belonging to the CSE department.

Example 3: Filter students whose age is greater than 20.

### 4. Multiple Filtering Conditions

AND (&):
Filter students with marks above 80 and age below 22.

OR (|):
Filter students belonging to CSE or ECE departments.

### 5. Count Records
Use len() to calculate the number of filtered records.

### 6. Display Results
Display the original and filtered DataFrames.

## Learning Outcomes
- Understanding Pandas DataFrames.
- Filtering records using comparison operators.
- Applying AND and OR conditions.
- Retrieving specific dataset records.
- Counting filtered records.

## Conclusion
This project helped me understand how to filter
and retrieve relevant records using Python Pandas.
I learned to apply multiple conditions and analyze
the resulting DataFrames efficiently.

## Author
AI & ML Track Intern

## Project Name
Filter Dataset Records
"""

with open("README.md", "w", encoding="utf-8") as file:
    file.write(readme_content)

from google.colab import files
files.download("README.md")
