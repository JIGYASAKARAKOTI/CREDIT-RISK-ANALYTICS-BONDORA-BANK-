# CREDIT-RISK-ANALYSIS-BONDORA-BANK
## INTRODUCTION
###  Business Understanding
####  The loan providing companies find it hard to give loans to the people due to their insufficient or non-existent credithistory. Because of that, some consumers use it to their advantage by becoming a defaulter. Suppose you work for a consumer finance company which specializes in lending various types of loans to urban customers. You have to use EDA to analyses the patterns present in the data. This will ensure that the applicants capable of repaying the loan are not rejected. When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision: If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

## PROBLEM STATEMENT
###  Two types of risks are associated with the bank’s/Financial Organization decision for Loan Approval:- 
#### 1- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company.
#### 2-  If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.
## EDA APPROACH:- 
![Screenshot 2024-08-28 100616](https://github.com/user-attachments/assets/80386ca7-14f4-48a1-97dc-bf2070c712f9)
![Screenshot 2024-08-28 100719](https://github.com/user-attachments/assets/7ac22258-c393-4eec-ad88-92d8574cdb2c)
![Screenshot 2024-08-28 100734](https://github.com/user-attachments/assets/31572c85-976e-4b02-8ed5-38807d7cee67)
![Screenshot 2024-08-28 100749](https://github.com/user-attachments/assets/54bf53e7-0bfa-4c29-9122-0fc44ecd5938)
![Screenshot 2024-08-28 100803](https://github.com/user-attachments/assets/5cc52745-88af-4ee3-8bd6-406a10bdaa43)
![Screenshot 2024-08-28 100816](https://github.com/user-attachments/assets/3ea0688d-5152-4378-885c-6019768599eb)
![Screenshot 2024-08-2![Screenshot 2024-08-28 100927](https://github.com/user-attachments/assets/ec38ba6d-f571-4898-966d-d6205524e630)
8!![Screenshot 2024-08-28 100911](https://github.com/user-attachments/assets/4c5248fa-b3ea-46d5-a7b9-e91bcec6f8b2)
[Screenshot 2024-08-28 100853](https://github.com/user-attachments/assets/27a845e4-1598-4695-9d55-1a0cf1059b8a)
 100836](https://github.com/user-attachments/assets/f5f28438-75bd-4798-a5be-1cf11e265be9)
## CONCLUSION
###  After analysing the datasets, there are few attributes of a client with which the bank would be able to identify if they will repay the loan or not. The analysis is consised as below with the contributing factors and categorization:
### Decisive Factor whether an applicant will be Repayer: 
#### NAME_EDUCATION_TYPE: Academic degree has less defaults.
##### NAME_INCOME_TYPE: Student and Businessmen have no defaults.
 #### REGION_RATING_CLIENT: RATING 1 is safer.
 #### ORGANIZATION_TYPE: Clients with Trade Type 4 and 5 and Industry type 8 have defaulted less than 3%.
##### DAYS_BIRTH: People above age of 50 have low probability of defaulting.
##### DAYS_EMPLOYED: Clients with 40+ year experience having less than 1% default rate.
##### AMT_INCOME_TOTAL: Applicant with Income more than 700,000 are less likely to default.
##### NAME_CASH_LOAN_PURPOSE: Loans bought for Hobby, Buying garage are being repayed mostly.
##### CNT_CHILDREN: People with zero to two children tend to repay the loans.
### Decisive Factor whether an applicant will be Defaulter: 
#####  CODE_GENDER: Men are at relatively higher default rate.
##### NAME_FAMILY_STATUS: People who have civil marriage or who are single default a lot.
##### NAME_EDUCATION_TYPE: People with Lower Secondary & Secondary education.
##### NAME_INCOME_TYPE: Clients who are either on Maternity leave or Unemployed default a lot.
##### REGION_RATING_CLIENT: People who live in Rating 3 have the highest defaults.
##### OCCUPATION_TYPE: Avoid Low-skill Laborers, Drivers, Waiters/barmen staff, Security staff, Laborers, and Cooking staff as the default rate is high.
##### ORGANIZATION_TYPE: Organizations with the highest percentage of loans not repaid are Transport: type 3 (16%), 
  ###### Industry: type 13 (13.5%), Industry: type 8 (12.5%), 
  ###### and Restaurant (less than 12%). 
  ##### Self-employed people have a relatively high defaulting rate and thus should be avoided for loan approval or provided with loans at higher interest rates to mitigate the risk of defaulting.
##### DAYS_BIRTH: Avoid young people who are in the age group of 20-40 as they have a higher probability of defaulting.
##### DAYS_EMPLOYED: People who have less than 5 years of employment have a high default rate.
##### CNT_CHILDREN & CNT_FAM_MEMBERS: Clients who have children equal to or more than 9 default 100% and hence their applications should be rejected.
##### AMT_GOODS_PRICE: When the credit amount goes beyond 3M, there is an increase in defaulters.
