# Python Exercises

This repository contains my Python exercises from the Data Analyst Training Program at Tose'e Institute.

The exercises start with basic Python programming and gradually move to data cleaning, Pandas, Excel files, grouping, merging, date analysis, missing values, and sales analysis.

## Course Information

* **Institute:** Tose'e Institute
* **Instructor:** Dr. Ehsan Khakbazan
* **Course:** Data Analyst Training Program
* **Language:** Python

## Exercises

### Exercise 01

Basic input and output, string formatting, and extracting the middle characters of a string.

### Exercise 02

Working with Python lists, including reversing lists, inserting and appending values, finding unique elements, replacing values, removing empty strings, and joining characters.

### Exercise 03

Functions, loops, number patterns, reversing numbers, list comprehension, dictionary comprehension, and basic string analysis.

### Exercise 04

Basic data cleaning with Pandas using the `WoodInc-sale.xlsx` file.

This exercise includes:

* Reading an Excel file
* Reviewing columns and data types
* Checking basic statistics
* Renaming columns
* Filtering customer records
* Removing extra spaces from text values

### Exercise 05

Customer and product sales analysis using Pandas.

This exercise includes:

* Calculating total purchases for each customer
* Finding the top three customers
* Calculating the sales share of top customers
* Calculating total purchases for each product
* Calculating the sales share of products

### Exercise 06

Date and monthly sales analysis using the WoodInc sales and purchase files.

This exercise includes:

* Converting dates to the Jalali calendar
* Calculating monthly sales
* Calculating average selling prices
* Counting customers by month
* Grouping customers by month
* Finding the top three customers in each month

### Exercise 07

Product inventory analysis based on sales and purchase data.

This exercise includes:

* Calculating total sales quantity by product
* Calculating total purchase quantity by product
* Calculating year-end inventory
* Calculating monthly inventory for each product

### Exercise 08

Combining store sales data and correcting inconsistent values.

This exercise includes:

* Reading multiple Excel sheets
* Combining store DataFrames
* Finding inconsistent SKU values
* Replacing incorrect characters in SKU values
* Finding and correcting invalid `Unit Sales` values

### Exercise 09

Time-based sales analysis using the TincyCo data.

This exercise includes:

* Finding missing values in `Dollar Sales`
* Replacing missing values with the overall average
* Converting the `Date` column to datetime
* Calculating sales by year, quarter, month, week, and day
* Calculating monthly sales for each SKU
* Replacing missing sales values with the average sales of the related SKU

## Data Files

The exercises use the following Excel files:

* `WoodInc-sale.xlsx`
* `WoodInc-purchase.xlsx`
* `TincyCo.xlsx`
* `TincyCo-V2.xlsx`

The Excel files are stored in the `data` folder.

## Repository Structure

```text
Fatemeh_Kamrani_Python_Exercises/
│
├── README.md
├── Fatemeh_Kamrani_Python_EX_01.ipynb
├── Fatemeh_Kamrani_Python_EX_02.ipynb
├── Fatemeh_Kamrani_Python_EX_03.ipynb
├── Fatemeh_Kamrani_Python_EX_04.ipynb
├── Fatemeh_Kamrani_Python_EX_05.ipynb
├── Fatemeh_Kamrani_Python_EX_06.ipynb
├── Fatemeh_Kamrani_Python_EX_07.ipynb
├── Fatemeh_Kamrani_Python_EX_08.ipynb
├── Fatemeh_Kamrani_Python_EX_09.ipynb
│
└── data/
    ├── WoodInc-sale.xlsx
    ├── WoodInc-purchase.xlsx
    ├── TincyCo.xlsx
    └── TincyCo-V2.xlsx
```

## Tools Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Excel files
* Data cleaning and transformation methods

## How to Use

1. Download or clone this repository.
2. Open the required Notebook in Jupyter Notebook or JupyterLab.
3. Make sure the related Excel files are inside the `data` folder.
4. Run the cells from top to bottom.

For example:

```python
pd.read_excel("data/WoodInc-sale.xlsx")
```

## Notes

* These exercises were completed as part of a data analyst training program.
* Each Notebook is related to one exercise.
* Some exercises use Excel files with missing or inconsistent values.
* The data cleaning steps are included in the related Notebooks.
* The results depend on the Excel files included in this repository.

## Author

**Fatemeh Kamrani**

[GitHub Profile](https://github.com/fatemehkamrani79)
