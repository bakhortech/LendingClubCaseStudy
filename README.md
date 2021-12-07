# Project Name
 ###### Lending Club Case Study:
    Identification of borrower behaviour that leads to default a loan payment using exploratory data analysis.
    Help lending organisation providing the driver variables that would identify the loan defaulters so that risk of lending is minimal.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
When working for a consumer finance company which specialises in lending various types of loans to urban customers, every loan application to the organisation brings in two types of risk with the bank’s decision-
   1. Not approving a loan to a good customer is loss to business
   2. Approving loan to a customer who might default loan payment is a financial loss.
   
Analysing past consumer behaviours might help the lending organisation to filter out customer who is probable to default a loan. Prime objective of this project is to understand borrower traits and identify the driver variables that would determine if a customer is probable to default the loan payment.

The provided dataset is loan.csv file, that contains information about past loan applicants and whether they ‘defaulted’ or not.
Analysig the file we need to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

We have used EDA to understand how consumer attributes and loan attributes influence the tendency of default.

## Conclusions
- The provided data has lot of null and missing values. Columns with more that 50% null have been droped and null have been enriched wherever applicable
- Few of the columns had malformed data. Those were standardized.
- Busines driven, data driven and type driven derived columns are created as required.
- After data understanding and cleanup, univariate and bivariate analysis have been done.
- Few of the strong driver variables identified are as follows: 

   - Increasing rate of interest shows more loan defaulter. Loans with greater interest might be a risk.
   - Number of borrower from CA is most and it also has the highest number of defaulter. Borrower from state CA needs to be scrutunized properly.
   - Lower grade of loan with increasing rate of interest shows higher chances of defaulter.
   - Loan with 60 months term shows greater number of defaulter when rate of interest is high.
   - Mortgaged and rented home owners shows more number of loan with more defaulters when interest rate is medium to high.
   - most of the people have taken loan for debt consolidation with high interest rate.

## Technologies Used
- jupyter notebook - version 6.0.3
- python - version 3.8
- pandas - version 1.0.5
- numpy - version 1.18.5
- matplotlib.pyplot
- seaborn - version 0.10.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project is created as part of upgrad assignment on case study with exploratory data analysis. Thanks to upgrad for inspiring to work on interesting problems.

## Contact
Created by [@bakhortechnologies] and [@IndrashisChatterjee] - feel free to connect!
