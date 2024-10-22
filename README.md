# Unicorn Investment Analysis - Data Validation and Preparation

## Project Overview

This project focuses on performing **data validation and preparation** on a dataset of unicorn companies—companies valued at over one billion dollars. Through this analysis, we aim to clean the data and prepare it for future analytical modeling by addressing data quality issues and converting categorical variables into a numerical format.

By conducting various transformations, particularly on datetime data, we can explore trends and patterns related to company growth and the timeline for achieving unicorn status.

## Table of Contents

- [Introduction](#introduction)
- [Tools Used](#tools-used)
- [Project Structure](#project-structure)
- [Data Validation Steps](#data-validation-steps)
  - [Step 1: Imports and Data Loading](#step-1-imports-and-data-loading)
  - [Step 2: Data Cleaning](#step-2-data-cleaning)
  - [Step 3: Converting Data Types](#step-3-converting-data-types)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)
- [References](#references)

## Introduction

Unicorn companies represent a fascinating segment of the business world, with their rapid rise to billion-dollar valuations. In this project, I analyzed a dataset of unicorn companies, focusing on trends in company age, valuation, and time to achieve unicorn status.

The analysis aims to address key questions:

- How long do companies take to achieve unicorn status?
- What are the valuation trends over time?
- How do different industries or regions affect these patterns?

## Tools Used

- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical operations.

## Project Structure

This analysis is divided into the following sections:

- **Step 1: Imports and Data Loading**: Import relevant libraries and load the dataset.
- **Step 2: Data Cleaning**: Explore dataset characteristics and clean the data.
- **Step 3: Converting Data Types**: Transform data types and encode categorical variables.

## Data Validation Steps

### Step 1: Imports and Data Loading

I began by importing the necessary libraries and loading the dataset into a Pandas DataFrame to start the cleaning and validation process.

### Step 2: Data Cleaning

- **Data Types**: Displayed the data types of each column to identify any necessary modifications.
- **Modify the Data Types**: Converted the `Date Joined` column to a `datetime` format for easier analysis.
- **Create a New Column**: Created a `Years To Unicorn` column to represent the time taken to reach unicorn status.
- **Input Validation**: Addressed issues like bad data, duplicate rows, and inconsistencies in `Industry` labels.

### Step 3: Converting Data Types

- **Convert Numerical Data to Categorical Data**: Created a `High Valuation` column based on the `Valuation` column.
- **Converting Categorical Data to Numerical Data**: Utilized various encoding methods (ordinal, nominal, dummy encoding) to transform categorical variables.

## Key Insights

- The `Years To Unicorn` column provides insights into how quickly companies achieve unicorn status.
- Data quality issues were systematically addressed to ensure accurate analysis.
- The choice of encoding methods for categorical variables was made based on the context.

## Conclusion

This project highlights the importance of data validation and preparation in any data analysis pipeline. By cleaning the data and converting categorical variables to numerical formats, I ensured the dataset was of high quality and ready for further analysis.

## How to Run

1. **Clone the repository**:

    ```bash
    git clone <https://github.com/MahmoudKhaled98/Unicorn-Investment-Analysis-Data-Validation-and-Preparation.git>
    ```

2. **Install the required dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter notebook**:

    ```bash
    jupyter notebook
    ```

## References

- [Bhat, M.A. *Unicorn Companies*](https://www.kaggle.com/datasets/mysarahmadbhat/unicorn-companies)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
