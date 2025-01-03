# Lending Club Case Study
> Lending Club is consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. The objective of this case study is to perform EDA to identify the factors that are indicators of a future default


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Lending Club is consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
- Two types of risks are associated with the bank’s decision:
	1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
	2. If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- The business problem we are trying to solve with this project is to identify risky loan applications based on the factors that contibuted to loans being 
Charged off from historical loan data
- Data set used for analysis [loan.csv](https://github.com/rams1011/Lending-Club-Case-Study/blob/main/loan.csv)

## Conclusions
- Applicants with loan purpose as small_business,educational,house and interest rate >= 15% has more chances of defaulting
- Any loan with interest rate above 18% has more chances of defaulting
- Applicants with grades E,F,G and annual income <=40000 has more chances of defaulting
- Applicants with Annual income <= 90k and Interest >= 17% has more chances of defaulting
- Applicants with more than one public recorded bankruptcies has more chances of defaulting

## Technologies Used
- Python 	 - version 3.12.4
- Numpy  	 - version 1.26.4
- Pandas 	 - version 2.2.2
- Matplotlib - version 3.8.4
- Seaborn  	 - version 0.13.2

## Acknowledgements
- This project was inspired by Upgrad live sessions and video turorials
- Plots created in this project based on [Seaborn Documentation](https://seaborn.pydata.org/api.html)
- Technical help from [Stackoverflow](https://stackoverflow.com/)

## Contact
Created by [@rams1011](https://github.com/rams1011) and [@vvw082024](https://github.com/vvw082024)

