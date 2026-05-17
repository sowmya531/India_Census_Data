# Census Data Analysis using Pandas

## Overview

This project demonstrates basic and intermediate data analysis operations using the Pandas library in Python on the India Census dataset.

The notebook includes:

* Data exploration
* Styling dataframes
* GroupBy operations
* Filtering data
* Setting indexes
* Aggregations and summaries

---

## Technologies Used

* Python
* Pandas
* Jupyter Notebook

---

## Dataset

The project uses the India Census dataset containing information such as:

* State names
* District names
* Population
* Male and Female population
* Literacy
* Workers data
* Religion-based statistics
* Education statistics
* Age group statistics

---

## Concepts Covered

### DataFrame Styling

* Hide indexes
* Add captions/headings
* Style dataframes

### Data Analysis

* Filtering rows
* Selecting columns
* GroupBy operations
* Aggregation functions (`sum()`, `count()`)
* Indexing
* Resetting index

### Examples Performed

* Total Male Workers in Maharashtra
* Setting `District_code` as index
* Viewing dataframe columns
* Applying dataframe styles

---

## Practice Questions Covered

### Q1. How will you hide the indexes of the dataframe?

### Q2. How can we set the caption / heading on the dataframe?

### Q3. Show the records related with the districts - New Delhi, Lucknow, Jaipur.

### Q4. Calculate state-wise:

* Total number of population
* Total population with different religions

### Q5. How many Male Workers were there in Maharashtra state?

### Q6. How to set a column as index of the dataframe?

### Q7a. Add a suffix to the column names.

### Q7b. Add a prefix to the column names.

---

## Sample Code

```python
# Setting a column as index
census = census.set_index('District_code')

# Total Male Workers in Maharashtra
census[census['State_name'] == 'MAHARASHTRA']['Male_Workers'].sum()

# Hiding dataframe index
census.style.hide(axis='index')
```

---

## How to Run

1. Install Python
2. Install Pandas

```bash
pip install pandas
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run the notebook cells sequentially.

---

## Learning Outcomes

By completing this project, you will understand:

* How to work with Pandas DataFrames
* Data filtering and aggregation
* Styling dataframes
* Index handling in Pandas
* Real-world dataset analysis

---




