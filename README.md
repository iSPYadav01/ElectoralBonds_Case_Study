### Electoral Bonds Analysis
#### By : [iSPYadav01](https://github.com/iSPYadav01)

This repository contains code snippets and analyses related to electoral bonds data. Electoral bonds are financial instruments used for making donations to political parties in India. The data used in this analysis includes two datasets: Data_Part1 and Data_Part2.

### [Datasets](https://www.eci.gov.in/disclosure-of-electoral-bonds)

#### [Data_Part1](https://www.eci.gov.in/eci-backend/public/api/download?url=LMAhAK6sOPBp%2FNFF0iRfXbEB1EVSLT41NNLRjYNJJP1KivrUxbfqkDatmHy12e%2FzBiU51zPFZI5qMtjV1qgjFmSC%2FSz9GPIId9Zlf4WX9G9EkbCvX7WNNYFQO4%2FMjBvNyKzGsKzKlbBW8rJeM%2FfYFA%3D%3D)

- **Source**: Election Commission of India
- **Description**: This dataset contains detailed information about electoral bonds purchased, including the date of purchase, purchaser name (usually corporate entities), and denomination (in INR).

#### [Data_Part2](https://www.eci.gov.in/eci-backend/public/api/download?url=LMAhAK6sOPBp%2FNFF0iRfXbEB1EVSLT41NNLRjYNJJP1KivrUxbfqkDatmHy12e%2FzBiU51zPFZI5qMtjV1qgjFmSC%2FSz9GPIId9Zlf4WX9G9EkbCvX7WNNYFQO4%2FMjBvNyKzGsKzKlbBW8rJeM%2FfYFA%3D%3D)

- **Source**: Election Commission of India
- **Description**: This dataset provides information about electoral bonds encashed, including the date of encashment, the name of the political party receiving the donation, and the denomination (in INR).

#### Analysis

1. **Total Denomination Analysis**
   - This analysis involves calculating the total denomination of electoral bonds from both Data_Part1 and Data_Part2.
   - The code snippets include pandas operations to sum the denominations and visualize the total denomination by different categories such as purchaser and political party.

Comparison of Total Number of Bond from Purchaser and Political Party.png - 
   - This graph shows the comparison between total number of
The total denomination analysis is performed to
understand the distribution of money in each denom

2. **Total Number of Rows Analysis**
   - This analysis focuses on counting the total number of rows in Data_Part1 and Data_Part2.
   - It provides insights into the volume of data available in each dataset and helps in understanding the dataset's completeness.

3. **Difference Analysis**
   - This analysis involves subtracting the values of Data_Part1 from Data_Part2 to understand the difference between purchased and encashed electoral bonds.
   - The resulting difference indicates the net outstanding bonds or discrepancies between purchased and encashed bonds.

4. **Encashment Trend Analysis**
   - This analysis examines the trend of encashment of electoral bonds over time, from 2019 to 2023, providing insights into the patterns and fluctuations in bond encashment.

5. **Party-wise Encashment Analysis**
   - This analysis focuses on the total encashment of electoral bonds by the top three political parties, namely Bharatiya Janata Party (BJP), All India Trinamool Congress (AITC), and President, All India Congress Committee (AICC), for each year from 2019 to 2023.
   - It helps in understanding the distribution of electoral bond encashments among the major political parties.


![BJP_Denomination_vs_Month_2019](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/BJP_Denomination_vs_Month_2019.png)

#### Instructions

To run the code snippets provided:

1. Clone the repository:
https://github.com/iSPYadav01/ElectoralBonds_Case_Study.git
