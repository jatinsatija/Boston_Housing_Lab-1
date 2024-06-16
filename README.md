# Boston Housing Data Analysis

# Overview

This project involves analyzing the Boston Housing dataset using PySpark to understand various aspects of the data. 
The dataset contains information on housing in Boston, including attributes like crime rate, number of rooms, and median value of homes. 
The goal is to preprocess the data, perform exploratory data analysis, and visualize key insights.

# Data Preparation

Loading the Data: The dataset is loaded from a CSV file into a PySpark DataFrame, with headers inferred and schema automatically detected.

Initial Data Inspection: Display the first few rows of the DataFrame and print the schema to understand the structure and types of data.

Observation Count: Calculate and print the number of observations in the dataset.

# Data Cleaning

Dropping Irrelevant Columns: Remove the column b from the DataFrame as it is not required for the analysis.

Rounding Numerical Columns: Round all numerical columns to two decimal places for consistency and ease of analysis.

Creating New Columns: Introduce a new column Age10, which scales the existing age column by a factor of 1.1.

# Data Visualization

Histogram of Age10: Plot a histogram of the newly created Age10 column to visualize its distribution.

Statistical Summary: Generate descriptive statistics for the dataset to get a summary of the central tendency, dispersion, and shape of the data distribution.

# Data Conversion

Convert to Pandas DataFrame: Transform the PySpark DataFrame to a Pandas DataFrame for easier manipulation and inspection.

Display Tail of Data: Print the last few rows of the Pandas DataFrame to verify the final state of the data.
