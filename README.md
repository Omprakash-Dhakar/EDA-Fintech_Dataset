# Loan Default Risk Analysis
This project aims to analyze the loan application data and identify patterns that indicate whether a client has difficulty paying their installments. The analysis can be used to take actions such as denying the loan, reducing the loan amount, lending to risky applicants at a higher interest rate, etc. By identifying such applicants using EDA, the company can ensure that consumers capable of repaying the loan are not rejected.

## Business Understanding
The loan-providing companies find it hard to give loans to people due to their insufficient or non-existent credit history. Because of that, some consumers use it to their advantage by becoming a defaulter. This project focuses on a consumer finance company specializing in lending various types of loans to urban customers.

When the company receives a loan application, they have to decide on loan approval based on the applicant's profile. Two types of risks are associated with the bank's decision:

1. If the applicant is likely to repay the loan, then not approving the loan results in a loss of business for the company.
2. If the applicant is not likely to repay the loan, i.e., he/she is likely to default, then approving the loan may lead to a financial loss for the company.

## Data Description
The dataset for this project contains information about loan applications at the time of applying for the loan. It contains two types of scenarios:

1. The client with payment difficulties: he/she had a late payment of more than X days on at least one of the first Y installments of the loan in our sample,
2. All other cases: All other cases when the payment is paid on time.

When a client applies for a loan, there are four types of decisions that could be taken by the client/company:

1. Approved: The company has approved the loan application.
2. Cancelled: The client cancelled the application sometime during approval.
3. Refused: The company had rejected the loan (because the client does not meet their requirements, etc.).
4. Unused offer: The loan has been cancelled by the client but at different stages of the process.

## Project Objectives
The objectives of this project are:

1. To identify patterns which indicate if a client has difficulty paying their installments, which may be used for taking actions such as denying the loan, reducing the amount of the loan, lending (to risky applicants) at a higher interest rate, etc.
2. To understand how consumer attributes and loan attributes influence the tendency to default.
3. To understand the driving factors (or driver variables) behind loan default, i.e., the variables that are strong indicators of default.

## File Description
This dataset has 3 files as explained below:

1. application_data.csv contains all the information of the client at the time of application. The data is about whether a client has payment difficulties.
2. previous_application.csv contains information about the client's previous loan data. It contains the data on whether the previous application had been Approved, Cancelled, Refused, or Unused offer.
3. columns_description.csv is a data dictionary that describes the meaning of the variables.

## Technologies Used
The project is implemented using the following technologies:

Python
<br>Jupyter Notebook
<br>Pandas
<br>Matplotlib
<br>Seaborn

## Conclusion
In conclusion, this project aimed to provide insights into the factors that drive loan default. By analyzing the loan application data, we can identify patterns that indicate whether a client has difficulty paying their installments. The company can use this information to minimize the risk of losing money while lending to customers. By using EDA techniques and visualization tools, we can understand the relationship between consumer attributes and loan attributes and their influence on the tendency to default.
