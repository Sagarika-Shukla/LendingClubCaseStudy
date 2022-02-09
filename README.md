# Lending Club Case Study
## Table of Contents
* [General Info](#general-information)
* [Conclusions](#Conslusions)
* [Technologies Used](#Technologies-Used)
* [Acknowledgements](#Acknowledgements)
* [Contact](#Contact)
  
## General Information
- Provide general information about your project here.
------>Lending Club is a marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return. 

- What is the background of your project?

------>When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

      -If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

      -If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

- What is the business probem that your project is trying to solve?

------->Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
        If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

- What is the dataset that is being used?

--------> We are using loans data in between the year 2007 to 2011 with various key aspects to help us analyse the data


## Conclusions
- Business saw an increase in number of default loans for unverified business, specially for lower income groups. We need a thorough verfication before goin ahead with loans
- Huge increment in delinquency percentage as loan amount increases
- There was a peak in loan approvals seen around December. We need to ask business reason on the same. It may be due to year end closure targets, agents start pushing their targets.
- We need to improve on the verification perspective on the Credit card, Debt Risk, vacation or wedding loans. We saw a lot of loans in these cases are unverified.
- There were multiple Debt loans taken for credit card loans, wherein borrowers were expecting to repay lower EMI to repay debt. 
- With increase in interest rate, default rate increasing
- Maximum loans are taken for the purpose of debt_consolidation
- Higher the risk,leads to higher value of ROI rate of interest charged. graph is between Defaulter/Total and tenure
- Increase in tenure leads to higher count of defaulter. The graph is between Defaulter/Total and tenure
- With increase in annual income capacity to bear loans increases and have higher amount of loans
- Loans are provided based on the loan purpose
  maximum number of defaulters for small business and renewable energy, we saw a higher count of Not verified business going in
- The people having higher income range are taking lesser number of loans for smaller amounts. The graph describes the frequency of people taking loans.
- A borrower’s position can also be judged based on their current condition, which also includes current Home ownership situation
-  dti Vs annual_inc:- We see a decrement in dti with an increase in annual income
- int_rate Vs emp_length:- We see a decrement in int_rate with increase in employment tenure
- grade vs emp_length : With an increase in employment tenure we see lower grade value (6 being highest) 	 which is directly correlated 
- to rate of interest charged to customer
- with an increase in grade, we saw an increase in interest rate
- With an inrease in loan amount, we saw increase in installment
- With an increase in annual income, we saw increase in installment with a higher capacity to bear loans
- With an increase in term, we saw an increase in interest rate




## Technologies Used
- Python - Python 3.10.2
- numpy - 1.21.5
- seaborn - 0.11.2
- matplotlib - 3.4.3
- Pandas - 1.3.4

## Acknowledgements

- This research was supported by Educational organisation Upgrad and under the guidance of our mentor Aditya Bhattacharya who helped us learn and work towars the case study


## Contact
Created by [aajjiitt] - https://github.com/aajjiitt/ 
in collaboration with  [Sagarika-Shukla] - https://github.com/Sagarika-Shukla/ 
feel free to contact us

