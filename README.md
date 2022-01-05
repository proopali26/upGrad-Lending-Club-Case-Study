# Project Name
Lending Club Case Study
 - Case study done on loan_data set to find patterns for defaulters 


## Table of Contents
* [General Info]
* [Technologies Used]
* [Conclusions]

## General Information

When a person applies for a loan, there are two types of decisions that could be taken by the company:
Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
	Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
	Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
	Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

Focus of this case study to figure out pattern of people who defaulted. What are the key variables and how and under what situation they influnce defaulter situation. 

For this case study, historical loan data set of current, paid off and charged off status was used.

## Technologies Used
- Python
- Pandas library 
- Matplotlib library 

## Conclusions
The parameters Term and Grade seem to influence loan status.
 - Loans with higher grades (A,B) seem to have higher ratio of fully paid off
 - Loans with term of 36 months seem to have higher ratio of fully paid off.
 - People with higher number of derogatory public records also seem to have higher number of bankruptcy record 

## Contact
Created by
Ashish Singh
Roopali Paliwal