# Superstore Data Analysis – Task 1

## Project Overview

This project analyzes the Superstore dataset using Python and data analysis libraries.
The main objective is to understand the dataset, check data quality, perform sales analysis, and visualize the results.

## Libraries Used

* **Pandas** – Used for loading, cleaning, and analyzing the dataset.
* **NumPy** – Used for numerical operations.
* **Matplotlib** – Used to create visualizations.
* **Seaborn** – Used for data visualization and graphical analysis.

## Cell-by-Cell Explanation

### Cell 1 – Import Libraries

The required Python libraries are imported. These libraries provide the functions needed for data analysis and visualization.

### Cell 2 – Load the Dataset

The Superstore CSV file is loaded using Pandas. The data is stored in a DataFrame named `df`.

### Cell 3 – Display First Five Rows

The `df.head()` function displays the first five records of the dataset. This helps to understand the structure and type of data available.

### Cell 4 – Dataset Information

The `df.info()` function displays the number of rows, columns, column names, and data types. It is useful for understanding the overall structure of the dataset.

### Cell 5 – Statistical Summary

The `df.describe()` function provides statistical information about numerical columns. It includes values such as count, mean, standard deviation, minimum, and maximum.

### Cell 6 – Date Conversion

The Order Date and Ship Date columns are converted into date format. This allows date-based calculations and analysis.

### Cell 7 – Check Data Types

The dataset information is checked again after converting the date columns. This confirms that the date columns have been converted correctly.

### Cell 8 – Calculate Delivery Days

Delivery Days are calculated by finding the difference between Ship Date and Order Date. A new `Delivery Days` column is created.

### Cell 9 – Display Updated Dataset

The updated DataFrame is displayed to verify the newly created Delivery Days column and other existing information.

### Cell 10 – Find Unique Categories

The unique values in the Category column are identified. The dataset contains Office Supplies, Furniture, and Technology categories.

### Cell 11 – Check Missing Values

The `isnull().sum()` function checks every column for missing values. The result shows that there are no missing values in the dataset.

### Cell 12 – Calculate Category-wise Sales

The dataset is grouped by Category and total Sales are calculated. Technology has the highest total sales, followed by Furniture and Office Supplies.

### Cell 13 – Sales Visualization

A bar chart is created to compare total sales for each product category.

##1.Sales by Category

<img width="721" height="560" alt="image" src="https://github.com/user-attachments/assets/1b279613-6ac8-4a60-b728-72a5a4fa4859" />

##2.Sales Distribution

<img width="704" height="470" alt="image" src="https://github.com/user-attachments/assets/8c3c7cbf-4441-4e95-9637-6f04776df8c3" />

## Conclusion

The analysis provides a basic understanding of the Superstore dataset. The dataset was inspected, validated, processed, and analyzed to identify category-wise sales performance.
