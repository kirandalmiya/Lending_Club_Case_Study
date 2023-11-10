# Lending Club Case Study
> This case study aims to empower the company a leading online loan marketplace with insights into loan default drivers, thereby enabling proactive measures to minimize credit loss and strengthen risk management strategies.

Leveraging Exploratory Data Analysis (EDA), the focus is on understanding key indicators of default empowering the company to optimize risk assessment and portfolio management.


## Table of Contents

- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [Collaborators](#collaborators)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This assignment is about using Exploratory Data Analysis (EDA) to solve a real business challenge in a consumer finance company. 
The goal is to understand and minimize the risk of losing money while lending to customers. In the dataset provided, which includes information about past loan applicants, we aim to identify patterns that indicate if a person is likely to default on a loan.
Key points include:
  The company faces risks in loan decisions: 
   losing business if a likely-to-repay applicant is rejected 
   financial loss if a likely-to-default applicant is approved.
  Through EDA, we want to find patterns that help make informed decisions, such as denying loans or adjusting interest      rates for risky applicants.
  The dataset includes loan acceptance scenarios (fully paid, current, charged-off) and rejected loans.
  The focus is on understanding how consumer and loan attributes influence the tendency of default, ultimately optimizing lending decisions.



## Conclusions
1 Loan applicants from states like California (CA), Florida (FL), and New York (NY) are more likely to default. 
  The company should monitor regional risk trends and adjust lending strategies or rates accordingly in these areas.

2.Given that a significant portion of "Charged Off" loans comes from applicants in Grades B, C, and D, it is advisable for the     company to enhance its risk assessment and underwriting criteria specifically for individuals in these grades. 
  This measure aims to mitigate the occurrence of defaulted loans and strengthen the overall quality of the lending portfolio.

3. Loan applicants with ten or more years of experience are more likely to default. 
This suggests that experience alone may not be a reliable indicator of credit worthiness. The company should use a more comprehensive credit scoring system that factors in other risk-related attributes.

4.Lending Club should exercise caution when dealing with loans intended for Small Business purposes, as they exhibit the highest charge-off rate. loans designated for Weddings, major purchases, car financing, and credit card payments demonstrate favorable repayment trends, making them advisable for acceptance. 

5. Higher the loan amount, the higher the chances of loan being charged off. Therefore Lending Company should consider accepting loans of lower amount . Hence the risk factor is low for lending club.

6. Lending Club should consider accepting more loans from applicants whose annual income is greater than 1000000 as their probability of charge off is minimum.

7.Lending Club should consider accepting more loans where interest rate is less than 7.5% as their probability of charge off is minimum.

8. Lending Club may find it beneficial to extend loans to applicants with both a substantial income and a moderate number of years of employment.

9.Lending Club should consider accepting more loans from people who owns a house.

10. Lending Club should accept more loans for the term of 36 months as the % of charged off loans is less and the no. of loan applicants are more. accepting more loans from applicants whose annual income is greater than 1000000 as their probability of charge off is minimum.



## Technologies Used
- Python](https://www.python.org/) - version 3.11.4
- [Numpy](https://numpy.org/) - version 1.24.3
- [Pandas](https://pandas.pydata.org/) - version 1.5.3
- [Matplotlib](https://matplotlib.org/) - version 3.7.1
- [Seaborn](https://seaborn.pydata.org/) - version 0.12.2
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by live session of upGrad on EDA
- UpGrad tutorials on Exploratory Data Analysis (EDA) on the learning platform

## Contact
Created by [@kirandalmiya]  (https://github.com/kirandalmiya)

