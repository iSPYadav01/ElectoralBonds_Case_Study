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


#### Instructions

To run the code snippets provided:

1. Clone the repository:
https://github.com/iSPYadav01/ElectoralBonds_Case_Study.git

===
{: .white_bg }

#### BJP_Denomination_vs_Month_2019
![BJP_Denomination_vs_Month_2019](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/BJP_Denomination_vs_Month_2019.png)

#### BJP_Denomination_vs_Month_2020
![BJP_Denomination_vs_Month_2020](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/BJP_Denomination_vs_Month_2020.png)

#### BJP_Denomination_vs_Month_2021
![BJP_Denomination_vs_Month_2021](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/BJP_Denomination_vs_Month_2021.png)

#### BJP_Denomination_vs_Month_2022
![BJP_Denomination_vs_Month_2022](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/BJP_Denomination_vs_Month_2022.png)

#### BJP_Denomination_vs_Month_2023
![BJP_Denomination_vs_Month_2023](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/BJP_Denomination_vs_Month_2023.png)

#### Comparison of Total Number of Bond from Purchaser and Political Party
![Comparison of Total Number of Bond from Purchaser and Political Party](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Comparison of Total Number of Bond from Purchaser and Political Party.png)

#### Count of Purchases by Purchaser and Denomination
![Count of Purchases by Purchaser and Denomination](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Count of Purchases by Purchaser and Denomination.png)

#### Denomination vs Month for Political Party
![Denomination vs Month for Political Party](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Denomination vs Month for Political Party.png)

#### Denomination vs Year for Data_Part1
![Denomination vs Year for Data_Part1](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Denomination vs Year for Data_Part1.png)

#### Denomination vs Year for Political Party
![Denomination vs Year for Political Party](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Denomination vs Year for Political Party.png)

#### Denomination_vs_Month
![Denomination_vs_Month](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Denomination_vs_Month.png)

#### Denomination_vs_Month_2019
![Denomination_vs_Month_2019](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Denomination_vs_Month_2019.png)

#### Denomination_vs_Month_2020
![Denomination_vs_Month_2020](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Denomination_vs_Month_2020.png)

#### Denomination_vs_Month_2021
![Denomination_vs_Month_2021](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Denomination_vs_Month_2021.png)

#### Denomination_vs_Month_2022
![Denomination_vs_Month_2022](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Denomination_vs_Month_2022.png)

#### Denomination_vs_Month_2023
![Denomination_vs_Month_2023](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Denomination_vs_Month_2023.png)

#### Denomination_vs_Month_2024
![Denomination_vs_Month_2024](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Denomination_vs_Month_2024.png)

#### Denomination_vs_Quarter
![Denomination_vs_Quarter](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Denomination_vs_Quarter.png)

#### Encashment_Trend_ALL INDIA TRINAMOOL CONGRESS
![Encashment_Trend_ALL INDIA TRINAMOOL CONGRESS](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Encashment_Trend_ALL INDIA TRINAMOOL CONGRESS.png)

#### Encashment_Trend_BHARTIYA JANTA PARTY
![Encashment_Trend_BHARTIYA JANTA PARTY](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Encashment_Trend_BHARTIYA JANTA PARTY.png)

#### Encashment_Trend_PRESIDENT, ALL INDIA CONGRESS COMMITTEE
![Encashment_Trend_PRESIDENT, ALL INDIA CONGRESS COMMITTEE](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Encashment_Trend_PRESIDENT, ALL INDIA CONGRESS COMMITTEE.png)

#### Encashment_Trend_Top3_Parties_2019
![Encashment_Trend_Top3_Parties_2019](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Encashment_Trend_Top3_Parties_2019.png)

#### Encashment_Trend_Top3_Parties_2020
![Encashment_Trend_Top3_Parties_2020](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Encashment_Trend_Top3_Parties_2020.png)

#### Encashment_Trend_Top3_Parties_2021
![Encashment_Trend_Top3_Parties_2021](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Encashment_Trend_Top3_Parties_2021.png)

#### Encashment_Trend_Top3_Parties_2022
![Encashment_Trend_Top3_Parties_2022](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Encashment_Trend_Top3_Parties_2022.png)

#### Encashment_Trend_Top3_Parties_2023
![Encashment_Trend_Top3_Parties_2023](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Encashment_Trend_Top3_Parties_2023.png)

#### image_list
![image_list](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/image_list.txt)

#### Least 20 Purchasers by Total Denomination
![Least 20 Purchasers by Total Denomination](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Least 20 Purchasers by Total Denomination.png)

#### Top 20 Name of the Political Party by Total Denomination
![Top 20 Name of the Political Party by Total Denomination](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Top 20 Name of the Political Party by Total Denomination.png)

#### Top 20 Purchasers by Total Denomination
![Top 20 Purchasers by Total Denomination](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Top 20 Purchasers by Total Denomination.png)

#### Total Denomination from Purchaser vs Political Parties
![Total Denomination from Purchaser vs Political Parties](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Total Denomination from Purchaser vs Political Parties.png)

#### Total Number of Bond from Purchaser vs Political Parties
![Total Number of Bond from Purchaser vs Political Parties](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Total Number of Bond from Purchaser vs Political Parties.png)

#### Total_Encashment_Top_3_Parties
![Total_Encashment_Top_3_Parties](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Total_Encashment_Top_3_Parties.png)

#### Year-wise_Encashment_Trend_Top_3_Parties
![Year-wise_Encashment_Trend_Top_3_Parties](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Year-wise_Encashment_Trend_Top_3_Parties.png)

#### Year_wise_Encashment_Trend_Top_3_Parties
![Year_wise_Encashment_Trend_Top_3_Parties](https://github.com/iSPYadav01/ElectoralBonds_Case_Study/blob/main/exported_images/Year_wise_Encashment_Trend_Top_3_Parties.png)