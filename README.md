# Loan Data From Prosper - Data Exploration
## by Hudson Nandere Lubinga


## Dataset

> The 'Loan Data From Prosper' data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. Prosper is the first peer-to-peer lending marketplace in the US founded way back in 2005. Since then, this company has facilitated more than USD 12 billion in loans to more than 770,000 people (https://www.prosper.com/about).

> - During my data exploration, I first of all loaded my dataset using pandas read_csv() function. 
- There after, I used several pandas function to visually and programmatically explore the dataset.
- Some of the functions include but not limited to head(), sample(), shape, info(), and describe().
- From there, I checked for duplicates and dropped them, I also dropped a column which had inconsistencies.
- Then I created another data frame consisting of only the 20 variables I was targeting. Again, I handled issues with this target dataframe such as incorrect datatypes, incorrect names, duplicates, among others.
- After this preliminary wrangling, I made deeper explorations starting with Univariate to Bivariate, and lastly Multivariate.
> 
## Summary of Findings

> Below is the summary of the main findings:
- The amount that is most frequently loaned is 4,000, followed by 15,000 and then 10,000.
- The interest rate variables, BorrowerAPR and BorrowerRate contain the same information.
- Borrower APR is negatively correlated with the loan original amount. Borrower APR is negatively correlated with credit score range lower.
- There is a positive correlation between loan original amount with monthly loan payment and with credit score.
- Higher income borrowers and home owners borrow higher amounts for lower rates compared with lower income borrowers.
- Unemployed borrowers pay the highest interest among all employment statuses.
- The higher the loan amounts, the lower the interest rate and the higher the monthly payments
- Borrowers who do not own a house pay a higher interest throughout the years
- Borrowers who own a house borrow more money on average throughout the years
- There is an upward trend in Loan Amounts for the last few years.
- Borrowers with higher income rates more frequently receive higher Loan Amounts through the years.

## Key Insights for Presentation

- The distibution of Loan Amount is multimodal. It has several peaks and the most popular loan amounts are 4,000, 15,000 and 10,000.
- Borrowers are segmented by whether they own a house or not. It is observed that home owners borrow higher amounts more frequently
- Loan Amounts is affects Interest rate and monthly payments. It is observed that the higher the loan amounts, the lower the interest rate and the higher the monthly payments
