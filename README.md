# Lending Club 

## Information

This assignment will give us an idea about how real business problems are solved using EDA. In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

  - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

  - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

When a person applies for a loan, there are two types of decisions that could be taken by the company:

  1.Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
   - Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

   - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

   - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

  2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Loan grade and sub-grade from E to G have higher default rate.
- Loan purpose increases the risk. Some of those purposes are small business, renewable energy , educational.
- Percentage of defaulters in the term of 36 months is higher than in 60 months.
- People who are in the rented house are more likely to default.
- Higher interest rate can also cause to default.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy
- Pandas - version 2.0
- MatplotLib 
- Seaborn
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by upgrad lessons
- Code used here are inspired from stacksoverflow
- This project was based on Lending case study live session


## Contact
Created by [@Vibes007] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
