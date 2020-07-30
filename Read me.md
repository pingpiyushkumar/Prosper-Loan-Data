### Communicating Data Findings: Prosper Loan Data
Prepared by: Piyush Kumar

#### Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. This data dictionary explains the variables in the data set. The project objective is not expected to explore all of the variables in the dataset! But focus on only exploration on about 10-15 of them.

We have too many for the purpose of visualization, I have cut down a few variables.

**The main feature(s) of interest in the dataset?**

What factors are responsible for Loan Grant. We would also be looking for any specific relationship between these variables. 

**Features that has helped support my investigation into feature(s) of interest?**

Borrower information occupation, income, Home ownership , Employment Status, prosper rating and Loan Status will be major contributing factors. 


#### Summary of Findings
- Most of the loans has term of 36 months.
- Although, a good no. of loans have been completed, most are still are current.
- Among the rated loans, A, B, C and D ratings are most prevalent.
- Notably, most of the borrowers live in CA, followed by TX, NY, FL and IL.
- Most of the borrowers fall under Others category though a many of them have said they're professional.
- Most of the borrowers are employed and only a few hundreds are unemployed, which is a healthy sign.
- Borrowers Income range follows a normal distribution, where most of the borrowers have Income in the range \\$25000 - \\$75000
- Borrower's Debt to Income ratio gives a long tail for the values between 0 to 1, i.e most of the borrowers have low debt to income ratio. Zooming into the range 0 to 1, we see a right skewed distribution, with most of the borrowers having debt to income ratio of less than 0.5
- Most of the loan amounts are around \\$5000 followed by \\$10,000, \\$15,000, \\$20,000 and \\$25,000.
- Borrower Rate seems to follow a unimodal distribution with most of the rate being under 0.1 to 0.3
- Most of the borrowers have been employed for less than 3 months.
- Apart from few outliers at, most of the borrowers have stated monthly income in the range \\$0 - \\$10,000 with the peak at around \\$5000.
- Most of the loans get funded by at least 100 Investors, and in that most receive participation by at least 10 investors.
- Most selected category for listing is Debt consolidation i.e people are taking loans to pay off their one or many other loans.
- We have a very even distribution for borrowers being a homeowner or not. This suggests that loan distribution doesn't depend on homeownership status of the borrower.
- Borrowers who take the highest loan amount are employed ones, followed by Self-employed, Others and Full-time employees.
- Stated monthly salary of the the borrowers who are employed is higher among all. 
- Loan amount is higher among all for loans with Prosper Rating A and B. 
- Loan amount and income range follow the expected trend that borrowers with higher income range are picking up loans with higher amount.
- Borrowers who are home owners have slightly more loans marked as completed than the borrowers who don't own a home.
- Most of the loans are taken by the employed borrowers who have income in the range of \\$25,000 - \\$75,000
- Highest no. of loans are bagged by the borrowers who are employed and have income range in \\$50,000 - \\$75,000 and have Prosper Rating as 'C'.
- Loan original amount and monthly loan payment is highly correlated and it is expected and borrowers interest rate and proper score are highly correlated(-vely), Borrower interest rate and loanamount are -vely correlated.
- Borrowers with prosper ratings from AA to D have the higher loan amount with increased salary
- Borrowers who are employed or full time employees have higher mean salaries.
- Most Borrowers have Prosper rating of B, irrespective of their income range except for the people with zero income.
- The monthly income of borrowers is highest for self-employed followed by employed, full-time and others.
- So, the main contributing factors for the loan grant is heavily dependent on borrower's information like IncomeRange, Home ownership status and employment status and employment duration too.


### Insights for Slides:
For the presentation, I focused mainly on the features that considerably impact the approval of loanstatus. I started by looking at the distrbuiton of each and every numeric and categorical variables and did all the necessary univariate, bivariate and mulitvariate analysis on the selected varaibles.

The major insights:

- LoanStatus of all Borrowers are with current and completed state 
- EmploymentStatus of all Borrowers are with Employed State 
- Top IncomeRange of all Borrowers are within \\$50,000-\\$75,000 
- Majority of the borrowers are with an occupation of Professional and Executive 
- Majority of the borrowers are with a rating or score from A, B, C and D. 
- The borrowers rate follow an approximately unimodal distribution, with the peak around 0.16. 
- The origination amount of the loan is interesting. Here we see that the distribution is a right skewed with multiple peaks observed at \\$5000, \\$10,000 and \\$15,000. 
- Loan original amount and monthly loan payment is highly correlated and it is expected and borrowers interest rate and proper score are highly correlated(-vely), Borrower interest rate and loanamount are -vely correlated.

To conclude the analysis , I would say that the loan approval is heavily dependent on the borrower's information on IncomeRange, Homeownerstatus and employment status.
