# Risky Loan Applicants Prediction
> The goal is to find patterns that can be used to determine if an applicant is likely to default, which can then be used to determine whether to grant the loan, reduce its size, charge riskier applicants a higher interest rate, etc.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#acknowledgements)

## General Information
We have the loan data set which has the entries of borrowers and their details
The ultimate goal is to identify the variables which all can be effectively used to identify the defaulters (Charged-Off borrowers)
Business Problem:
- It will help the investors & approvers to pre-filter/ predict risky loan applicants
loan dataset is used here

## Conclusions
**Univariate Analysis**
- Interest rate ratio is high between 10.0% to 15.0%
- Due term is high on 36 months, whereas charged off values were similar for each
- Applicants mostly from Rented and Mortgage and the high no of Charged Off borrowers than others
- Most of the loans were given between 5000 to 15000 from

**Bivariate Analysis** 
- Annual income of 0 to 15000 are the highest no of defaulters whereas borrowers earning more than 75K+ are likely to be not defaulters
- Borrowers from G and F grade were found to be highest defaulters
- Loan taken for the purpose of "Small business" has high rate of defaulters compare to others
- The loan amount obtained for small business purpose has the highest median, 95th percentile, and 75th percentile values of any reason. whereas house seems to be 2nd and Credit card seems to be as 3rd line
- Borrowers whose interest rate is more than 20% are most likely to be a defaulter than others rates
- borrowers are defaulters who has been defaulted before in the ratio of more than 40%
- More than 60% of borrowers were charged off in NE state
- Higher the term duration higher the interest rate
- As loan amount increases. Interest rate increase
- Charged off borrowers earning less annual income than the other one each

**Correlation Analysis**
- The more annual income, the more chance of loan amount sanctioned

## Technologies Used
- seaborn - version 0.12.2
- pandas - version 2.0.1
- matplotlib.pyplot - version 3.7.1


## Contact
Created by [@rgurum] - feel free to contact me!