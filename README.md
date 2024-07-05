# Credit Card Part 2

## Description

This project involves analyzing and cleaning data to identify bank clients with overdue payments exceeding 29 days. The tasks include reading data, merging datasets, cleaning and imputing missing values, converting categorical features, and adding dummy variables.


## Files

- `application_record.csv`: Contains application records of bank clients.
- `credit_record.csv`: Contains credit records of bank clients.

## Set Up
**Ensure you have the necessary libraries installed**:
    ```sh
    pip install pandas numpy
    ```

    ## Steps

### Task 1: Reading, Summarising, and Cleaning Data

#### Question 1
- Load the `application_record.csv` and `credit_record.csv` into DataFrames.
- Determine the number of rows and unique clients in both DataFrames.
- Merge the DataFrames on the `ID` column and analyze the merged DataFrame.

#### Question 2
- Map the `STATUS` values according to the given mapping.
- Create an array `list_of_defaults` containing clients with overdue payments within the last 12 months.
- Create `df_final` containing these clients and add non-defaulting clients to balance the data.
- Impute missing values and prepare the DataFrame for analysis.

### Task 2: Imputing Missing Values and Dealing with Categorical Features

#### Question 3
- Drop the `ID` column.
- Identify numeric and nominal variables.
- Analyze

  #### Question 4 
- Impute missing values in numeric and nominal columns using appropriate methods.

### Task 3: Converting Categorical Features and Adding Dummy Variables

#### Question 5
- Convert ordinal categorical features (e.g., `OCCUPATION_TYPE`) into numeric values.

#### Question 6
- Add dummy variables for nominal categorical features using one-hot encoding.


## Author

Kate Lee
* k4t3l33@gmail.com
