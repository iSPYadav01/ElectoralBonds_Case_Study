# Electoral Bonds Analysis

This repository contains code snippets and analyses related to electoral bonds data. Electoral bonds are financial instruments used for making donations to political parties in India. The data used in this analysis includes two datasets: Data_Part1 and Data_Part2.

## Datasets

### Data_Part1

- **Source**: Electoral Bonds Database
- **Description**: This dataset contains detailed information about electoral bonds purchased, including the date of purchase, purchaser name (usually corporate entities), and denomination (in INR).

### Data_Part2

- **Source**: Electoral Bonds Database
- **Description**: This dataset provides information about electoral bonds encashed, including the date of encashment, the name of the political party receiving the donation, and the denomination (in INR).

## Analysis

1. **Total Denomination Analysis**
   - This analysis involves calculating the total denomination of electoral bonds from both Data_Part1 and Data_Part2.
   - The code snippets include pandas operations to sum the denominations and visualize the total denomination by different categories such as purchaser and political party.

2. **Total Number of Rows Analysis**
   - This analysis focuses on counting the total number of rows in Data_Part1 and Data_Part2.
   - It provides insights into the volume of data available in each dataset and helps in understanding the dataset's completeness.

3. **Difference Analysis**
   - This analysis involves subtracting the values of Data_Part1 from Data_Part2 to understand the difference between purchased and encashed electoral bonds.
   - The resulting difference indicates the net outstanding bonds or discrepancies between purchased and encashed bonds.

## Instructions

To run the code snippets provided:

1. Clone the repository:
