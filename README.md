# Data Cleaning & Reporting Automation

## Project Overview

This project focuses on automating the process of data cleaning, preprocessing, reporting, and visualization using Python. A sales dataset was created and processed using Google Colab, Pandas, and Matplotlib.

The project demonstrates how raw and inconsistent data can be transformed into a clean and useful dataset and then used to generate automated reports and visual summaries.

## Objective

The main objectives of this project are to:

* Identify and handle missing values.
* Detect and remove duplicate records.
* Standardize inconsistent data.
* Calculate missing sales values.
* Generate automated summary reports.
* Create product-wise and city-wise sales reports.
* Generate visualizations for better understanding of the data.
* Export the cleaned data and reports for further use.

## Tools & Technologies

* Python
* Pandas
* Matplotlib
* Google Colab
* GitHub
* CSV

## Dataset

The project uses a sample sales dataset containing information about:

* Order ID
* Date
* Customer
* City
* Product
* Quantity
* Price
* Sales

The original dataset intentionally contains missing values, duplicate records, and inconsistent product names to demonstrate the data-cleaning process.

## Data Cleaning Process

The following preprocessing steps were performed:

1. Loaded and inspected the raw dataset.

2. Checked the number of rows and columns.

3. Identified missing values.

4. Detected duplicate records.

5. Removed duplicate records.

6. Handled missing quantity values.

7. Calculated sales values using:

   `Sales = Quantity × Price`

8. Standardized inconsistent product names.

9. Handled missing dates.

10. Created and saved the cleaned dataset.

## Reporting

After cleaning the data, automated reports were generated, including:

* Overall sales summary
* Total number of orders
* Total quantity sold
* Total sales
* Product-wise sales
* City-wise sales

## Data Visualization

The project also generates visual summaries to make the results easier to understand.

The visualizations include:

* Product-wise Sales Chart
* City-wise Sales Chart

## Project Workflow

```text
Raw Sales Data
      ↓
Data Inspection
      ↓
Missing Value Detection
      ↓
Duplicate Detection
      ↓
Data Cleaning
      ↓
Data Standardization
      ↓
Sales Calculation
      ↓
Cleaned Dataset
      ↓
Automated Reports
      ↓
Data Visualizations
```

## Expected Outcome

The project demonstrates how Python can automate data preprocessing and reporting tasks. It improves data quality by handling missing values, duplicates, and inconsistent data while reducing manual effort in generating reports.

The final outputs provide a clean dataset, structured reports, and visual summaries that can be used for further analysis and decision-making.

## Conclusion

This project demonstrates a complete data-cleaning and reporting workflow, starting from raw sales data and ending with cleaned data, automated reports, and visualizations. It provides practical experience in data preprocessing, automation, reporting, and data visualization using Python.
