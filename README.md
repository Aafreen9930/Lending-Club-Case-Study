# Lending-Club-Case-Study

## Problem Statement
Solving this assignment will give you an idea about how real business problems are solved using Exploratory Data AnalysisDA. In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

## Business Understanding
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company

If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, you will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

1.Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

2.Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

3.Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

## Business Objectives
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

## Conclusions
- It's notable that Grade G exhibits the highest percentage of defaulters among all loan grades. This indicates that borrowers assigned to Grade G are more likely to default on their loans compared to other grade categories.
- It's worth noting that the loan purpose 'small_business' exhibits the highest percentage of risk of defaulters among all loan purposes. This is followed by 'renewable_energy' and 'educational' purposes, indicating a higher likelihood of default in these categories.
- It's noteworthy that the highest percentage of risk of defaulters is associated with customers having 10+ years of experience. On the other hand, the lowest percentage of risk is observed among customers with 9 years of experience. Customers with other years of experience fall in between these extremes, indicating varying levels of risk.
- When considering the percentage of defaulters based on home ownership, the highest percentage is observed among those categorized as 'Other,' followed by 'Rent,' 'Own,' and 'Mortgage,' in descending order.
- It's important to note that the highest percentage of defaulters is observed in the Northeast (address) region, accounting for 60%. This information can be crucial for making informed decisions and risk assessments in the lending business, as it highlights the region with the highest default risk.
- Analysis of loan terms reveals that a higher percentage of defaulters, approximately 25.31%, are observed in the 60-month loan term compared to the 36-month loan term, which has a lower default rate of approximately 11.09%. This suggests that longer loan terms may carry a higher risk of default.


## Technologies Used
- Name: numpy & Version: 1.24.3
- Name: pandas & Version: 1.5.3
- Name: matplotlib & Version: 3.7.1
- Name: seaborn & Version: 0.12.2

## Contact
Created by [@Aafreen9930] - feel free to contact me!
