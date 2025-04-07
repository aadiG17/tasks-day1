# Netflix Data Analysis Notebook

This Jupyter Notebook performs exploratory data analysis (EDA) on a Netflix dataset. It covers various aspects of data manipulation, cleaning, analysis, and visualization using the Pandas library in Python.

## Table of Contents

1. **Importing & Loading Data**
    - Importing the Pandas library
    - Loading the Netflix dataset from a CSV file
    - Saving the DataFrame as a CSV file
    - Displaying the first 5 rows
    - Displaying the last 5 rows
    - Displaying 5 random rows
    - Getting the dataset shape (rows, columns)
    - Getting column names
2. **Data Inspection**
    - Dataset summary using `info()`
    - Summary statistics using `describe()`
    - Getting data types
    - Checking memory usage
    - Getting the index
    - Counting unique values per column
    - Counting missing values
    - Counting duplicate rows
    - Counting non-null values per column
    - Counting occurrences of unique values
3. **Handling Missing Values**
    - Dropping missing values using `dropna()`
    - Replacing specific values using `replace()`
4. **Filtering & Selecting Data**
    - Selecting specific columns
    - Selecting a row by index using `iloc[]`
    - Filtering rows based on conditions using `loc[]`
    - Filtering with `isin()`
    - Selecting specific rows and columns using index with `iloc[]`
    - Getting a value at a specific row and column using `iloc[]` and `get_loc()`
    - Getting unique values using `unique()`
    - Counting unique values using `nunique()`
5. **Sorting & Ordering Data**
    - Sorting by a column using `sort_values()`
    - Multi-column sort using `sort_values()`
    - Sorting by index using `sort_index()`
    - Resetting the index using `reset_index()`
    - Renaming the index
6. **Grouping & Aggregation**
    - Summary statistics per group using `groupby()` and `describe()`
    - Counting the number of rows per segment using `groupby()` and `size()`
    - Getting the first row of each group using `groupby()` and `first()`
    - Getting the last row of each group using `groupby()` and `last()`
    - Ranking within each group using `groupby()` and `rank()`
7. **Merging, Joining & Concatenation**
    - Merging datasets using `merge()` with different `how` options (inner, left)
    - Appending rows using `concat()`
    - Converting columns to rows using `stack()`
    - Converting rows to columns using `unstack()`
8. **Pivot Tables & Crosstab**
    - Creating pivot tables using `pivot_table()`
    - Creating crosstabs using `crosstab()`
    - Pivoting data using `pivot()`
    - Unpivoting data using `melt()`
    - Transposing the dataset using `transpose()`
9. **String Operations**
    - Converting strings to lowercase using `str.lower()`
    - Converting strings to uppercase using `str.upper()`
    - Converting strings to title case using `str.title()`
    - Replacing values in strings using `str.replace()`
    - Checking for substrings using `str.contains()`


## Dataset

The notebook uses a Netflix dataset containing information about movies and TV shows. The dataset is loaded from a CSV file named 'netflix_titles.csv'.
Here is the kaggle link of the dataset: (https://www.kaggle.com/datasets/shivamb/netflix-shows)

## Requirements

- Python 3
- Pandas library

## Usage

1. Open the notebook in Google Colab or a Jupyter Notebook environment.
2. Install the required libraries if necessary.
3. Run the cells in the notebook sequentially to execute the code.
4. Explore the results and visualizations generated by the code.


## Note

- The notebook assumes that the Netflix dataset file ('netflix_titles.csv') is located in the same directory as the notebook.
- This notebook is for educational and demonstration purposes. It provides a basic framework for data analysis using Pandas and may require modifications for specific use cases.
