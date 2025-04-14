# International debt analysis #
## Project Overview ##

International debt is the money a country owes to foreign lenders like governments, international organizations (e.g., the World Bank or IMF), or private investors. Countries borrow to fund development, stabilize their economies, or manage budget deficits. Types of debt include government (sovereign), corporate, and private debt. While borrowing can support growth, poor management can cause high interest burdens, instability, or debt crises. SQL queries were used to analyze which country has the highest debt and key debt indicators.

## Objectives ##

### 1) Assess the Overall Debt Landscape
Quantify the total debt owed by all countries, count the number of distinct countries, and identify the different types of debt indicators along with their meanings.

### 2) Analyze Country-Specific Debt Metrics
Determine which country has the highest total debt and the highest principal repayments, and calculate the average debt across different debt indicators.

### 3) Identify Key Debt Patterns and Trends
Find the most common debt indicator across countries and summarize major debt trends and insights from the dataset to support strategic analysis.

## Tools and Technology used: ##
#### .) Postgres: 
Act as a  database management system used to conduct debt analysis and indicators.
#### .) Query Language.
The database management system uses the query language SQL (Structured Query Language) for retrieving and processing data through aggregation operations while filtering and performing analytical calculations.
#### .) Dbeaver
For query execution and database administration

## Key InsightsAnd Findings ##
1) The total debt held by all countries between 1970 and 2015 amounted to 2.82 trillion dollars.

  ![image](https://github.com/user-attachments/assets/d218b04a-d713-41be-99ec-8ad28f9e4844)
  
2) A total of 125 distinct countries are recorded in the dataset, highlighting the dataset’s broad international coverage.
   
   ![image](https://github.com/user-attachments/assets/58d3e95d-a7fc-4fb3-a026-330213fc2407)
   
3) ## Debt indicators
   
   ![image](https://github.com/user-attachments/assets/4bfa2b9f-ab9a-4e7d-aa84-c17a0850b7fa)
   
   .) PPG = Public and Publicly Guaranteed debt
   
   .) PNG = Private Nonguaranteed debt
   
   .) AMT = Principal Amount (money borrowed)
   
   .) INT = Interest payments
   
   .) Multilateral = Organizations like the World Bank
   
   .) Bilateral = Country-to-country lending
   
### 3.1 Unique debt indicators  are as below: ###
#### a) Principal repayments on external debt, private nonguaranteed (PNG) (AMT, current US$)
 The amount paid back (principal only, not interest) on external debt borrowed by private companies without a government guarantee.
 
#### b) PPG, bonds (INT, current US$)
Interest payments on bonds issued by the public sector (PPG = Public and Publicly Guaranteed debt).

#### c) Interest payments on external debt, long-term (INT, current US$)
Total interest payments made on long-term external debt (debt with an original maturity of more than one year).

#### d) PPG, multilateral (INT, current US$)
Interest payments on loans from multilateral institutions (like the World Bank or IMF) made by the public sector.

#### e) PPG, commercial banks (AMT, current US$)
Amounts owed by the public sector to commercial banks (principal amounts, not interest).

#### f) PPG, official creditors (AMT, current US$)
Amounts owed by the public sector to official creditors (other governments or multilateral organizations).

#### g) PPG, bonds (AMT, current US$)
The total principal amount owed on bonds issued by the public sector.

#### h) Interest payments on external debt, private nonguaranteed (PNG) (INT, current US$)
Interest payments on external debt borrowed by private companies without government guarantees.

#### i) PPG, bilateral (AMT, current US$)
Principal amounts owed by the public sector to bilateral creditors (debt from one government to another).

#### j) PPG, private creditors (INT, current US$)
Interest payments made by the public sector to private creditors (like private banks or investors).

4) China had the highest amount of debt of a total of 266.46 Billion shilling between 1970 and 2015. This indicates  both its significant global economic presence and the scale of its borrowing activities. While this underscores China's investment-driven growth strategy, it also highlights the importance of careful debt management to avoid financial vulnerabilities.
   
   ![image](https://github.com/user-attachments/assets/fb4d7a86-37bc-4c8a-8f55-47e153f24d14)

5) The average debt across all indicators ranged between 0.1 billion and 6.93 billion USD, suggesting that while some types of debt are relatively minor, others involve substantial amounts. This range highlights a diverse distribution of debt among different categories, reflecting varying borrowing patterns, repayment obligations, and financial priorities among countries.
   
   ![image](https://github.com/user-attachments/assets/931d34d2-c644-40e1-a7f6-5ef9fc5d506d)
    
6) China has made the highest amount of principal repayments of 168,611.61 million dollars. Indicating strong debt management practices and suggests that China is actively working to reduce its external debt burden.
   
   ![image](https://github.com/user-attachments/assets/003bc506-0ed7-474e-8011-4b2770eefebb)
   
7) PPG (Public and Publicly Guaranteed) official creditors(INT, currency(us$) is the most common debt indicator, appearing in 107 countries.This indicates that borrowing from official creditors, backed by public guarantees, is widespread globally. It reflects the heavy reliance of many countries on official international funding sources (such as the World Bank, IMF, or government-backed loans) to support their development and financial needs.
   
   ![image](https://github.com/user-attachments/assets/5dc4b3f1-edd9-45fd-89f0-465687fa4efb)
   
## Other Debt indicators ##
### 1. GDP- Gross Domestic Indicators ###
The most generally used and common indicator is the debt-to-GDP ratio. It is calculated by dividing the total public debt outstanding at a point in time by the
country’s GDP. It measures the indebtedness level relative to the country’s economicactivity and assumes that all GDP resources are available to finance the debt burden,which may not be necessarily true. However, this indicator is recognized as the most relevant in measuring degree of indebtedness, stressing the government’s solvency
capability. 

### 2. Fixed Debt to floating debt ###
Fixed debt matures or re-financed in a period over 12 months while floating debt matures before a year. Analysis of ratio of debt placed at a term of less than one year and the one placed at a longer term shows the time government has to face its obligations in the maturity calendar. The longer the term, the longer the project maturation would be thus allowing making resources available for their payment. 

### 3. Public debt / domestic government revenue ###
This measures indebtedness level relative to the government’s payment capacity. It shows the number of required years to pay the total debt balance. This ratio shows the Government’s possibilities to collect revenues compared to the debt burden.

### 4. Interest / GDP ###
This indicator shows the burden of the interest on the public debt to the country. Itm can be interpreted as the country’s possibilities to face unproductive expenditures.

### 5. Market risk ###
Refers to the risk of increases in the cost of the debt arising from changes in market variables. Market risk includes interest rate risk and exchange rate risk,
refinancing risk, liquidity risk, and credit risk. The most common types of market risk are the interest rate risk and exchange rate risk.

### 6. Interest Rate risk/Refixing risk ###  
Refers to the risk of increases in the cost of the debt arising from changes in interest rates. For both domestic and foreign currency debt, changes in interest rates affect debt servicing costs on new issues when fixed rate debt is refinanced, and on existing and new floating rate debt at the rate reset dates.
Hence, short-term or floating rate debt is usually considered to be more risky than long-term, fixed rate debt.

## Conclusion ##
In conclusion, the international debt analysis highlighted significant global borrowing trends, with China emerging as the country with the highest debt and repayments. The analysis revealed that Public and Publicly Guaranteed (PPG) official creditor debts are the most common worldwide. The average debt across indicators shows a wide disparity in financial obligations among countries. Insights into principal repayments and debt types provide a clearer picture of global debt management practices. These findings shows the need for sustainable borrowing strategies to ensure economic stability.








   






   

